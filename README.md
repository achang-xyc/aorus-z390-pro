<img src="https://i.postimg.cc/HsP2c9cn/pic.png" alt="" width="599" height="400" />
<h2>iMac19,1</h2>
<ul>
<li>Aorus Z390 Pro/Pro WiFi</li>
<li>Intel i7 9700K</li>
<li>32GB RAM (2666Hz)</li>
<li>Sapphire Radeon RX 5700 XT</li>
<li>Samsung EVO 970 Pro Plus 500GB</li>
</ul>

<h2>BIOS Settings (F12d/F12c)</h2>
<ul>
<li>Boot -> Windows 8/10 Features -> Win 8/10WHQL﻿</li>
<li>Boot -> CSM Support -> Disabled</li>
<li>Favourites -> Extreme Memory Profile (X.M.P.) -> Profile1</li>
<li>Favourites -> VT-d -> Disabled</li>
<li>Settings -> IO Ports -> USB Configuration -> XHCI Hands-off -> Enabled</li>
<li>Settings -> IO Ports -> Internal Display Output -> PCIe 1 Slot</li>
<li>Settings -> IO Ports -> Internal Graphics -> Enabled</li>
<li>Settings -> IO Ports -> DVMT Pre-Allocated -> 32M</li>
<li>Settings -> IO Ports -> DVMT Total GFX0-Allocated -> 256M</li>
<li>Settings -> IO Ports -> Aperture Size -> 256MB</li>
<li>Settings -> IO Ports -> Audio Controller -> Enabled</li>
<li>Settings -> IO Ports -> Above 4G Decoding -> Enabled</li>
<li>Settings -> IO Ports -> USB Configuration -> Legacy USB Support -> Disabled</li>
<li>Settings -> IO Ports -> USB Configuration ->  XHCI Hand-off -> Enabled</li>
<li>Settings -> Miscellaneous -> Software Guard Extensions (SGX) -> Disabled﻿</li>
<li>Settings -> Platform Power -> Platform Power Management -> Enabled</li>
<li>Settings -> Platform Power -> ErP -> Enabled</li>
<li>Settings -> Platform Power -> RC6(Render Standby) -> Enabled</li>
 </ul>

<h2>USB Port Map</h2>
<img src="https://i.postimg.cc/FKJN5pcL/ports.png" alt="" width="450" height="500" />
<ul>
<li>HS01 – Unused</li>
<li>HS02 – Unused</li>
<li>SS01 – USB-C (case)</li>
<li>SS02 – USB-C (case)</li>
<li>HS/SS03 – USB3</li>
<li>HS/SS04 – USB3</li>
<li>HS/SS05 – USB3</li>
<li>HS/SS06 – USB-C (with switch)</li>
<li>HS/SS07 – USB3</li>
<li>HS/SS08 – USB3</li>
<li>HS/SS09 – USB3 (case)</li>
<li>HS/SS10 – USB3 (case)</li>
<li>HS11 – Internal USB 2.0 Header (WiFi/BT card)</li>
<li>HS12 – Unused</li>
<li>HS13 – 4xUSB2.0</li>
</ul>

<img src="https://i.postimg.cc/FKJN5pcL/ports.png" alt="" width="450" height="500" />
<p>Hackintool USB output. Each port has been tested with a USB2.0 and USB3.X device and shows correct assignment (Internal on HS11 hub and ISB-C with switch on HS/SS06). To mirror an iMac more closely, ports SS01/02 can be enabled (either for an external case or to provide macOS the exact port number layout.)

<h2>About</h2>
<p>A highly modified version of AudioGod's <a href="https://www.insanelymac.com/forum/topic/339980-audiogods-aorus-z390-pro-patched-dsdt-mini-guide-and-discussion/">Z390 Build</a>. <em>Remember to complete the PlatformInfo block with your uique serial, ROM, etc.</em></p>
