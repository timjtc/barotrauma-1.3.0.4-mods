1. Locate your Barotrauma game folder and cd into it. For example:
`cd C:\Games\Barotrauma`

2. Execute the following command(s):
```
git init && git remote add origin https://github.com/timjtc/barotrauma-1.3.0.4-mods && git fetch origin && git checkout -b master --track origin/master
```

3. Open the game and go to the Mods menu. Click the folder icon on the bottom side of the left pane to load a modlist, and load the modlist `MP-Modded1`. Hit apply once the mods are loaded.

4. Return to the main menu and host a server. In the Server executable, select Lua for Barotrauma. Hit F3 to open the debug console and run the following command: `install_cl_lua`

5. Restart the game.
