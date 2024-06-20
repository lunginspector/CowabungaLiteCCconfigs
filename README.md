# Cowabunga Lite Control Center Configurations
## For iOS 17.x ONLY, might work on 16.x and 15.x but I haven't tested.

**On iOS 17, changing the control center layout is possible with Cowabunga Lite. However, there are two problems. One, it only works on Macs, and two, there is a bug which moves the Screen Mirroring toggle to the middle, causing the rest of the layout to be pushed down. However, I have figured out how to fix both of these issues. (on some layouts, because I've added new ones.)**

## Tutorial (Windows Only):

1. Make sure you have Cowabunga Lite installed and your device is ready.
2. Open File Explorer and type in the directory “%APPDATA%/CowabungaLite/Workspace”
3. Locate the UDID of your device and click on the “SkipSetup” folder
4. Create a new folder called “HomeDomain” and open it.
5. Create a new folder called “Library” and open it.
6. Create a new folder called “ControlCenter” and open it.
7. Import the ModuleConfiguration file into the folder (the files are found in this repo).
8. Open Cowabunga Lite, make sure “Skip Setup” is checked and click the “Apply” button.

## Important Information
**Do not attempt to move around or delete any modules in the settings app unless you know what you are doing.** Once you delete a module, you cannot add it back unless you repeat the steps again. This is not my fault. It's the behavior of the settings app that causes it to not reappear after being deleted in the settings pane.

**Cowabunga Lite (by leminlimez):** https://github.com/Avangelista/CowabungaLiteWindows

## So why does the mute/screen mirroring toggle stay at the top and refuse to move down?
Due to changes of the control center in iOS 17, the toggle will now stay at the top. I'm not sure why this is happening however.
