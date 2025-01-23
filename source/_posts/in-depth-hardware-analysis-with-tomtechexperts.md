---
title: In-Depth Hardware Analysis with TomTechExperts
date: 2025-01-21T03:12:32.753Z
updated: 2025-01-22T18:33:49.251Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/m73AaKbv4AF6cNcLYtefbX-320-80.jpg
---

## Master the Latest Tech Trends with Tom's Hardware Reviews & Tips

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-how-to-make-killer-youtube-channel-art/"><u>[New] 2024 Approved How to Make Killer YouTube Channel Art</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/esigning-an-editorial-epilogue-for-2024/"><u>[New] Designing an Editorial Epilogue for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-how-to-create-metaverse-avatar-with-ease-an-ultimate-guide/"><u>[New] How to Create Metaverse Avatar with Ease An Ultimate Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-the-symphony-of-well-being-learn-from-asmr/"><u>[Updated] In 2024, The Symphony of Well-Being – Learn From ASMR</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-complete-insight-into-vivacut-2024-features-and-functionality/"><u>[Updated] The Complete Insight Into VivaCut 2024 Features & Functionality</u></a></li>
<li><a href="https://hardware-help.techidaily.com/boost-your-gaming-fsps-2500w-psu-powers-up-to-four-monster-rtx-4090-graphics-cards/"><u>Boost Your Gaming: FSP's 2500W PSU Powers Up to Four Monster RTX 4090 Graphics Cards</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-assessment-performance-testing-for-corsairs-cx7er-m-power-unit/"><u>Comprehensive Assessment: Performance Testing for Corsair's CX7er M Power Unit</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-top-gear-analysis-with-toms-hardware-hub/"><u>Discover Top Gear Analysis with Tom's Hardware Hub</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-eliminate-screen-fluttering-in-google-chrome-on-windows-an-authoritative-2024-tutorial/"><u>How to Eliminate Screen Fluttering in Google Chrome on Windows - An Authoritative 2024 Tutorial</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-lava-yuva-2-phone-without-password-by-drfone-android/"><u>How To Unlock Lava Yuva 2 Phone Without Password?</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-the-complete-guide-to-cd-conversion-and-burning-with-wmp/"><u>In 2024, The Complete Guide to CD Conversion & Burning with WMP</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-unveiling-the-secrets-of-superior-tunefab-recordings/"><u>In 2024, Unveiling the Secrets of Superior Tunefab Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-error-handling-fixing-missing-updates-error-code-0x80070003/"><u>Mastering Windows Error Handling: Fixing Missing Updates (Error Code: 0X80070003)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/navigating-new-electronics-with-tom-in-depth-hardware-analysis/"><u>Navigating New Electronics with Tom: In-Depth Hardware Analysis</u></a></li>
<li><a href="https://hardware-help.techidaily.com/newly-released-info-on-high-performance-60n-watt-pcie-gen-5-cord-for-gpus-inside-look/"><u>Newly Released Info on High-Performance 60N Watt PCIe Gen 5 Cord for GPUs – Inside Look</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-technological-reviews-your-ultimate-source-for-hardware-expertise/"><u>Tom’s Technological Reviews: Your Ultimate Source for Hardware Expertise</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unboxing-and-testing-the-msi-power-supply-unit-psu-model-mpg-a10-expert-analysis-and-review/"><u>Unboxing & Testing the MSI Power Supply Unit (PSU) Model MPG A10# - Expert Analysis and Review</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleashing-the-potential-galaxs-latest-dual-16-pin-1300-watt-power-unit-for-gaming-rigs/"><u>Unleashing the Potential: Galax's Latest Dual 16-Pin 1300 Watt Power Unit for Gaming Rigs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/up-to-1300-watt-performance-exploring-cooler-masters-high-capacity-v-series-and-its-x-silent-fanless-psus/"><u>Up to 1300-Watt Performance: Exploring Cooler Master's High Capacity V Series and Its X Silent Fanless PSUs</u></a></li>
</ul></div>

