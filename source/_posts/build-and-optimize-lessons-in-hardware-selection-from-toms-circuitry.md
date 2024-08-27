---
title: "Build and Optimize: Lessons in Hardware Selection From Tom's Circuitry"
date: 2024-08-26T08:05:56.013Z
updated: 2024-08-27T08:05:56.013Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/170a02146718886a24f76eaa0c0aba6ab58e23eceef32078422970e554d48bd8.jpg
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

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-decoding-youtubes-operations-following-uploads/"><u>[New] 2024 Approved  Decoding YouTube’s Operations Following Uploads</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-mastering-igtv-thumbnail-creation-and-editing/"><u>[New] 2024 Approved  Mastering IGTV Thumbnail Creation & Editing</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-the-components-that-lift-you-in-youtube-viewership/"><u>[New] 2024 Approved  The Components That Lift You in YouTube Viewership</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-ultimate-stream-software-showdown-obs-vs-shadowplay/"><u>[New] 2024 Approved  The Ultimate Stream Software Showdown  OBS vs ShadowPlay</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-no-more-ads-convert-fb-videos-to-1080p720p-mp4-online-for-free/"><u>[New] In 2024, No More Ads? Convert FB Videos to 1080P/720p MP4 Online for Free</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-in-2024-top-4-strategies-for-success-in-instagram-loop-creation/"><u>[New] In 2024, Top 4 Strategies for Success in Instagram Loop Creation</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-social-media-live-showdown-facebook-vs-youtube-and-twitter-periscope/"><u>[Updated] 2024 Approved  Social Media Live Showdown  Facebook Vs. YouTube & Twitter Periscope</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-the-must-know-aspect-ratio-for-tweeting-videos/"><u>[Updated] 2024 Approved  The Must-Know Aspect Ratio for Tweeting Videos</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-a-beginners-journey-into-gameplay-capturing-with-obs/"><u>[Updated] A Beginner's Journey Into Gameplay Capturing with OBS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-guide-to-eliminate-insta-suggest-feature/"><u>[Updated] In 2024, Guide to Eliminate Insta Suggest Feature</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-leading-5-internet-screenshot-kits/"><u>[Updated] In 2024, Leading 5 Internet Screenshot Kits</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-the-insider-look-at-ios-video-recording-tools/"><u>[Updated] In 2024, The Insider Look at IO's Video Recording Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/amd-gears-up-to-release-compatible-800-series-chipsets-tailored-for-ryzen-cpus-numbered-system-echoes-intels-approach/"><u>AMD Gears Up to Release Compatible 800 Series Chipsets Tailored For Ryzen CPUs - Numbered System Echoes Intel's Approach</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-nokia-xr21-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Nokia XR21? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/asrock-launches-latest-lineup-of-arrow-lake-supported-mini-itx-and-atx-boards-featuring-the-revamped-taichi-model-with-camm2-ram/"><u>ASROCK Launches Latest Lineup of Arrow Lake Supported Mini-ITX & ATX Boards Featuring the Revamped Taichi Model With CAMM2 RAM</u></a></li>
<li><a href="https://hardware-help.techidaily.com/asrocks-latest-masterpiece-the-z89-taichi-aqua-motherboard-10x-usb-type-c-and-dual-thunderbolt-functionality-explored/"><u>ASRock's Latest Masterpiece: The Z89# Taichi Aqua Motherboard - 10X USB Type-C & Dual Thunderbolt Functionality Explored</u></a></li>
<li><a href="https://hardware-help.techidaily.com/budget-conscious-gaming-with-asrocks-b760m-pro-rs-robust-m2-capabilities-included/"><u>Budget-Conscious Gaming with ASRock's B760M Pro RS - Robust M.2 Capabilities Included</u></a></li>
<li><a href="https://games-able.techidaily.com/discovering-mac-friendly-switch-titles/"><u>Discovering Mac-Friendly Switch Titles</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dive-into-hardware-mastery-with-toms-expert-reviews/"><u>Dive Into Hardware Mastery with Tom's Expert Reviews</u></a></li>
<li><a href="https://hardware-help.techidaily.com/diy-mastermind-user-friendly-motherboards-to-streamline-your-custom-pc-craftsmanship/"><u>DIY MasterMind: User-Friendly Motherboards to Streamline Your Custom PC Craftsmanship</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-gear-analysis-by-toms-technology-hub-unveiling-the-best-in-pc-components/"><u>Expert Gear Analysis by Tom's Technology Hub - Unveiling the Best in PC Components</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-picks-for-top-performing-motherboards-in-2024-detailed-analysis-based-on-socket-and-chipset-options/"><u>Expert Picks for Top-Performing Motherboards in 202^4 - Detailed Analysis Based on Socket & Chipset Options</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-computer-gear-with-toms-hardware-insights/"><u>Exploring Computer Gear with Tom's Hardware Insights</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-cutting-edge-technology-with-toms-hardware-guides/"><u>Exploring Cutting-Edge Technology with Tom's Hardware Guides</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-technology-with-tom-comprehensive-hardware-evaluations/"><u>Exploring Technology with Tom: Comprehensive Hardware Evaluations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-future-of-pc-building-with-asrocks-new-ryzen-9000-chipset-boards/"><u>Exploring the Future of PC Building with ASRock's New Ryzen 9000 Chipset Boards</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-latest-in-computing-gear-with-tom-a-comprehensive-guide/"><u>Exploring the Latest in Computing Gear with Tom - A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-to-optimizing-your-pc-with-new-ati-graphics-card-drivers-on-windows/"><u>Guide to Optimizing Your PC with New ATI Graphics Card Drivers on Windows</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-or-downgrade-apple-iphone-14-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade Apple iPhone 14 Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-zte-blade-a73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-apple-watch-or-apple-iphone-12-from-icloud-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Apple Watch Or Apple iPhone 12 from iCloud</u></a></li>
<li><a href="https://hardware-help.techidaily.com/in-depth-gigabyte-b65t-aorus-elite-ax-ice-mobo-review-top-notch-features-justify-the-hefty-price-tag-and-abundant-usb-ports/"><u>In-Depth Gigabyte B65t Aorus Elite AX Ice Mobo Review: Top-Notch Features Justify the Hefty Price Tag & Abundant USB Ports</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-the-circuitry-unveiling-tech-secrets-at-toms-gadget-corner/"><u>Inside the Circuitry: Unveiling Tech Secrets at Tom's Gadget Corner</u></a></li>
<li><a href="https://hardware-help.techidaily.com/introducing-sapphires-budget-friendly-am5-mini-itx-motherboard-enhanced-connectivity-via-pcie-gen-4-at-lower-prices-in-china/"><u>Introducing Sapphire's Budget-Friendly AM5 Mini ITX Motherboard: Enhanced Connectivity via PCIe Gen 4 at Lower Prices in China</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-digital-world-insights-from-toms-hardware-experts/"><u>Mastering the Digital World: Insights From Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/motherboard-sales-surge-to-39-million-units-as-shipments-bounce-back-to-pre-pandemic-figures/"><u>Motherboard Sales Surge to 39 Million Units as Shipments Bounce Back to Pre-Pandemic Figures</u></a></li>
<li><a href="https://hardware-help.techidaily.com/new-asus-firmware-release-tackles-instability-on-raptor-lake-and-refresh-intel-processors-enhancing-gaming-performance/"><u>New ASUS Firmware Release Tackles Instability on Raptor Lake and Refresh Intel Processors, Enhancing Gaming Performance</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-best-liked-platforms-to-access-compilation-of-guitar-chord-diagrams-and-visual-themes-for-2024/"><u>New Best-Liked Platforms to Access Compilation of Guitar Chord Diagrams & Visual Themes for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/next-level-gaming-rigs-spotted-early-certified-msi-z890-and-b870-motherboards-tailored-for-the-latest-intel-arrow-lake-s-processors-unveiled-in-a-leak-compu84/"><u>Next-Level Gaming Rigs Spotted Early: Certified MSI Z890 & B870 Motherboards Tailored for the Latest Intel Arrow Lake-S Processors Unveiled in a Leak - Computex Anticipation Builds</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-adjustment-of-youtube-vids-for-mac-screen/"><u>Rapid Adjustment of YouTube Vids for Mac Screen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/storytellers-sanctum-summit-selections/"><u>Storytellers Sanctum – Summit Selections</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-meizu-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Meizu Phone Hassle-Free</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-blueprint-to-dominate-with-your-spotify-ad-campaign/"><u>The Blueprint to Dominate With Your Spotify Ad Campaign</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-insights-your-guide-to-the-latest-hardware/"><u>Tom's Tech Insights - Your Guide to the Latest Hardware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-review-in-depth-insights-on-computer-components/"><u>Tom's Tech Review: In-Depth Insights on Computer Components</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-reviews-in-depth-insights-on-the-latest-hardware/"><u>Tom's Tech Reviews: In-Depth Insights on the Latest Hardware</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/transforming-language-education-why-mondly-emerges-as-a-champion/"><u>Transforming Language Education – Why Mondly Emerges as a Champion</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steps-for-the-black-screen-issue-in-rainbow-six-siege-pc-guide/"><u>Troubleshooting Steps for the Black Screen Issue in Rainbow Six Siege - PC Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-techniques-fixing-issues-with-ieframedll-errors-swiftly/"><u>Troubleshooting Techniques: Fixing Issues with Ieframe.Dll Errors Swiftly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guides-and-tutorials-by-toms-hardware-experts/"><u>Ultimate Guides and Tutorials by Tom's Hardware Experts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultra-strong-motherboards-from-gigabyte-accommodating-128-pound-graphics-cards-with-reinforced-slots-yet-cracking-continues-to-plague-gpus/"><u>Ultra-Strong Motherboards From Gigabyte: Accommodating 128-Pound Graphics Cards with Reinforced Slots – Yet, Cracking Continues to Plague GPUs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unleash-next-gen-computing-power-msis-groundbreaking-z790-project-zero-motherboards-the-first-to-support-enhanced-camm2-memory-standard-in-pcs/"><u>Unleash Next-Gen Computing Power: MSI's Groundbreaking Z790 Project Zero Motherboards, The First to Support Enhanced CAMM2 Memory Standard in PCs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/unveiling-the-latest-in-pc-gear-insights-from-toms-hardware-experts/"><u>Unveiling the Latest in PC Gear - Insights From Tom's Hardware Experts</u></a></li>
<li><a href="https://driver-download.techidaily.com/update-to-the-newest-hp-officejet-pro-8740-driver-for-windows-11-10-and-8-easy-installation/"><u>Update to the Newest HP OfficeJet Pro 8740 Driver for Windows 11, 10 & 8 – Easy Installation</u></a></li>
<li><a href="https://hardware-help.techidaily.com/world-record-breaking-oc-achievements-on-the-latest-asrock-z790i-lightning-wifi-mobo-by-splave/"><u>World Record-Breaking OC Achievements on the Latest ASRock Z790I Lightning WiFi Mobo by Splave</u></a></li>
<li><a href="https://hardware-help.techidaily.com/your-ultimate-resource-for-cutting-edge-pc-components-at-toms-hardware/"><u>Your Ultimate Resource for Cutting-Edge PC Components at Tom's Hardware</u></a></li>
</ul></div>
