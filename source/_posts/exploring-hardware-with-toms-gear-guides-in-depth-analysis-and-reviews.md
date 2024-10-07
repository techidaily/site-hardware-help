---
title: Exploring Hardware with Tom's Gear Guides - In-Depth Analysis and Reviews
date: 2024-10-03T21:20:35.336Z
updated: 2024-10-07T21:10:58.425Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/Jzk6akrLgxNy3ui2DHcLRi-320-80.jpg
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-blue.techidaily.com/new-in-2024-expanding-screen-coverage-of-youtube-videos/"><u>[New] In 2024, Expanding Screen Coverage of YouTube Videos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-inshot-unpacked-editors-edition-detailed-review/"><u>[New] InShot Unpacked Editor's Edition Detailed Review</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-precision-sculpting-perfect-circles-spheres-in-minecraft-world/"><u>[Updated] In 2024, Precision Sculpting Perfect Circles, Spheres in Minecraft World</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-screenflow-unleashed-the-ultimate-macos-experience/"><u>2024 Approved ScreenFlow Unleashed The Ultimate MacOS Experience</u></a></li>
<li><a href="https://fox-that.techidaily.com/breaking-down-barriers-connect-your-iphone-to-a-vpn-in-7-steps/"><u>Breaking Down Barriers: Connect Your iPhone to a VPN in 7 Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722960957445-download-and-enhance-your-dell-screen-with-effortless-driver-updates/"><u>Download and Enhance Your Dell Screen with Effortless Driver Updates!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/free-electronic-signatures-for-word-2021-by-ldigisigner-sign-a-word-sign-a-word/"><u>Free electronic signatures for Word 2021</u></a></li>
<li><a href="https://hardware-help.techidaily.com/geforce-rtx-3080-drivers-installation-guide-for-windows-10-8-and-7-users/"><u>GeForce RTX 3080 Drivers: Installation Guide for Windows 10, 8 & 7 Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-fast-and-secure-epson-scanner-drivers-downloads-at-your-fingertps/"><u>Get Fast and Secure Epson Scanner Drivers: Downloads at Your Fingertps</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/gpt-3s-academic-impact-revolutionizing-or-undermining-students-works/"><u>GPT-3's Academic Impact: Revolutionizing or Undermining Students' Works?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/innovative-discussion-themes-for-vloggers-for-2024/"><u>Innovative Discussion Themes for Vloggers for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-13th-gen-processors-face-significant-return-challenges-retailers-report-a-surge-in-rmas-over-amd/"><u>Intel 13Th Gen Processors Face Significant Return Challenges: Retailers Report a Surge in RMAs Over AMD</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcome-iphone-icloud-syncing-error-9-proven-strategies-for-a-successful-backup/"><u>Overcome iPhone iCloud Syncing Error: 9 Proven Strategies for a Successful Backup</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-and-easy-asus-z370-e-driver-downloads-enhanced-performance-and-stability/"><u>Quick & Easy ASUS Z370-E Driver Downloads: Enhanced Performance and Stability</u></a></li>
<li><a href="https://hardware-help.techidaily.com/resolved-fixing-dts-audio-not-available-on-your-selected-sound-hardware/"><u>Resolved: Fixing 'DTS Audio Not Available' On Your Selected Sound Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-solution-for-when-your-usb-sticks-are-ignored-by-windows-10/"><u>Step-by-Step Solution for When Your USB Sticks Are Ignored by Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-review-in-depth-hardware-analysis/"><u>Tom's Tech Review: In-Depth Hardware Analysis</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-microphone-issues-live-recording-fixes-in-obs-w11/"><u>Troubleshooting Microphone Issues: Live Recording Fixes in OBS, W11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722967167762-ultimate-compatibility-with-your-devices-update-tp-link-tl-ub400-bluetooth-adapter-driver-here/"><u>Ultimate Compatibility with Your Devices: Update TP-Link TL-UB400 Bluetooth Adapter Driver Here!</u></a></li>
</ul></div>

