Th0rheim Community Server
All the required mods conveniently packed in to one modpack!


=== Install instructions ===

1. Open the folder called "Open and move content"

2. Copy all the files and folders inside it

3. Open your local Valheim files.
   These can easily be found if you:
   - Right click Valheim in your Steam Library
   - Hover over "Manage"
   - Click "Browse Local Files"

4. Paste the copied content straight into that Valheim folder.
   Example path: C:\Games\Steam\steamapps\common\Valheim

5. Start the game.
   If it works straight away, enjoy!
   If it does not load the mods immediately, just close the game and start it one more time.


=== Errors, crashes and general Troubleshooting ===

So you have issues?
You can always ask in the Discord. But here is some stuff that might pop up:

* My game crashes instantly on boot:
  Remove all the modpack files you added (including the BepInEx folder).
  Move them back into the Valheim folder, but this time leave the "plugins" folder out.
  Start the game. If it starts, great success! Now move the "plugins" folder back inside the BepInEx folder and restart the game.
  If it still crashes, one of the mods is corrupted. Use the links below to download the newest versions.

* I get a message about a missing or outdated mod:
  There is either a mod missing from "Valheim/BepInEx/plugins", or one of the mods has been updated on the server side, or you manually downloaded a different version. Check the Discord for info.

* I want to play on another server with no mods or other mods!
  - For another modded server: Take note of the current mods (see list below) and move them out of your plugins folder to a safe backup folder.
  - To go back to vanilla (no mods): Go to your Valheim folder and delete these exact files/folders:
    - Delete the folder: BepInEx
    - Delete the folder: doorstop_libs
    - Delete the file: .doorstop_version
    - Delete the file: doorstop_config.ini
    - Delete the file: winhttp.dll


=== Modlist ===

* BepInExPack Valheim
  The "modloader" or injector required to even be able to use mods.
  Link: https://thunderstore.io

* YamlDotNet
  Required library mod.
  Link: https://thunderstore.io

* Expand World Data
  Required for world modifications.
  Link: https://thunderstore.io

* Drop N Spawn
  Used to change the behavior of enemy spawns.
  Link: https://thunderstore.io/c/valheim/p/sighsorry/DropNSpawn/
