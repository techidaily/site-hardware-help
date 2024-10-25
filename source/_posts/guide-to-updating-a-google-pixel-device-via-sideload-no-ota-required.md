---
title: Guide to Updating a Google Pixel Device via Sideload - No OTA Required
date: 2024-10-22T16:00:14.867Z
updated: 2024-10-25T03:30:10.679Z
tags:
  - android
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/android-logo-adb.png
---

## Guide to Updating a Google Pixel Device via Sideload - No OTA Required

### Quick Links

* [Get Everything Ready](https://graphic-issues.techidaily.com/cutting-edge-visuals-updated-nvidia-geforce-for-windows-10/)
* [Connect Device and Boot into Recovery Mode](https://screen-video-capture.techidaily.com/transform-speech-into-text-the-accurate-google-method/)
* [Sideload the OTA Update](https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-galaxy-m34-pattern-lock-if-forgotten-6-ways-by-drfone-android/)

 Google Pixel phones generally get updates before other Android devices, but that's not always the case. There are times when you may want to manually install a firmware update before it arrives over the air. We'll show you how to sideload an OTA update on Pixels.

 In order to do this, we'll be using the Android SDK and running some commands [Command Prompt](https://fox-access.techidaily.com/unleashing-your-cameras-potential-with-top-rated-drones-gimbals-for-2024/) on Windows 10 and 11 and [Terminal](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/) on Mac. This is not a terribly difficult process, but if not followed correctly, it can permanently damage your device.

 This process does not wipe your Android device clean. It installs just like any other update. However, it's a good idea to [back up everything](https://facebook-clips.techidaily.com/optimal-mp4-transporter-to-fb-hub/) you might not want to lose if something goes wrong.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Get Everything Ready

 Before we start the process, there are a number of things we need to get ready. The first thing you'll need is ADB and "Platform Tools." [Follow the steps in our ADB guide](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) to install the appropriate files and get it all up and running on your Windows or Mac computer.

Related: [How to Install and Use ADB, the Android Debug Bridge Utility](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) 

 Next, we need to turn on USB debugging on your handset. [Enabling USB debugging](https://buynow-tips.techidaily.com/navigating-marvels-team-up-the-truth-behind-the-avengers-ratings/) on Pixels is a simple process that we've outlined in a separate guide.

![Enable USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-30-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037346/7443" target="_top" id="2037346">
  <img src="//a.impactradius-go.com/display-ad/7443-2037346" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037346/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The last thing we need is the OTA file for your device. This is the actual update that will be applied to your specific Google Pixel. You can find the latest OTA for your Pixel from [Google's website](https://developers.google.com/android/ota#legal). The latest OTA will be at the bottom of each device's list.

 Be extra sure you are downloading the OTA for the correct Pixel device and mobile carrier.

![Download the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-33-09.jpg) 

##  Connect Device and Boot into Recovery Mode

 Okay, now we can really get started. First, connect your Pixel phone to your Windows or Mac computer. You will immediately be asked to "Allow USB Debugging" on your smartphone. Select "Always Allow From This Computer" and tap "OK."

 The "Allow USB Debugging" message might not appear the moment you plug your Pixel into your computer. If it doesn't, continue following the steps below, and the notice should appear once you run the 

        `adb devices`
    
 command.

![Allow USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-41-02.jpg) 

 Next, on Windows 11 or 10, go to the folder where you downloaded the ADB files. Press Shift on your keyboard and right-click on your mouse simultaneously on a blank area and select "Open Command Windows Here"---or "PowerShell"---from the menu.

![Click "Open Command Windows here."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-56-52.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 On Mac, [open](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/)[the Terminal app](https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-s17-by-drfone-android/) and type 

        `cd "folder destination"`
    
 \---replace "folder destination" with the location of where you saved the ADB files. For example, if the ADB and Platform Tools files were saved to your Downloads folder, you would type in 

        `cd Downloads`
    
 (capitalization matters).

![CD command in Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/image-12.png) 

 In the command or Terminal window, make sure the computer can see the device with the following command. You will see a device listed if everything is working.

 On Mac, the 

        `adb `
    
 command is 

        `./adb`
    
 . Make sure you are using that command everywhere 

        `adb`
    
 is mentioned in the steps below.

        `adb devices`
    
![Device listed in ADB.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-57-50.jpg) 

 Next, use this command to reboot the device into recovery:

        `adb reboot recovery`
    

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129043/19576" target="_top" id="2129043">
  <img src="//a.impactradius-go.com/display-ad/19576-2129043" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129043/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Sideload the OTA Update

 Your Pixel will reboot following the last command, and you'll see a screen with a sad Android robot lying on his back with a red exclamation mark. To open the hidden recovery menu, press the Volume Up button while holding the Power button.

![Dead Android robot screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8463-650x433-1-650x277.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

 Now use the Volume Down button to navigate to "Apply update from ADB" option, then press the Power button to select the option.

![Select &quot;Apply update from ADB.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8461-650x433.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

 Go back to your computer and type the following command. Replace "updatefile.zip" with the name of your OTA file. If the OTA file isn't in the same folder as your ADB files, you can drag it from the File Explorer on Windows or Finder on Mac into the Command Prompt or Terminal.

        `adb sideload updatefile.zip`
    
![Sideload the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-04-12.jpg) 

 You'll see a completion percentage while the file is being pushed to your device. When it's finished, the recovery menu will show up again on your phone, with the "Reboot system now" option already highlighted. Hit the Power button to restart your Pixel.

![Progress of installation.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-05-14.jpg) 

<!-- affiliate ads begin -->
<span id="1983539">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983539.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983539">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983539.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983539%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983539/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's it! Your Pixel phone will now be running the latest OTA update from Google. This is a much easier process than it used to be, thankfully. Hopefully, you [don't have to do it too often](https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-to-computer-drfone-by-drfone-ios/), though.

Related: [How to Manually Check for System Updates on an Android Phone](https://screen-mirror.techidaily.com/how-to-stream-apple-iphone-11-pro-to-computer-drfone-by-drfone-ios/)

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-permanent-capture-sustaining-facebook-live-footage/"><u>[New] 2024 Approved Permanent Capture Sustaining Facebook Live Footage</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-exclusive-access-prime-video-downloader-picks/"><u>[Updated] 2024 Approved Exclusive Access Prime Video Downloader Picks</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-streaming-success-live-tiktok-broadcasts-on-computers/"><u>2024 Approved Streaming Success Live TikTok Broadcasts on Computers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/at-lp120xusb-unveiled-record-revival-on-a-turntable/"><u>AT-LP120XUSB Unveiled: Record Revival on a Turntable</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-poco-x6-pro-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Poco X6 Pro</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-ways-to-upgrade-your-lenovo-docks-compatibility-with-latest-drivers/"><u>Effortless Ways to Upgrade Your Lenovo Dock's Compatibility with Latest Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/find-and-fix-issues-with-the-elan-smbus-driver-for-windows-a-comprehensive-update-guide/"><u>Find and Fix Issues with the Elan SMBus Driver for Windows: A Comprehensive Update Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-solve-lg-device-not-recognized-issue-for-windows-10-8-and-7-users/"><u>How to Solve 'LG Device Not Recognized' Issue for Windows 10, 8 & 7 Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-vivo-s17-pro-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Vivo S17 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-what-does-jailbreaking-iphone-11-i-do-get-answers-here-by-drfone-ios/"><u>In 2024, What Does Jailbreaking iPhone 11 i Do? Get Answers here</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-top-notch-drivers-on-your-msi-b3n-motherboard-download-compatible-with-windows-10-and-windows-e7-the-new-tomahawk-variant/"><u>Install Top-Notch Drivers on Your MSI B3n Motherboard: Download Compatible with Windows 10 and Windows E7 - The New Tomahawk Variant</u></a></li>
<li><a href="https://hardware-help.techidaily.com/installation-instructions-for-eveos-wireless-bluetooth-receiver-firmware/"><u>Installation Instructions for Eveo's Wireless Bluetooth Receiver Firmware</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-updates-lenovo-thunderbolt-3-docking-station-software/"><u>Latest Updates: Lenovo Thunderbolt 3 Docking Station Software</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastery-of-components-toms-authoritative-hardware-evaluations/"><u>Mastery of Components: Tom's Authoritative Hardware Evaluations</u></a></li>
<li><a href="https://fox-that.techidaily.com/solve-your-idevices-typing-troubles-keyboard-malfunctions-addressed-with-6-effective-fixes/"><u>Solve Your iDevice's Typing Troubles: Keyboard Malfunctions Addressed with 6 Effective Fixes</u></a></li>
<li><a href="https://data-wizards.techidaily.com/spacecraft-data-salvage-hub/"><u>Spacecraft Data Salvage Hub</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-fixes-for-asus-wireless-network-adapter-issues-on-win10-8-and-7-drivers-demystified/"><u>Step-by-Step Fixes for ASUS Wireless Network Adapter Issues on Win10, 8 & 7 - Drivers Demystified</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-fresh-microsoft-drivers-for-windows-10-8-or-7-systems/"><u>Step-by-Step Tutorial: Fresh Microsoft Drivers for Windows 10, 8 or 7 Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-chatbot-potential-top-5-strategies-for-using-chatgpt-without-signup/"><u>Unlocking Chatbot Potential: Top 5 Strategies for Using ChatGPT without Signup</u></a></li>
</ul></div>

