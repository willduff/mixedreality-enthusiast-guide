---
title: Windows Mixed Reality minimum PC hardware compatibility guidelines
description: Chart outlining the minimum PC system requirements for compatibility with Windows Mixed Reality.
ms.topic: article
keywords: Windows Mixed Reality, Mixed Reality, Virtual Reality, VR, MR, Ultra, compatible, compatibility, system requirements, PC
---


# Minimum PC hardware guidelines

**NOTE:** guidelines for development PCs are higher than those for consumers' PCs running mixed reality apps.

Performance may vary depending on your exact setup. You'll also need to make sure your PC has the [right ports](recommended-adapters-for-windows-mixed-reality-capable-pcs.md) for the Windows Mixed Reality immersive headset that you are using.

## Windows Mixed Reality PC Check app

![Screenshot of Windows Mixed Reality PC Check](images/screenshot-mr-pc-check.jpg) 
<a class="doc-storelink" href="https://www.microsoft.com/store/productid/9NZVL19N7CNC"><div>
<div>
Windows Mixed Reality PC Check
</div><div>
Microsoft Corporation
</div><div>
Available for free in the Microsoft Store
</div>
</div><div>
<img alt="Windows Mixed Reality PC Check icon" width="150" height="150" src="images/store-icon-windows-mixed-reality-pc-check.png" />
</div></a>


The *[Windows Mixed Reality PC Check](windows-mixed-reality-pc-check-app.md)* app is the best way to make sure your PC is ready to run mixed reality. Upon running the app, you'll get one of the following messages:
* **You're good to go.** Your PC has what it takes to run Windows Mixed Reality.
* **You’re nearly there.** This PC may be able to run Windows Mixed Reality, but some features might be limited.
* **Can't run mixed reality.** This PC doesn't meet the minimum requirements needed to run Windows Mixed Reality.

You will then get an analysis of your PC against the required hardware, drivers, and operating system.

<table>
<tr>
<th></th><th> What it means</th>
</tr><tr>
<td> <img alt="Succeeded" width="60" height="60" src="images/glyph-succeeded.png" /></td><td> Your PC passes the required item.</td>
</tr><tr>
<td> <img alt="Warning" width="60" height="60" src="images/glyph-warning.png" /></td><td> There may be issues with your PC for the given requirement. If you encounter issues, you may need to troubleshoot or upgrade your PC.</td>
</tr><tr>
<td> <img alt="Error" width="59" height="60" src="images/glyph-error.png" /></td><td> Your PC does not meet the requirements for the specified item.</td>
</tr>
</table>



## Compatibility guidelines
> [!NOTE]
> We will be updating, making additions to and may be revising these Windows Mixed Reality PC Compatibility Guidelines. Please check back regularly for the latest guidelines and requirements.

<table>
<tr>
<th style="width:20%"></th><th style="width:40%">Windows Mixed Reality Ultra PCs<br /><img alt="Windows Mixed Reality Ultra badge" width="104" height="147" src="images/Badge-windows-mixed-reality-ultra-pc.png" /></th><th style="width:40%">Windows Mixed Reality PCs<br /><img alt="Windows Mixed Reality badge" width="103" height="120" src="images/Badge-windows-mixed-reality-pc.png" /></th>
</tr><tr>
<td>Operating System</td><td colspan="2" style="vertical-align: middle; text-align: center;">Windows 10 Fall Creators Update (RS3) - Home, Pro, Business, Education</td>
</tr><tr>
<td>Processor</td><td>Intel Core i5 4590 (4th generation), quad core (or better) AMD Ryzen 5 1400 3.4Ghz (desktop), quad core (or better)</td><td>Intel Core i5 7200U (7th generation mobile), dual core with Intel&#174; Hyper-Threading Technology enabled (or better)</td>
</tr><tr>
<td>RAM</td><td>8GB DDR3 (or better)</td><td>8GB DDR3 dual channel (or better)</td>
</tr><tr>
<td>Free disk space</td><td colspan="2" style="vertical-align: middle; text-align: center;">At least 10 GB</td>
</tr><tr>
<td>Graphics Card</td><td>NVIDIA GTX 960/1050 (or greater) DX12-capable discrete GPU AMD RX 460/560 (or greater) DX12-capable discrete GPU GPU must be hosted in a PCIe 3.0 x4+ Link slot</td><td>Integrated Intel&#174; HD Graphics 620 (or greater) DX12-capable integrated GPU <a href="https://en.wikipedia.org/wiki/List-of-Intel-graphics-processing-units#Ninth-generation">(Check if your model is greater)</a> NVIDIA MX150/965M (or greater) DX12-capable discrete GPU</td>
</tr><tr>
<td>Graphics Driver</td><td>Windows Display Driver Model (WDDM) 2.2 (7/17/2017 or later)</td><td>Windows Display Driver Model (WDDM) 2.2 (7/24/2017 or later)</td>
</tr><tr>
<td><a href="Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md">Graphics display port</a></td><td>HDMI 2.0 or DisplayPort 1.2</td><td>HDMI 1.4 or DisplayPort 1.2</td>
</tr><tr>
<td>Display</td><td colspan="2" style="vertical-align: middle; text-align: center;">Connected external or integrated VGA (800x600) display (or better)</td>
</tr><tr>
<td><a href="Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md">USB connectivity</a></td><td colspan="2" style="vertical-align: middle; text-align: center;">USB 3.0 Type-A or Type-C</td>
</tr><tr>
<td>Bluetooth connectivity (for <a href="Motion-controllers.md">motion controllers</a>)</td><td colspan="2" style="vertical-align: middle; text-align: center;">Bluetooth 4.0</td>
</tr><tr>
<td>Expected headset framerate</td><td>90 Hz</td><td>60 Hz</td>
</tr>
</table>



**Notes:**
* Larger laptops (with screens of at least 15") perform best.
* Hybrid graphics configurations are compatible only with a Windows Mixed Reality Ultra setup. The hybrid system’s discrete card must meet the same specifications listed for Windows Mixed Reality Ultra above.
* Different headsets may require different hardware ports, so make sure your PC has the correct ports or [port adapters](Recommended-adapters-for-Windows-Mixed-Reality-Capable-PCs.md) to connect to your headset.

*Discrete and integrated graphics hardware that don't meet the minimum confirmed specifications have not been tested, confirmed, or optimized for Windows Mixed Reality and may not function properly or at all.*

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
* [Recommended adapters for Windows Mixed Reality capable PCs](recommended-adapters-for-windows-mixed-reality-capable-pcs.md)
