# Changelog
---
## June 7th 2019
### Major Changes
- Converted to plugin: needs to be brought in as submodule 
https://github.com/ryangadz/RadialMenu
- All math and functionality is now on the BP_Radial Menu Actor
- BPI_RadialMenu is an interface that can drive any menu item actor that uses it
- Menu items are listed in data table, set "Data Table" and "Starting Data Table Row" when spawning
![RadialMenuSetup](/assets/RadialMenuSetup.PNG) 
- Use BP_MenuItem as a template for your own menu items
