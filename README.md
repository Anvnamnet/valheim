# Th0rheim Community Server
All the required mods conveniently packed in to one modpack!
<br>
<br>

## Install instructions

### 1. Open the folder called **"Open and move content"**

### 2. Copy all the files in the folder

### 3. Open the local Valheim files.

**These can easily be found if you:**
 1. **Right click** Valheim in your Steam Library
 2. Hover over **Manage**
 3. Click **Browse Local Files**

### 4. Paste content from <u>step 1</u> straight in to that folder.
Example where:<br>
`C:\Games\Steam\steamapps\common\Valheim`

### 5. Start game
Here you might have to boot it and then close it once.<br>
If it works straight away, enjoy. <br>
If it doesn't, just start game, and then close it, and then start again!

<br>
<br>

## Errors, crashes and general Troubleshooting
### So you have issues?
You can always ask in the Discord.<br>
But here are som stuff that might popup.
#

* **My game crashes instantly on boot:**
  * Yeah.. uhm. Remove everything from step 1 (look up teh file names) including the bepinex folder.<br>
  Move almost all the files including the BepInEx folder back to your Valheim folder.<br>
  If you moved it all, remove the plugin folder inside BepInEx folder.<br>
  Start game. if it starts, great success. Move the plugins folder to BepInEx. Start game.<br>
If this does not work, one of the mods is corrupted and you can use the links below to see and download the newest versions.
#
* **I get a message about missing or outdated mod:**
  * There is either a mod missing from `valheim/BepInEx/plugins` *(plugins folder)*.<br>
  Or one of the mods have been updated either on server side or you have downloaded it manually and have a newer or older version. Check in the Discord for info.
#
* **I want to play on another server with no mods or other mods!**
  * **Another modded server:**<br>
  Make note of the mods currently in use *(see list below)*, and move them out of the plugins folder to somewhere else.<br>
  Done<br>
  <br>
  * **Go back to vanilla:**<br>
  Go to your valheim folder<br>
  *Example`C:\Games\Steam\steamapps\common\Valheim`*<br>
     * Remove the folder called BepInEx, 
     * Remove the folder called doorstop_libs
     * Remove .doorstop_version
     * Remove doorstop_config.ini
     * Remove winhttp.dll<br>
**Done**
<br>
<br>
# Modlist:
* [**BepInExPack Valheim**](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/) &ensp;&ensp;-&ensp;&ensp; The "modloader" or the injector to even be able to use mods.
* [**YamlDotNet**](https://thunderstore.io/c/valheim/p/ValheimModding/YamlDotNet/) &ensp;&ensp;-&ensp;&ensp; Required for:
* [**Expand World Data**](https://thunderstore.io/c/valheim/p/JereKuusela/Expand_World_Data/) &ensp;&ensp;-&ensp;&ensp; required for:
* [**Drop N Spawn**](https://thunderstore.io/c/valheim/p/sighsorry/DropNSpawn/) &ensp;&ensp;-&ensp;&ensp; To change the behavior of enemy spawns

