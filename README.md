# SideLoader - APK Installer for Android
A lightweight Windows desktop utility for installing Android APK files directly to your Android device via ADB (Android Debug Bridge).
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
>[!NOTE] 
>This is just an application created to enhance my C# knowledge and MVS experience. Please note that if you found/downloaded this software elsewhere other than my personal website > (my portfolio ~ Gdrive, social media, LinkedIn and in GitHub), software might contain viruses or modified to contain backdoors which might put your device at risk. I am not responsible for any damages like virus attack or privacy issues caused to you as this software does not originally have any backdoors, or any sort of viruses.  

**Below you may find 1. Installation guidelines, 2. Features, and 3. Disclaimers.**
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 
## 1.📱 ADB Installation Instructions

This application requires ' platform-tools ' packages to be installed/located in your C:\ (primary disk), follow the guidelines below this line;
### Step-by-Step Installation:

1. **Download Android SDK Platform Tools**
   - Visit: https://developer.android.com/studio/releases/platform-tools  (for windows)
   - Download the ZIP file

2. **Extract the Files**
   - Create a folder named ' platform-tools ' or Extract the zip file to your C:\ (primary disk), but ensure that all the extracted files must be within a folder named 'platform-tools'.

*This location is non-negotiable as this software application will only look for the platform-tool folder located among the folders in your C:\ disk or refer to[^1]. This app originally will not access any other system or personal files other than files in ' C:\platform-tools ' folder.*

NOTE: Extracting files to this location ensures that this app won't access any personal or system files.

   - You should have: `C:\platform-tools\adb.exe`

**I did not ship the software together with platform-tools in order to be protected from license and copyright issues. However still, Manual installation ensure latest Platform tool packages/ADB drivers installed for usage and reduces security concerns like false accusations to me or other HOST-privacy concerns. Without Platform tools, this app does not have any purpose.**

3. **Run APK Installer** -> *Click yes in admin privilege request. This ensure that program will run smoothly without any restrictions to access platform-tools files.*
   - Launch the application
   - It will automatically detect ADB at `C:\platform-tools`
**Some times, application may display 'ADB not installed' once started, but neglect the warning-massage box and click 'Refresh' button.

[^1]:Alternative Locations (if C:\platform-tools doesn't work):  
:The app will also check these locations:  
 :- `C:\adb\adb.exe`*  
 :- `C:\Android\platform-tools\adb.exe`*  
_________________________________________________________________________________
To Verify whether platform tools are Installation
   - Open Command Prompt
   - Type: `C:\platform-tools\adb.exe version`
   - You should see the ADB version information
_________________________________________________________________________________

4. **Enable ADB in your Android device** - > *In order to install any app, ADB feature must be enabled in your device.*
   - Open your android device's settings
   - Got to about page (may differ amoung brands)
   - Click OS version of your device 3-4 times until you see ' Developer settings are now enabled ' or similar massage.
   - In settings, look or search for developer settings/options. *Different manufacturers locate it under different names and settings pages.*
   - In developer options/settings, scroll down until you find, USB debugging. Enable it, if any warning(s) are given, accept it.
   - Enable 'Install via USB '  feature too to make the process smoother.
**Please remember to disable them back as well as developer options/settings once you installed your application. Do not leave them enabled. Your device may expose to risk as well as apps like banking apps will stop working until DEV settings/options is disabled.**
     
5. **Installing an APK** -> *Now go back to the ' SideLoad - APK_Installer ' app.*
   - Click refresh devices button. Your device must be listed.
   **If not listed, please ensure you have extracted platform-tools in the correct location.
   - If your device get listed, now click ' Select APK ' and search and locate the APK in your PC you wish to install.
   - Once everything is done, finally click ' Install APK ' .

   **NOTE:**
   - This application is included with several safety features. If you do not know about them, leave them as it is. If you encounter any errors, please report/mention the issue in this repo discussion.
   - Currently, I found no functional issue(s) with any functions.

## 2.✨ Features
### 2.1. Core Functionality 🚀
One-Click APK Installation - Select any APK file and install it to your Android device with a single click.

Real-Time Status Updates - Visual feedback for every action and process.

Secure Copy - Creates temporary secure copies of APK files during installation for safety.

Comprehensive Error Handling - Clear error messages for common issues (unauthorized devices, insufficient storage, etc.).

### 2.2. Security Features 🔒
Debugger Detection - Protects against reverse engineering attempts.

Integrity Verification - Ensures the application hasn't been tampered with.

APK Validation - Validates APK files before installation to prevent corruption.

Command Sanitization - Prevents command injection attacks.

Suspicious Location Warning - Alerts if running from temporary or downloads folder.

Secure Copy - Uses temporary secure copies to protect your system.

Configurable Security - All security features can be toggled on/off in settings.

*All Security features were added using AI technologies* (I am new to computer security technologies 😑)

## Additional Features 📋
Settings Management - Customize security preferences and application behavior

Logging - Optional logging for troubleshooting

Admin Privilege Check - Automatically requests administrator privileges when needed

## 3.⚠️ DISCLAIMER

This software is provided "AS IS" without any warranties.

### 3.1. **Risks:** 🔒
- Using ADB with Android devices may void warranties
- Improper usage may damage your device as well as increase risk of data loss.
  ~Example:
  1. Downloading this program from other websites which may have been modified and contain malicious codes will put your personal data at a risk.
  2. Installing unknown/unsafe/potential-malicious/moded APK application to your device.
- Some devices may behave differently

### 3.2. **Safety Practices:** ✅
- Always backup your device before installation *(usually no need unless your are installing unsafe/unsure/system-modifying APKs.)*
- Only download APKs from trusted sources or 
- Enable USB Debugging only when needed
- Disconnect USB when not in use

**3.3. By using this software, you agree that:**
- The developer is not liable for any damages.
- You are responsible for your device (I have given warnings as much as possible here as well as in 'info' page @app).
- You have read and understood these terms.

##Thank You!

Developer : GamerLaza_ (Gamertag) / K.C Arosha Silva (name) </br>
[Portfolio](https://sites.google.com/view/arosha-silva/home)
[LinkedIN](https://lk.linkedin.com/in/arosha-silva-5673b51b7)
