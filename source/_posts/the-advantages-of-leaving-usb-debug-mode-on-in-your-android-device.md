---
title: The Advantages of Leaving USB Debug Mode On in Your Android Device
date: 2024-09-04T02:10:43.024Z
updated: 2024-09-05T02:10:43.024Z
tags:
  - android
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/android-mascot-holding-a-phone-with-usb-debugging-enabled.jpg
---

## The Advantages of Leaving USB Debug Mode On in Your Android Device

### Key Takeaways

* USB debugging in Android isn't just for developers - it can be used to recover data and control your phone from a computer.
* Remember to keep USB debugging enabled to access files or control your phone even if the screen is broken.
* Be cautious - enabling USB debugging can allow unwanted access to your data, but Android's security can prevent this.

 You may think that Android's USB debugging feature, hidden within the developer options, is only for, well, developers. But it can be very useful for just about anyone and could very well save your back someday. To do that, you'll need to have enabled the feature beforehand.

##  USB Debugging Can Help Recover Data

 On-device [developer options](https://youtube-docs.techidaily.com/approved-decode-your-youtube-preferences-with-these-6-fan-favorite-questionnaires/) exist to help app developers debug (find and fix technical issues) and test apps. Typically, developers code apps in Android Studio on a PC. Enabling USB debugging allows them to send data and commands between their computer and their phone.

 But debugging isn’t all. We can use the same feature to access a phone’s files and control them from our computer. The cool part? It works even if the device display or touch screen is broken. As long as the phone is turned on, you can interact with it. The only requirement is that USB debugging _has_ to be enabled already since you can't do it after the fact on a device with a broken screen.

 If you have it enabled, you can simply plug your phone into a pre-authorized computer via USB cable. Then you just have to install [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) (ADB) tools on the computer, and you get full access to your phone—messages, photos, contacts, essentially everything.

 Leaving USB debugging enabled comes with a serious caveat. With USB debugging on, anyone who gains physical access can read your data, modify things, or install malicious apps. Even the screen lock won’t protect you. Thankfully, Android’s security stops unwanted access like that. You have to grant permission on your phone to each computer to establish a connection manually. That’s where you can pre-authorize a computer for future use.

##  How to Enable USB Debugging

 Enabling USB Debugging is simple enough. Just go to Settings > About Phone > Build Number. Tap “Build Number” seven times to enable Developer Options.

![The step-by-step process of enabling developer options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-8.png) 

 Then open Developer Options > USB Debugging. Enable the toggle and confirm.

![Two red arrows highlighting USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-9.png) 

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098702/14409" target="_top" id="2098702">
  <img src="//a.impactradius-go.com/display-ad/14409-2098702" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098702/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 These settings and menus vary slightly between Android manufacturers. If you can’t find these menus, we have a detailed guide on how to [enable Developer Options and USB Debugging](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

##  How to Recover Data Using ADB

 Once you have enabled “USB Debugging,” we need to set up a recovery point (to use in case your phone malfunctions or breaks).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Everything You Need

 To create a “recovery point,” you need:

* ADB tools
* USB Cable
* Scrcpy

 You can grab [ADB Tools from the official website](https://developer.android.com/tools/releases/platform-tools#downloads) and [Scrcpy from its GitHub](https://github.com/Genymobile/scrcpy) repo. ADB tools let you interact with the phone through the command line. We’ll pull files off the phone using ADB. [Scrcpy is an awesome tool for mirroring](https://win11-tips.techidaily.com/workflow-enhancer-integrating-sticky-notes-into-your-windows-morning-ritual/) and controlling your phone using your computer’s mouse.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Installing ADB

 ADB is officially bundled in "Platform Tools." Extract the Platform Tools archive (that you just downloaded) anywhere on your computer. Open the extracted folder. Hold down shift and right-click anywhere on the blank space. Click “Open PowerShell window here” and wait for the terminal to open.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044586/7443" target="_top" id="2044586">
  <img src="//a.impactradius-go.com/display-ad/7443-2044586" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044586/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Connect your phone to the computer using a USB cable (make sure “USB Debugging” is still enabled). A small pop-up should appear on your phone as soon as you do that. Select “Always Allow From This Computer” and then tap “OK” to allow the connection.

![Allowing USB debugging for a computer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/screenshot_20240801-014110.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094483/7443" target="_top" id="2094483">
  <img src="//a.impactradius-go.com/display-ad/7443-2094483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 It’s crucial that you keep “Always Allow From This Computer” checked. It’ll safelist your computer. So you won’t have to manually grant this permission on your phone if it ever breaks.

 Now back to the PowerShell window we just opened. Type the following command and press Enter:

adb devices

 You’ll get a list of attached devices, along with their identifier strings.

![Using the PowerShell terminal to verify a successful ADB connection.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012651.png) 

 If the “adb devices” is returning a blank result, your computer is likely missing the relevant Android drivers. You can install the official drivers from the device manufacturer’s website, restart the computer, and try again.

###  Installing Scrcpy

 Open the official [Scrcpy repository](https://github.com/Genymobile/scrcpy/releases/tag/v2.5) on GitHub and download the relevant package for your operating system. I downloaded the “win64” zip archive. Extract it anywhere on your computer and open the extracted folder.

![Launching Scrcpy from the extracted folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014359.png) 

 You can double-click “scrcpy.exe” to instantly mirror the Android screen on your computer. You should be able to interact with this mirrored screen using your mouse right away.

![Mirrored Android phone screen using Scrcpy.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-014500.png) 

 I tested Scrcpy on an older phone, and the mouse didn't work on its own. If you're having trouble with the mouse control, click the “open a terminal here” file. Once the command prompt window opens, type in the following command and press Enter.

scrcpy --mouse=uhid

Close 

 A rectangular window should automatically pop up, but it might be blank at first. Simply press the power button on your phone or the right-click button on your mouse to wake it up. Scrcpy will “capture” the cursor, and it’ll stick within the mirrored window. You can release it and use the mouse normally by pressing the Window or Alt key (Command or Option on Mac).

 If the mouse isn’t working in the mirrored window, close the window and try again with this command: scrcpy --mouse=aoa

 Scrcpy will only start streaming the screen after you’ve unlocked the phone. You can unlock it by using the fingerprint scanner. Alternatively, you can wake up the screen by right-clicking anywhere.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Recovering Data

 There are two ways you can recover your data. The simplest solution is just opening a Scrcpy instance with mouse interaction enabled. From there, it’s a simple matter of uploading your important files, contacts, messages, and photos to the personal cloud service of your choice. Alternatively, you can use [Nearby Share](https://article-knowledge.techidaily.com/new-2024-approved-the-gopro-camera-leap-hero4-to-hero5/) to send files to your computer.

 Pulling files directly from your phone is a little bit trickier. One way to do it is to connect the phone to your computer using a USB cable. Then, mirror the phone screen via Scrcpy, use the mouse to pull down the notification shade, and set the USB preferences to “File Transfer.” The phone’s storage should pop up as a [separate drive in Windows Explorer](https://tech-renaissance.techidaily.com/boosting-the-quality-of-photography-on-your-iphoneipad-a-comprehensive-guide/).

 We’re going to run a different ADB command on our computer to get the job done.

 Navigate to the “Platform Tools” folder, hold down shift, and right-click anywhere blank to open the context menu. Select “Open a Powershell Window Here,” just like you did before.

![Opening a PowerShell window using Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-012603.png) 

 To make the transfer, you’ll need the location of the file on your phone. Open the [file manager](https://visual-screen-recording.techidaily.com/updated-2024-approved-comprehensive-manual-best-practices-for-using-mobizen-recording-tool/) of your choice on your phone and locate the file you want to transfer (you can do this by interacting with the phone using Srncpy on your computer). Tap the file to open it, click the three-dot button, and select “File Info.” It’ll reveal the file’s location.

Close 

 Type the following command in the Powershell window and press Enter. Replace the example location in this command with the location of your file.

adb pull /storage/emulated/0/Pictures/pic.png

![Pulling a file from an Android phone using an ADB command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ksnip_20240801-020401.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080317/19272" target="_top" id="2080317">
  <img src="//a.impactradius-go.com/display-ad/19272-2080317" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080317/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You’ll find this pulled file inside the Users directory in your Windows drive.

---

 Sliding one toggle on your phone’s settings can save you the headache of taking it to the shop just to recover your important files.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-advanced-tips-for-capturing-and-storing-desktop-content-for-2024/"><u>[New] Advanced Tips for Capturing and Storing Desktop Content for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-beat-writers-block-learning-ms-words-voice-transcription-techniques/"><u>[New] Beat Writer’s Block  Learning MS Word's Voice Transcription Techniques</u></a></li>
<li><a href="https://article-files.techidaily.com/new-merge-skype-and-zoom-easy-techniques-for-effective-communication-for-2024/"><u>[New] Merge Skype and Zoom  Easy Techniques for Effective Communication for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/qualcomm-chip-usb-driver-installation-guide-and-files-for-win-11-10-8-and-7/"><u>[Qualcomm Chip] USB Driver Installation Guide & Files for Win 11, 10, 8 and 7</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-elevating-imagery-the-hdr-revolution-in-video-workflows/"><u>[Updated] In 2024, Elevating Imagery  The HDR Revolution in Video Workflows</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-transform-your-work-from-home-experience-with-skype-screen-sharing-techniques/"><u>[Updated] In 2024, Transform Your Work-From-Home Experience with Skype Screen Sharing Techniques</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-navigating-success-best-business-management-and-economy-games-for-2024/"><u>[Updated] Navigating Success  Best Business Management and Economy Games for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-rhythmic-resonance-select-sites-for-downloading-tones/"><u>[Updated] Rhythmic Resonance  Select Sites for Downloading Tones</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-top-pick-composition-tools-for-iphone-best-free-apps-reviewed-for-2024/"><u>[Updated] Top Pick Composition Tools for iPhone  Best Free Apps Reviewed for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-spectacular-free-image-editors-the-new-era/"><u>2024 Approved  Spectacular Free Image Editors  The New Era</u></a></li>
<li><a href="https://hardware-help.techidaily.com/acer-trackpad-driver-download-guide-for-windows-10-users/"><u>Acer TrackPad Driver Download Guide for Windows 10 Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cutting-edge-narratives-defining-great-movies/"><u>Cutting-Edge Narratives Defining Great Movies</u></a></li>
<li><a href="https://hardware-help.techidaily.com/differing-approaches-to-intels-enhanced-processor-warranty-disparities-uncovered-by-recent-market-research/"><u>Differing Approaches to Intel's Enhanced Processor Warranty: Disparities Uncovered by Recent Market Research</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-hp-laserjet-pro-m428fdw-printer-drivers-supports-win-1087xpvista/"><u>Download & Install HP LaserJet Pro M428fdw Printer Drivers - Supports Win 10/8/7/XP/Vista</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-intel-i82579-chipset-drivers-for-free-simple-and-fast-installation-guide/"><u>Download Intel I82579 Chipset Drivers for Free - Simple & Fast Installation Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-samsung-m2020-printer-drivers-complete-guide/"><u>Download Samsung M2020 Printer Drivers: Complete Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-latest-epson-wf-3640-printer-drivers-for-your-windows-pc/"><u>Download the Latest Epson WF-3640 Printer Drivers for Your Windows PC</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/drop-in-price-alert-phrozen-high-resolution-8k-ss-resin-3d-printer-now-available-for-just-325/"><u>Drop in Price Alert: Phrozen High-Resolution 8K sS Resin 3D Printer Now Available for Just $325</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvd-2-layer/"><u>DVD 2-Layer圧縮に必要な自由ソフトとその使用方法解説</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-of-ricoh-printer-drivers-for-windows-operating-systems/"><u>Effortless Installation of Ricoh Printer Drivers for Windows Operating Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fast-download-get-your-samsung-c460-drivers-instantly/"><u>Fast Download: Get Your Samsung C460 Drivers Instantly!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-download-updated-epson-l3110-drivers-for-windows-operating-systems-win11107/"><u>Free Download: Updated Epson L3110 Drivers for Windows Operating Systems (Win11/10/7)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-nvidia-3d-vision-driver-downloads-for-windows-comprehensive-guide/"><u>Free Nvidia 3D Vision Driver Downloads for Windows – Comprehensive Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-updates-for-hp-deskjet-ink-advantage-printer-model-3520/"><u>Get the Latest Updates for HP Deskjet Ink Advantage Printer Model 3520</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-focusrite-scarlett-cu2-audio-driver-for-windows-installed-with-this-easy-guide/"><u>Get Your Focusrite Scarlett Cu2 Audio Driver for Windows Installed with This Easy Guide!</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/global-linguistic-impacts-anglicized-lexicon-adaptations/"><u>Global Linguistic Impacts: Anglicized Lexicon Adaptations</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-install-updated-drivers-for-your-netgear-wifi-adapter-efficiently/"><u>How to Install Updated Drivers for Your NETGEAR WiFi Adapter Efficiently</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-elitebook-x360-gen9-laptop-free-download-of-latest-device-drivers/"><u>HP EliteBook X360 Gen9 Laptop - Free Download of Latest Device Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-video-quality-freshly-released-usb-to-hdmi-driver-patches-available-for-download/"><u>Improve Video Quality: Freshly Released USB-to-HDMI Driver Patches Available for Download</u></a></li>
<li><a href="https://hardware-help.techidaily.com/improve-your-computers-visual-output-the-definitive-walkthrough-for-graphics-card-driver-updates-in-windows-11/"><u>Improve Your Computer’s Visual Output: The Definitive Walkthrough for Graphics Card Driver Updates in Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-nvme-driver-installation-made-effortless-start-here/"><u>Intel NVME Driver Installation Made Effortless – Start Here</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-hp-printer-driver-updates-for-windows-11-systems/"><u>Latest HP Printer Driver Updates for Windows 11 Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/successfully-setting-up-arduino-nano-driver-for-windows-operating-systems/"><u>Successfully Setting Up Arduino Nano Driver for Windows Operating Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unlocking-the-power-of-igtv-from-novice-to-pro/"><u>Unlocking the Power of IGTV  From Novice to Pro</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-arduino-hardware-new-usb-driver-options-for-pcs/"><u>Update Your Arduino Hardware: New USB Driver Options for PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/what-voices-resound-in-belgian-halls/"><u>What Voices Resound in Belgian Halls?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/wpcs-are-environmentally-friendly-alternatives-to-pure-plastics-as-they-incorporate-recycled-wood-fibers-reducing-waste-and-lessening-the-impact-on-forests.340/"><u>WPCs Are Environmentally Friendly Alternatives to Pure Plastics, as They Incorporate Recycled Wood Fibers, Reducing Waste and Lessening the Impact on Forests</u></a></li>
</ul></div>
