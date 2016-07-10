Installation instructions for Linux:
- Copy this folder to .local/share/steam/steamapps/sourcemods/
- Restart Steam

Issues:
- Error with menu background disappearing during load.
- The shader for wave overlays appears to be missing entirely from the Linux engine, as it is based on some DirectX feature.

Note for modders:
It took a few extra changes to make the mod work properly on Linux:

Make sure folder names, and the "gameinfo.txt" filename, are lower-case characters only.

In the resource folder, include .res files from the Linux version of Episode 2.

Changes to .vmt files in materials/vgui/chapters to make chapter thumbnails display correctly.
