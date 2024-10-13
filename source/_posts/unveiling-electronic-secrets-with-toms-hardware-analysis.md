---
title: Unveiling Electronic Secrets with Tom's Hardware Analysis
date: 2024-10-07T18:31:52.661Z
updated: 2024-10-13T12:14:11.236Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/sD8J7DtA734484kPwzyAEE-320-80.jpg
---

## Discovering Top Tech at Tom's Hardware - Your Ultimate Guide

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
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-secure-and-efficient-lecture-recording-with-apple-devices/"><u>[New] Secure & Efficient Lecture Recording with Apple Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-streamline-your-wedding-countdown-the-best-androidios-clock-apps-guide/"><u>[New] Streamline Your Wedding Countdown The Best Android/iOS Clock Apps Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-go-live-in-style-a-detailed-guide-to-youtubes-full-sphere-videos/"><u>[Updated] Go Live in Style A Detailed Guide to YouTube's Full-Sphere Videos</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-verified-vids-the-reality-of-instas-self-validation/"><u>2024 Approved Verified Vids The Reality of Insta’s Self-Validation</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-hp-laserjet-pro-mfp-m127fn-printer-drivers-free-and-easy/"><u>Download HP LaserJet Pro MFP M127FN Printer Drivers - Free and Easy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-updated-gpu-drivers-enhance-your-experience-with-rtx-s-2060-super-on-windows-11/"><u>Download Updated GPU Drivers: Enhance Your Experience with RTX S 2060 Super on Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-acer-pcs-wi-fi-up-and-running-free-driver-downloads-now/"><u>Get Your Acer PC's Wi-Fi Up and Running: FREE Driver Downloads Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/gigabyte-z370p-motherboard-drivers-download-get-the-latest-version-now/"><u>Gigabyte Z370P Motherboard Drivers Download: Get the Latest Version Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-obtain-the-latest-hp-laserjet-pro-m452dn-printer-software/"><u>How to Obtain the Latest HP LaserJet Pro M452dn Printer Software</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-unlock-icloud-activation-lock-and-icloud-account-on-iphone-11-pro-by-drfone-ios/"><u>In 2024, How to Unlock iCloud Activation Lock and iCloud Account On iPhone 11 Pro?</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professional-video-shooting-on-the-go-the-10-leading-smartphone-titans-with-ois/"><u>In 2024, Professional Video Shooting on the Go The 10 Leading Smartphone Titans with OIS</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Lenovo ThinkPhone? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/in-depth-analysis-of-next-gen-technology-at-toms-hardware-haven/"><u>In-Depth Analysis of Next-Gen Technology at Tom's Hardware Haven</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-driver-upgrade-for-epson-wf-7720-to-optimize-performance-on-windows-systems/"><u>Latest Driver Upgrade for Epson WF-7720 to Optimize Performance on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-guide-acquiring-insgnias-best-in-class-drives-for-windows-users/"><u>Quick Guide: Acquiring Insgnia's Best-in-Class Drives for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-restoring-right-click-capability-for-your-mouse-under-windows-11/"><u>Step-by-Step Solution: Restoring Right-Click Capability for Your Mouse Under Windows 11</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-call-logs-from-htc-u23-pro-by-fonelab-android-recover-call-logs/"><u>Undelete lost call logs from HTC U23 Pro</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleashing-performance-how-the-ryzen-9-9950x-eclipses-core-i9-14900k-by-18-while-maintaining-a-slender-power-footprint/"><u>Unleashing Performance: How the Ryzen 9 9950X Eclipses Core I9-14900K by 18% While Maintaining a Slender Power Footprint</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-no-budget-no-problem-top-free-wmv-video-editors/"><u>Updated In 2024, No Budget? No Problem! Top Free WMV Video Editors</u></a></li>
</ul></div>

