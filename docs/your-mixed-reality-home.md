---
title: Your mixed reality home
description: How to navigate and teleport within the Windows Mixed Reality home, launch apps and games, personalize the home, and change visual, audio, and speech settings.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Home, Navigate, Get around, apps, games
---


# Your mixed reality home

## What is the mixed reality home?

Windows Mixed Reality is the first spatial operating system. Instead of using a flat screen and a 2D interface, it leverages our instinctual ability to navigate three-dimensional space. Every place has a purpose, and content has context. Just as your PC starts at the desktop interface and your phone begins with a home screen, Windows Mixed Reality starts at the mixed reality home. It's an environment that you can navigate and personalize to make your own. It's the canvas for the thousands of apps available in the Microsoft Store. You can multitask with these apps like you've never been able to before--in 3D where space almost limitless. 

## How do I move through the mixed reality home?
* **Physically walking:** If you have setup your headset with a room boundary and have cleared available space to safely walk around, you can take physical steps to move short distances in your home. One step in the real world is approximately a step in the virtual experience.
* **Teleporting (using motion controllers):** You can quickly jump to a location by teleporting. Using the motion controllers, you can teleport by pushing the right or left thumbstick forward, aiming towards the direction you want to go, and then releasing the thumbstick.
* **Teleporting (using gamepad):** Using a gamepad, you can teleport by pushing the left thumbstick forward.
* **Teleporting (using mouse):** Using a mouse, hold down the right-click mouse button and release at your desired location.
  * You can modify the direction you teleport in for all the above inputs by rotating the thumbstick (for the motion controllers and gamepad) or by using the scroll wheel on the mouse.
  * A handy feature is called "Snap to app" that lets you jump to the ideal position to interact with app windows. Simply point you teleportation arc to a window and let go. The system will automatically place you in the ideal location to enjoy the content of that targeted window.
* **Virtually walking:** You can virtually move continuously by depressing the thumbstick (you should feel it click) on your motion controllers or gamepad and then moving in the desired direction.

## How do I launch an app?

1. From your mixed reality home, press the Windows button on your controller to launch the Start menu. 
2. Select the app you wish to launch. 
3. Place the app where you would like to use it.

## How do I browse the web?

1. Press the Windows button on your controller to open the Start menu.
2. Launch Microsoft Edge.

## How do I play music?

1. Press the Windows button on your controller to open the Start menu.
2. Launch Groove Music.

## How do I download an app?

1. Press the Windows button on your controller to open the Start menu.
2. Launch Microsoft Store.
3. Browse for an app or game you want, and then click "Get" or "Buy."

Alternatively, you can use the "New for you" app to browse for content, which appears as a shopping bag in your mixed reality home.

## What is the "New for you" app?

You may notice that there is a Microsoft Store bag in your mixed reality home. Clicking it will show you new and exciting apps that you can download and/or purchase.

## How do I personalize my home?

You can decorate your home with apps and holograms. Apps can be downloaded from the Microsoft Store. You can also use the Holograms app to place objects in your home.

You can adjust the location and size of things in your home by using the Adjust button. You can also use two motion controllers to quickly move and resize items by pointing to any part of a hologram, or the menu bar of an app window, with both controllers and then moving them closer or farther apart.

## How do I go to the roof?

To get to the roof, start in the yard facing the mountain. Use the platforms to the right to teleport up to the roof.

## How do I change the visual quality settings?

To change the visual quality settings, go to **Settings > Mixed Reality > Visual Quality**. From this screen you can set the quality to low, medium, or high. The Automatic setting directs Windows Mixed Reality to select the best setting for your PC hardware. Note, that not all hardware will run the high setting.

## How do I reset my home's furniture and app placement back to default?

Go to **Settings > Mixed Reality > Environment > Reset my home** ![Windows Settings panel to reset my home](images/1050px-environmentreset.png)

## How do I uninstall Windows Mixed Reality?
1. Unplug your headset
2. Close Mixed Reality Portal
3. Go to **Settings > Mixed Reality > Uninstall > Uninstall** ![Windows Settings panel to uninstall mixed reality](images/1050px-uninstall2.png)

## What is the maximum size of the boundary?
The currently supported maximum boundary size in Windows Mixed Reality is 18x18ft (5.7x5.7m) or 13ft (4m) radius from the center.  The boundary size is dependent on the anchor point and how far from the anchor point you can move before you risk the stability of the boundary.  Windows Mixed Reality is built on a stage abstraction in the platform, the stage being the space you move around in, and that stage depends on a single anchor (which nearly every app also assumes – it’s how Vive and Oculus work too, as they only have a single coordinate system).  The reason that this is important is that with inside-out tracking, as you move further away from an anchor point the headset tracking is reliable at keeping the boundary stable.  Where the boundary is intended to help avoid physical obstacles, it becomes more and more of a problem the further out from the center you go.  Two factors went into the decision on maximum boundary size; the maximum distance at which Windows Mixed Reality headsets could provide the best room scale experience with a boundary and the length of the headset cable, which for most Windows Mixed Reality headsets is 10ft (3m). 

## How do I turn off the boundary?

Go to Mixed Reality Portal and open the menu in the upper left of the screen. Select **Run Set up > Room Boundary**. Switch the toggle to OFF. You should remain seated at your desk if you turn off the boundary.

## How does spatial sound work in the Windows Mixed Reality home?

The Windows Mixed Reality home includes a spatial sound simulation where sound from each app come from the location of the app. As you turn around, or move closer or farther to the app, the sound direction and volume will change, just like in real life.

## How do I use voice commands and Cortana inside of the Windows Mixed Reality home?

[Learn the voice commands you can use in the Windows Mixed Reality home](https://support.microsoft.com/en-us/help/4041322/windows-10-speech-in-windows-mixed-reality)

## How can I show a preview of what I'm seeing in my headset on my desktop's screen?

Just press the **Play** icon at the bottom of the Mixed Reality Portal app. 

> [!NOTE]
> This feature is disabled on PCs with integrated graphics due to the load placed on the GPU.

## See also

* [Troubleshooting the Windows Mixed Reality home](troubleshooting-windows-mixed-reality.md#windows-mixed-reality-home)
* [Using games and apps in Windows Mixed Reality](using-games-and-apps-in-windows-mixed-reality.md)
* [How inside-out tracking works](tracking-system.md)
* [How motion controllers work](motion-controllers.md)
* [Using WebVR with Windows Mixed Reality](webvr.md)
* [Using SteamVR with Windows Mixed Reality](using-steamvr-with-windows-mixed-reality.md)
* [Filing bugs and feedback](filing-feedback.md)
