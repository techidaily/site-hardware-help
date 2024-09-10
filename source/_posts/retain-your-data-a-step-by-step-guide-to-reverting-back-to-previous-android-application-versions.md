---
title: "Retain Your Data: A Step-by-Step Guide to Reverting Back to Previous Android Application Versions"
date: 2024-09-09T16:10:02.172Z
updated: 2024-09-10T16:10:02.172Z
tags:
  - android
categories:
  - tech
thumbnail: https://thmb.techidaily.com/9e5ef4400f63e7f920ad051c5a9167da56f0ec84a54929789d005136b7898918.jpg
---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Retain Your Data: A Step-by-Step Guide to Reverting Back to Previous Android Application Versions

### Quick Links

* [What You Need to Downgrade an App](https://some-techniques.techidaily.com/in-2024-exploring-together-top-metaverse-multiplayer-joints/)
* [Step 1\. Set Up ADB](https://techidaily.com/things-you-dont-know-about-tecno-spark-10-pro-reset-code-drfone-by-drfone-reset-android-reset-android/)
* [Step 2\. Downgrade an App Using ADB](https://digital-screen-recording.techidaily.com/updated-in-2024-the-7-best-total-war-games/)
* [Step 3\. Disable Auto Updates](https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nokia-g42-5g-phone-without-google-account-by-drfone-android/)

### Key Takeaways

* You can downgrade most Android apps by going to Settings > Apps > Manage Apps and choosing to “Uninstall Updates” for a particular app, but this will also log out and remove all your app data.
* To downgrade an app and keep your data, set up Android Debug Bridge and sideload an app using the APK file for the version you want.
* Finally, avoid unwanted updates in the Play Store by going to Settings > Network Preferences > Auto-Update Apps and selecing “Don’t Auto-Update Apps.”

 Sometimes an update breaks an app’s functionality or slows it down. Sometimes developers redesign the UI or leave out the features you like. But you can get your favorite interface and features back by downgrading the app to an older version.

##  What You Need to Downgrade an App

 The Android UI lets you downgrade some apps with a single tap. Just go to Settings > Apps > Manage Apps. Select the app you want to downgrade. Then tap “Uninstall Updates.” But for most apps, you’ll have to uninstall the current app and [sideload the older version](https://facebook-video-content.techidaily.com/updated-unlock-premium-quality-streaming-on-the-worlds-largest-network/) using an APK file. Either way, both methods log out all your accounts and erase any saved progress or preferences, which is far from ideal.

 For a seamless downgrade that keeps the data intact, you need to use the Android Debug Bridge (ADB) instead. Here’s what you’ll need to do that:

1. A computer (I used one running Windows)
2. A cable to connect your device to the computer
3. An APK file for the older app version

 This method may not work perfectly for all apps on devices with Android 9 or older.

[Back up your phone](https://youtube-help.techidaily.com/in-2024-master-your-stream-utilizing-youtubes-av1-technology/), including any important login credentials or app data before proceeding. Secondly, watch out for [critical security updates](https://common-error.techidaily.com/simple-solutions-troubleshooting-and-enhancing-your-file-explorer-on-windows-11/). We don’t recommend skipping or downgrading those.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Step 1\. Set Up ADB

 ADB is a command-line tool for interacting with an Android device through a computer. To set it up, you’ll need to download [SDK Platform Tools](https://developer.android.com/tools/releases/platform-tools) from the official Android website. Extract the downloaded zip file anywhere on your computer. Then open the extracted folder.

![An extracted folder containing Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-6.PNG) 

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014850/22899" target="_top" id="2014850">
  <img src="//a.impactradius-go.com/display-ad/22899-2014850" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014850/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hold down the Shift key and right-click on a blank area. When the context menu opens, click “Open Powershell Window Here.”

![A red arrow pointing at the context menu item for launching Powershell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-10.PNG) 

 Once the terminal appears, connect your Android device to your computer via a USB cable.

 On your phone, select “File Transfer” on the pop-up menu. Go to Settings > About Phone > Build Number. Tap Build Number seven times, or until you see the “You are now a developer!” message. This action unlocks [Developer Options on Android](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/).

![Red arrow pointing at the Build Number in the settings menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/a-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
!['You are now a developer' message popping up in the settings app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/c.jpg) 

![Developer options toggle enabled in the settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/d.jpg) 

Close 

 Next, go to Settings > System > Advanced > Developer Options > USB Debugging. Enable USB Debugging and tap OK to confirm.

![A red arrow pointing at the USB debugging toggle in developer options.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-12.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![A red arrow pointing at the confirmation dialog for enabling USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-13.png) 

Close 

 To test the ADB connection type the following command in the PowerShell terminal on your computer and press Enter.

adb devices

![ADB connection successfully established inside PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-5.PNG) 

 The device ID should show up if the connection is working. If it returns a blank ID, you’ll have to install the Android drivers for your device first.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Step 2\. Downgrade an App Using ADB

 With ADB working, all you need is the APK file for the desired version of the app you want to downgrade to.

 Be careful when installing APK bundles from third parties since these files can contain malware.

 I recommend downloading the untouched APK file from a trusted source, like [APKMirror](https://www.apkmirror.com/) or the official website for the app. Then we’ll install that version on top of the current one (while keeping the data intact).

 Normally, Android doesn’t allow installing apps on top of older versions. But you can bypass that restriction by using ADB commands. We’ll demonstrate the step-by-step process by downgrading Twitter to an older version. That’s right, you can follow this process to revert from X to Twitter!

 First, copy the APK file to the Platform Tools folder on your computer.

![A red arrow pointing at the APK file for the old Twitter app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-8.PNG) 

 The APK file will likely have a long and complicated name. Renaming it to something simpler keeps things tidy and manageable.

 In the PowerShell window, type the following and press Enter. Remember to replace “twitter.apk” with the name of your APK file.

adb install -d twitter.apk

![The app installation process inside an ADB terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture2-1.PNG) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Wait for the “Success” message.

![Successful app installation inside an ADB terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture3.PNG) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The command restored the older version of Twitter without logging me out.

![The X (formerly Twitter) app being downgraded to the old Twitter app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/untitled-1.png) 

 The APK files for some apps are split into multiple packages. To install a split APK bundle, download the APKM bundle and use 7Zip or a similar app to extract the APKM file anywhere.

![APKM file extracted to a folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-9.PNG) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Navigate to the extracted folder and copy the APK files to the Platform Tools folder.

![Different split APK files inside the Platform Tools folder.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/capture-11.PNG) 

 Enter the following command in the PowerShell terminal.

adb install-multiple -d base.apk config1.apk config2.apk config3.apk

 Wait for the “Success” message.

##  Step 3\. Disable Auto Updates

 By default, the Google Play Store automatically updates apps to their latest version. To prevent your newly downgraded app from getting updates, you’ll have to [disable the Auto Update feature](https://youtube-zero.techidaily.com/cing-video-success-top-8-yt-thumbnail-strategies-for-2024/).

 Open the Google Play Store app and tap your profile icon. Go to Settings > Network Preferences > Auto-Update Apps. Select “Don’t Auto-Update Apps.”

![Network preferences being highlighted in Google Play Store](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/k.png) 

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Auto-update apps button being highlighted.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/l.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Auto-update apps menu in Google Play Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/z.png) 

Close 

 Your app is now locked into the same version until you manually update it.

---

 With that, you have everything you need to downgrade an Android without losing its data. And you’ll never be stuck with an update you don’t like.

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
<li><a href="https://article-files.techidaily.com/new-2024-approved-tomtom-actioncams-latest-features/"><u>[New] 2024 Approved TomTom ActionCam's Latest Features</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-high-fidelity-android-3d-player/"><u>[New] High-Fidelity Android 3D Player</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-step-by-step-setting-up-a-channel-for-streaming/"><u>[New] In 2024, Step-by-Step Setting up a Channel for Streaming</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-short-track-speed-skating-olympics-2022-highlights/"><u>[New] Short Track Speed Skating Olympics 2022 Highlights</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/become-an-engaging-speaker-on-google-meet-platforms-for-2024/"><u>Become an Engaging Speaker on Google Meet Platforms for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/complete-guide-to-installing-printer-drivers-brother-l2absolutely-here-are-five-new-seo-friendly-titles-similar-to-brother-mfc-l2700dw-driver-download-and-i26/"><u>Complete Guide To Installing Printer Drivers - Brother L2absolutely! Here Are Five New SEO-Friendly Titles Similar to Brother MFC-L2700DW Driver Download & Install for Windows:</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-guide-how-to-securely-obtain-and-install-epson-xp-430-drivers-on-your-windows-device/"><u>Comprehensive Guide: How To Securely Obtain & Install Epson XP-430 Drivers on Your Windows Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722960059335-direct-link-to-nvidia-rtx-3080-graphics-card-driver-compatible-with-windows-versions/"><u>Direct Link to NVIDIA RTX 3080 Graphics Card Driver - Compatible with Windows Versions!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-epson-gt-s50-driver-for-windows-7810/"><u>Download Epson GT S50 Driver for Windows 7/8/10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-linksys-ae2500-wifi-router-software-now/"><u>Download Linksys AE2500 WiFi Router Software Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easily-install-or-update-your-mpow-bluetooth-driver-on-windows-systems-versions-1187/"><u>Easily Install or Update Your MPOW Bluetooth Driver on Windows Systems (Versions 11/8/7)</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-instructions-to-download-and-maintain-hid-keyboard-drivers/"><u>Easy Instructions to Download and Maintain HID Keyboard Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-steps-to-install-latest-driver-for-your-intel-centrino-advanced-n-6235-wifi-card/"><u>Easy Steps to Install Latest Driver for Your Intel Centrino Advanced-N 6235 WiFi Card</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-installation-fresh-surface-book-2-drivers-at-your-fingertips/"><u>Effortless Installation: Fresh Surface Book 2 Drivers at Your Fingertips!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-graphics-experience-download-amds-newest-radeon-rx-6700-xt-driver-for-windows-operating-system-compatibility-win11win10win7-supported/"><u>Enhance Your Graphics Experience - Download AMD's Newest Radeon RX 6700 XT Driver for Windows Operating System Compatibility: Win11/Win10/Win7 Supported</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-seamless-printing-with-canon-ip110-drivers-for-windows-latest-versions-available/"><u>Ensure Seamless Printing with Canon IP110 Drivers for Windows - Latest Versions Available!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-canon-printer-and-scanner-driver-downloads-for-windows-fast-and-simple-installation/"><u>Free Canon Printer and Scanner Driver Downloads for Windows - Fast & Simple Installation</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-rtx-2070-super-graphics-driver-downloads-and-updates-for-windows-11/"><u>Free RTX 2070 Super Graphics Driver Downloads and Updates for Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/freshly-released-nvidia-quadro-rtx-driver-update-supports-win-10-8-7/"><u>Freshly Released: Nvidia Quadro RTX Driver Update - Supports Win 10, 8, 7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-amd-rx-5700-xt-driver-software-for-windows-operating-systems-version-111087/"><u>Get the Latest AMD RX 5700 XT Driver Software for Windows Operating Systems: Version 11/10/8/7</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-nvidia-geforce-rtx-1080-driver-update-on-windows-10-made-easy/"><u>Get the Latest NVIDIA Geforce RTX 1080 Driver Update on Windows 10 Made Easy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722967427447-get-your-hands-on-the-updated-magicard-rio-pro-driver-for-windows-users/"><u>Get Your Hands on the Updated Magicard Rio Pro Driver for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-samsung-phones-adb-software-on-the-go/"><u>Get Your Samsung Phone's ADB Software on the Go!</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-from-your-iphone-6-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock from your iPhone 6 and iPad</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-latest-driver-update-for-your-logitech-k35cu-full-size-keyboard/"><u>How to Get the Latest Driver Update for Your Logitech K35cu Full-Size Keyboard</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-wi-fi-drivers-in-windows-11-and-windows-10/"><u>How to Update Wi-Fi Drivers in Windows 11 and Windows 10</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-vivo-t2x-5g-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Vivo T2x 5G</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-endless-eradication-guide-bypassing-youtubes-snappy-content/"><u>In 2024, Endless Eradication Guide Bypassing YouTube's Snappy Content</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-secure-and-enhance-slack-communications-with-top-10-free-audio-apps/"><u>In 2024, Secure & Enhance Slack Communications with Top 10 Free Audio Apps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-4-sim-location-trackers-to-easily-find-your-lost-oneplus-device-by-drfone-android/"><u>In 2024, Top 4 SIM Location Trackers To Easily Find Your Lost OnePlus Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-geforce-rtx-2080-driver-updates-available-for-windows-11-7-and-8-operating-systems/"><u>Latest GeForce RTX 2080 Driver Updates Available for Windows 11, 7 & 8 Operating Systems</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-the-art-of-visual-flow-with-kinemaster-for-2024/"><u>Mastering the Art of Visual Flow with Kinemaster for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mediatek-usb-driver-downloads-made-simple-and-fast/"><u>MediaTek USB Driver Downloads Made Simple and Fast</u></a></li>
<li><a href="https://hardware-help.techidaily.com/optimizing-your-sound-quality-on-windows-fixing-issues-with-the-realtek-alc887-driver/"><u>Optimizing Your Sound Quality on Windows: Fixing Issues with the Realtek ALC887 Driver</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-install-realtek-alc892aaic7380-audio-driver-update-for-windows-11/"><u>Quick Install: RealTek ALC892A/AIC7380 Audio Driver Update for Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/selecting-the-vice-president/"><u>Selecting the Vice-President</u></a></li>
<li><a href="https://hardware-help.techidaily.com/speedy-installation-secure-your-pioneer-dj-ddj-sx2-device-drivers-today/"><u>Speedy Installation: Secure Your Pioneer DJ DDJ-SX2 Device Drivers Today</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-solution-to-haldll-errors-across-various-windows-versions-including-vista/"><u>Step-by-Step Solution to Hal.dll Errors Across Various Windows Versions Including Vista</u></a></li>
</ul></div>
