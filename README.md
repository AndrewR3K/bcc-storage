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
![image](https://user-images.githubusercontent.com/10902965/168003538-09a76c95-d6f6-47d6-b18e-8dcb963cb21c.png)
2. Type `/scene:save` will place your storage chest
3. Type `/scene:del` will delete you storage chest (WARNING THIS WILL CURRENTLY DELETE ALL ITEMS IN THE STORAGE!)
4. Hold `[R]` while in from of the chest to open
![image](https://user-images.githubusercontent.com/10902965/168003606-4c526b5b-b45e-4a8e-b788-969a19b9ff7d.png)
5. Click `x` to clost storage
![image](https://user-images.githubusercontent.com/10902965/168003674-812e6605-b26d-416c-b070-6de0cdc2874d.png)
6. Drag item from one storage to the other to move
![image](https://user-images.githubusercontent.com/10902965/168003758-37cc94d7-5e7f-40a9-8efb-1139d9fab613.png)
7. If there is more than 1 item, a prompt will appear asking how many to move.
![image](https://user-images.githubusercontent.com/10902965/168003818-189a2d4f-5678-40db-bbcb-14a9f0f52f15.png)

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
