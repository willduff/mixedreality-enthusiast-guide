---
title: Windows Mixed Reality minimum PC hardware compatibility guidelines
description: Chart outlining the minimum PC system requirements for compatibility with Windows Mixed Reality.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Ultra, compatible, compatibility, system requirements, PC
---


# Minimum PC hardware guidelines

>[!NOTE]
>Guidelines for development PCs are higher than those for consumers' PCs running mixed reality apps. If you're a mixed reality developer, [see recommended development PC specifications](https://developer.microsoft.com/en-us/windows/mixed-reality/install_the_tools#immersive_headset_development).

Performance may vary depending on your exact setup. You'll also need to make sure your PC has the [right ports](recommended-adapters-for-windows-mixed-reality-capable-pcs.md) for the Windows Mixed Reality immersive headset that you are using.

## Windows Mixed Reality PC Check app

The **[Windows Mixed Reality PC Check](windows-mixed-reality-pc-check-app.md)** app is the best way to make sure your PC is ready to run Windows Mixed Reality. 


<table>
  <tr>
    <td></td>
    <td></td>
    <td><a href="https://www.microsoft.com/store/productid/9NZVL19N7CNC"><img alt="Windows Mixed Reality PC Check app icon" width="90" height="90" src="images/Store-icon-windows-mixed-reality-pc-check.png"/></a></td>
    <td><a href="https://www.microsoft.com/store/productid/9NZVL19N7CNC">Download the app for free <br> from the Microsoft Store</a></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

Upon running the app, you'll get one of the following messages:
* **You're good to go.** Your PC has what it takes to run Windows Mixed Reality.
* **You’re nearly there.** This PC may be able to run Windows Mixed Reality, but some features might be limited.
* **Can't run mixed reality.** This PC doesn't meet the minimum requirements needed to run Windows Mixed Reality.

You will then get an analysis of your PC against the required hardware, drivers, and operating system.
![Screenshot of Windows Mixed Reality PC Check](images/screenshot-mr-pc-check.jpg) 

<table>
<tr>
<th>Icon</th><th>What it means</th>
</tr><tr>
<td> <img alt="Succeeded" width="30" height="30" src="images/glyph-succeeded.png" /></td><td style="vertical-align: middle">Your PC passes the required item.</td>
</tr><tr>
<td> <img alt="Warning" width="30" height="30" src="images/glyph-warning.png" /></td><td style="vertical-align: middle">There may be issues with your PC for the given requirement. If you encounter issues, you may need to troubleshoot or upgrade your PC.</td>
</tr><tr>
<td> <img alt="Error" width="30" height="30" src="images/glyph-error.png" /></td><td style="vertical-align: middle">Your PC does not meet the requirements for the specified item.</td>
</tr>
</table>

## Compatibility guidelines
> [!IMPORTANT]
> We will be updating, making additions to and may be revising these Windows Mixed Reality PC Compatibility Guidelines. Please check back regularly for the latest guidelines and requirements.

<table>
<tr>
<th style="width:20%"></th><th style="vertical-align: middle; text-align: center; width:40%">Windows Mixed Reality Ultra PCs</th><th style="vertical-align: middle; text-align: center; width:40%">Windows Mixed Reality PCs</th>
</tr><tr>
<td style="vertical-align: middle">Operating System</td><td colspan="2" style="vertical-align: middle; text-align: center;">Windows 10 Fall Creators Update (RS3) - Home, Pro, Business, Education</td>
</tr><tr>
<td style="vertical-align: middle">Processor</td><td style="vertical-align: middle; text-align: center;">Intel Core i5 4590 (4th generation), quad-core (or better) <br>AMD Ryzen 5 1400 3.4Ghz (desktop), quad-core (or better)</td><td style="vertical-align: middle; text-align: center;">Intel Core i5 7200U (7th generation mobile), dual-core with Intel&#174; Hyper-Threading Technology enabled (or better)</td>
</tr><tr>
<td style="vertical-align: middle">RAM</td><td style="vertical-align: middle; text-align: center;">8GB DDR3 (or better)</td><td style="vertical-align: middle; text-align: center;">8GB DDR3 dual channel (or better)</td>
</tr><tr>
<td style="vertical-align: middle">Free disk space</td><td colspan="2" style="vertical-align: middle; text-align: center;">At least 10 GB</td>
</tr><tr>
<td style="vertical-align: middle">Graphics Card</td><td style="vertical-align: middle; text-align: center;">NVIDIA GTX 960/1050 (or greater) DX12-capable discrete GPU <br>AMD RX 460/560 (or greater) DX12-capable discrete GPU <br>GPU must be hosted in a PCIe 3.0 x4+ Link slot</td><td style="vertical-align: middle; text-align: center;">Integrated Intel&#174; HD Graphics 620 (or greater) DX12-capable integrated GPU <a href="https://en.wikipedia.org/wiki/List-of-Intel-graphics-processing-units#Ninth-generation">(check if your model is greater)</a> <br>NVIDIA MX150/965M (or greater) DX12-capable discrete GPU</td>
</tr><tr>
<td style="vertical-align: middle">Graphics Driver</td><td style="vertical-align: middle; text-align: center;">Windows Display Driver Model (WDDM) 2.2</td><td style="vertical-align: middle; text-align: center;">Windows Display Driver Model (WDDM) 2.2</td>
</tr><tr>
<td style="vertical-align: middle"><a href="Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md">Graphics display port</a></td><td style="vertical-align: middle; text-align: center;">HDMI 2.0 or DisplayPort 1.2</td><td style="vertical-align: middle; text-align: center;">HDMI 1.4 or DisplayPort 1.2</td>
</tr><tr>
<td style="vertical-align: middle">Display</td><td colspan="2" style="vertical-align: middle; text-align: center;">Connected external or integrated VGA (800x600) display (or better)</td>
</tr><tr>
<td style="vertical-align: middle"><a href="Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md">USB connectivity</a></td><td colspan="2" style="vertical-align: middle; text-align: center;">USB 3.0 Type-A or Type-C</td>
</tr><tr>
<td style="vertical-align: middle">Bluetooth connectivity (for <a href="Motion-controllers.md">motion controllers</a>)</td><td colspan="2" style="vertical-align: middle; text-align: center;">Bluetooth 4.0</td>
</tr><tr>
<td style="vertical-align: middle">Expected headset framerate</td><td style="vertical-align: middle; text-align: center;">90 Hz</td><td style="vertical-align: middle; text-align: center;">60 Hz</td>
</tr>
</table>

**Additional information:**
* Larger laptops (with screens of at least 15") perform best.
* Hybrid graphics configurations are compatible only with a Windows Mixed Reality Ultra setup. The hybrid system’s discrete card must meet the same specifications listed for Windows Mixed Reality Ultra above.
* Different headsets may require different hardware ports, so make sure your PC has the correct ports or [necessary adapters](Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md) to connect to your headset.

>[!NOTE]
>Discrete and integrated graphics hardware that don't meet the minimum confirmed specifications have not been tested, confirmed, or optimized for Windows Mixed Reality and may not function properly or at all.

## Windows Mixed Reality and Surface

Surface Book 2, Surface Studio, Surface Laptop and Surface Pro (2017) support Windows Mixed Reality when equipped with an Intel Core i5 CPU (or better) and at least 8GB of RAM.

**Requirements:**
* Surface products require driver updates to be compatible with Windows Mixed Reality. These drivers can be installed on your Surface by going to **Settings > Update and Security > Check for Updates**.
* Surface products require an [adapter](Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md) from the video port (Mini DisplayPort or USB-C) to HDMI 2.0 for Windows Mixed Reality headsets. The most recent version of the Surface Mini DisplayPort to HDMI AV Adapter is compatible with HDMI 2.0 (the older version is not). Similarly, the new <a href="https://www.microsoft.com/en-us/store/d/surface-usb-c-to-hdmi-adapter/94chb2m80s54/4gj5">Surface USB-C to HDMI Adapter</a> is also compatible with HDMI 2.0.

>[!WARNING]
>Not all Mini DisplayPort or USB-C to HDMI adapters are HDMI 2.0-capable. Consider checking for explicit “HDMI 2.0” compatibility or “4K” compatibility on any adapter.

More information on Surface compatibility with Windows Mixed Reality is available in the table below:

<table>
	<tr>
		<th> Surface </th><th> Windows Mixed Reality supported? </th><th> Minimum configuration </th><th> Notes</th>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Pro (original)/ Surface Pro 2 </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Pro 3 </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Pro 4 </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface 3 </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Book </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Book with Performance Base </td><td style="vertical-align: middle"> No </td><td> </td><td></td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Pro (2017) </td><td style="vertical-align: middle"> Yes </td><td style="vertical-align: middle"> Intel 7th generation Core i5/i7 with 8GB of RAM or more </td>
		<td>
			<ul>
				<li>Requires HDMI 2.0-compatible Mini DisplayPort adapter</li>
				<li>Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li>
				<li>Achieves Windows Mixed Reality (60Hz) experience</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Book 2 (13.5&quot; and 15&quot;) </td><td style="vertical-align: middle"> Yes </td><td style="vertical-align: middle"> All configurations </td>
		<td>
			<ul>
				<li>Requires <a href="https://www.microsoft.com/en-us/store/d/surface-usb-c-to-hdmi-adapter/94chb2m80s54/4gj5">Surface USB-C to HDMI Adapter</a> (other adapters may work, but are untested)</li>
				<li>Configurations with only the Intel HD Graphics 620 integrated GPU achieve Windows Mixed Reality (60Hz) experience</li>
				<li>Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li>
				<li>Configurations with NVIDIA GeForce GTX 1050 and 1060 discrete GPU achieve Windows Mixed Reality (90Hz) experience</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Studio </td><td style="vertical-align: middle"> Yes </td><td style="vertical-align: middle"> All configurations </td>
		<td>
			<ul>
				<li>Requires HDMI 2.0-compatible Mini DisplayPort adapter</li><li>Windows Mixed Reality headset must be connected to USB port with “+” symbol</li>
				<li>Configurations with NVIDIA GeForce GTX 965m achieve Windows Mixed Reality (60Hz) experience.</li>
				<li>Configurations with NVIDIA GeForce GTX 980m achieve Windows Mixed Reality (90Hz) experience.</li>
				<li>Requires installation of Windows Mixed Reality <a href="https://www.microsoft.com/en-us/download/details.aspx?id=54311">preview drivers</a>. Final drivers will be published to Windows Update when available.</li>
			</ul>
		</td>
	</tr>
	<tr>
		<td style="vertical-align: middle"> Surface Laptop </td><td style="vertical-align: middle"> Yes </td><td style="vertical-align: middle"> Intel 7th generation Core i5/i7 with 8GB of RAM or more </td>
		<td>
			<ul>
				<li>Requires HDMI 2.0-compatible Mini DisplayPort adapter</li><li>Requires <a href="https://support.microsoft.com/en-us/help/4023450/surface-surface-battery-and-power">Performance Slider</a> set to “Best Performance” during usage</li><li>Achieves Windows Mixed Reality (60Hz) experience</li>
			</ul>
		</td>
	</tr>
</table>


## See also
* [Recommended adapters for Windows Mixed Reality capable PCs](recommended-adapters-for-windows-mixed-reality-capable-pcs.md)
* [Windows Mixed Reality PC Check app](windows-mixed-reality-pc-check-app.md)
