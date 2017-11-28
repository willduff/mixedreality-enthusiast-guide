---
title: Check your compatibility
description: How to make sure your PC is compatible with, and ready for, Windows Mixed Reality.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, compatible, compatibility, get started, setup, PC, system requirements
---


# Check your compatibility

## Make sure your PC is connected to the internet

Check that your PC is connected to the Internet. You will need to do bit of downloading to get mixed reality up and running.

## Make sure you have the Windows 10 Fall Creators Update installed

You must be running the Windows 10 Fall Creators Update to run Windows Mixed Reality. You can check this by running winver.exe: **Start > Run > winver.exe**. The Version should be **1709**.

## Make sure your PC is compatible with Windows Mixed Reality

**Download and run the app:** Launch the Store app from your Desktop, search for the **Windows Mixed Reality PC Check App** and click "Get" to download and install it. You can also [follow this link](https://aka.ms/mrcheck) to launch the correct Store page.

![Mixed Reality PC Check App](images/700px-mrpccheck.png)

After the app has installed, run the app. After reading the terms and conditions, press **I agree** to accept.

![PC Compat Check](images/700px-pccompatcheck.png)

**See if your PC is compatible with Windows Mixed Reality:** You should get results that look similar to the image below. **Green** checks mean your PC passed the required item! **Orange** triangles mean that there may be issues with your PC for the given requirement. If you encounter issues, you may need to troubleshoot or upgrade your PC. **Red** X's mean your PC does not meet the requirements for the specified item. For more information on troubleshooting issues with PC Compatibility go [here](https://support.microsoft.com/en-us/help/4045777/windows-10-get-help-with-pc-compatibility-in-windows-mixed-reality).

![Good to go](images/700px-goodtogo.png)

## Windows Mixed Reality and Surface

Surface Book 2, Surface Studio, Surface Laptop and Surface Pro (2017) support Windows Mixed Reality when equipped with an Intel Core i5 CPU (or better) and at least 8GB of RAM.

Surface products require driver updates to be compatible with Mixed Reality. These drivers can be installed on your Surface by going to **Start** -> **Settings** -> **Update and Security** -> **Check for Updates**.
Surface products require an adapter from the video port (Mini DisplayPort or USB-C) to HDMI 2.0 for Windows Mixed Reality Headsets. The most recent version of the Surface Mini DisplayPort to HDMI AV Adapter is compatible with HDMI 2.0. Similarly, the new Surface USB-C to HDMI Adapter is also compatible with HDMI 2.0.

**Note:** not all Mini DisplayPort or USB-C to HDMI adapters are HDMI 2.0-capable. Consider checking for explicit “HDMI 2.0” compatibility or “4K” compatibility on any adapter.

More information on Surface compatibility with Windows Mixed Reality is available in the table below.

<table>
	<tr bgcolor="#D3D3D3">
		<th style="border: solid 1px black;"> Surface </th><th style="border: solid 1px black;"> Windows Mixed Reality Supported? </th><th style="border: solid 1px black;"> Minimum Configuration </th><th style="border: solid 1px black;"> Notes</th>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Pro</b> (original) <b>/ Surface Pro 2</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Pro 3</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Pro 4</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface 3</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Book</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Book with Performance Base</b> </td><td style="border: solid 1px black;"> No </td><td style="border: solid 1px black;"> </td><td style="border: solid 1px black;"></td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Pro (2017)</b> </td><td style="border: solid 1px black;"> Yes </td><td style="border: solid 1px black;"> Intel 7th-Gen Core i5/i7 min 8GB of RAM or more </td>
		<td style="border: solid 1px black;">
			<ul>
				<li>Requires HDMI 2.0-compatible Mini Display Port adapter</li>
				<li>Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li>
				<li>Achieves Windows Mixed Reality (60Hz) experience</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Book 2 (13.5&quot; and 15&quot;)</b> </td><td style="border: solid 1px black;"> Yes </td><td style="border: solid 1px black;"> All Configurations </td>
		<td style="border: solid 1px black;">
			<ul>
				<li>Requires HDMI 2.0-compatible USB C adapter</li>
				<li>Configurations with only the Intel HD Graphics 620 integrated GPU achieve Windows Mixed Reality (60Hz) experience, Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li>
				<li>Configurations with NVIDIA GeForce GTX 1050 and 1060 discrete GPU achieve Windows Mixed Reality (90Hz) experience</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Studio</b> </td><td style="border: solid 1px black;"> Yes </td><td style="border: solid 1px black;"> All Configurations </td>
		<td style="border: solid 1px black;">
			<ul>
				<li>Requires HDMI 2.0-compatible Mini Display Port adapter</li><li>Windows Mixed Reality HMD must be connected to USB port with “+” symbol</li>
				<li>Configurations with NVIDIA GeForce GTX 965m achieve Windows Mixed Reality (60Hz) experience.</li>
				<li>Configurations with NVIDIA GeForce GTX 980m achieve Windows Mixed Reality (90Hz) experience.</li>
				<li>Requires installation of Mixed Reality <a href="https://www.microsoft.com/en-us/download/details.aspx?id=54311">preview drivers</a>. Final drivers will be published to Windows Update when available.</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="border: solid 1px black;"> <b>Surface Laptop</b> </td>
		<td style="border: solid 1px black;"> Yes </td>
		<td style="border: solid 1px black;"> Intel 7th-Gen Core i5/i7 min 8GB of RAM or more </td>
		<td style="border: solid 1px black;">
			<ul>
				<li>Requires HDMI 2.0-compatible Mini Display Port adapter</li><li>Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li><li>Achieves Windows Mixed Reality (60Hz) experience</li>
			</ul>
		</td>
	</tr>
</table>

## See also

* [Plug in your headset](plug-in-your-headset.md)
