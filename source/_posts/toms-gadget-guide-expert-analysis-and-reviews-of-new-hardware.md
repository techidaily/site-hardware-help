---
title: "Tom's Gadget Guide: Expert Analysis and Reviews of New Hardware"
date: 2024-09-21T23:08:03.804Z
updated: 2024-09-26T23:07:49.566Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
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
<li><a href="https://eaxpv-info.techidaily.com/updated-a-beginners-guide-to-embedding-youtube-playlists-in-code-for-2024/"><u>[Updated] A Beginner's Guide to Embedding YouTube Playlists in Code for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-udemy-alternatives-10-best-online-learning-sites-like-udemy/"><u>[Updated] In 2024, Udemy Alternatives 10 Best Online Learning Sites Like Udemy</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-saving-instagrams-finest-in-your-photo-gallery/"><u>2024 Approved Saving Instagram's Finest in Your Photo Gallery</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-wirecast-analysis-with-equivalents/"><u>2024 Approved WireCast Analysis with Equivalents</u></a></li>
<li><a href="https://hardware-help.techidaily.com/complete-instructions-for-magic-mouse-driver-acquisition-and-installation-on-windows/"><u>Complete Instructions for Magic Mouse Driver Acquisition & Installation on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-the-latest-epson-wf-3520-printer-drivers-on-windows/"><u>Download and Install the Latest Epson WF-3520 Printer Drivers on Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-newly-updated-hp-officejet-njw-4500-printer-driver-software-for-optimal-performance/"><u>Download the Newly Updated HP OfficeJet Njw 4500 Printer Driver Software for Optimal Performance</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-oppo-a59-5g-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Oppo A59 5G Phone? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easily-upgrade-to-newest-amd-radeon-r9-200-series-driver-on-windows-os/"><u>Easily Upgrade to Newest AMD Radeon R9 200 Series Driver on Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-smooth-networking-downloading-and-updating-netgear-wi-fi-card-drivers/"><u>Ensure Smooth Networking: Downloading & Updating NETGEAR Wi-Fi Card Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976628485-get-the-latest-asus-pce-ac68-device-driver-software-here/"><u>Get the Latest ASUS PCE-AC68 Device Driver Software Here</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-apple-iphone-14-pro-max-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your Apple iPhone 14 Pro Max Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-analysis-of-asus-rog-strix-xg27acs-unparalleled-precision-meets-dynamic-180hz-gameplay/"><u>In-Depth Analysis of Asus ROG Strix XG27ACS: Unparalleled Precision Meets Dynamic 180Hz Gameplay</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-the-latest-logitech-keyboard-driver-for-enhanced-windows-11-performance/"><u>Install the Latest Logitech Keyboard Driver for Enhanced Windows 11 Performance</u></a></li>
<li><a href="https://win-answers.techidaily.com/master-the-art-of-stable-gaming-top-8-fixes-to-stop-hogwarts-legacy-crash-on-pc-startup/"><u>Master the Art of Stable Gaming: Top 8 Fixes to Stop Hogwarts Legacy Crash on PC Startup</u></a></li>
<li><a href="https://hardware-help.techidaily.com/nvidia-quadro-graphics-drivers-for-win10-direct-download-from-official-site/"><u>Nvidia Quadro Graphics Drivers for Win10 - Direct Download From Official Site</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/remove-interference-from-laptop-vision-line/"><u>Remove Interference From Laptop Vision Line</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/understanding-the-disappearance-of-light-gun-games-in-the-era-of-modern-hdtv-technology/"><u>Understanding the Disappearance of Light Gun Games in the Era of Modern HDTV Technology</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-brother-mfc-copier-7860dw-free-driver-software-for-windows-users/"><u>Update Your Brother MFC-Copier-7860DW: Free Driver Software for Windows Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528681/16446" target="_top" id="1528681">
  <img src="//a.impactradius-go.com/display-ad/16446-1528681" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528681/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

