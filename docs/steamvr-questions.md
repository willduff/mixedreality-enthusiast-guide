---
title: SteamVR questions
description: Advanced Windows Mixed Reality troubleshooting that goes beyond our standard consumer support documentation.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Troubleshoot, Errors, Help, Support, SteamVR
---


## SteamVR questions

### How can I play SteamVR games in my Windows Mixed Reality immersive headset?

You must install Windows Mixed Reality for SteamVR on your PC and set up SteamVR:
* [Download and install SteamVR](https://steamcdn-a.akamaihd.net/client/installer/SteamWindowsMRInstaller.exe).
* Start SteamVR. The SteamVR Tutorial should start automatically.
* Connect your headset to your PC and turn on your motion controllers.
* Once the Windows Mixed Reality home has loaded and your controllers are visible, open the Steam app on your desktop.
* Use the Steam app to launch a SteamVR game from your Steam library. To launch SteamVR games without taking off your headset, you can find and launch them under Windows Mixed Reality's **Start > All Apps**. 

### I get a message that says “To use SteamVR with Windows Mixed Reality, you need to install the latest Windows Update" or "Windows Developer Mode Required".

1. Make sure your PC is running the latest version of Windows 10. To check this, go to **Settings  > System > About**. Under "Windows specifications", make sure "OS Build" is 16299.64 or greater.
2. Make sure you don’t have any updates waiting to download or install. Go to **Settings  > Update & Security > Windows Update** and select "Check for updates". You may have to check for updates multiple times so keep checking for updates until no further updates are available and then restart your PC.

### SteamVR is crashing after updating Windows.

Some older versions of Windows Mixed Reality for SteamVR are no longer compatible with Windows. You may have an old version of Windows Mixed Reality for SteamVR. To ensure that you are up to date:
1. In your Steam library, go to **Software > Windows Mixed Reality for SteamVR**.
2. Right click it and go to "Properties".
3. Select the "Update" tab and select "Always keep this application up to date".
4. Force the update by going to the "Local Files" tab and selecting “Verify integrity of application files”.
5. Restart Steam and SteamVR.

If SteamVR is still crashing after updating you may have two installations of Windows Mixed Reality for SteamVR on your machine. To confirm if this is the case:
1. Locate %localappdata%\openvr\openvrpaths.vrpath and open it in Notepad.
2. Under the "external drivers" sections look for multiple entries for "MixedRealityVRDriver" 
   ```json
   "external_drivers" : [
      "D:\\Steam\\steamapps\\common\\MixedRealityVRDriver",
      "E:\\Steam\\steamapps\\common\\MixedRealityVRDriver"
   ],
   ```
3. If you see multiple entries, remove the older of the two entries. Note that once you have only one entry there should no longer be a comma at the end of the line, for example:
   ```json
   "external_drivers" : [
      "D:\\Steam\\steamapps\\common\\MixedRealityVRDriver"
   ],
   ```
4. Save the file and close it.
5. Restart Steam and SteamVR.

### My controllers aren't working as expected in SteamVR.

1. Close SteamVR.
2. Return to the Mixed Reality Home and confirm that your controllers are working as expected.
3. Launch the SteamVR experience again and your controllers should be back to normal.
4. If issues persist please file feedback using the [Windows Feedback Hub](https://support.microsoft.com/en-us/help/4021566/windows-10-send-feedback-to-microsoft-with-feedback-hub-app) under the Mixed Reality category and include SteamVR in the summary.

Note that you'll use your motion controllers differently in different games. Here are a few basics to help you get started:
* To open the Steam dashboard, press straight down on the left thumbstick.
* To exit a SteamVR game and return to the Windows Mixed Reality home, press the Windows button. Then select the Mixed Reality Home button that appears on screen.

### My left and right controllers are reversed in SteamVR.

Start the game with your controllers off and then turn the left one on, followed by the right one.

### My games are running slowly.

1. Confirm that your PC meets the specifications for SteamVR in Windows Mixed Reality
2. Confirm that your PC meets the specifications for the SteamVR game you are playing.
2. In Mixed Reality Portal on your desktop, select "Pause" to stop desktop preview.
3. Follow the instructions above to make sure you are running Windows 10 build 16299.64 or later.
4. Make sure your PC has the latest graphics drivers.
5. Check Task Manager to see what other processes might be running on your PC and consuming resources.
6. Check to see if Steam is downloading a game in the background. This can consume resources and make games run poorly.
7. There is a known performance issue that affects a small class of apps that do not have a visible window, for example, SteamVR Home. The vast majority of apps do not fall into this category, and a fix will be available in a future update.

If you're still running into unexpected performance issues, please send us feedback using the Windows Feedback Hub. Make sure to follow the instructions to [include a SteamVR Performance Trace](using-steamvr-with-windows-mixed-reality.md#sharing-feedback-on-steamvr). 

### SteamVR is showing a compositor error (for example, "Shared IPC Compositor Connect Failed (400)").

There is a known issue where this can happen if your headset and primary monitor are on two different video adapters. Attach your monitor to the same adapter as your headset and configure that monitor to be the primary monitor in **Settings app > System > Display**.

### SteamVR content appears in the wrong place, like beneath the floor or above my head.

Reset your position: 
1. Click the left controller's thumbstick to bring up the "SteamVR Dashboard".
2. Select the "Settings" button.
3. Select "Reset Seated Position".

### My Steam app closed unexpectedly.

The Steam app will close if you lock your PC screen, remove your headset, switch users, or if your PC goes to sleep.
