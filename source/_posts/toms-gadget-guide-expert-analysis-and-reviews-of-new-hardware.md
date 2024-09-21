---
title: "Tom's Gadget Guide: Expert Analysis and Reviews of New Hardware"
date: 2024-09-18T23:13:59.405Z
updated: 2024-09-21T06:22:38.026Z
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
<li><a href="https://extra-approaches.techidaily.com/updated-pushing-the-limits-of-visual-impact-in-ae-titles/"><u>[Updated] Pushing the Limits of Visual Impact in AE Titles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-guide-to-choosing-a-camera-gimbal-for-drone-photographers/"><u>2024 Approved The Ultimate Guide To Choosing A Camera Gimbal For Drone Photographers</u></a></li>
<li><a href="https://sound-issues.techidaily.com/cyberpunk-2077-audio-issues-resolved-a-guide-to-restoring-game-sound-on-windows-10/"><u>Cyberpunk 2077 Audio Issues Resolved? A Guide to Restoring Game Sound on Windows 10</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/download-the-latest-amd-radeon-gpu-software-version-2410-drivers/"><u>Download the Latest AMD Radeon GPU Software Version 24.10 Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-audio-experience-on-windows-11-10-and-81-with-the-latest-dolby-driver-updates/"><u>Enhance Your Audio Experience on Windows 11, 10 & 8.1 with the Latest Dolby Driver Updates</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-gadget-guides-discover-hardware-secrets-with-tom/"><u>Expert Gadget Guides - Discover Hardware Secrets with Tom</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-infinix-zero-5g-2023-turbo-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Infinix Zero 5G 2023 Turbo Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-locked-iphone-13-pro-max-by-restoring-by-drfone-ios-unlock-ios-unlock/"><u>How to Unlock locked iPhone 13 Pro Max by restoring</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-masterful-approaches-to-live-sports-video-capture/"><u>In 2024, Masterful Approaches to Live Sports Video Capture</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-hp-deskjet-3755-all-in-one-printer-driver-download-for-windows-10-8-7/"><u>Latest HP DeskJet 3755 All-in-One Printer Driver Download for Windows 10, 8, 7</u></a></li>
<li><a href="https://extra-hints.techidaily.com/nostruggle-livecast-how-to-simplify-your-podcast-broadcast/"><u>NoStruggle Livecast How to Simplify Your Podcast Broadcast</u></a></li>
<li><a href="https://tech-hub.techidaily.com/top-4-ai-detection-software-solutions-for-educators-and-managers-checking-gpt-authenticity/"><u>Top 4 AI Detection Software Solutions for Educators & Managers Checking GPT Authenticity</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047351/19272" target="_top" id="2047351">
  <img src="//a.impactradius-go.com/display-ad/19272-2047351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

