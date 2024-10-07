---
title: Navigating the World of Hardware with Tom's Guides
date: 2024-10-02T19:34:15.008Z
updated: 2024-10-07T18:38:56.555Z
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-a-beginners-guide-to-gameye-win10-for-2024/"><u>[New] A Beginner's Guide to GamEye Win10 for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-swift-strategies-to-end-windows-10s-unstable-photo-viewing/"><u>[Updated] In 2024, Swift Strategies to End Windows 10'S Unstable Photo Viewing</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-advanced-approaches-to-obs-facebook-streaming/"><u>2024 Approved Advanced Approaches to OBS-Facebook Streaming</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-new-magicard-rio-pro-driver-update-compatible-with-windows-1011-81-and-win-7/"><u>Download the New Magicard Rio Pro Driver Update - Compatible with Windows 10/11, 8.1 & Win 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-download-hp-officejet-4650-printer-software-suite-for-windows/"><u>Free Download: HP OfficeJet 4650 Printer Software Suite for Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-dolby-audio-driver-updates-for-windows-111081-free-download-now/"><u>Get the Latest Dolby Audio Driver Updates for Windows 11/10/8.1 - Free Download Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-secure-update-and-enhance-your-gaming-experience-with-fresh-amd-vega-56-drivers-on-windows/"><u>How To: Secure, Update And Enhance Your Gaming Experience With Fresh AMD Vega 56 Drivers on Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-enhance-mobile-viewing-fb-videos-on-android/"><u>In 2024, Enhance Mobile Viewing FB Videos on Android</u></a></li>
<li><a href="https://win-able.techidaily.com/mastering-ubisoft-connect-tips-and-tricks-to-overcome-setbacks/"><u>Mastering Ubisoft Connect: Tips and Tricks to Overcome Setbacks !</u></a></li>
<li><a href="https://extra-tips.techidaily.com/motion-control-in-vr-keeping-nausea-at-bay/"><u>Motion Control in VR Keeping Nausea at Bay</u></a></li>
<li><a href="https://games-able.techidaily.com/tips-for-deciding-to-mend-or-replace-your-console/"><u>Tips for Deciding to Mend or Replace Your Console</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

