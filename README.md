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


![looted_Report](https://github.com/grimmier378/looted/assets/124466615/cb45adb9-361a-48d9-b27f-5542aa06c00b)
