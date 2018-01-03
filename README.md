# Swinout

An apple script that writes Swinsian current track information to files.

Useful for live streaming software, e.g. OBS, to display the "Now Playing" information.

## Support
- Track name
- Artist name
- Album name
- Album artwork

## Setup
1. Download the script from the repo
2. Open the script with Script Editor
3. Modify the `directory` in your own use case
4. Export as application "Swinout.app"
5. Run Swinsian
6. Run Swinout
7. Play a song in Swinsian
8. The current track information is now available in the files (track, artist, album, artwork)

## Use with OBS
P.S. OBS does not support choosing files without extensions, you will need to choose a "dummy" text file, and then edit the file path in your scene file.
### Steps
1. In OBS, File > Show Settings Folder
2. Go to basic/scenes
3. Open your scene file (*.json) with any text editor
4. Replace the "dummy" text file paths with the files provided by Swinout
