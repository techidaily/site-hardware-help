---
title: "Tom's Gadget Guide: Expert Analysis and Reviews of New Hardware"
date: 2024-09-04T02:28:43.364Z
updated: 2024-09-05T02:28:43.364Z
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
<li><a href="https://some-knowledge.techidaily.com/new-imovie-cropping-mystery-unveiled/"><u>[New] IMovie Cropping Mystery Unveiled</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-facebooks-blue-icon-decoding-its-meaning-in-chats/"><u>[New] In 2024, Facebook's Blue Icon  Decoding Its Meaning in Chats</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-9-techniques-for-attractive-and-engaging-unboxings-on-instagram/"><u>[Updated] 9 Techniques for Attractive and Engaging Unboxings on Instagram</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-crafting-immersive-experiences-with-compelling-tiktok-captions-top-5/"><u>[Updated] In 2024, Crafting Immersive Experiences with Compelling TikTok Captions (Top 5)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/beyond-fractal-design-the-rise-of-a-new-diy-north-case-solution-for-raspberry-pi-aficionados-by-makers/"><u>Beyond Fractal Design: The Rise of a New DIY North Case Solution for Raspberry Pi Aficionados by Makers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/core-i9-11900k-achieves-historic-milestone-shatters-expectations-at-7abbbb-ghz/"><u>Core I9-11900K Achieves Historic Milestone: Shatters Expectations at 7.abbbb GHz</u></a></li>
<li><a href="https://hardware-help.techidaily.com/cxmt-chinese-dram-producer-confirms-adherence-to-us-export-regulations-for-185nm-chip-production-debunking-previous-allegations-of-non-compliance-at-17nm/"><u>CXMT, Chinese DRAM Producer, Confirms Adherence to US Export Regulations for 18.5Nm Chip Production: Debunking Previous Allegations of Non-Compliance at 17Nm</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ddr5-7200-corsair-dominator-titanium-xl-premium-2x24gb-memory-kit-assessment-and-exceeding-specs/"><u>DDR5-7200 Corsair Dominator Titanium XL - Premium 2X24GB Memory Kit Assessment & Exceeding Specs!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dive-into-computing-with-toms-hardware-experts-your-ultimate-resource-for-gadget-analysis/"><u>Dive Into Computing with Tom's Hardware Experts: Your Ultimate Resource for Gadget Analysis</u></a></li>
<li><a href="https://location-social.techidaily.com/does-honor-100-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Honor 100 Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/enhanced-with-cookiebot-technology-boosting-your-online-presence/"><u>Enhanced with Cookiebot Technology: Boosting Your Online Presence</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-enhanced-laptop-performance-with-seirams-innovative-solution-128gb-camm2-standard-certified-memory-sticks-get-jedec-endorsement/"><u>Experience Enhanced Laptop Performance with SEIRAM's Innovative Solution: 128GB CAMM2-Standard-Certified Memory Sticks Get JEDEC Endorsement</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-technology-with-tom-your-trusted-source-for-hardware-insights-and-reviews/"><u>Exploring Technology with Tom: Your Trusted Source for Hardware Insights and Reviews</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-latest-tech-an-insightful-guide-with-toms-hardware/"><u>Exploring the Latest Tech: An Insightful Guide with Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723964507934-get-ready-affordable-12-m2-hardware-adapter-now-available-for-your-raspberry-pi-5/"><u>Get Ready: Affordable $12 M.2 Hardware Adapter Now Available for Your Raspberry Pi 5!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-is-ai-revolutionizing-the-future-of-medicine-with-tools-like-chatgpt/"><u>How Is AI Revolutionizing the Future of Medicine with Tools Like ChatGPT?</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-continuous-freezing-in-tormented-souls-for-pc-users/"><u>How to Fix Continuous Freezing in Tormented Souls for PC Users</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-boost-your-channel-game-essential-video-editing-advice/"><u>In 2024, Boost Your Channel Game  Essential Video Editing Advice</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-motorola-razr-40-ultra-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Motorola Razr 40 Ultra online without jailbreak</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Vivo Y100t | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-toms-gadget-review-expert-insights-on-digital-devices-and-systems/"><u>Inside Tom's Gadget Review: Expert Insights on Digital Devices and Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/lpddr5x-camm2-teamgroup-expands-options-with-their-innovative-compact-memory-modules-now-boasting-advanced-ai-features/"><u>LPDDR5X CAMM2: TeamGroup Expands Options with Their Innovative, Compact Memory Modules - Now Boasting Advanced AI Features</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723964500081-maintain-a-natural-and-coherent-speech-pattern-despite-the-constraints-of-embedding-hidden-messages/"><u>Maintain a Natural and Coherent Speech Pattern Despite the Constraints of Embedding Hidden Messages.</u></a></li>
<li><a href="https://hardware-help.techidaily.com/maximizing-raspberry-pi-5s-potential-with-the-pi-ice-tower-plus-an-in-depth-review-on-rapid-heat-dissipation-performance/"><u>Maximizing Raspberry Pi 5'S Potential with the Pi Ice Tower Plus: An In-Depth Review on Rapid Heat Dissipation Performance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-gadget-innovations-with-toms-reviews-and-guides/"><u>Navigating Gadget Innovations with Tom's Reviews and Guides</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-steams-space-utilization-mastery-guide/"><u>Navigating Steam's Space Utilization Mastery Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-world-of-gadgets-with-tom-expert-hardware-guidance/"><u>Navigating the World of Gadgets with Tom - Expert Hardware Guidance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pi-technology-set-to-launch-public-offering-in-london-market/"><u>Pi Technology Set to Launch Public Offering in London Market</u></a></li>
<li><a href="https://hardware-help.techidaily.com/review-of-rodecaster-duo-the-ultimate-toolkit-for-streamers/"><u>Review of Rodecaster Duo: The Ultimate Toolkit for Streamers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723964502567-the-embedded-message-future-care-should-be-spread-across-different-sentences-throughout-the-monologue-not-all-in-one-go/"><u>The Embedded Message FUTURE CARE Should Be Spread Across Different Sentences Throughout the Monologue, Not All in One Go</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleash-peak-performance-with-corsair-vengeance-ddr5-5200-c38-a-4x48gb-memory-powerhouse-for-experts-and-enthusiasts/"><u>Unleash Peak Performance with Corsair Vengeance DDR5-5200 C38, a 4X48GB Memory Powerhouse for Experts and Enthusiasts</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-power-of-chatgpt-on-your-smartphone-with-new-android-support/"><u>Unlock the Power of ChatGPT on Your Smartphone with New Android Support!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-gadgets-with-tom-comprehensive-guides-on-pc-hardware/"><u>Unveiling Gadgets with Tom: Comprehensive Guides on PC Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-tachyon-on-particle-board-an-advanced-single-board-computer-with-integrated-ai-acceleration-by-snapdragon-technology/"><u>Unveiling Tachyon on Particle Board: An Advanced Single-Board Computer with Integrated AI Acceleration by Snapdragon Technology</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->