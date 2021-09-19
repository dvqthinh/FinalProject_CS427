# Arena Game
## Authors - Group 9 - 'Wakanda'
 1. [Nguyen Minh Quan](https://github.com/zxquan123) &emsp;&ensp; - 1751097     
 2. [Nguyen Minh Nhat](https://github.com/born99) &emsp;&ensp;&nbsp; - 1751090
 3. [Dang Le Tuan Anh](https://github.com/dangletuananh69) &emsp;&ensp;&ensp;&nbsp; - 1751049
 4. [Do Vuong Quoc Thinh](https://github.com/dvqthinh25111999) &ensp; - 1751105


Arena Game is a Unity game made with Forge networking. 




# Features!

  - A fully working FPS shooter with a simple map and a main menu
  - Fully commented source code!
  - A networked weapon system with several weapons and easy flexibilty
  - Seperated world & view model system
  - Player customization with player name and player skin, saved locally and fully networked!
  - Animated & networked characters!
  - Player health, respawn, spawnpoints
  - HUD & UI
  - Ragdolls!!
  - A few more things    
___
The project includes some nice things, however, an example project would be too big and complex if I had to feature every thing Forge has to offer, so here is a list of things this project does **not** feature.
 - Master server registration. This is very easy to setup with Forge though.
 - NAT Punchthrough server. Forge offers a natpunch which I'm not using for this project.
 - Server browser. This project is direct connect only, however Forge comes with examples of both a lobby system and a server browser.
 - An actual gamemode, however everything you need for creating your own is there (A gamemode class)
 - Any sounds at all :(
 - No options menu! The game is using some post processing that you can't turn off ingame. If you computer is struggeling to run this, disable it on the player's camera.

Arena Game was a project designed to show off how certain things are done in Forge Remastered, showcased as a fully featured game since I figured that's the best way to example stuff. \
It's created by me, NF Mynster, come for a chat on the Forge Discord server [here](https://discord.gg/yzZwEYm) if you are interested in Forge or want to have a general chat with some nice people!


# Preferences

For making this a better example, I've used a few assets

* [SimpleSky](https://www.assetstore.unity3d.com/en/#!/content/42373) - An awesome cartoony skydome!
* [SimpleFX](https://www.assetstore.unity3d.com/en/#!/content/67834) - Some very nice cartoony particle, where I modified some of them slightly.
* [Unity's postprocessing stack v1](https://github.com/Unity-Technologies/PostProcessing) - Unity's great post processing stack
* TextMesh Pro - superior text in Unity

# Usage

ArenaGame is made with  Unity 2018.2.3f1 using Forge 24.2.
It should work on other Unity installations, try it out.
Just open up the project in Unity, open the /Scenes/MainMenu and press play, and you are good to go.
If you want to build it, make sure you make the main menu the first scene and the ArenaScene the second scene in the build menu. 

**There is also a compiled build included for Windows, if you just wanna have a quick test run**

