---
title: "Tom's Tech Hub: Expert Reviews & Insights"
date: 2024-09-04T02:23:39.864Z
updated: 2024-09-05T02:23:39.864Z
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
<li><a href="https://fox-direct.techidaily.com/new-synthesizing-worlds-latest-trends-in-virtual-tech-for-2024/"><u>[New] Synthesizing Worlds  Latest Trends in Virtual Tech for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-cutting-edge-computers-optimal-machines-for-media-creation/"><u>[Updated] 2024 Approved  Cutting-Edge Computers  Optimal Machines for Media Creation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-filming-to-fame-discovering-the-top-10-ladies-on-youtube/"><u>[Updated] 2024 Approved  From Filming to Fame  Discovering the Top 10 Ladies on YouTube</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-unveiling-the-power-of-youtube-backlinks-for-creators/"><u>[Updated] 2024 Approved  Unveiling the Power of YouTube Backlinks for Creators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-eight-essential-free-fb-link-extractors/"><u>[Updated] Eight Essential Free FB Link Extractors</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-how-to-add-filters-effects-and-masks-in-google-meet/"><u>[Updated] In 2024, How to Add Filters, Effects, and Masks in Google Meet?</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-instant-inspiration-free-video-intro-kits-for-2024/"><u>[Updated] Instant Inspiration - Free Video Intro Kits for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-ultimate-unlimited-fb-photomovie-builder/"><u>[Updated] Ultimate Unlimited FB Photo/Movie Builder</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-advanced-typography-animation-suites/"><u>2024 Approved  Advanced Typography Animation Suites</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-cutting-through-the-facade-real-vs-pretend-facebook-followers/"><u>2024 Approved  Cutting Through the Facade  Real vs Pretend Facebook Followers</u></a></li>
<li><a href="https://media-tips.techidaily.com/channel-loss-across-52-regions-impacts-directv-subscribers/"><u>Channel Loss Across 52 Regions Impacts DirecTV Subscribers</u></a></li>
<li><a href="https://facebook.techidaily.com/exploring-metaais-strength-against-standard-ai-chatbots/"><u>Exploring MetaAI's Strength Against Standard AI Chatbots</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-whatsapp-messages-on-vivo-v27-without-them-knowing-drfone-by-drfone-virtual-android/"><u>How to Track WhatsApp Messages on Vivo V27 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-update-canon-pixma-drivers-quickly-and-easily/"><u>How to Update Canon PIXMA Drivers | Quickly & Easily</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-lava-storm-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Lava Storm 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-toms-computer-world-in-depth-analysis-of-toms-hardware-solutions/"><u>Inside Tom's Computer World: In-Depth Analysis of Tom's Hardware Solutions</u></a></li>
<li><a href="https://program-issues.techidaily.com/instant-solution-overcome-sluggish-performance-in-assassins-creed-valhalla/"><u>Instant Solution: Overcome Sluggish Performance in Assassin's Creed: Valhalla</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-core-i7-258-v-vs-amd-ryzen-phoenix-a-battle-for-the-top-spot-on-bapco-benchmarks/"><u>Intel Core I7-258 V vs AMD Ryzen Phoenix: A Battle for the Top Spot on BAPCO Benchmarks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/introducing-the-asus-expertbook-p5-the-newest-intel-core-i7-based-notebook-with-lunar-lake-processors/"><u>Introducing the Asus ExpertBook P5: The Newest Intel Core I7-Based Notebook with Lunar Lake Processors</u></a></li>
<li><a href="https://techtrends.techidaily.com/mastering-citations-how-to-credit-chatgpt-in-academic-writing/"><u>Mastering Citations: How to Credit ChatGPT in Academic Writing</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-pc-building-with-toms-hardware-wisdom/"><u>Mastering PC Building with Tom's Hardware Wisdom</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-tech-essentials-hardware-explained-by-tom/"><u>Mastering Tech Essentials - Hardware Explained by Tom</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-tech-with-insights-from-tomn-hardware-experts/"><u>Mastering Tech with Insights From Tom'n Hardware Experts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-digital-age-through-toms-pc-and-peripherals-guides/"><u>Mastering the Digital Age Through Tom's PC and Peripherals Guides</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-gadget-galaxy-tips-from-toms-tech-hub/"><u>Navigating Gadget Galaxy: Tips From Tom's Tech Hub</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-technology-with-toms-hardware-insights/"><u>Navigating Technology with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-digital-landscape-with-toms-computer-chronicles/"><u>Navigating the Digital Landscape with Tom's Computer Chronicles</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-world-of-electronics-with-toms-hardware-hub/"><u>Navigating the World of Electronics with Tom’s Hardware Hub</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pc-brands-accused-of-overusing-the-term-ai-framework-raises-concerns-about-authenticity/"><u>PC Brands Accused of Overusing the Term 'AI' - Framework Raises Concerns About Authenticity</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pioneering-in-processor-benchmarks-a-closer-look-by-toms-hardware/"><u>Pioneering in Processor Benchmarks - A Closer Look by Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pioneering-performance-analysis-by-toms-components-review/"><u>Pioneering Performance Analysis by Tom's Components Review</u></a></li>
<li><a href="https://hardware-help.techidaily.com/power-play-at-a-bargain-snag-alienwares-massive-rtx-4090-m18-r2-gaming-laptop-with-huge-savings-of-700/"><u>Power-Play at a Bargain: Snag Alienware’s Massive RTX 4090 M18 R2 Gaming Laptop with Huge Savings of $700!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/premier-picks-elite-gaming-pc-laptops-for-less-than-1000-dollars/"><u>Premier Picks: Elite Gaming PC Laptops for Less than 1000 Dollars</u></a></li>
<li><a href="https://hardware-help.techidaily.com/qualcomm-invests-massively-in-promotion-superior-battery-life-propels-copilotplus-pc-popularity-eclipsing-ai-features/"><u>Qualcomm Invests Massively in Promotion: Superior Battery Life Propels Copilot+ PC Popularity, Eclipsing AI Features</u></a></li>
<li><a href="https://data-recovery.techidaily.com/resurrect-inaccessible-storage-areas-with-leading-edge-partition-restoration-applications/"><u>Resurrect Inaccessible Storage Areas with Leading-Edge Partition Restoration Applications</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/revealed-the-ultimate-guide-to-the-newly-unveiled-evga-classified-x67t-amd-board-demanding-over-1300/"><u>Revealed: The Ultimate Guide to the Newly Unveiled EVGA Classified X67t AMD Board - Demanding Over $1,300</u></a></li>
<li><a href="https://hardware-help.techidaily.com/tech-enthusiast-replaces-malfunctioning-lenovo-keyboard-and-boosts-pc-with-high-end-titanium-casing-and-mechanical-keys/"><u>Tech Enthusiast Replaces Malfunctioning Lenovo Keyboard & Boosts PC with High-End Titanium Casing & Mechanical Keys</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-future-of-lightweight-device-charging-unlocked-by-massless-carbon-fiber-structural-batteries/"><u>The Future of Lightweight Device Charging Unlocked by 'Massless' Carbon Fiber Structural Batteries</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-ultimate-review-source-exploring-toms-hardware/"><u>The Ultimate Review Source - Exploring Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-comprehensive-guide-to-cutting-edge-hardware/"><u>Tom's Comprehensive Guide to Cutting-Edge Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-electronics-roundup-in-depth-hardware-evaluations/"><u>Tom's Electronics Roundup: In-Depth Hardware Evaluations</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->