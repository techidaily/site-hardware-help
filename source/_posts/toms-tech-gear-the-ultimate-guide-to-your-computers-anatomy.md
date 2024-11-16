---
title: "Tom's Tech Gear: The Ultimate Guide to Your Computer's Anatomy"
date: 2024-11-09T00:54:23.282Z
updated: 2024-11-15T17:45:45.763Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/e77b802386df347968174243d9eec6b1ff5aaa13a757fb94ecaebe8d1775e8b5.jpg
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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-expert-strategies-for-choosing-valheim-crops/"><u>[New] 2024 Approved Expert Strategies for Choosing Valheim Crops</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-skyrocketing-fb-engagement-masterful-seo-techniques-explored/"><u>[New] In 2024, Skyrocketing FB Engagement Masterful SEO Techniques Explored</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-slash-length-amplify-impact-youtube-video-editing/"><u>[New] In 2024, Slash Length, Amplify Impact YouTube Video Editing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-optimal-obs-configuration-for-budget-pcs/"><u>[New] Optimal OBS Configuration for Budget PCs</u></a></li>
<li><a href="https://blog-min.techidaily.com/2-popular-youtube-to-mp3-converter-programs-ideal-replacements-for-keepvid/"><u>2. Popular YouTube-to-MP3 Converter Programs: Ideal Replacements for Keepvid</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-heartfelt-goodbyes-free-or-subscribed-video-endings/"><u>2024 Approved Heartfelt Goodbyes Free or Subscribed Video Endings</u></a></li>
<li><a href="https://hardware-help.techidaily.com/2024s-ultimate-guide-to-streaming-mic-selection-by-experts-zdnet/"><u>2024'S Ultimate Guide to Streaming Mic Selection by Experts - ZDNet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/become-a-better-self-the-20-best-exercising-soundtracks-for-2024/"><u>Become a Better Self The 20 Best Exercising Soundtracks for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fast-and-simple-guide-linking-laptop-to-tv-seamlessly-tips/"><u>Fast & Simple Guide: Linking Laptop to TV Seamlessly - Tips</u></a></li>
<li><a href="https://hardware-help.techidaily.com/grab-your-discounted-m1-macbook-air-today-save-200-see-deals/"><u>Grab Your Discounted M1 MacBook Air Today - Save $200! See Deals</u></a></li>
<li><a href="https://hardware-help.techidaily.com/huge-savings-alert-get-your-lenovo-pro-laptops-for-up-to-50-less-before-october-prime-day-gadget-news-hub/"><u>Huge Savings Alert: Get Your Lenovo Pro Laptops for Up to 50% Less Before October Prime Day | Gadget News Hub</u></a></li>
<li><a href="https://hardware-help.techidaily.com/save-big-this-black-friday-exclusive-offer-on-dell-inspiron-16-inch-2-in-1-laptop-for-250-less-find-your-deal-at-znet/"><u>Save Big This Black Friday: Exclusive Offer on Dell Inspiron 16-Inch 2-in-1 Laptop for $250 Less | Find Your Deal at Znet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

