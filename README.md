Haskell plugin for LightTable
===

Currently it supports:
* Hoogling via `ctrl-shift-d` and selecting hsh (default)
* Hayooing via `ctrl-shift-d` and selecting hsy
* Hayooing inline via `ctrl-d`
* Stylish haskell via sidebar "Haskell: Reformat file"
* Syntax checking via sidebar "Haskell: Check syntax"
* Linting via sidebar "Haskell: Check lint"

Working on:
* ghc-mod features
* Running a simple haskell file


Requirements
===

A recent version of `cabal` that supports `cabal sandbox` and `cabal run`. This must be on a load path that LightTable can read.

Installation
===

To use this plugin simply check it out (or symlink it) into the plugins directory of your LightTable installation. For example, on OS X:

```bash
cd /Applications/LightTable.app/Contents/Resources/app.nw/plugins
```

Restart LightTable, and run the command (ctrl-space) `Show plugin manager`. You should see Haskell as an installed plugin. After, simply go to a
haskell file and start running the commands. The plugin bootstraps itself and builds the executable, so give it a minute the first time around.
If you don't see what you expect after running a command and waiting a bit, try restarting LightTable. If you still are having trouble, please look at the bottom bar for errors and don't hesitate to submit an issue or help out.

Contributing
===

This plugin is in the early stages, and can use any kind of help. The best place to start is the issues. I've marked things as `easy` that should be, well, easy. Feel free to comment on any issue asking for help/direction.
