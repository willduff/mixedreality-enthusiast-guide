---
title: Mixed Reality software overview and release history
description: An overview of the major software components for Windows Mixed Reality, and their release history
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, software components, release history, release notes, version history
---


# Mixed Reality software overview and release history

## Introduction to Mixed Reality software

Windows Mixed Reality consists of the following major software components:

1. **Mixed Reality Portal**, a key component of the Windows 10 operating system. Support for Windows Mixed Reality requires Version 1709 (the Fall Creator's Update) or newer
2. The **Mixed Reality feature-on-demand package** (FOD), automatically downloaded and installed during Mixed Reality Portal's first-run. More information about the FOD package can be found [here](https://docs.microsoft.com/en-us/windows/application-management/manage-windows-mixed-reality)
3. The **Mixed Reality headset and motion controller driver** (also known as the HoloLens Sensors driver.) This is automatically downloaded and installed via Windows Update the first time your Mixed Reality headset is plugged in
4. The **Mixed Reality motion controller model drivers**, which contains the 3D models of the Mixed Reality motion controllers and needed for third-party Mixed Reality experiences. This is automatically downloaded and installed via Windows Update the first time your Mixed Reality motion controllers are paired to your PC

In addition, using Windows Mixed Reality in SteamVR requires the following software:

5. **SteamVR**, developed and maintained by Valve Corporation that enables virtual reality apps and games on Steam. More information can be found [here](https://go.microsoft.com/fwlink/?linkid=862788)
6. The **Windows Mixed Reality for SteamVR** component, which bridges SteamVR with Windows Mixed Reality. More information about this component can be found [on the Windows Mixed Reality for SteamVR page](http://store.steampowered.com/app/719950/Windows_Mixed_Reality_for_SteamVR/)


## Release history ##

### Mixed Reality headset and motion controller driver release history ###

This driver is automatically downloaded and installed via Windows Update, but download links are provided inline:

   | Version          | Release Date          | Major changes                                                 |
   |------------------|-----------------------|---------------------------------------------------------------|
   | 10.0.16299.1070  | February 6th, 2018    | <ul><li>No major changes</li></ul> |
   | [10.0.16299.1062](https://www.microsoft.com/en-us/download/details.aspx?id=56332)  | December 19th, 2017   | <ul><li>Resolves HID issue leading to *Something Went Wrong* error code 2181038087-7 on some PCs</li><li>Various stability and reliability fixes</li></ul> |
   | [10.0.16299.1058](https://www.microsoft.com/en-us/download/details.aspx?id=56277)  | December 5th, 2017    | <ul><li>Improved headset tracking</li><li>Resolves issue where driver installation could sometimes fail</li><li>Various stability and reliability fixes</li></ul> |
   | [10.0.16299.1042](https://www.microsoft.com/en-us/download/details.aspx?id=56265)  | November 21st, 2017   | <ul><li>Resolves an issue that led to headset displays sometimes going black during use</li><li>Resolves an issue that led to Motion Controllers disappearing</li><li>Presence sensor performance improvements for the Dell Visor headset</li><li>Various stability and reliability fixes</li></ul> |
   | 10.0.16299.1036  | November 7th, 2017    | <ul><li>Motion Controller throwing mechanic improvements:<ul><li>Velocity will now be reported properly when position accuracy is approximate, so you can now throw behind your head!</li><li>Example code for throwing can be found in the "ThrowingStarter" unity package [here](https://github.com/keluecke/MixedRealityToolkit-Unity/tree/master/External/Unitypackages/). Open the throwing scene to get started</li></ul></li><li>Improved Motion Controller battery reporting</li><li>Various stability and reliability fixes</li></ul> |
   | 10.0.16299.1012  | October 17th, 2017    | Initial public release of the driver                              |

### SteamVR release history ###

Valve's release notes for SteamVR can be found here: [https://steamcommunity.com/app/250820](https://steamcommunity.com/app/250820)

### Windows Mixed Reality for SteamVR Release History ###

Our release notes for the Windows Mixed Reality for SteamVR component can be found here: [http://steamcommunity.com/games/719950/announcements/](http://steamcommunity.com/games/719950/announcements/)
