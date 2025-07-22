# LC-DL Version History / Changelog

### Latest Version: 0.3.1 Beta (5)
**Changelog:**
- Accidentaly pushed v0.3 without fixing a bug I added while making it, causing repo names to list the **entire** repo file contents, this has been fixed.
- All file downloads have been redone to be more accommodating for file hosting sites than Github, app.zip, tweaks.zip, and data.zip can all be in different download locations and still work!
- Data folders have been redone and made even easier for publishers! The container UUID (aka Container Folder Name) is now fetched from the applications .app file which negates the need to specify the “dataFolder” string in the app.json and also allows you to upload more than one!
- Setup has been changed, it now explicitly says "Tap here to select the folder!" this should help people getting confused. I wish apple would just understand that `On My iPhone > LiveContainer` is the same on every phone!


#### Version 0.2 Beta (3)
**Changelog:**
- Downloadable data folders have been added! Apps can now have a specific data folder downloaded automatically. MeloNX and Folium will now come with necessary keys/firmware.
- Repositories now fetch new apps automatically.


#### Version 0.1.1 Beta (2)
**Changelog:**
- Auto updater added! When a new shortcut version is found it will be downloaded automatically!
- Added setup when installing the shortcut to avoid “File was not found” error.


#### Version 0.1 Beta (1)
**Changelog:**
-Initial Beta Release
