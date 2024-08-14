---
title: "Navigating the World of Computing: Trustworthy Insights From Tom's Hardware Professionals"
date: 2024-08-13T12:50:22.806Z
updated: 2024-08-14T12:50:22.806Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/6e23731e5459bef762d6b1bc2a8183e3bf6b31c4a9b6b999e3d277b3627f742d.jpg
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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-beyond-the-buzz-a-ranked-guide-to-non-vimeo-edits/"><u>[New] 2024 Approved  Beyond the Buzz  A Ranked Guide to Non-Vimeo Edits</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-excellent-4k-cameras-and-their-perfect-gimbals-for-2024/"><u>[New] Excellent 4K Cameras & Their Perfect Gimbals for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-hits-at-hyperspeed-the-fast-track-to-100-million-views-on-youtube-in-24/"><u>[New] In 2024, Hits at Hyperspeed  The Fast Track to 100 Million Views on YouTube in '24</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-swiveling-screens-mastering-video-rotation-on-instagram-for-2024/"><u>[New] Swiveling Screens  Mastering Video Rotation on Instagram for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-top-8-undead-adventures-ultimate-zombie-game-guide/"><u>[Updated] In 2024, Top 8 Undead Adventures  Ultimate Zombie Game Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-adding-youtube-music-to-video/"><u>2024 Approved  Adding YouTube Music To Video</u></a></li>
<li><a href="https://hardware-help.techidaily.com/brother-hl-l234er-dual-toner-laser-printer-setup-and-software-for-windows-free-downloads/"><u>Brother HL-L234er Dual Toner Laser Printer Setup and Software for Windows - Free Downloads</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypass-maplestorys-initial-hurdles-and-dive-into-the-game-seamlessly/"><u>Bypass MapleStory's Initial Hurdles & Dive Into the Game Seamlessly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-mg3600-how-to-find-and-install-latest-printer-drivers-easily/"><u>Canon MG3600: How to Find and Install Latest Printer Drivers Easily</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-guide-to-download-pci-device-drivers-on-windows-11-10-and-older-editions/"><u>Comprehensive Guide to Download PCI Device Drivers on Windows 11, 10, and Older Editions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/deciding-on-perfect-pc-ventilation-the-battle-between-pwm-and-dc-fans-for-optimal-performance/"><u>Deciding on Perfect PC Ventilation: The Battle Between PWM and DC Fans for Optimal Performance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-ricoh-printer-software-on-your-windows-pc/"><u>Download & Install Ricoh Printer Software on Your Windows PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-hp-laserjet-m506-printer-drivers-easy-guide/"><u>Download and Update HP LaserJet M506 Printer Drivers - Easy Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-now-official-csr-bluetooth-driver-pack/"><u>Download and Update Now: Official CSR Bluetooth Driver Pack</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-razer-mamba-drivereasily-and-quickly/"><u>Download Razer Mamba Driver|Easily & Quickly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/downloading-and-installing-evga-drivers-for-optimal-performance-in-windows/"><u>Downloading and Installing EVGA Drivers for Optimal Performance in Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-asus-maximus-x-hero-graphics-card-driver-upgrade-expert-advice-and-guidelines/"><u>Effortless ASUS Maximus X Hero Graphics Card Driver Upgrade - Expert Advice and Guidelines</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-your-asus-bt500-stays-connected-download-drivers-for-win11-win10-and-win8-support/"><u>Ensure Your Asus BT500 Stays Connected: Download Drivers for Win11, Win10 & Win8 Support</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977863904-epson-wf-2760-driver-download-windows-11108/"><u>Epson WF 2760 Driver Download – Windows 11/10/8</u></a></li>
<li><a href="https://hardware-help.techidaily.com/epson-wf-7710-driver-download-guide-ready-for-windows-108187-operating-systems/"><u>Epson WF-7710 Driver Download Guide - Ready for Windows 10/8.1/8/7 Operating Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-the-most-recent-drivers-for-toshiba-office-machines-using-windows-operating-systems/"><u>Find and Install the Most Recent Drivers for Toshiba Office Machines Using Windows Operating Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-the-perfect-drivers-for-your-logitech-g27-steering-wheel-on-windows-11-10-and-7/"><u>Find and Install the Perfect Drivers for Your Logitech G27 Steering Wheel on Windows 11, 10 & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fresh-install-of-amd-graphics-software-on-windows-os-versions-10-11-and-7/"><u>Fresh Install of AMD Graphics Software on Windows OS Versions: 10, 11, and 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722968175752-get-the-latest-canon-device-drivers-installed-in-no-time-on-your-windows-computer/"><u>Get the Latest Canon Device Drivers Installed in No Time on Your Windows Computer!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-canon-mg3000-driver-version-with-easy-steps/"><u>Get the Newest Canon MG3000 Driver Version with Easy Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-hp-printer-software-for-windows-11-installation-steps/"><u>Get the Newest HP Printer Software for Windows 11 - Installation Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-easily-update-your-nvidia-quadro-rtx-4000-with-the-latest-drivers-free-guide-available-now/"><u>How to Easily Update Your NVIDIA Quadro RTX 4000 with the Latest Drivers – Free Guide Available Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-newest-hp-deskjet-2700-software-for-your-device/"><u>How to Get the Newest HP DeskJet 2700 Software for Your Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-install-logitech-driving-force-pro-complete-download-tutorial-for-windows-users-versions-7-10/"><u>How to Install Logitech Driving Force Pro: Complete Download Tutorial for Windows Users (Versions 7-10)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-install-usb-c-support-in-windows-11-free-downloads-available/"><u>How to Install USB-C Support in Windows 11 - Free Downloads Available</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-resolve-bluetooth-driver-glitches-in-windows-10-effortlessly/"><u>How to Resolve Bluetooth Driver Glitches in Windows 10 Effortlessly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-successfully-update-your-ati-radeon-graphics-cards-drivers-using-windows/"><u>How To Successfully Update Your ATI Radeon Graphics Card's Drivers Using Windows</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-apple-iphone-13-mini-blacklist-removal-tips-and-tools-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to Apple iPhone 13 mini Blacklist Removal Tips and Tools</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-apple-iphone-13-pro-max-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From Apple iPhone 13 Pro Max Lock Screen | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-and-updating-your-hp-n840-g3-printers-drivers-a-complete-walkthrough/"><u>Installing and Updating Your HP N840 G3 Printer's Drivers: A Complete Walkthrough</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-driver-pack-for-enhanced-performance-on-corsair-h80i-v2/"><u>Latest Driver Pack for Enhanced Performance on Corsair H80i V2</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-driver-upgrades-enhancing-msi-gpu-performance-in-windows-11-and-7/"><u>Seamless Driver Upgrades: Enhancing MSI GPU Performance in Windows 11 and 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-installation-guide-brother-mfc-7360n-printer-software-on-latest-windows-platforms/"><u>Seamless Installation Guide: Brother MFC-7360N Printer Software on Latest Windows Platforms</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-to-installing-mf8500c-driver-for-windows-users/"><u>Step-by-Step Guide to Installing MF8500C Driver for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-installing-your-samsung-devices-official-adb-drivers/"><u>Step-by-Step Guide: Installing Your Samsung Device’s Official ADB Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-updating-your-epson-printer-drivers-on-windows-10/"><u>Step-by-Step Guide: Updating Your Epson Printer Drivers on Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-installation-of-wacom-intuos-tablet-drivers-in-windows-environments-guaranteed-optimal-performance/"><u>Step-by-Step Installation of Wacom Intuos Tablet Drivers in Windows Environments - [Guaranteed Optimal Performance]</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-and-fixing-amd-radeon-driver-issues-solutions-proven-effective/"><u>Troubleshooting and Fixing AMD Radeon Driver Issues: Solutions Proven Effective</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guide-updating-your-webcam-drivers-on-windows-10/"><u>Ultimate Guide: Updating Your WebCam Drivers on Windows 10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unraveling-revenue-how-much-do-creators-make-on-youtube-adverts-for-2024/"><u>Unraveling Revenue  How Much Do Creators Make on Youtube Adverts for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-to-newest-nvidia-geforce-rtx-3060-ti-driver-version-compatible-with-windows-11/"><u>Update to Newest NVIDIA GeForce RTX 3060 Ti Driver Version Compatible with Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-huawei-nova-y71-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Huawei Nova Y71 Phone Network-Ready</u></a></li>
</ul></div>
