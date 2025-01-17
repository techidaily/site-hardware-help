---
title: "Navigating the World of Computing: Trustworthy Insights From Tom's Hardware Professionals"
date: 2025-01-12T21:05:08.363Z
updated: 2025-01-16T17:26:13.734Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-blitz-photo-screening-for-windows-users/"><u>[New] 2024 Approved Blitz Photo Screening for Windows Users</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-evaluating-mr-beasts-fortune/"><u>[Updated] 2024 Approved Evaluating Mr. Beast’s Fortune</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/compress-videos-in-minutes-10-free-online-tools-with-no-software/"><u>Compress Videos in Minutes 10 Free Online Tools with No Software</u></a></li>
<li><a href="https://hardware-help.techidaily.com/direct-link-to-downloading-the-focusrite-scarlett-2i2-windows-driver-free/"><u>Direct Link to Downloading the Focusrite Scarlett 2I2 Windows Driver (Free)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-newest-geforce-rtx-3080-ti-drivers-compatible-with-windows-11-10-and-7/"><u>Download the Newest GeForce RTX 3080 Ti Drivers: Compatible with Windows 11, 10 & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-gaming-performance-with-the-recent-update-of-nvidia-geforce-210-drivers-for-windows-10/"><u>Enhance Gaming Performance with the Recent Update of Nvidia GeForce 210 Drivers for Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/instant-update-guide-new-surface-dock-driver-download-and-installation/"><u>Instant Update Guide: New Surface Dock Driver Download and Installation</u></a></li>
<li><a href="https://facebook.techidaily.com/master-the-art-of-reducing-personalized-marketing-efforts-online/"><u>Master the Art of Reducing Personalized Marketing Efforts Online</u></a></li>
<li><a href="https://some-guidance.techidaily.com/seamless-blu-ray-to-avchd-video-upgrade-master-the-art-of-easy-disc-conversions-with-our-top-notch-software-solution/"><u>Seamless Blu-Ray to AVCHD Video Upgrade - Master the Art of Easy Disc Conversions with Our Top-Notch Software Solution</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-xiaomi-redmi-note-12r-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Xiaomi Redmi Note 12R Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://win-top.techidaily.com/windows-78mp3-wav/"><u>Windows 7/8向けにMP3, WAV音声ファイルを効果的に編集する手引き</u></a></li>
</ul></div>

