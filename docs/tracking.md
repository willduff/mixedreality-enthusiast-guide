---
title: Tracking FAQs
description: Advanced Windows Mixed Reality troubleshooting that goes beyond our standard consumer support documentation.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Troubleshoot, Errors, Help, Support, Tracking
---


# Tracking FAQs

## My headset has stopped tracking.

Make sure the lights are on, and that there isn't anything obstructing the inside-out tracking cameras on the front of your headset. If tracking is lost, it can take a few seconds to resume. If it doesn't resume, restart the Windows Mixed Reality Portal. 

## I can look around but I can't translate (I'm stuck in 3DOF).

This means that the tracking system cannot generate pose, or the application has stopped using new pose data to render. Check the following:
* Make sure the room has enough light.
* Make sure the room has enough details to track.
* Unplug the device, close Windows Mixed Reality, and plug in the device again.
* If the message persists, contact [customer support](https://support.microsoft.com/)

## The view in the HMD is completely frozen.

This usually means the application or a system level component has failed. Try to:
1. Press the "home" button to leave the application.
2. Unplug the device, close MRP and plug the device back in.
3. Restart the PC.

## The view in the headset is jittering and stuttering a lot.

The system may not be able to render content to the headset, or the tracking system may be experiencing problems. Check the following:
1. Open Task Manager to make sure that your PC has enough compute resources. You should have 80% of CPU free, 400MB of RAM, and disk IO should be below 80%.
2. Make sure you have the latest graphics drivers for your hardware. See the [graphics driver section](before-you-start.md#make-sure-you-have-a-compatible-graphics-driver).
3. Make sure the room has enough light.
4. Unplug the device, close Windows Mixed Reality, and plug it in again.
5. Restart your PC.
6. If the problem persists, contact [customer support](https://support.microsoft.com/).

## The world briefly froze and perhaps tilted or flipped upside down before returning to normal.

This could be caused by an application or system level component hitting a fatal error, or a temporary lack of memory or CPU resources. To check:
1. Open Task Manager and ensure that at least 20% of the CPU is free, 400MB of memory is available and disk IO should be below 80%.
2. Go to **Event Viewer > Windows Logs > Application** to look for any errors from around the time of the freeze. Look for anything that refers to HoloLens sensors, Mixed Reality, or the application that you were running around that time. Those logs might explain what caused the failure.
3. Restart the PC if the problem persists.

## The world flipped upside down momentarily and returned to normal.

This is typically caused by errors in obtaining sensor data from the headset to inform the tracking algorithms. If this happens frequently:
1. Plug the headset into a different USB 3.0 port.
2. Plug the headset directly into the PC rather than into a USB 3.0 hub.
3. If the problem persists, contact [customer support](https://support.microsoft.com/).

## The world is tilted but I can navigate and walk around in Windows Mixed Reality.

If sensor data errors are recorded into the environment data on your PC, it can cause Windows Mixed Reality to appear tilted, sometimes permanently. To fix this:
1. Unplug the headset, close Windows Mixed Reality and plug the headset back in.
2. Restart the PC.
3. Clear your environment data.

