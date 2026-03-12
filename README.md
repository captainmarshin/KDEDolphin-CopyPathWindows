<img width="290" height="28" alt="Screenshot_20260312_140458-5" src="https://github.com/user-attachments/assets/d365900f-9232-4186-afa5-86d1a7279f74" />

This is a simple KDE Dolphin Context Menu Service Action to convert copied file path to Windows style path.
It takes current path of selected file, replaces `/` to `\` and prepends `Z:` to the beginning.
Useful for Windows apps when you need absolute path to file (mostly in Open file windows).

For example: <br>
Original path:
```
/home/deck/.local/share/Steam/steamapps/common/Skyrim/Data/Dragonborn.bsa
```
Copy Path (Windows):
```
Z:\home\deck\.local\share\Steam\steamapps\common\Skyrim\Data\Dragonborn.bsa
```

### Installation
Put `copy_path_win.desktop` to `/home/deck/.local/share/kio/`<br/>
Allow executing (Right click on file > Properties > Permissions > ckechkbox on Allow executing file as program)<br/>

Tested on SteamOS (Deck)
