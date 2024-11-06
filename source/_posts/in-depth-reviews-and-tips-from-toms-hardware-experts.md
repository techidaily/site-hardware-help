---
title: In-Depth Reviews and Tips From Tom's Hardware Experts
date: 2024-10-30T22:23:10.208Z
updated: 2024-11-05T16:18:13.979Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/KqsTkijmXtNepKSEWE4XDE-320-80.jpg
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
<li><a href="https://fox-blue.techidaily.com/2024-approved-navigating-the-thrilling-world-of-drone-racing-and-premium-fpv-units/"><u>2024 Approved Navigating the Thrilling World of Drone Racing & Premium FPV Units</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-unparalleled-flexibility-the-dell-inspiron-outshines-competitors-in-comprehensive-performance-review/"><u>Experience Unparalleled Flexibility: The Dell Inspiron Outshines Competitors in Comprehensive Performance Review</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/high-performance-network-adapters-extend-connectivity-range-and-escalate-information-flow/"><u>High-Performance Network Adapters: Extend Connectivity Range & Escalate Information Flow</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hps-greatest-seasonal-discounts-for-the-holidps-a-comprehensive-guide-curated/"><u>HP's Greatest Seasonal Discounts for the Holidps - A Comprehensive Guide | Curated</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-artistic-zoomers-handbook-a-filters-journey/"><u>In 2024, The Artistic Zoomer's Handbook A Filters Journey</u></a></li>
<li><a href="https://hardware-help.techidaily.com/prime-day-goldmine-unbeatable-best-buy-offers-for-the-upcoming-october-prime-day-2024-highlights/"><u>Prime Day Goldmine: Unbeatable Best Buy Offers for the Upcoming October Prime Day 2024 Highlights</u></a></li>
<li><a href="https://solve-lab.techidaily.com/top-5-techniques-to-enhance-image-clarity-and-quality/"><u>Top 5 Techniques to Enhance Image Clarity and Quality</u></a></li>
<li><a href="https://os-tips.techidaily.com/top-6-solutions-for-resolving-your-ipads-screen-mirroring-problem/"><u>Top 6 Solutions for Resolving Your iPad's Screen Mirroring Problem</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-rated-ram-mods-enhancing-your-pcs-performance-for-productivity-and-play-tech-insights-by-zdnet/"><u>Top Rated RAM Mods : Enhancing Your PC's Performance for Productivity & Play | Tech Insights by ZDNet</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-pc-problems-in-bloodhunt-eliminating-freezes-and-stutters/"><u>Troubleshooting PC Problems in Bloodhunt: Eliminating Freezes & Stutters</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guide-to-the-ideal-power-bank-for-macbook-pro-users-expert-picks-and-reviews-cnet/"><u>Ultimate Guide to the Ideal Power Bank for MacBook Pro Users: Expert Picks and Reviews - CNET</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094421/7443" target="_top" id="2094421">
  <img src="//a.impactradius-go.com/display-ad/7443-2094421" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094421/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

