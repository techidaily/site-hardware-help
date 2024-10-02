---
title: "Tom's Tech Hub: Expert Reviews & Insights"
date: 2024-10-01T00:45:05.914Z
updated: 2024-10-02T00:46:57.736Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/b707c0511382e78c7bbc2631c8c2ac749bfdb8b7dcef137c48ff3983d7a66e67.jpg
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
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-clan-combat-chronicles-top-10-games-inspired-by-ghost-of-tsushima/"><u>[Updated] In 2024, Clan Combat Chronicles Top 10 Games Inspired by Ghost of Tsushima</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/4-easy-ways-for-your-itel-a60-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>4 Easy Ways for Your Itel A60 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-hp-laserjet-pro-mfp-m428fdw-software-for-pc-windows-11107-supported-versions/"><u>Download HP LaserJet Pro MFP M428fdw Software for PC - Windows 11/10/7 Supported Versions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/gastrointestinal-complications/"><u>Gastrointestinal Complications</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1715860142549-in-2024-master-the-art-of-organizing-group-conversations-on-skype-irrespective-of-your-systems-os/"><u>In 2024, Master the Art of Organizing Group Conversations on Skype, Irrespective of Your System's OS.</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/is-opting-for-applecareplus-a-wise-decision-or-not/"><u>Is Opting for AppleCare+ a Wise Decision or Not?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-updating-the-intel-centrino-advantage-n-6230w-wireless-networking-card-driver/"><u>Step-by-Step Guide: Updating the Intel Centrino Advantage-N 6230W Wireless Networking Card Driver</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-untold-journey-of-an-instagram-story-enthusiast/"><u>The Untold Journey of an Instagram Story Enthusiast</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-hp-monitor-drivers-in-windows-11-8-and-7-step-by-step-solutions/"><u>Troubleshooting HP Monitor Drivers in Windows 11, 8 & 7: Step-by-Step Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

