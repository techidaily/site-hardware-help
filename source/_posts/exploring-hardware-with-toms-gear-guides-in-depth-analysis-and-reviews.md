---
title: Exploring Hardware with Tom's Gear Guides - In-Depth Analysis and Reviews
date: 2024-09-04T02:34:12.833Z
updated: 2024-09-05T02:34:12.833Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/Jzk6akrLgxNy3ui2DHcLRi-320-80.jpg
---

## Unveiling Cutting-Edge Gadgets with Tom's Hardware Review

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Intel statement on via oxidation

**Short answer:** We can confirm there was a via Oxidation manufacturing issue (addressed back in 2023) but it is not related to the instability issue.

**Long answer:**   _We can confirm that the via Oxidation manufacturing issue affected some early Intel Core 13th Gen desktop processors. However, the issue was root caused and addressed with manufacturing improvements and screens in 2023\. We have also looked at it from the instability reports on Intel Core 13th Gen desktop processors and the analysis to-date has determined that only a small number of instability reports can be connected to the manufacturing issue._

 _For the Instability issue, we are delivering a microcode patch which addresses exposure to elevated voltages which is a key element of the Instability issue. We are currently validating the microcode patch to ensure the instability issues for 13th/14th Gen are addressed. -_ Intel representative[via Reddit](https://www.reddit.com/r/intel/comments/1e9mf04/comment/lefz09c/) .


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-crafting-cool-youtube-previews-in-imovie-easily/"><u>[New] 2024 Approved  Crafting Cool YouTube Previews in iMovie Easily</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-instagram-innovations-enhancers-that-excite/"><u>[New] 2024 Approved  Instagram Innovations  Enhancers that Excite</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-shine-and-share-the-art-of-crafting-instagram-spotlights-3-ways/"><u>[New] 2024 Approved  Shine and Share  The Art of Crafting Instagram Spotlights (3 Ways)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-soundwave-statements-on-whatsapp-snapshots/"><u>[New] 2024 Approved  Soundwave Statements on WhatsApp Snapshots</u></a></li>
<li><a href="https://article-files.techidaily.com/new-motion-control-in-vr-keeping-nausea-at-bay-for-2024/"><u>[New] Motion Control in VR  Keeping Nausea at Bay for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-tutorial-uploading-youtube-to-instagram-stories-effortlessly/"><u>[Updated] 2024 Approved  Tutorial  Uploading YouTube to Instagram Stories Effortlessly</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-adding-melodies-to-timelines-a-stepwise-guide-iosandroid-for-2024/"><u>[Updated] Adding Melodies to Timelines  A Stepwise Guide (iOS/Android) for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-enhance-your-videos-call-to-action-a-step-by-step-filmora-guide/"><u>[Updated] In 2024, Enhance Your Video's Call-to-Action  A Step-by-Step Filmora Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/amds-newest-processor-the-ryzen-7-9700x-with-zen-5-architecture-claimed-by-enthusiast-early-coming-soon-amd-ready-to-distribute-thousands-from-warehouses-to53/"><u>AMD’s Newest Processor, the Ryzen 7 9700X with Zen 5 Architecture, Claimed by Enthusiast Early – Coming Soon: AMD Ready to Distribute Thousands From Warehouses to Stores</u></a></li>
<li><a href="https://hardware-help.techidaily.com/chinese-tech-breakthrough-loongsons-new-16-core-cpu-goes-head-to-head-with-intels-xeon-silver/"><u>Chinese Tech Breakthrough: Loongson's New 16-Core CPU Goes Head-to-Head with Intel's Xeon Silver</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723208722915-diagnosing-and-repairing-when-you-cant-watch-netflix-solutions-inside/"><u>Diagnosing & Repairing When You Can't Watch Netflix – Solutions Inside</u></a></li>
<li><a href="https://hardware-help.techidaily.com/direct-download-compatible-drivers-for-your-wacom-cintiq-artist-pen-display/"><u>Direct Download: Compatible Drivers for Your Wacom Cintiq Artist Pen Display</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-innovation-at-toms-hardware-leading-tech-insights-unveiled/"><u>Discover Innovation at Tom's Hardware: Leading Tech Insights Unveiled</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-guide-for-the-latest-amd-radeon-3450-graphics-card-drivers/"><u>Effortless Installation Guide for the Latest AMD Radeon 3450 Graphics Card Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-get-your-samsung-m207n-fw-drivers-downloaded-today/"><u>Effortless Installation: Get Your Samsung M207n FW Drivers Downloaded Today</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-gaming-experience-free-drivers-available-for-geforce-gtx-1650-super-on-windows-1011/"><u>Enhance Your Gaming Experience: Free Drivers Available for GeForce GTX 1650 Super on Windows 10/11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-acer-wireless-network-adapter-driver-fast-installation-guide/"><u>Free Acer Wireless Network Adapter Driver - Fast Installation Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/freshly-released-geforce-rtx-2070-driver-update-compatible-with-all-windows-users-free-to-download/"><u>Freshly Released Geforce RTX 2070 Driver Update: Compatible with All Windows Users - Free to Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-intel-uhd-graphics-software-on-windows-11-installation-guide-and-update-tips/"><u>Get the Newest Intel UHD Graphics Software on Windows 11 - Installation Guide & Update Tips</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-latest-asus-dvd-software-step-by-step-downloads/"><u>How to Get the Latest Asus DVD Software: Step-by-Step Downloads</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-sound-quality-with-the-newest-dolby-audio-drivers-for-windows-111081-download-now/"><u>Improve Sound Quality with the Newest Dolby Audio Drivers for Windows 11/10/8.1 - Download Now</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-new-lens-on-cinema-embracing-vr-tech/"><u>In 2024, A New Lens on Cinema  Embracing VR Tech</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-14-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password On your iPhone 14</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-first-steps-in-virtual-conferencing-with-zoom/"><u>In 2024, First Steps in Virtual Conferencing with Zoom</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/iphone-6s-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>iPhone 6s Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-mpow-bluetooth-drivers-for-optimal-performance-on-windows-pcs/"><u>Latest MPOW Bluetooth Drivers for Optimal Performance on Windows PCs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-nvidia-geforce-rtx-ti-drivers-for-enhanced-gaming-on-windows-11/"><u>Latest NVIDIA GeForce RTX 지류티 (Ti) Drivers for Enhanced Gaming on Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-vga-driver-software-download-for-startechs-universal-usb-adapters/"><u>Latest VGA Driver Software - Download for StarTech's Universal USB Adapters</u></a></li>
<li><a href="https://buynow-info.techidaily.com/leveraging-chatgpt-as-an-alternative-dm-tool-in-tabletop-gaming-a-practical-guide/"><u>Leveraging ChatGPT as an Alternative DM Tool in Tabletop Gaming - A Practical Guide</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-top-glitch-video-editing-software-for-windows-and-mac-free-and-paid-options-for-2024/"><u>New Top Glitch Video Editing Software for Windows and Mac Free and Paid Options for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/pc-hdr-optimization-made-simple/"><u>PC HDR Optimization Made Simple</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pioneer-dj-ddj-sx2-usb-driver-for-swift-connection-free-download-available/"><u>Pioneer DJ DDJ-SX2 USB Driver for Swift Connection - Free Download Available</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-download-guide-install-asus-z370-e-motherboard-drivers/"><u>Quick Download Guide: [INSTALL] Asus Z370-E Motherboard Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722962057513-resolving-asus-pce-ac56-wifi-card-compatibility-with-windows-11-8-and-7-solutions-inside/"><u>Resolving ASUS PCE-AC56 WiFi Card Compatibility with Windows 11, 8 & 7: Solutions Inside!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-graphics-and-gaming-new-vga-driver-updates-ready-to-go/"><u>Seamless Graphics and Gaming: New VGA Driver Updates Ready to Go</u></a></li>
<li><a href="https://techtrends.techidaily.com/the-next-gen-pixel-buds-pro-2-teasers-on-pricing-release-schedule-and-features/"><u>The Next-Gen Pixel Buds Pro 2: Teasers on Pricing, Release Schedule, and Features</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-ultimate-blueprint-for-branding-success-on-snapchat-for-2024/"><u>The Ultimate Blueprint for Branding Success on SnapChat for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-ultimate-solution-to-fixing-intel-dynamic-platform-and-thermal-frameworks-failed-driver-setup/"><u>The Ultimate Solution to Fixing Intel Dynamic Platform & Thermal Framework's Failed Driver Setup</u></a></li>
<li><a href="https://hardware-help.techidaily.com/windows-11-update-now-includes-built-in-printer-and-scanner-support/"><u>Windows 11 Update: Now Includes Built-In Printer and Scanner Support</u></a></li>
</ul></div>
