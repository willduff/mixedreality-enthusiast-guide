---
title: Using SteamVR with Windows Mixed Reality
description: How to play SteamVR games on Windows Mixed Reality headsets with compatible PCs.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, games, SteamVR, Steam, system requirements
---


# Using SteamVR with Windows Mixed Reality
Windows Mixed Reality for SteamVR allows users to run SteamVR experiences on Windows Mixed Reality immersive headsets. After installing the Windows Mixed Reality for SteamVR, users can launch their favorite SteamVR applications from their desktop or Steam library and play them directly on their Windows headset.

## Get your PC ready
* Make sure you have no pending updates: Select **Start > Settings > Update & Security > Windows Update**. If updates are available, select **Install now**. If no updates are available, select **Check for updates**, and then install any new ones. 
* PC requirements vary for the apps and content on Steam. See the minimum requirements per title. A PC with a GTX 1070 graphics card (or equivalent) and an Intel® Core™ i7 processor should offer a good experience for a broad range of titles.

## Set up Windows Mixed Reality for SteamVR
1. Install Steam and SteamVR on your PC. [Learn how](https://go.microsoft.com/fwlink/?linkid=862788) 
2. Install [Windows Mixed Reality for SteamVR](http://store.steampowered.com/app/719950/Windows_Mixed_Reality_SteamVR_preview/).

## Play SteamVR games
1. Connect your headset to your PC and turn on your motion controllers.
2. Once the Windows Mixed Reality home has loaded and your controllers are visible, open the Steam app on your desktop.
3. Use the Steam app to launch a SteamVR game from your Steam library. 

**Tip**: To launch SteamVR games without taking off your headset, use the Desktop app (**Start > Desktop**) to view and interact with your PC desktop inside Windows Mixed Reality.

## Using Motion Controllers with SteamVR
You'll use your motion controllers differently in different games. Here are a few basics to help you get started:
* To open the Steam dashboard, press straight down on the left or right thumbstick. 
* To exit a SteamVR game and return to the Windows Mixed Reality home, press the Windows button.

## Changing the resolution

You can adjust the "Supersampling" slider in the SteamVR -> Settings -> Developer window at any time if you'd like to play games at a higher resolution. Note that when using a higher "Supersampling" multiplier you can expect the game to put more strain on your PC. If you increase the multiplier and see degraded performance readjust this slider to the default level and restart the game to ensure that the change takes effect.![Adjust Supersampling](images/RenderTarget.jpg)

## Using multiple headsets

If you're a VR enthusiast you might regularly use more than one VR headset on the same PC. If that's the case note that when a Windows Mixed Reality headset is plugged in, SteamVR games will always launch to the Windows Mixed Reality headset. If you'd like to launch SteamVR games on another headset make sure to first unplug the Windows Mixed Reality headset before continuing. 

## Getting the most out of SteamVR on Windows Mixed Reality

We will be releasing frequent updates to improve the performance, reliability, and overall experience of using SteamVR on Windows Mixed Reality immersive headsets. To stay up to date with the latest improvements:
* Check for Windows updates regularly
* Switch to the SteamVR beta if you want to try out fixes before they're released to a broader audience
  1. In Steam - use the drop down under your Library to filter to Tools and then locate SteamVR in the list
  2. Open SteamVR properties - right click SteamVR in the same Tools page and open the Properties dialog.![Install SteamVR from the tools section of your Steam Library](images/steamvr-install.png)
  3. Join the SteamVR Beta - click the Betas tab and opt into SteamVR Beta Update by selecting it from the drop down. **Note:** The beta access code field should be left blank and you can just hit close to confirm.![Switch to the SteamVR beta in the properties dialog for SteamVR](images/steamvr-beta.png)

## Enabling controller thumbstick turning in any SteamVR application

**Windows Mixed Reality for SteamVR** has an experimental feature to enable the use of a controller thumbstick for artificial turns in any StreamVR application.  

To enable thumbstick turning:
1. Edit "C:\Program Files (x86)\Steam\steamapps\common\MixedRealityVRDriver\resources\settings\default.vrsettings"
    * Path will be different if **Windows Mixed Reality for SteamVR** was installed to a different library
2. Change either `thumbstickTurnLeftEnabled` or `thumbstickTurnRightEnabled` to `true`
3. Select **stutter turn** or **smooth turn** as shown in the examples below

**Example 1: Enabling stutter turn**

    "driver_Holographic_Experimental" : {
        "thumbstickTurnLeftEnabled" : false,
        "thumbstickTurnRightEnabled" : true,

        // Some people may experience increased discomfort such as nausea, motion sickness, dizziness,
        // disorientation, headache, fatigue, or eye strain when using “smooth turns” in Windows Mixed Reality.
        "thumbstickTurnSmooth" : false
    }
    
**Example 2: Enabling smooth turn**

    "driver_Holographic_Experimental" : {
        "thumbstickTurnLeftEnabled" : false,
        "thumbstickTurnRightEnabled" : true,

        // Some people may experience increased discomfort such as nausea, motion sickness, dizziness,
        // disorientation, headache, fatigue, or eye strain when using “smooth turns” in Windows Mixed Reality.
        "thumbstickTurnSmooth" : true
    }
    
## Sharing feedback on SteamVR

Your feedback is invaluable when it comes to improving the Windows Mixed Reality SteamVR experience. Please submit all feedback and bugs through the [Windows Feedback Hub](filing-feedback.md). Please follow these suggestions to help us get the most from your feedback: 
1. In Feedback Hub, indicate that you're reporting a new Problem in the "What kind of feedback is it?" section at the top.
2. Select the **Mixed Reality** category and the **Apps** subcategory.
3. Put the word "SteamVR" in the problem summary. That helps us find your feedback.
4. Describe what SteamVR game or application you were using when you encountered the issue.
5. Please consider attaching a SteamVR System Report to your feedback. This provides additional logs that can help us diagnose your problem. 
    1. On the SteamVR Window (the small windows that shows your controller status) click on the title to open the menu.
    2. Select "Create System Report"
    3. Save to File
    4. Attach the file to your Feedback Hub entry directly.
6. If your feedback is about SteamVR performance, please collect a Mixed Reality Performance trace: 
    1. Click the **Recreate my Problem** button
    2. In the drop down next to "include data about" select **Mixed Reality Performance** 
    3. Make sure the game is running and click **Start Capture**
    4. Spend a few seconds playing the game to capture the trace. Please do not capture the trace for more than 10-15 seconds, or it will be too large to submit.
    5. Click **Stop Capture**.
7. Click **Submit** once you have completed the rest of the fields.

If you have questions or comments to share, you can also reach us on our [Steam forum](http://steamcommunity.com/app/719950/discussions/). 

## See also
* [Troubleshooting SteamVR with Windows Mixed Reality](troubleshooting-windows-mixed-reality.md#steamvr)
* [Using games and apps in Windows Mixed Reality](using-games-and-apps-in-windows-mixed-reality.md)
* [Minimum PC hardware guidelines](windows-mixed-reality-minimum-pc-hardware-compatibility-guidelines.md)
* [Filing bugs and feedback](filing-feedback.md)
