![MCShop](https://raw.githubusercontent.com/LakenH/MCShop/master/logo.png)
Web site for viewing items for sale on a Minecraft server, automatically updates using the plugin SignShopExport

## Live Demo
[MCShop for the Gamealition Minecraft Server](http://laken.pw/mcshop)

## Features
- Automatically updates all shops located on the server every 30 minutes (Thanks to SignShopExport)
- Dynmap support, all coordinates are clickable and will take you to that location on dynmap
- Support for enchanted items
- Shows player heads next to playername (Using Minotaur API)
- Select drop-down box is filterable by typing (Using Select2)
- Sorts results by lowest price (Using Lodash JS Library)
- Results displayed in cards (Materialize CSS Framework)
- Mobile Friendly (Materialize CSS Framework)

## How to set up
1. Install the server plugin [SignShopExport](https://github.com/Gamealition/SignShopExport) by RoyCurtis. This plugin is compatable with SignShop and Quickshop.
2. Inside of the script element tag, edit the values of the two variables, JSONUrl and dynmapURL with your URLs
3. Upload all files to a web server. (NOTE: If MCShop is located on a different server than the JSON, you may run into some trouble, to fix this, add `Header set Access-Control-Allow-Origin "*"` to the .htaccess file in the directory that the JSON is located)
4. If you run into any issues, feel free to open an issue


## To-Do
1. Clean up the code. It's a mess.
2. Work well with SignShop item sets (currently quite buggy)
3. At certain screen widths, some longer item's names go outside of the item's card

## How to Contribute
Have an idea for a feature, want to fix a bug, or implement something from the To-Do list? Feel free to open a Pull Request!
