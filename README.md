# BCC - Storage
**THIS IS CURRENTLY UNDER DEVELOPMENT AND WILL MOST LIKELY HAVE MINOR ISSUES**

> A RedM free placement storage system for [Vorp Core](http://docs.vorpcore.com:3000/)

Join the [VORP Community Discord](https://discord.gg/23MPbQ6)

## Features
1. Freely Add Text a storage object for your character
2. Store Items within the storage chest
5. Easily configurateble settings
7. Custom Vue.js UI

## Installation
1. Download this repo/codebase
2. Extract and place `bcc-storage` into your `resources` folder
3. Add `ensure bcc-storage` to your `server.cfg` file
4. Add `data.sql` to you database
5. Restart your server (unless you have nightly restarts)

## How-to-use
1. Type `/storage:edit` to activate tracking ball _(Or press Z if hotkeys are enabled)_
![image](https://user-images.githubusercontent.com/10902965/166846929-739318de-7b7d-482e-9702-6b2d4f03a82c.png)
2. Type `/scene:save` will place your storage chest
3. Type `/scene:del` will delete you storage chest (WARNING THIS WILL CURRENTLY DELETE ALL ITEMS IN THE STORAGE!)
4. Hold `[R]` while in from of the chest to open
5. Click `x` to clost storage


## How-to-configure
All configurations available in `/config.lua`

## TODO
- Close Storage Boxes properly
- UI warning when deleting storage with items in it
- Migrate the slash commands to an easier methedology
- Update the drag/drop logic to be closer to the cursor
- Add everything to the Config.lua and propegate it through to nui
- Add screenshots to tut section of readme

## Long Term Goals
1. Sharable storage access
2. Lock pickable storage
3. Choose what chest model you want to use
4. Add storage chest item that can be used to then place the chest (Revamp slash commands)

 ## Dependency
 - Vorp Core
