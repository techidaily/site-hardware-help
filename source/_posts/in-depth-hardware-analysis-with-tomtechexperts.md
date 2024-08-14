---
title: In-Depth Hardware Analysis with TomTechExperts
date: 2024-08-13T12:49:14.512Z
updated: 2024-08-14T12:49:14.512Z
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
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
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
<li><a href="https://hardware-help.techidaily.com/latest-and-fast-new-version-of-vga-drivers-free-download-for-optimal-performance/"><u>[Latest & Fast] New Version of VGA Drivers - Free Download for Optimal Performance</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-tiktoks-toptwitter-tweets-amassing-views/"><u>[New] 2024 Approved  TikTok's #TopTwitter Tweets Amassing Views</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-a-beginners-pathway-to-innovative-snapchat-expressions/"><u>[New] A Beginner's Pathway to Innovative Snapchat Expressions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-captivate-and-conquer-with-customized-content-shorts-for-2024/"><u>[New] Captivate and Conquer with Customized Content Shorts for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-mastery-over-picture-in-picture-for-improved-productivity-for-2024/"><u>[New] Mastery over Picture In Picture for Improved Productivity for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-simplify-your-social-media-uploading-multiple-photos-and-vids-on-ig-for-2024/"><u>[New] Simplify Your Social Media  Uploading Multiple Photos and Vids on IG for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-step-by-step-guide-to-professional-podcast-scriptwriting-techniques/"><u>[New] Step-by-Step Guide to Professional Podcast Scriptwriting Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-art-of-plating-on-camera-food-video-production-guide/"><u>[New] The Art of Plating on Camera  Food Video Production Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-extract-and-save-youtube-gallery-files/"><u>[Updated] Extract and Save YouTube Gallery Files</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-confirm-your-youtube-account-securely-for-2024/"><u>[Updated] How to Confirm Your YouTube Account Securely for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-top-10-instagram-insights-tools-detailed-data-analysis-made-simple/"><u>[Updated] In 2024, Top 10 Instagram Insights Tools  Detailed Data Analysis Made Simple</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-top-pick-prodigious-insta-hlv-pages-creators-for-2024/"><u>[Updated] Top Pick  Prodigious Insta HLV Pages Creators for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-breaking-barriers-masterful-techniques-for-photosvideos-in-win11/"><u>2024 Approved  Breaking Barriers  Masterful Techniques for Photos/Videos in Win11</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-download-facebook-audio-mp3s/"><u>2024 Approved  Download Facebook Audio MP3s</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unveiling-ms-edges-picture-in-picture-magic/"><u>2024 Approved  Unveiling MS Edge's Picture-in-Picture Magic</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/age-defying-brain-the-power-of-multilingualism-after-fifty/"><u>Age-Defying Brain: The Power of Multilingualism After Fifty</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/android-audio-goldies-for-2024/"><u>Android Audio Goldies for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/bluetooth-50-asus-usb-bt500-drivers-compatible-with-windows-11108/"><u>Bluetooth 5.0 Asus USB-BT500 Drivers - Compatible with Windows 11/10/8</u></a></li>
<li><a href="https://win11.techidaily.com/bringing-forlorn-windows-apps-back-into-use/"><u>Bringing Forlorn Windows Apps Back Into Use</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-path-restarting-issues-in-windows-photoshop/"><u>Clearing the Path: Restarting Issues in Windows PhotoShop</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-amd-radeon-graphics-driver-for-windows-8-complimentary-version/"><u>Download AMD Radeon Graphics Driver for Windows 8: Complimentary Version</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-to-finding-and-upgrading-logitech-webcam-software/"><u>Easy Guide to Finding and Upgrading Logitech Webcam Software</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-guide-to-installing-new-dell-network-card-software-on-your-windows-7-machine/"><u>Easy Guide to Installing New Dell Network Card Software on Your Windows 7 Machine</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-steps-to-download-and-install-official-corsair-mouse-driver/"><u>Easy Steps to Download and Install Official Corsair Mouse Driver</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-of-hp-envy-56e-drivers-get-them-now/"><u>Effortless Installation of HP Envy 56E Drivers – Get Them Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722970605441-effortless-installation-get-the-latest-samsung-nvme-ssd-drivers-right-now/"><u>Effortless Installation: Get the Latest Samsung NVMe SSD Drivers Right Now!</u></a></li>
<li><a href="https://win-forum.techidaily.com/engage-your-audience-on-major-sites-like-facebook-twitter-instagram-and-youtube/"><u>Engage Your Audience on Major Sites Like Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-organization-synergizing-to-do-and-ifttt/"><u>Enhance Organization: Synergizing To-Do & IFTTT</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-seamless-compatibility-download-logitech-g920-drivers-now-supports-windows-11-10-8-and-windows-7-platform/"><u>Ensure Seamless Compatibility: Download Logitech G920 Drivers Now - Supports Windows 11, 10, 8 and Windows 7 Platform</u></a></li>
<li><a href="https://hardware-help.techidaily.com/epson-perfection-v500-driver-download-get-your-printer-up-and-running/"><u>Epson Perfection V500 Driver Download: Get Your Printer Up & Running</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-advice-for-acquiring-and-keeping-your-epson-et-3760-driver-updated-on-windows-machines/"><u>Expert Advice for Acquiring and Keeping Your Epson ET-3760 Driver Updated on Windows Machines</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/facebooks-best-eight-free-link-collector-tools/"><u>Facebook's Best  Eight FREE Link Collector Tools</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722973394495-flexural-bending-failure-occurs-when-bending-moments-exceed-material-capacity-leading-to-cracking-and-deformation-of-beams-and-columns/"><u>Flexural (Bending) Failure Occurs when Bending Moments Exceed Material Capacity, Leading to Cracking and Deformation of Beams and Columns</u></a></li>
<li><a href="https://facebook.techidaily.com/friends-across-platforms-embodying-your-social-media-self-on-whatsapp/"><u>Friends Across Platforms: Embodying Your Social Media Self on WhatsApp</u></a></li>
<li><a href="https://driver-install.techidaily.com/gaomon-s620-driver-guide-and-installation-tips/"><u>Gaomon S620 Driver Guide & Installation Tips</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722978324816-get-the-newest-intel-wi-fi-6-ax200-drivers-compatible-with-windows-11-and-10-free-update-now/"><u>Get the Newest Intel Wi-Fi 6 AX200 Drivers Compatible with Windows 11 & 10 - Free Update Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-epson-wf-ds30-printer-drivers-installed-for-windows-1011-8-and-7-users/"><u>Get Your Epson WF-DS30 Printer Drivers Installed for Windows 10/11, 8 & 7 Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-lenovo-x1-carbon-drivers-quick-and-easy-download-guide-for-win-10-and-7-users/"><u>Get Your Lenovo X1 Carbon Drivers: Quick and Easy Download Guide for Win 10 & 7 Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-msi-speakers-and-headphones-up-to-date-with-new-drivers-windows/"><u>Get Your MSI Speakers & Headphones Up-to-Date with New Drivers [Windows]</u></a></li>
<li><a href="https://hardware-help.techidaily.com/guide-enhancing-your-windows-11-experience-with-the-newest-intel-iris-gpu-drivers/"><u>Guide: Enhancing Your Windows 11 Experience with the Newest Intel Iris GPU Drivers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-poco-c65-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Poco C65 FRP Bypass Instantly</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fixing-foneazy-mockgo-not-working-on-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Fixing Foneazy MockGo Not Working On Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-motorola-edge-40-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-12-pro-to-mac-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 12 Pro to Mac? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-oppo-a78-5g-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Oppo A78 5G to iPod | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-of-the-samsung-galaxy-tab-s5e-your-guide-to-a-high-end-android-experience/"><u>In-Depth Analysis of the Samsung Galaxy Tab S5e: Your Guide to a High-End Android Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-the-latest-all-in-one-printer-drivers-for-hp-deskjet-3755-supported-on-windows-vistaxp/"><u>Install the Latest All-in-One Printer Drivers for HP DeskJet 3755 – Supported on Windows Vista/XP</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installing-updated-geforce-rtx-2070-graphics-card-drivers-on-windows-systems/"><u>Installing Updated GeForce RTX 2070 Graphics Card Drivers on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-driver-utility-how-to-find-and-download-the-latest-version/"><u>Intel Driver Utility: How To Find And Download The Latest Version</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-drivers-and-firmware-updates-for-logitech-mk710-mouse/"><u>Latest Drivers and Firmware Updates for Logitech MK710 Mouse</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-logitech-rx-250-driver-software-for-windows-operating-systems-download-now/"><u>Latest Logitech RX-250 Driver Software for Windows Operating Systems - Download Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/m-audio-fast-track-driver-supported-on-multiple-os-platforms-windows-11-7-8-and-81-download-options/"><u>M-Audio Fast Track Driver Supported on Multiple OS Platforms: Windows 11, 7, 8, and 8.1 Download Options.</u></a></li>
<li><a href="https://hardware-help.techidaily.com/marker-assisted-selection-can-expedite-the-identification-of-desirable-traits-within-a-genetically-diverse-population/"><u>Marker-Assisted Selection Can Expedite the Identification of Desirable Traits Within a Genetically Diverse Population</u></a></li>
<li><a href="https://hardware-help.techidaily.com/masterful-fixes-for-your-windows-11-bluetooth-connection-issues-a-step-by-step-solution/"><u>Masterful Fixes for Your Windows 11 Bluetooth Connection Issues: A Step-by-Step Solution</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ring-the-art-of-vlogging-your-ultimate-journey-begins-here/"><u>Mastering The Art of Vlogging  Your Ultimate Journey Begins Here</u></a></li>
<li><a href="https://hardware-help.techidaily.com/official-downloads-installing-the-logitech-g29-driving-force-for-microsoft-operating-systems-windows-11107/"><u>Official Downloads: Installing the Logitech G29 Driving Force for Microsoft Operating Systems (Windows 11/10/7)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/pros-and-cons-should-you-get-the-chatgpt-mobile-app/"><u>Pros and Cons: Should You Get the ChatGPT Mobile App?</u></a></li>
<li><a href="https://games-able.techidaily.com/questful-commuting-smart-tips-for-in-transit-gaming/"><u>Questful Commuting: Smart Tips for In-Transit Gaming</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-guide-microsoft-drivers-downloading-and-updating-on-windows-11-8-and-7/"><u>Quick Guide: Microsoft Drivers Downloading and Updating on Windows 11, 8 & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-start-how-to-find-and-install-the-right-toshiba-printer-drivers-on-windows-systems/"><u>Quick Start: How to Find & Install the Right Toshiba Printer Drivers on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722956790544-resolved-issues-with-the-igfxem-module-now-fixed/"><u>Resolved: Issues with the IgfxEM Module Now Fixed</u></a></li>
<li><a href="https://hardware-help.techidaily.com/resolving-ralink-rt3290-drivers-problems-on-windows-11-8-and-7-a-comprehensive-guide/"><u>Resolving Ralink RT3290 Drivers Problems on Windows 11, 8 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/secure-your-bluetooth-connection-download-broadcom-drivers-for-windows-1187/"><u>Secure Your Bluetooth Connection: Download Broadcom Drivers for Windows (11/8/7)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-solutions-for-addressing-known-graphics-driver-issues/"><u>Step-by-Step Solutions for Addressing Known Graphics Driver Issues</u></a></li>
<li><a href="https://some-skills.techidaily.com/streamline-your-vlc-experience-best-practices-for-macos-for-2024/"><u>Streamline Your VLC Experience  Best Practices for MacOS for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-guide-correcting-issues-in-realtek-rtl8811au-wireless-card-driver/"><u>Troubleshooting Guide: Correcting Issues in Realtek RTL8811AU Wireless Card Driver</u></a></li>
<li><a href="https://extra-information.techidaily.com/tuneful-timelines-music-in-imovie-editing-journey/"><u>Tuneful Timelines  Music in iMovie Editing Journey</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-hp-printer-software-for-windows-11-easy-guide-and-links-to-download/"><u>Update Your HP Printer Software for Windows 11: Easy Guide and Links to Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/updating-to-the-newest-nvidia-1080-drivers-on-windows-10-made-simple/"><u>Updating to the Newest NVIDIA 1080 Drivers on Windows 10 Made Simple</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722969412894-z2-the-best-pc-upgrade-get-your-intel-z270-gaming-pro-carbon-motherboard-now/"><u>Z2 The Best PC Upgrade: Get Your Intel Z270 Gaming Pro Carbon Motherboard Now</u></a></li>
</ul></div>
