---
title: Navigating the World of Hardware with Tom's Guides
date: 2024-09-04T02:12:52.034Z
updated: 2024-09-05T02:12:52.034Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/JHeXfkUtGq9irev5csBqFK-320-80.jpg
---

## Legacy Over: How LLVM Compiler's Departure Signals the End of AMD's 3DNow

AMD’s near-ancient 3DNow! instructions have faded even further into obscurity.[Open-source compiler LLVM](https://github.com/llvm/llvm-project/commit/f0eb5587ceeb641445b64cb264c822b4751de04a) is finally removing support for the set of instructions that hasn’t been supported by AMD’s CPUs since 2011.

 The 3DNow! instruction set was introduced in 1998 as a competitor to Intel’s MMX. It added Single Instruction, Multiple Data (SIMD) instructions to AMD’s base x86 instruction set, which helped the CPUs do vector processing of floating-point operations using vector registers.

[AMD replaced 3DNow!](https://www.tomshardware.com/news/3dnow-simd-extensions-phenom-sse,11128.html) with the newer SSE equivalents in 2011 and stopped including that feature flag bit beginning with the K10 Bulldozer CPUs. It did take some time for compilers to start dropping support for the instruction set, though, since the CPUs remained in use for quite some time.

 In 2021,[Linux retired the instruction set](https://www.tomshardware.com/news/linux-says-goodbye-to-amd-3d-now) from its kernel, but LLVM maintained support long after everyone else dropped it. The developers behind the LLVM compiler also work to remove MMX types and instructions from the tool.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 A commit for LLVM 19, expected to be released in September or October, confirmed the impending removal.

 _“This set of instructions was only supported by AMD chips starting in the K6-2 (introduced 1998), and before the “Bulldozer” family (2011). They were never much used, as they were effectively superseded by the more-widely-implemented SSE (first implemented on the AMD side in Athlon XP in 2001)._

 _This is being done as a predecessor towards general removal of MMX register usage. Since there is almost no usage of the 3DNow! intrinsics, and no modern hardware even implements them, simple removal seems like the best option.”_

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 The AMD 3DNow! instructions were popular in the late 90s and early 2000s for improving gaming, video playback, and Adobe Photoshop workflows. Then, Intel released the SSE instructions, which became more dominant overall. When Intel released SSE2, AMD adopted it and dropped its older SIMD instruction set.

 Developers who need to write for old AMD processors can still use 3DNow! instructions in Assembly, including inline Assembly code with LLVM. Other than that, anything related to 3DNow! should be considered deprecated and no longer used.


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
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-churn-memetic-content-for-gif-hub/"><u>[New] 2024 Approved  Churn Memetic Content for GIF Hub</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-broadcast-battleground-pick-your-preferred-livestreaming-champion-vmixwirecast/"><u>[New] Broadcast Battleground  Pick Your Preferred Livestreaming Champion (VMix/Wirecast)</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-harnessing-new-trends-transmitting-fb-videos-through-whatsapp/"><u>[New] Harnessing New Trends  Transmitting FB Videos Through WhatsApp</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-enhancing-video-content-step-by-step-cropping-and-export-guide/"><u>[New] In 2024, Enhancing Video Content  Step-by-Step Cropping & Export Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-spotting-success-stories-2023s-most-shared-tweets/"><u>[New] In 2024, Spotting Success Stories  2023’S Most Shared Tweets</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-the-ultimate-companion-for-your-gaming-setup-xbox-recorder/"><u>[New] The Ultimate Companion for Your Gaming Setup  Xbox Recorder</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-fiscal-horizons-exploring-mr-beasts-income/"><u>[Updated] In 2024, Fiscal Horizons  Exploring Mr. Beast's Income</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unveiling-a-simple-yet-powerful-copywriting-model-for-ads/"><u>[Updated] Unveiling a Simple, Yet Powerful Copywriting Model for Ads</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-prime-top-10-audio-capture-software-for-spotify-users/"><u>2024 Approved  Prime Top 10 Audio Capture Software for Spotify Users</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-superior-pcs-for-serious-workers/"><u>2024 Approved  Superior PCs for Serious Workers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/advanced-insights-from-toms-computer-components-blog/"><u>Advanced Insights From Tom's Computer Components Blog</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canoscan-lide-220-update-and-download-guide-for-optimal-scanning-performance/"><u>CanoScan LiDE 220 Update & Download Guide for Optimal Scanning Performance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/combine-and-rotate-the-ultimate-guide-to-multimedia-editing-android/"><u>Combine & Rotate  The Ultimate Guide to Multimedia Editing (Android)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/compatible-windows-programs-for-easy-installation-of-your-brother-hl-l2340dw-printer/"><u>Compatible Windows Programs for Easy Installation of Your Brother HL-L2340DW Printer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-guide-downloading-and-upgrading-intel-optane-drivers-the-right-way-for-windows-users/"><u>Comprehensive Guide: Downloading & Upgrading Intel Optane Drivers - The Right Way for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/definitive-guide-to-overcoming-intel-hd-graphics-630-driver-glitches-on-windows-machines/"><u>Definitive Guide to Overcoming Intel HD Graphics 630 Driver Glitches on Windows Machines</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-official-drivers-for-ricoh-mp-c3003-printers/"><u>Download & Install Official Drivers for Ricoh MP C3003 Printers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-hp-deskjet-inkjet-printer-driver-vijey-software-compatible-with-windows-10/"><u>Download HP Deskjet Inkjet Printer Driver Vijey Software Compatible with Windows 10</u></a></li>
<li><a href="https://program-issues.techidaily.com/effective-solutions-overcoming-the-persistent-game-bug-6164-on-call-of-duty/"><u>Effective Solutions: Overcoming the Persistent Game Bug 6164 on Call of Duty</u></a></li>
<li><a href="https://win-forum.techidaily.com/effortless-remote-start-how-to-configure-wake-on-lan-on-windows-10-and-11/"><u>Effortless Remote Start: How to Configure Wake-on-LAN on Windows 10 & 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-solution-to-your-hp-beats-speaker-problem-in-various-versions-of-windows/"><u>Effortless Solution to Your HP Beats Speaker Problem in Various Versions of Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-pcs-audio-experience-free-steelseries-engine-driver-for-windows-11/"><u>Enhance Your PC's Audio Experience – Free SteelSeries Engine Driver for Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-usb-c-driver-downloads-to-enhance-your-windows-10-experience/"><u>Essential USB-C Driver Downloads to Enhance Your Windows 10 Experience</u></a></li>
<li><a href="https://buynow-help.techidaily.com/evaluating-lg-k92s-5g-feature-a-step-too-far-or-innovative-leap-forward/"><u>Evaluating LG K92's 5G Feature: A Step Too Far or Innovative Leap Forward?</u></a></li>
<li><a href="https://extra-resources.techidaily.com/full-review-exploring-hero4-black-functions/"><u>Full Review  Exploring Hero4 Black Functions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-epson-wf-3520-printing-software-for-windows-compatible-with-all-versions/"><u>Get the Newest Epson WF 3520 Printing Software for Windows - Compatible with All Versions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-free-amd-radeon-gpu-drivers-now-compatible-with-windows/"><u>Get Your Free AMD Radeon GPU Drivers Now - Compatible with Windows!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-reno-11f-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo Reno 11F 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-bypass-activation-lock-on-iphone-11-by-drfone-ios/"><u>In 2024, 3 Effective Ways to Bypass Activation Lock on iPhone 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-pro-max-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 Pro Max?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/in-depth-review-and-analysis-of-top-tech-products-on-toms-hardware/"><u>In-Depth Review & Analysis of Top Tech Products on Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-linksys-ae2500-device-drivers-with-ease-get-them-now/"><u>Install Linksys AE2500 Device Drivers with Ease - Get Them Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-upgraded-tp-link-ub400-adapter-drivers-step-by-step-instructions-and-free-downloads/"><u>Install Upgraded TP-Link UB400 Adapter Drivers - Step by Step Instructions and Free Downloads</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-and-updating-toshiba-satellite-dynabox-drivers-for-windows-computers/"><u>Installing and Updating Toshiba Satellite Dynabox Drivers for Windows Computers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-atheros-chipset-drivers-on-windows-easy-instructions/"><u>Installing Atheros Chipset Drivers on Windows – Easy Instructions</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-s23plusfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy S23+FRP Lock</u></a></li>
<li><a href="https://hardware-help.techidaily.com/modelfarm-achieves-remarkable-50-quality-improvement-with-unreal-engine-and-intel-plans-shift-to-high-performance-amd-ryzen-cpus/"><u>ModelFarm Achieves Remarkable 50%% Quality Improvement with Unreal Engine and Intel, Plans Shift to High-Performance AMD Ryzen CPUs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-installation-process-how-to-get-wd-ses-drives-up-and-running-with-recent-usb-drivers/"><u>Navigating the Installation Process: How to Get WD SES Drives Up and Running with Recent USB Drivers</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-lava-blaze-2-pro-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best Lava Blaze 2 Pro Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ralink-rt3290-driver-troubles-in-windows-1087-here-are-the-solutions/"><u>Ralink RT3290 Driver Troubles in Windows 10/8/7? Here Are the Solutions!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722975632922-realtek-rtl8723be-driver-fixes-solve-your-network-card-issues-now/"><u>Realtek RTL8723BE Driver Fixes – Solve Your Network Card Issues Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/respect-for-acting/"><u>Respect for Acting</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revamp-your-pc-newegg-cpu-exchange-program-offers-cashbacks-including-300-for-an-i9-14900k-and-220-for-a-7800x3d-ryzen/"><u>Revamp Your PC: Newegg CPU Exchange Program Offers Cashbacks, Including $300 for an I9-14900K and $220 for a 7800X3D Ryzen</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-installation-nvidia-1080-drivers-compatible-with-windows-11/"><u>Seamless Installation: NVIDIA 1080 Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://facebook.techidaily.com/spotting-hidden-activity-on-your-pcemails/"><u>Spotting Hidden Activity on Your PC/Emails</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-for-epson-xp-430-driver-download-on-pc/"><u>Step by Step Tutorial for Epson XP-430 Driver Download on PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-instructions-to-effortlessly-install-wacoms-intuos-pro-driver-with-windows-11/"><u>Step-by-Step Instructions to Effortlessly Install Wacom's [Intuos Pro Driver] with Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-on-updating-and-downloading-the-ch340g-serial-converter-drivers-for-modern-windows-systems/"><u>Step-by-Step Tutorial on Updating and Downloading the CH340G Serial Converter Drivers for Modern Windows Systems</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/talk-like-an-aussie-the-language-of-the-landscape/"><u>Talk Like an Aussie: The Language of the Landscape</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-infinix-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Infinix Phone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-cwindowssystem32configsystemprofile-desktop-error-resolution/"><u>Troubleshooting Guide: C:\\Windows\\system32\\config\\SystemProfile Desktop Error Resolution</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/ultimate-list-of-hd-webcams-compatible-with-windows-11-pcs-for-2024/"><u>Ultimate List of HD Webcams Compatible with Windows 11 PCs for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unlocking-full-functionality-a-comprehensive-guide-for-downloading-your-dell-mouse-driver/"><u>Unlocking Full Functionality: A Comprehensive Guide for Downloading Your Dell Mouse Driver</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-epson-tm-t88v-printers-driver-to-enhance-printing-performance-on-windows-systems/"><u>Update Your EPSON TM-T88V Printer's Driver to Enhance Printing Performance on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722967439549-update-your-msi-b3ns-with-the-newest-drivers-for-windows-10-and-7-get-the-tomahawk-edition/"><u>Update Your MSI B3n's with the Newest Drivers for Windows 10 and 7 - Get the Tomahawk Edition!</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/user-experience-revolutionized-by-cookiebot-technology/"><u>User Experience Revolutionized by Cookiebot Technology</u></a></li>
<li><a href="https://hardware-help.techidaily.com/windows-compatible-drivers-for-hp-officejet-4650-free-download/"><u>Windows Compatible Drivers for HP OfficeJet 4650 - Free Download</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030395/7443" target="_top" id="2030395">
  <img src="//a.impactradius-go.com/display-ad/7443-2030395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->