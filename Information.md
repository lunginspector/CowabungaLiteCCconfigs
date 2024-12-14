# Custom Control Center configurations for [Cowabunga Lite](https://cowabun.ga)
**These configurations were made for iOS 17.x and earlier.** With these configurations, you can customize your Control Center without any exploits or extra tweaks. The configurations available work around a bug that causes every module to be shifted down below where it use to be.

# How do I use these configurations?
## On Windows

1. Open File Explorer and type in the directory “%APPDATA%/CowabungaLite/Workspace”
2. Locate the UDID of your device and click on the “SkipSetup” folder
3. Create a new folder called “HomeDomain”.
4. In the new folder, create another folder called “Library”.
5. In the new folder, create another folder called “ControlCenter".
7. Copy/Drag the ModuleConfiguration file into the folder.
8. Open Cowabunga Lite, make sure “Skip Setup” is checked and click the “Apply” button.

## On Mac
1. Import the Cowoperation into "Custom Operations" and enable it.
2. Click the "Apply" button.

*** 

## What's the bug?
* On most iPhones, the "Screen Mirroring" toggle will refuse to move to the bottom. The same will happen with the "Mute" option on iPads and any device with an action button.
* The other issue is that the modules will be moved to the bottom and a blank space will occur above, presumably because the modules were never meant to be moved in the first place.
* **This is why all configurations have been made with these issues in mind, and have been created to evade the issue.**

## Settings App Warning
**Do not attempt to move around or delete any modules in the settings app unless you know what you are doing.** Once you delete a module, you cannot add it back unless you repeat the steps again. This is not my fault. It's the behavior of the settings app that causes it to not reappear after being deleted in the settings pane.
