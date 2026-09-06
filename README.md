
1. 
## 📱 ADB Installation Instructions

This application requires ' platform-tools ' packages to be installed/located in your C:\ (primary disk), follow the guidelines below this line;
### Step-by-Step Installation:
1. **Download Android SDK Platform Tools**
   - Visit: https://developer.android.com/studio/releases/platform-tools  (for windows)
   - Download the ZIP file

2. **Extract the Files**
   - Create a folder named ' platform-tools ' or Extract the zip file to your C:\ (primary disk), but ensure that all the extracted files must be within a folder named 'platform-tools'.
//This location is non-negotiable as this software application will only look for the platform-tool folder located among the folders in your C:\ disk or refer to (3.1) in this page. This app originally will not access any other system or personal files other than files in ' C:\platform-tools 'folder.

NOTE: Extracting files to this location ensures that this app won't access any personal or system files.

   - You should have: `C:\platform-tools\adb.exe`

**Manual installation ensure latest Platform tool packages/ADB drivers will be installed and reduces security concerns like false accusations to me or other HOST-privacy concerns. Without Platform tools, this app does not have any purpose.**

3. **Run APK Installer**
   - Launch the application
   - It will automatically detect ADB at `C:\platform-tools`
**Some times, application may display 'ADB not installed' once started, but neglect the warning-massage box and click 'Refresh' button.

(3.1) ### Alternative Locations (if C:\platform-tools doesn't work):
The app will also check these locations:
- `C:\adb\adb.exe`
- `C:\Android\platform-tools\adb.exe`

_________________________________________________________________________________
To Verify whether platform tools are Installation
   - Open Command Prompt
   - Type: `C:\platform-tools\adb.exe version`
   - You should see the ADB version information
_________________________________________________________________________________

4. In order to install any app, ADB feature must be enabled in your device.
   - Open your android device's settings
   - Got to about page (may differ among brands)
   - Click OS version of your device 3-4 times until you see ' Developer settings are now enabled ' or similar.
   - Go back and look for developer settings/options (or search it in settings). Different manufacturers locate it under different settings pages.
   - In developer options/settings, scroll down until you find, USB debugging. Enable it, if any warning are given, accept it.
   - Enable 'Install via USB '  feature too to make the process smoother.
     **Please remember to disable these as well as developer options/settings once you installed your application. Do not leave them unabled. Your device may expose to risk as well as some apps like banking apps will stop working until DEV settings/options is disabled.
     
4. Now go back to the ' SideLoad - APK_Installer ' app.
   - Click refresh devices button. Your device must be listed.
   **If not listed, please ensure you have extracted platform-tools in the correct location.
   - If the app listed your device, now click ' Select APK ' and search and locate the APK in your PC you wish to install.
   - Once everything is done, finally click ' Install APK ' .
  
5. " Additional "
   - This application is included with several safety features. If you do not know about them, leave them as it is. If you encounter any errors, please report/mention the issue in this repo discussion.
   - Currently, I found no issues with any functions.
