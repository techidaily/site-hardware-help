---
title: Comprehensive Hardware Analysis by Tom's Computing Guide
date: 2024-08-19T12:31:08.505Z
updated: 2024-08-20T12:31:08.505Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/oQjfKNyL7NhTMuhWXBFZVV-320-80.png
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
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
<li><a href="https://youtube-help.techidaily.com/new-side-splitting-scripts-crafting-7-hilarious-youtube-scenes/"><u>[New] Side-Splitting Scripts  Crafting 7 Hilarious YouTube Scenes</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-top-tiers-of-treasured-valheim-trees-for-2024/"><u>[New] The Top Tiers of Treasured Valheim Trees for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-a-closer-look-ffmpeg-for-pristine-audio-extraction/"><u>[Updated] A Closer Look  FFmpeg for Pristine Audio Extraction</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-efficient-use-of-telegram-browser-interface/"><u>[Updated] In 2024, Efficient Use of Telegram Browser Interface</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-essential-fb-video-plays-top-10-choices/"><u>2024 Approved  Essential FB Video Plays  Top 10 Choices</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-file-sync-solutions-top-ways-to-bring-data-home/"><u>2024 Approved  File Sync Solutions  Top Ways To Bring Data Home</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-have-a-products-sponsorship-in-youtube/"><u>2024 Approved  How to Have a Products Sponsorship in Youtube</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-video-capture-on-periscope-a-comprehensive-manual/"><u>2024 Approved  Mastering Video Capture on Periscope  A Comprehensive Manual</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-oneplus-open-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track OnePlus Open without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-epson-wf-3540-printer-driver-on-your-windows-pc/"><u>Download & Install Epson WF-3540 Printer Driver on Your Windows PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-latest-dolby-audio-driver-update-now-compatible-with-windows-111081/"><u>Download the Latest Dolby Audio Driver Update Now! Compatible with Windows 11/10/8.1</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-install-of-bcm20702a0-wi-fi-drivers-on-windows-pcs-step-by-step-download/"><u>Effortless Install of BCM20702A0 Wi-Fi Drivers on Windows PCs | Step by Step Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-latest-dell-d31n-driver-software-for-your-pc/"><u>Effortless Installation: Latest Dell D31n Driver Software for Your PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-driver-updates-and-downloads-for-optimizing-your-lenovo-t420-on-windows/"><u>Essential Driver Updates and Downloads for Optimizing Your Lenovo T420 on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-tips-for-fixing-driver-conflicts-with-ralinks-rt3290-in-various-windows-environments-windows-11-8-and-surveys/"><u>Expert Tips for Fixing Driver Conflicts with Ralink's RT3290 in Various Windows Environments (Windows 11, 8, & Surveys)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-epson-tm-t88v-printer-software-version-for-windows-pcs-free-download/"><u>Get the Newest EPSON TM-T88v Printer Software Version for Windows PCs - Free Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-kyocera-printer-up-and-running-on-windows-with-these-essential-driver-downloads/"><u>Get Your KYOCERA Printer Up & Running on Windows with These Essential Driver Downloads</u></a></li>
<li><a href="https://hardware-help.techidaily.com/getting-the-latest-sata-driver-updates-made-simple-for-windows-users/"><u>Getting the Latest SATA Driver Updates Made Simple for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-correctly-install-arduino-uno-driver-on-a-pc-running-windows-os/"><u>How to Correctly Install Arduino Uno Driver on a PC Running Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-resolve-lg-device-usb-connection-problems-on-windows-10-8-and-7/"><u>How to Resolve LG Device USB Connection Problems on Windows 10, 8 & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-your-lenovo-legion-5-pro-16ach6h-essential-driver-software-guide/"><u>How to Update Your Lenovo Legion 5 Pro (16ACH6H) - Essential Driver Software Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-printer-driver-installation-guide-and-download-options/"><u>HP Printer Driver Installation Guide and Download Options</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-your-epson-xp-640-printer-functionality-with-our-windows-driver-update-tutorial/"><u>Improve Your Epson XP-640 Printer Functionality with Our Windows Driver Update Tutorial</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-apps-and-online-tools-to-track-poco-x6-phone-withwithout-imei-number-by-drfone-android/"><u>In 2024, Top Apps and Online Tools To Track Poco X6 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-the-latest-hp-officejet-amage/"><u>Installing the Latest HP OfficeJet Amage:</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-geforce-rtx-2060-super-graphics-card-drivers-for-win10-and-win11-free-download/"><u>Latest GeForce RTX 2060 Super Graphics Card Drivers for Win10 & Win11 – Free Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-nvidia-quadro-graphics-driver-download-for-windows-10-improved-compatibility-with-popular-editing-tools/"><u>Latest NVIDIA Quadro Graphics Driver Download for Windows 10: Improved Compatibility with Popular Editing Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-version-of-geforce-rtx-2070-drivers-optimized-for-windows-10-8-and-7/"><u>Latest Version of Geforce RTX 2070 Drivers: Optimized for Windows 10, 8 & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/official-driver-pack-for-hp-pagewide-pro-cu477a-install-on-win10-8-and-upgraded-to-win11/"><u>Official Driver Pack for HP PageWide Pro Cu477a - Install on Win10, 8 & Upgraded to Win11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-effortless-intel-cpu-driver-installation-for-enthusiasts/"><u>Quick & Effortless Intel CPU Driver Installation for Enthusiasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-setup-obtain-your-samsung-c46-driver-for-smooth-printing-operations/"><u>Quick Setup: Obtain Your Samsung C46# Driver for Smooth Printing Operations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-updating-and-downloading-your-intel-optane-driver-on-pcs/"><u>Step-by-Step Tutorial: Updating and Downloading Your Intel Optane Driver on PCs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722968475203-stream-flawlessly-with-your-insigh-networking-device-for-xbox-grab-the-official-drivers-here/"><u>Stream Flawlessly with Your Insigh Networking Device for Xbox; Grab the Official Drivers Here!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-math-skills-with-leading-ai-solutions-the-essential-list/"><u>Transform Your Math Skills with Leading AI Solutions: The Essential List</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-or-install-epson-wf-27n60-printer-drivers-for-windows-versions-win-11-win-10-win-8/"><u>Update or Install Epson WF-27n60 Printer Drivers for Windows Versions (Win 11, Win 10, Win 8)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgrade-your-system-easily-with-no-charge-free-download-of-qualcomm-atheros-ar9-8x-driver/"><u>Upgrade Your System Easily with [No Charge] Free Download of Qualcomm Atheros AR9 8X Driver</u></a></li>
</ul></div>
