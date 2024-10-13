---
title: "End of an Era: AMD's 3DNow! Architecture Loses LLVM Compiler Backing"
date: 2024-10-07T23:02:52.351Z
updated: 2024-10-13T04:13:37.914Z
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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-excellent-ios-apps-the-ultimate-psp-emulators/"><u>[New] In 2024, Excellent iOS Apps The Ultimate PSP Emulators</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unveiling-horizon-based-approaches-to-post-on-igtv/"><u>[New] Unveiling Horizon-Based Approaches to Post on IGTV</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-unlocking-windows-hdr-capabilities-for-cutting-edge-video-workflows/"><u>2024 Approved Unlocking Windows' HDR Capabilities for Cutting-Edge Video Workflows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722964413347-efficient-amd-smbus-driver-installation-get-latest-version-now/"><u>Efficient AMD SMBus Driver Installation: Get Latest Version Now</u></a></li>
<li><a href="https://win-guides.techidaily.com/effortless-strategies-for-saving-hotmail-correspondence-on-your-laptop/"><u>Effortless Strategies for Saving Hotmail Correspondence on Your Laptop</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-performance-quick-and-easy-driver-updates-for-your-amd-radeon-rx-470/"><u>Enhance Performance: Quick and Easy Driver Updates for Your AMD Radeon RX 470</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-and-prevent-your-ark-software-from-crashing-effectively/"><u>How to Fix and Prevent Your Ark Software From Crashing Effectively</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-your-connectivity-download-the-updated-intel-wifi-6-ax200-drivers-for-modern-windows-os/"><u>Improve Your Connectivity: Download the Updated Intel WiFi 6 AX200 Drivers for Modern Windows OS</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-analysis-of-the-serious-book-lovers-device-kobo-forma/"><u>In Depth Analysis of the Serious Book Lover's Device - Kobo Forma</u></a></li>
<li><a href="https://hardware-help.techidaily.com/no-cost-logitech-webcam-drivers-install-and-boost-your-pcs-video-quality-today/"><u>No-Cost Logitech Webcam Drivers: Install and Boost Your PC’s Video Quality Today</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-install-guide-intel-thunderbolt-chip-drivers-for-smooth-performance/"><u>Quick Install Guide: Intel Thunderbolt Chip Drivers for Smooth Performance</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ltimate-guide-to-freely-download-youtube-series-on-mobile-for-2024/"><u>The Ultimate Guide to Freely Download YouTube Series on Mobile for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unleashing-artful-expression-the-most-exceptional-9-sites-for-3d-graffiti-typefaces-for-2024/"><u>Unleashing Artful Expression The Most Exceptional 9 Sites for 3D Graffiti Typefaces for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/updated-wi-fi-plus-bluetooth-art-pen-display-software-get-your-wacom-cintiq-13-hd-drivers-now/"><u>Updated Wi-Fi + Bluetooth Art Pen Display Software - Get Your Wacom Cintiq 13 HD Drivers Now!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

