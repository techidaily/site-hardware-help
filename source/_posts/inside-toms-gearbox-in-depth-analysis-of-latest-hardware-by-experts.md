---
title: "Inside Tom's Gearbox: In-Depth Analysis of Latest Hardware by Experts"
date: 2024-08-19T12:18:36.604Z
updated: 2024-08-20T12:18:36.604Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/e274a732c7d0d3f61527d48aecc65a65fbbf84ca45a89dafe19b065f7716c31c.jpg
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-flavorful-frames-principles-of-food-filmmaking/"><u>[New] 2024 Approved  Flavorful Frames  Principles of Food Filmmaking</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-screen-saver-games-the-top-9-independent-titles-for-android-no-wi-fi/"><u>[New] 2024 Approved  Screen-Saver Games  The Top 9 Independent Titles for Android (No Wi-Fi)</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-best-live-sound-experience-service-for-2024/"><u>[New] Best Live Sound Experience Service for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-capturing-your-workspace-a-step-by-step-screenrec-guide/"><u>[New] Capturing Your Workspace  A Step-by-Step ScreenRec Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-crafting-captivating-tiktoks-mastering-the-use-of-pre-designed-templates-for-2024/"><u>[New] Crafting Captivating TikToks  Mastering the Use of Pre-Designed Templates for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-innovative-ideas-to-make-money-from-your-snapchat-community/"><u>[New] In 2024, Innovative Ideas to Make Money From Your Snapchat Community</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elite-women-gaming-leaders-top-10-on-yt/"><u>[Updated] 2024 Approved  Elite Women Gaming Leaders  Top 10 On YT</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-accelerated-image-viewer-in-windows-environment/"><u>[Updated] Accelerated Image Viewer in Windows Environment</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-apowersoft-screen-recorder-2023-review-for-high-performance-pcs-for-2024/"><u>[Updated] Apowersoft Screen Recorder 2023 Review for High-Performance PCs for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-detailed-methods-for-seamless-wirecast-livestreams-on-youtube/"><u>[Updated] Detailed Methods for Seamless WireCast Livestreams on YouTube</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-affordable-gear-for-aspiring-content-creators/"><u>[Updated] In 2024, Affordable Gear for Aspiring Content Creators</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-streamline-your-multi-tasking-pip-settings-in-safari/"><u>[Updated] Streamline Your Multi-Tasking  PIP Settings in Safari</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlocking-swiftness-in-fb-video-transfers-with-top-tools-and-extensions/"><u>[Updated] Unlocking Swiftness in FB Video Transfers with Top Tools and Extensions</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-3-techniques-to-retrieve-and-save-youtubes-iconic-images/"><u>2024 Approved  3 Techniques to Retrieve & Save YouTube's Iconic Images</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-gimbal-guide-to-pro-video-shooting-with-dslrs-and-mirrorless/"><u>2024 Approved  Gimbal Guide to Pro Video Shooting with DSLRs & Mirrorless</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-playful-escape-the-ultimate-relief-list/"><u>2024 Approved  Playful Escape  The Ultimate Relief List</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-superior-real-time-media-streamers/"><u>2024 Approved  Superior Real-Time Media Streamers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-tecno-phantom-v-fold-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/a-closer-look-at-the-vivid-high-speed-gameplay-on-the-viewsonic-xg272-2k-oled-monitor-in-depth-review/"><u>A Closer Look at the Vivid, High-Speed Gameplay on the ViewSonic XG272-2K OLED Monitor - In Depth Review</u></a></li>
<li><a href="https://hardware-help.techidaily.com/a-decision-must-cause-harm-to-someone-this-element-acknowledges-that-in-many-moral-dilemmas-any-choice-made-will-negatively-impact-at-least-one-party-involv263/"><u>A Decision Must Cause Harm to Someone: This Element Acknowledges that in Many Moral Dilemmas, Any Choice Made Will Negatively Impact at Least One Party Involved. It Is Often Impossible to Find a Solution Where No Harm Is Done</u></a></li>
<li><a href="https://hardware-help.techidaily.com/acer-predator-xb261hd-monitor-driver-downloads-fast-and-simple-instructions/"><u>Acer Predator XB2^61HD Monitor Driver Downloads: Fast and Simple Instructions</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://app-tips.techidaily.com/comprehensive-guide-understanding-icloud-backup-essentials/"><u>Comprehensive Guide: Understanding iCloud Backup Essentials</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-m-audio-fast-track-drivers-supports-windows-11-7-8-and-81/"><u>Download and Install M-Audio Fast Track Drivers: Supports Windows 11, 7, 8 & 8.1</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-radeon-rx-470-drivers-simplified-steps/"><u>Download and Update Radeon RX 470 Drivers - Simplified Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-epson-ds-530-printer-driver-compatible-with-windows-11-64-bit-systems/"><u>Download Epson DS-530 Printer Driver: Compatible with Windows 11 64-Bit Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-new-nvidia-geforce-rtx-3080-ti-drivers-compatible-with-windows-1187/"><u>Download New NVIDIA GeForce RTX 3080 Ti Drivers Compatible with Windows 11/8/7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-newest-intel-iris-plus-graphics-drivers-v396546-for-windows-10-and-11/"><u>Download the Newest Intel Iris Plus Graphics Drivers (v39.6546) for Windows 10 and 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easily-download-and-install-the-latest-driver-for-brother-l2300d-the-ultimate-guide/"><u>Easily Download & Install the Latest Driver for Brother L2300D - The Ultimate Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-honor-90-lite-device-sim-by-drfone-android/"><u>Easily Unlock Your Honor 90 Lite Device SIM</u></a></li>
<li><a href="https://fox-helps.techidaily.com/exploring-gopros-peak-adapters-the-ultimate-6-selection-guide-for-2024/"><u>Exploring GoPro's Peak Adapters  The Ultimate 6 Selection Guide for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-install-high-quality-audio-drivers-for-windows-computers/"><u>Find & Install High-Quality Audio Drivers for Windows Computers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/gambling/"><u>Gambling</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722977124757-get-the-latest-asus-laptop-drivers-for-optimal-performance-heres-where/"><u>Get the Latest ASUS Laptop Drivers for Optimal Performance – Here's Where</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-camera-driver-setup-tools-for-windows-users-supports-win-111087/"><u>Get the Latest Camera Driver Setup Tools for Windows Users - Supports Win 11/10/8/7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-most-out-of-your-racers-edge-with-logitech-g29-drivers-free-downloads-for-windows-xp-vista-and-7/"><u>Get the Most Out of Your Racer's Edge with Logitech G29 Drivers - Free Downloads for Windows XP, Vista & 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722979124601-get-the-new-canon-pixma-ts322-driver-downloads-here/"><u>Get the New Canon PIXMA TS322 Driver Downloads Here</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-amd-radeon-rx-amoledo-470-graphics-card-driver-software-for-your-pc-quick-and-easy/"><u>Get the Newest AMD Radeon RX Amoledo 470 Graphics Card Driver Software for Your PC, Quick & Easy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-game-ready-nvidia-drivers-for-your-windows-gaming-system/"><u>Get the Newest Game-Ready NVIDIA Drivers for Your Windows Gaming System</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-geforce-rtx-ebytes-3080-driver-for-your-windows-system-supporting-win1187/"><u>Get the Newest GeForce RTX Ebytes 3080 Driver for Your Windows System (Supporting Win11/8/7)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-updated-and-fixed-wi-fi-card-drivers-here/"><u>Get Your Updated & Fixed Wi-Fi Card Drivers Here!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-windows-device-ready-with-new-hp-officejet-pro-4650-printing-drivers-free-downloads/"><u>Get Your Windows Device Ready with New HP Officejet Pro 4650 Printing Drivers - Free Downloads</u></a></li>
<li><a href="https://hardware-help.techidaily.com/grab-your-free-qualcomm-atheros-ar938x-drivers-with-ease-step-by-step-guide-included/"><u>Grab Your Free Qualcomm Atheros AR938X Drivers with Ease – Step by Step Guide Included</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hassle-free-guide-upgrade-to-intel-dual-band-ac-7260-wifi-drivers-today/"><u>Hassle-Free Guide: Upgrade to Intel Dual Band AC 7260 WiFi Drivers Today</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-fix-and-install-broadcom-gigabit-ethernet-drivers-on-your-windows-10-machine-successfully/"><u>How to Fix and Install Broadcom Gigabit Ethernet Drivers on Your Windows 10 Machine Successfully</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-and-install-updated-drivers-for-your-hp-officejet-pro-e8610-on-windows-systems/"><u>How to Get and Install Updated Drivers for Your HP Officejet Pro E8610 on Windows Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-and-set-up-drivers-for-an-xbox-360-gaming-controller/"><u>How to Get and Set Up Drivers for an Xbox 360 Gaming Controller</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-successfully-download-and-implement-new-drivers-for-your-canon-mg3000/"><u>How To Successfully Download And Implement New Drivers For Your Canon MG3000</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-network-locked-tecno-spark-10c-phone-by-drfone-android/"><u>How to Unlock a Network Locked Tecno Spark 10C Phone?</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-about-tecno-camon-30-pro-5g-frp-bypass-by-drfone-android/"><u>In 2024, About Tecno Camon 30 Pro 5G FRP Bypass</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-recommended-best-applications-for-mirroring-your-poco-c65-screen-drfone-by-drfone-android/"><u>In 2024, Recommended Best Applications for Mirroring Your Poco C65 Screen | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-hp-officejet-3830-printer-drivers-on-your-pc-with-windows-os/"><u>Install HP OfficeJet 3830 Printer Drivers on Your PC with Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/instant-driver-installation-for-your-acer-predator-xb271h-display/"><u>Instant Driver Installation for Your Acer Predator XB271H Display</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/learn-the-process-of-capturing-your-watched-youtube-content-without-spending/"><u>Learn the Process of Capturing Your Watched YouTube Content Without Spending</u></a></li>
<li><a href="https://hardware-help.techidaily.com/obtain-your-brother-mfc-nw-cw-drivers-secure-download-now/"><u>Obtain Your Brother MFC-Nw CW Drivers - Secure Download Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/obtain-your-qualcomm-atheros-ar93-8x-drivers-without-cost-quick-and-safe-download/"><u>Obtain Your Qualcomm Atheros AR93 8X Drivers Without Cost – Quick & Safe Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-get-started-with-your-x230-lenovo-essential-drivers-downloaded-in-minutes/"><u>Quick Get Started with Your X230 Lenovo - Essential Drivers Downloaded in Minutes</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-guide-linksys-ae2500-device-drivers-free-downloads-inside/"><u>Quick Guide: Linksys AE2500 Device Drivers – Free Downloads Inside</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722963389521-rapid-samsung-m2n070fw-driver-setup-download-instantly-now/"><u>Rapid Samsung M2n070Fw Driver Setup - Download Instantly Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/reliable-sades-headset-driver-download-for-windows-completely-secure/"><u>Reliable Sades Headset Driver Download for Windows - Completely Secure</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-tips-for-acquiring-and-setting-up-the-epson-xp-830-printer-drivers/"><u>Troubleshooting Tips for Acquiring and Setting Up the Epson XP-830 Printer Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-logitech-g203-driver-setup-free-download-for-windows-users-on-latest-versions/"><u>Ultimate Logitech G203 Driver Setup - Free Download for Windows Users on Latest Versions</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-potential-top-tactics-for-medical-ads-on-social-networks/"><u>Unlocking Potential  Top Tactics for Medical Ads on Social Networks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722978244622-update-your-amd-rx-480-gpu-drivers-with-these-simple-steps/"><u>Update Your AMD RX 480 GPU Drivers with These Simple Steps!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/usb-audio-driver-for-behringer-interfaces-secure-your-free-downloads-here/"><u>USB Audio Driver for Behringer Interfaces - Secure Your Free Downloads Here</u></a></li>
<li><a href="https://hardware-help.techidaily.com/windows-11-enhancement-instructions-for-inbuilt-printerscanner-driver-setup/"><u>Windows 11 Enhancement: Instructions for Inbuilt Printer/Scanner Driver Setup</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->