---
title: Comprehensive Hardware Analysis by Tom's Computing Guide
date: 2024-11-10T19:53:42.529Z
updated: 2024-11-16T05:34:52.901Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/oQjfKNyL7NhTMuhWXBFZVV-320-80.png
---

## Unveiling Cutting-Edge Gadgets with Tom's Hardware Review

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Intel statement on via oxidation

**Short answer:** We can confirm there was a via Oxidation manufacturing issue (addressed back in 2023) but it is not related to the instability issue.

**Long answer:**   _We can confirm that the via Oxidation manufacturing issue affected some early Intel Core 13th Gen desktop processors. However, the issue was root caused and addressed with manufacturing improvements and screens in 2023\. We have also looked at it from the instability reports on Intel Core 13th Gen desktop processors and the analysis to-date has determined that only a small number of instability reports can be connected to the manufacturing issue._

 _For the Instability issue, we are delivering a microcode patch which addresses exposure to elevated voltages which is a key element of the Instability issue. We are currently validating the microcode patch to ensure the instability issues for 13th/14th Gen are addressed. -_ Intel representative[via Reddit](https://www.reddit.com/r/intel/comments/1e9mf04/comment/lefz09c/) .

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
<li><a href="https://fox-cloud.techidaily.com/new-mixease-mac-and-windows-unifier-for-2024/"><u>[New] MIXEase Mac & Windows Unifier for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-night-of-the-living-dead-games-an-epic-selection-for-2024/"><u>[New] Night of the Living Dead Games An Epic Selection for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-best-in-class-elite-4k-televisions/"><u>[Updated] Best in Class Elite 4K Televisions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-easy-to-follow-strategies-recording-hulu-across-windowsmacandroidios/"><u>[Updated] Easy-to-Follow Strategies Recording Hulu Across Windows/Mac/Android/iOS</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-free-vecto-art-and-graphic-sites-compared-whos-the-best-for-2024/"><u>[Updated] Free Vecto Art & Graphic Sites Compared – Who's the Best for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-crafting-memes-the-ultimate-guide-to-gif-creation/"><u>[Updated] In 2024, Crafting Memes The Ultimate Guide to GIF Creation</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/insta360-x2-pro-capture-your-adventures-anywhere-even-wet/"><u>Insta360 X2 Pro: Capture Your Adventures Anywhere, Even Wet</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/mastering-transitions-in-audition-fade-in-basics/"><u>Mastering Transitions in Audition Fade-In Basics</u></a></li>
<li><a href="https://hardware-help.techidaily.com/optimize-entertainment-with-plex-top-prime-day-bargains/"><u>Optimize Entertainment with Plex: Top Prime Day Bargains</u></a></li>
<li><a href="https://hardware-help.techidaily.com/review-of-eufy-omni-s1-pro-the-futuristic-automaton-vacuum/"><u>Review of Eufy Omni S1 Pro: The Futuristic Automaton Vacuum</u></a></li>
<li><a href="https://hardware-help.techidaily.com/revolutionary-leap-intel-enhances-performance-of-moon-inspired-silicon-wafers/"><u>Revolutionary Leap: Intel Enhances Performance of Moon-Inspired Silicon Wafers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/smart-displays-on-chargers-a-comprehensive-look-at-the-shargeek-170-review/"><u>Smart Displays on Chargers: A Comprehensive Look at the Shargeek 170 Review</u></a></li>
<li><a href="https://win-answers.techidaily.com/tackling-the-critical-error-in-ark-file-management-system-a-step-by-step-guide/"><u>Tackling the Critical Error in ARK File Management System - A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-evolution-of-gaming-mice-how-keychron-q1-he-leads-the-way-with-its-innovative-magnetic-switches/"><u>The Evolution of Gaming Mice: How Keychron Q1 HE Leads the Way with Its Innovative Magnetic Switches</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-ultimate-guide-to-using-your-tv-remote-for-console-gaming-and-smart-devices-like-amazon-fire-stick-or-appletv/"><u>The Ultimate Guide to Using Your TV Remote for Console Gaming & Smart Devices Like Amazon Fire Stick or AppleTV</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-weeks-insights-on-ios-upgrades-and-tech-recall-highlights-for-iphones/"><u>The Week's Insights on iOS Upgrades & Tech Recall Highlights for iPhones</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-5-essential-devices-you-need-for-unexpected-power-losses/"><u>Top 5 Essential Devices You Need for Unexpected Power Losses</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-rated-fire-tv-stick-models-a-comprehensive-guide/"><u>Top Rated Fire TV Stick Models : A Comprehensive Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-realme-c53-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Realme C53 without Him Knowing | Dr.fone</u></a></li>
</ul></div>

