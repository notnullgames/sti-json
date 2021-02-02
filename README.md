# WIP

I am still working on this

# sti-json

JSON tiled map support for [STI](https://github.com/karai17/Simple-Tiled-Implementation) a loader for maps made in [tiled](https://www.mapeditor.org/) for love2d.

This will add the ability to load JSON maps, a native format for Tiled, so you don't have to export them to lua before using them.

## usage

Put sti-json.lua in your project's path.

Load your map in STI as you normally do, with one extra step:

```lua
local sti = require "sti"
local sti_json = require "sti-json"

map = sti(sti_json("maps/map01.json"))
```

