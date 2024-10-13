---
title: "Tom's Gadget Guide: Expert Analysis and Reviews of New Hardware"
date: 2024-10-12T13:53:25.080Z
updated: 2024-10-12T19:15:50.201Z
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
<li><a href="https://screen-video-capture.techidaily.com/new-essential-screen-recording-steps-for-perfection-for-2024/"><u>[New] Essential Screen Recording Steps for Perfection for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-revamping-your-podcasts-identity-leading-ai-tools-for-2024/"><u>[Updated] Revamping Your Podcast's Identity Leading AI Tools for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/pcmacbookcd/"><u>「PCやMacBookで音楽CDプレイヤー設定 - トラブルシューティングガイド付き」</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-pixel-queens-rising-youtubes-top-10/"><u>2024 Approved Pixel Queens Rising YouTube's #Top 10</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-syncing-sonata-to-still-images-in-the-cyberrealm/"><u>2024 Approved Syncing Sonata to Still Images in the Cyberrealm</u></a></li>
<li><a href="https://hardware-help.techidaily.com/complete-guide-to-downloading-and-installing-konica-minolta-printer-drivers-on-windows-platforms/"><u>Complete Guide to Downloading and Installing Konica Minolta Printer Drivers on Windows Platforms</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fixing-compatibility-issues-with-startech-devices-in-windows-1187-operating-systems/"><u>Fixing Compatibility Issues with StarTech Devices in Windows 11/8/7 Operating Systems</u></a></li>
<li><a href="https://android-location.techidaily.com/how-to-fake-gps-on-android-without-mock-location-for-your-nokia-xr21-drfone-by-drfone-virtual/"><u>How to Fake GPS on Android without Mock Location For your Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-impact-of-photoshops-stabilization-on-quality-control/"><u>In 2024, The Impact of Photoshop's Stabilization on Quality Control</u></a></li>
<li><a href="https://hardware-help.techidaily.com/new-version-of-software-for-enhancing-your-logitech-extreme-3d-experience/"><u>New Version of Software for Enhancing Your Logitech Extreme 3D Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722966291100-quick-and-trouble-free-setup-for-your-usb-camera-expertly-crafted-drivers-awaiting/"><u>Quick & Trouble-Free Setup for Your USB Camera - Expertly Crafted Drivers Awaiting</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/strategizing-for-secure-interactions-with-adaptive-ai/"><u>Strategizing for Secure Interactions with Adaptive AI</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-art-of-empire-in-imperator-rome-insights-and-reviews/"><u>The Art of Empire in Imperator: Rome – Insights & Reviews</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-guide-fixed-issues-with-pci-cryptographic-controllers/"><u>Troubleshooting Guide: Fixed Issues with PCI Cryptographic Controllers</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

