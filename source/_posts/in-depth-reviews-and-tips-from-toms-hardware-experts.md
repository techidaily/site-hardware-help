---
title: In-Depth Reviews and Tips From Tom's Hardware Experts
date: 2024-08-26T08:01:23.600Z
updated: 2024-08-27T08:01:23.600Z
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
<li><a href="https://screen-activity-recording.techidaily.com/new-capturing-creativity-premium-screen-recorder-software-on-pc-and-mac-for-2024/"><u>[New] Capturing Creativity - Premium Screen Recorder Software on PC & Mac for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-quick-methods-for-scavenging-free-frame-videos/"><u>[New] In 2024, Quick Methods for Scavenging Free Frame Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-peak-performance-frames-per-second-slow-motion/"><u>[New] Peak Performance Frames Per Second Slow Motion</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamlining-screen-captures-on-mi-11-lite/"><u>[New] Streamlining Screen Captures on Mi 11 Lite</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-fixed-camera-resumes-with-obs/"><u>[Updated] 2024 Approved  Fixed  Camera Resumes with OBS</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-samsung-ubd-k8500-2023-edition-analysis/"><u>[Updated] Samsung UBD-K8500  2023 Edition Analysis</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-insider-tips-skyrocketing-your-canva-experience/"><u>2024 Approved  Insider Tips  Skyrocketing Your Canva Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/building-knowledge-not-just-text/"><u>Building Knowledge, Not Just Text</u></a></li>
<li><a href="https://sound-issues.techidaily.com/comprehensive-guide-shut-down-audio-enhancements-on-your-windows-10-device/"><u>Comprehensive Guide: Shut Down Audio Enhancements on Your Windows 10 Device</u></a></li>
<li><a href="https://youtube-data.techidaily.com/vating-an-audience-naturally-youtubes-way-for-2024/"><u>Cultivating an Audience Naturally - YouTube's Way for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/cutting-edge-5-online-media-recording-units-for-2024/"><u>Cutting-Edge 5 Online Media Recording Units for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/essential-hardware-know-how-for-enthusiasts-curated-by-tom/"><u>Essential Hardware Know-How for Enthusiasts, Curated by Tom</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-enhanced-multitasking-the-intel-core-driven-acemagix-x1-laptop-featuring-dual-full-hd-screens-starting-at-just-899/"><u>Experience Enhanced Multitasking: The Intel Core-Driven AceMagix X1 Laptop Featuring Dual Full HD Screens, Starting at Just $899</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-high-performance-with-intelamd-fusion-explore-asus-latest-marvels-the-zenbook-s-and-the-tuf-a14/"><u>Experience High Performance with Intel/AMD Fusion - Explore Asus' Latest Marvels: The ZenBook S and the TUF A14</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-insights-into-computing-discover-more-with-toms-hardware/"><u>Expert Insights Into Computing - Discover More with Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-computer-hardware-with-toms-picks/"><u>Exploring Computer Hardware with Tom's Picks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-hands-on-the-latest-razer-blade-15-at-a-record-breaking-1000-discount-this-year/"><u>Get Your Hands on the Latest Razer Blade 15 at a Record-Breaking $1,000 Discount This Year</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/guide-eradicating-pending-videos-on-your-youtube-queue-for-2024/"><u>Guide  Eradicating Pending Videos on Your YouTube Queue for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hands-on-evaluation-of-alienware-m18-r2s-premium-keyboard-and-performance-features/"><u>Hands-On Evaluation of Alienware M18 R2's Premium Keyboard & Performance Features</u></a></li>
<li><a href="https://hardware-help.techidaily.com/high-tier-gaming-laptops-that-wont-break-your-bank-price-under-1000/"><u>High-Tier Gaming Laptops That Won't Break Your Bank (Price Under $1,000)</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-samsung-galaxy-m14-4g-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Samsung Galaxy M14 4G Phone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-icebound-battles-spectacular-moments-from-22s-snowboard-cross-faceoffs/"><u>In 2024, Icebound Battles  Spectacular Moments From '22'S Snowboard Cross Faceoffs</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-leaders-shaping-the-marvel-online-experience/"><u>In 2024, Leaders Shaping the Marvel Online Experience</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-reasons-why-pokemon-gps-does-not-work-on-nokia-c12-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Reasons why Pokémon GPS does not Work On Nokia C12 Pro? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-top-thumbnail-dimensions-for-online-success/"><u>In 2024, Top Thumbnail Dimensions for Online Success</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ultimate-guide-to-catch-the-regional-located-pokemon-for-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate Guide to Catch the Regional-Located Pokemon For Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/in-depth-analysis-of-the-updated-dell-xps-13-9345-timeless-aesthetics-meets-enhanced-performance/"><u>In-Depth Analysis of the Updated Dell XPS 13 (9345): Timeless Aesthetics Meets Enhanced Performance</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-and-snapdragon-showdown-who-wins-when-it-comes-to-elite-battery-life-for-laptops/"><u>Intel and Snapdragon Showdown: Who Wins When It Comes to Elite Battery Life for Laptops?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-driven-two-14-inch-displays-experience-the-acemagic-x1-laptop-for-under-900/"><u>Intel Driven, Two 14-Inch Displays: Experience the Acemagic X1 Laptop for Under $900</u></a></li>
<li><a href="https://hardware-help.techidaily.com/introducing-a-game-changing-mainboard-new-framework-partners-with-deepcomputing-to-harness-the-power-of-risc-v-in-their-latest-jh7110-laptop-board/"><u>Introducing a Game-Changing Mainboard: New Framework Partners with DeepComputing to Harness the Power of RISC-V in Their Latest JH7110 Laptop Board</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-technology-choices-with-guidance-from-toms-hardware/"><u>Mastering Technology Choices with Guidance From Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-technology-choices-a-deep-dive-into-hardware-with-toms-experts/"><u>Mastering Technology Choices: A Deep Dive Into Hardware with Tom's Experts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-game-with-alienware-m1-r2-review-powerhouse-pc-and-clicky-keys-showdown/"><u>Mastering the Game with Alienware M1# R2 Review: Powerhouse PC and Clicky Keys Showdown</u></a></li>
<li><a href="https://hardware-help.techidaily.com/meet-asus-trailblazing-laptop-the-new-expertbook-p5405-equipped-with-advanced-intel-processors/"><u>Meet Asus' Trailblazing Laptop: The New ExpertBook P5405 Equipped with Advanced Intel Processors</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigate-the-tech-world-discoveries-from-toms-hardware-innovators/"><u>Navigate the Tech World: Discoveries From Tom's Hardware Innovators</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-tech-world-through-toms-hardware-lens/"><u>Navigating the Tech World Through Tom's Hardware Lens</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-the-world-of-electronics-at-toms-hardware/"><u>Navigating the World of Electronics at Tom's Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pioneering-the-future-of-tech-in-depth-hardware-analysis-from-toms-workshop/"><u>Pioneering the Future of Tech: In-Depth Hardware Analysis From Tom's Workshop</u></a></li>
<li><a href="https://hardware-help.techidaily.com/qualcomm-and-lenovo-unite-meet-the-elite-snapdragon-powered-long-battery-life-thinkpad-t14s-laptop-with-top-tier-ram-and-ssd-storage/"><u>Qualcomm & Lenovo Unite: Meet the Elite Snapdragon-Powered, Long-Battery-Life ThinkPad T14s Laptop with Top-Tier RAM and SSD Storage</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revolutionize-your-communication-morse-code-input-through-lid-impacts-handle-gently-to-avoid-damage/"><u>Revolutionize Your Communication: Morse Code Input Through Lid Impacts – Handle Gently to Avoid Damage</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revolutionize-your-tech-setup-new-frameworks-latest-innovation-with-deepcomputings-starfive-soc-board-features-advanced-risc-v-technology-for-laptops/"><u>Revolutionize Your Tech Setup: New Framework's Latest Innovation with DeepComputing's StarFive SoC Board Features Advanced RISC-V Technology for Laptops</u></a></li>
<li><a href="https://hardware-help.techidaily.com/snapdragon-elite-x-laptops-hit-shelves-discover-your-microsoft-copilot-ready-purchase-options/"><u>Snapdragon Elite X Laptops Hit Shelves - Discover Your Microsoft Copilot-Ready Purchase Options</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722972781906-step-by-step-update-for-intels-latest-iris-plus-graphics-card-drive-with-speed-and-ease/"><u>Step-by-Step Update for Intel's Latest Iris Plus Graphics Card - Drive with Speed and Ease</u></a></li>
<li><a href="https://hardware-help.techidaily.com/taking-flight-on-creativity-discover-the-unique-battery-operated-all-in-one-pc-by-flying-lotus-crafted-with-a-laptop-core-and-advanced-3d-prints/"><u>Taking Flight on Creativity - Discover the Unique Battery-Operated All-in-One PC by Flying Lotus, Crafted with a Laptop Core and Advanced 3D Prints</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-apex-gamers-choice-of-2024-in-depth-benchmarking-and-reviews-of-leading-laptops/"><u>The Apex Gamers' Choice of 2024: In-Depth Benchmarking and Reviews of Leading Laptops</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-comprehensive-guide-to-computer-systems-by-toms-hardware-experts/"><u>The Comprehensive Guide to Computer Systems by Tom’s Hardware Experts</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-windows-defender-smartscreen-temporarily-unavailable/"><u>Troubleshooting: Windows Defender SmartScreen Temporarily Unavailable</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->