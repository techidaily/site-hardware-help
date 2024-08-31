---
title: "End of an Era: AMD's 3DNow! Architecture Loses LLVM Compiler Backing"
date: 2024-08-30T15:49:23.033Z
updated: 2024-08-31T15:49:23.033Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/b1e13c65cf79c8bfe0a90a1ea55d4cf4b25b6f465fd497be9c6686a8f2877ff5.jpg
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-navigating-daily-life-on-facebook-a-step-by-step-guide/"><u>[New] 2024 Approved  Navigating Daily Life on Facebook  A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-simplified-processes-instantly-clearing-youtube-comments/"><u>[New] 2024 Approved  Simplified Processes  Instantly Clearing Youtube Comments</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-how-to-seamlessly-add-vimeo-videos-to-insta-feed/"><u>[New] In 2024, How to Seamlessly Add Vimeo Videos to Insta Feed</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-selecting-superior-webcams-on-windows-10-for-2024/"><u>[New] Selecting Superior Webcams on Windows 10 for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-visual-wonders-the-10-list-of-exceptional-4k-for-macs/"><u>[Updated] In 2024, Visual Wonders  The #10 List of Exceptional 4K for Macs</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-ultimate-guide-to-unparalleled-streaming-experience/"><u>[Updated] The Ultimate Guide to Unparalleled Streaming Experience</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-innovative-downloaders-unveiled-top-8-of-2023/"><u>2024 Approved  Innovative Downloaders Unveiled  Top 8 of 2023</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-oneplus-11r-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked OnePlus 11R Phone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/advanced-insights-from-toms-computer-components-blog/"><u>Advanced Insights From Tom's Computer Components Blog</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canoscan-lide-220-update-and-download-guide-for-optimal-scanning-performance/"><u>CanoScan LiDE 220 Update & Download Guide for Optimal Scanning Performance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/compatible-windows-programs-for-easy-installation-of-your-brother-hl-l2340dw-printer/"><u>Compatible Windows Programs for Easy Installation of Your Brother HL-L2340DW Printer</u></a></li>
<li><a href="https://win-howtos.techidaily.com/decrease-system-load-in-windows-11-by-tackling-svchostexes-excessive-cpu-utilization-a-practical-guide/"><u>Decrease System Load in Windows 11 by Tackling svchost.exe's Excessive CPU Utilization - A Practical Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/definitive-guide-to-overcoming-intel-hd-graphics-630-driver-glitches-on-windows-machines/"><u>Definitive Guide to Overcoming Intel HD Graphics 630 Driver Glitches on Windows Machines</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-official-drivers-for-ricoh-mp-c3003-printers/"><u>Download & Install Official Drivers for Ricoh MP C3003 Printers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-hp-deskjet-inkjet-printer-driver-vijey-software-compatible-with-windows-10/"><u>Download HP Deskjet Inkjet Printer Driver Vijey Software Compatible with Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-solution-to-your-hp-beats-speaker-problem-in-various-versions-of-windows/"><u>Effortless Solution to Your HP Beats Speaker Problem in Various Versions of Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-usb-c-driver-downloads-to-enhance-your-windows-10-experience/"><u>Essential USB-C Driver Downloads to Enhance Your Windows 10 Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-epson-wf-3520-printing-software-for-windows-compatible-with-all-versions/"><u>Get the Newest Epson WF 3520 Printing Software for Windows - Compatible with All Versions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-free-amd-radeon-gpu-drivers-now-compatible-with-windows/"><u>Get Your Free AMD Radeon GPU Drivers Now - Compatible with Windows!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-fix-windows-11-bluetooth-connectivity-problems-a-complete-guide/"><u>How to Fix Windows 11 Bluetooth Connectivity Problems: A Complete Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-install-or-upgrade-your-pcs-pl2303-drivers-on-windows/"><u>How to Install or Upgrade Your PC's PL2303 Drivers on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-linksys-ae2500-device-drivers-with-ease-get-them-now/"><u>Install Linksys AE2500 Device Drivers with Ease - Get Them Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-atheros-chipset-drivers-on-windows-easy-instructions/"><u>Installing Atheros Chipset Drivers on Windows – Easy Instructions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/modelfarm-achieves-remarkable-50-quality-improvement-with-unreal-engine-and-intel-plans-shift-to-high-performance-amd-ryzen-cpus/"><u>ModelFarm Achieves Remarkable 50%% Quality Improvement with Unreal Engine and Intel, Plans Shift to High-Performance AMD Ryzen CPUs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-installation-process-how-to-get-wd-ses-drives-up-and-running-with-recent-usb-drivers/"><u>Navigating the Installation Process: How to Get WD SES Drives Up and Running with Recent USB Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ralink-rt3290-driver-troubles-in-windows-1087-here-are-the-solutions/"><u>Ralink RT3290 Driver Troubles in Windows 10/8/7? Here Are the Solutions!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/rapid-rhythmic-revision-software-roundup-mobiledesktop/"><u>Rapid Rhythmic Revision Software Roundup (Mobile/Desktop)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722975632922-realtek-rtl8723be-driver-fixes-solve-your-network-card-issues-now/"><u>Realtek RTL8723BE Driver Fixes – Solve Your Network Card Issues Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/respect-for-acting/"><u>Respect for Acting</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revamp-your-pc-newegg-cpu-exchange-program-offers-cashbacks-including-300-for-an-i9-14900k-and-220-for-a-7800x3d-ryzen/"><u>Revamp Your PC: Newegg CPU Exchange Program Offers Cashbacks, Including $300 for an I9-14900K and $220 for a 7800X3D Ryzen</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ryzen-9000-launch-on-hold-exploring-the-impact-of-a-mislabeled-ryzen-7-chip-and-ryzen-5-series-disruption/"><u>Ryzen 9000 Launch on Hold? Exploring the Impact of a Mislabeled Ryzen 7 Chip & Ryzen 5 Series Disruption</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-installation-nvidia-1080-drivers-compatible-with-windows-11/"><u>Seamless Installation: NVIDIA 1080 Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-update-to-intel-dual-band-wifi-ac-3160-a-user-friendly-guide-for-speedier-connectivity/"><u>Seamless Update to Intel Dual Band WiFi AC 3160: A User-Friendly Guide for Speedier Connectivity</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-for-epson-xp-430-driver-download-on-pc/"><u>Step by Step Tutorial for Epson XP-430 Driver Download on PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-on-updating-and-downloading-the-ch340g-serial-converter-drivers-for-modern-windows-systems/"><u>Step-by-Step Tutorial on Updating and Downloading the CH340G Serial Converter Drivers for Modern Windows Systems</u></a></li>
<li><a href="https://driver-error.techidaily.com/swift-solution-to-mtp-driver-complications/"><u>Swift Solution to MTP Driver Complications</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->