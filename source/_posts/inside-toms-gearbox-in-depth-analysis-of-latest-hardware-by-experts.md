---
title: "Inside Tom's Gearbox: In-Depth Analysis of Latest Hardware by Experts"
date: 2024-12-02T01:04:15.805Z
updated: 2024-12-05T09:55:28.515Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/e274a732c7d0d3f61527d48aecc65a65fbbf84ca45a89dafe19b065f7716c31c.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-tiktok-streams-decoded-finding-your-special-hashtag/"><u>[Updated] 2024 Approved TikTok Streams Decoded Finding Your Special Hashtag</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-laughter-loops-scouring-the-best-chuckles-in-youtube-worlds/"><u>[Updated] Laughter Loops Scouring the Best Chuckles in YouTube Worlds</u></a></li>
<li><a href="https://hardware-help.techidaily.com/boost-productivity-with-this-versatile-dual-usb-charging-station-now-discounted-by-35-essential-addition-to-your-workspace/"><u>Boost Productivity with This Versatile Dual USB Charging Station Now Discounted by 35%, Essential Addition to Your Workspace</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/le-inducing-cover-versions-for-2024/"><u>Chuckle-Inducing Cover Versions for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dont-miss-out-amazon-slashes-prices-by-36-on-samsungs-8tb-t5-ssd-after-prime-day-insights-via-zdnet/"><u>Don't Miss Out: Amazon Slashes Prices by 36% on Samsung's 8TB T5 SSD After Prime Day – Insights via ZDNET</u></a></li>
<li><a href="https://hardware-help.techidaily.com/elevate-your-game-day-with-top-tier-sound-quality-save-big-now-at-amazon-the-1-rated-speaker-system-reviewed-by-zdnet/"><u>Elevate Your Game Day with Top-Tier Sound Quality! Save Big Now at Amazon – The #1 Rated Speaker System Reviewed by ZDNET</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-revolutionary-ar-like-3d-art-visualization-with-asus-latest-laptop-technology-no-vr-gear-required/"><u>Experience Revolutionary AR-Like 3D Art Visualization with Asus' Latest Laptop Technology - No VR Gear Required</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-a-smart-laptop-stand-converts-your-mobile-device-into-a-seamless-additional-display-featured-on-zdnet/"><u>How a Smart Laptop Stand Converts Your Mobile Device Into a Seamless Additional Display - Featured on ZDNET</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oneplus-open-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On OnePlus Open | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-enhance-your-mobile-calls-with-these-top-10-safe-and-free-chat-applications-for-iosandroid/"><u>In 2024, Enhance Your Mobile Calls with These Top 10 Safe & Free Chat Applications for iOS/Android</u></a></li>
<li><a href="https://program-issues.techidaily.com/quick-fix-guide-resolving-world-of-warships-issues-on-windows-machines-5-methods/"><u>Quick Fix Guide: Resolving World of Warships Issues on Windows Machines [5 Methods]</u></a></li>
<li><a href="https://some-approaches.techidaily.com/response/"><u>Response</u></a></li>
</ul></div>

