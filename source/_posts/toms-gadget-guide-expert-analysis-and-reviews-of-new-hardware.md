---
title: "Tom's Gadget Guide: Expert Analysis and Reviews of New Hardware"
date: 2024-10-18T06:10:08.848Z
updated: 2024-10-24T23:37:01.628Z
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
<li><a href="https://hardware-help.techidaily.com/solved-xbox-acc-driver-issues-on-windows-1187/"><u>[SOLVED] XBOX ACC Driver Issues on Windows 11/8/7</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-enhancing-visual-aesthetics-adding-black-bar-and-box-to-videos/"><u>[Updated] In 2024, Enhancing Visual Aesthetics Adding Black Bar & Box to Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-love-in-action-top-9-premium-wedding-films-on-youtube-and-vimeo/"><u>[Updated] Love in Action Top 9 Premium Wedding Films on YouTube and Vimeo</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-miniature-drones-unveiled-top-10-list-ready/"><u>[Updated] Miniature Drones Unveiled Top 10 List Ready</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-optimal-activities-coexisting-with-listening-podcasts/"><u>[Updated] Optimal Activities Coexisting with Listening Podcasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-gtx-1650-super-drivers-windows-1011/"><u>Download & Update GTX 1650 SUPER Drivers – Windows 10/11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-steps-for-fresh-amd-radeon-rx-460-drivers-download/"><u>Easy Steps for Fresh AMD Radeon RX 460 Drivers Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977792346-effortless-ft2ft232rusbuartdriver-quick-access-and-download-now/"><u>Effortless FT2#FT232R_USB_UART_Driver: Quick Access & Download Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fix-guide-overcoming-ralink-rt3290-driver-compatibility-issues-on-windows-operating-systems-1087/"><u>Fix Guide: Overcoming Ralink RT3290 Driver Compatibility Issues on Windows Operating Systems (10/8/7)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Realme 12 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/how-to-ensure-a-sticker-free-video-experience-on-tiktok/"><u>How to Ensure a Sticker-Free Video Experience on TikTok</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-hp-laserjet-1320-drivers-for-windows-download-and-installation-guide/"><u>Latest HP LaserJet 1320 Drivers for Windows: Download and Installation Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-vivo-g2-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Vivo G2 Phone Pattern Lock</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-full-screen-flexibility-with-pip-feature-on-iphones-for-2024/"><u>Unlock Full Screen Flexibility with PIP Feature on iPhones for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/user-experience-insights-for-snappy-driver-installer-v113/"><u>User Experience Insights for Snappy Driver Installer V1.13</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

