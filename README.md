# Looted #

Simple console window Dedicated to displaying who looted what in group, with item links.

# Standalone Mode #
* start in standalone mode 
```
/lua run looted start
```

# Standalone Commands #
```
/looted show toggles show hide on window. 
/looted stop exit sctipt.
```
Or you can Import into another lua.

# Import Mode #

1. place in your scripts folder name it looted.lua.
2. local guiLoot = require('looted')
3. guiLoot.imported = true
4. guiLoot.shouldDrawGUI = true|false to show or hide window.
