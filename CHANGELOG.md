# LC-DL Version History

### Latest Version: 0.4 Beta (8) (Rebuilt)
Changelog:

- LC-DL has been **completely** rebuilt from the ground up, adding new features, optimizing the shortcut, and giving a better user experience, all while using less than 5 more actions than the original.

- **LC2HS Integration** • LC2HS is another shortcut made by me that allows you to add LiveContainer apps to your home screen without needing to create shorcuts manually. LC-DL v0.4 has LC2HS integration meaning you will be asked if you want to add your newly installed apps to your homescreen! In a future version this will be able to be changed between the following options: "Always Run LC2HS Automatically", "Never Run LC2HS Automatically", "Always ask to run LC2HS".

- **Tweak Downloading** • You can now download tweaks with LC-DL, these tweaks are in a folder you can set in the app specific settings in LiveContainer, in a future version you will be able to choose to install a tweak to an existing app folder, create a new one, or install the tweak globally.

#### 0.3.2 Beta (7)
Changelog:

- I broke the setup in 0.3.1...... and then left a debugging thing in on 0.3.2....
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
