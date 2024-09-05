---
title: Guide to Updating a Google Pixel Device via Sideload - No OTA Required
date: 2024-09-04T02:12:19.090Z
updated: 2024-09-05T02:12:19.090Z
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

##  Get Everything Ready

 Before we start the process, there are a number of things we need to get ready. The first thing you'll need is ADB and "Platform Tools." [Follow the steps in our ADB guide](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) to install the appropriate files and get it all up and running on your Windows or Mac computer.

Related: [How to Install and Use ADB, the Android Debug Bridge Utility](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/) 

 Next, we need to turn on USB debugging on your handset. [Enabling USB debugging](https://buynow-tips.techidaily.com/navigating-marvels-team-up-the-truth-behind-the-avengers-ratings/) on Pixels is a simple process that we've outlined in a separate guide.

![Enable USB debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_16-30-01.jpg) 

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, use this command to reboot the device into recovery:

        `adb reboot recovery`
    
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Sideload the OTA Update

 Your Pixel will reboot following the last command, and you'll see a screen with a sad Android robot lying on his back with a red exclamation mark. To open the hidden recovery menu, press the Volume Up button while holding the Power button.

![Dead Android robot screen.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8463-650x433-1-650x277.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118326/7443" target="_top" id="2118326">
  <img src="//a.impactradius-go.com/display-ad/7443-2118326" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118326/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now use the Volume Down button to navigate to "Apply update from ADB" option, then press the Power button to select the option.

![Select &quot;Apply update from ADB.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/05/IMG_8461-650x433.jpg?trim=1,1&amp;bg-color=000&amp;pad=1,1) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Go back to your computer and type the following command. Replace "updatefile.zip" with the name of your OTA file. If the OTA file isn't in the same folder as your ADB files, you can drag it from the File Explorer on Windows or Finder on Mac into the Command Prompt or Terminal.

        `adb sideload updatefile.zip`
    
![Sideload the OTA file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-04-12.jpg) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087485/7443" target="_top" id="2087485">
  <img src="//a.impactradius-go.com/display-ad/7443-2087485" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087485/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You'll see a completion percentage while the file is being pushed to your device. When it's finished, the recovery menu will show up again on your phone, with the "Reboot system now" option already highlighted. Hit the Power button to restart your Pixel.

![Progress of installation.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/12/2021-12-27_17-05-14.jpg) 

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-optimize-your-films-a-mac-approach-to-instagram-shortening/"><u>[New] 2024 Approved  Optimize Your Films  A Mac Approach to Instagram Shortening</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-the-ultimate-guide-to-the-most-effective-pc-screen-capture-apps/"><u>[New] 2024 Approved  The Ultimate Guide to the Most Effective PC Screen Capture Apps</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-achieving-effortless-seams-in-inshot-videos-for-2024/"><u>[New] Achieving Effortless Seams in Inshot Videos for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-your-digital-den-top-12-animal-simulator-games-on-android-for-2024/"><u>[New] Your Digital Den  Top 12 Animal Simulator Games on Android for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-making-history-shine-again-instagram-effects-for-your-archive/"><u>[Updated] 2024 Approved  Making History Shine Again  Instagram Effects for Your Archive</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-a-compre-written-in-the-stars-how-to-choose-an-ideal-podcast-title/"><u>[Updated] A Compre Written in the Stars  How to Choose an Ideal Podcast Title</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-introduction-to-adding-new-fonts-in-ae/"><u>[Updated] Introduction to Adding New Fonts in AE</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-perfecting-your-youtube-video-archive-setup-for-2024/"><u>[Updated] Perfecting Your YouTube Video Archive Setup for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/agni-2-5g-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>Agni 2 5G support - Forgotten screen lock.</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/best-rated-wedding-timekeepers-a-comprehensive-android-and-ios-app-review/"><u>Best-Rated Wedding Timekeepers  A Comprehensive Android & iOS App Review</u></a></li>
<li><a href="https://hardware-help.techidaily.com/beyond-being-cool-can-folding-phones-evolve-into-essential-mobile-devices-for-everyone/"><u>Beyond Being Cool: Can Folding Phones Evolve Into Essential Mobile Devices for Everyone?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/busting-the-myth-you-may-not-actually-want-a-larger-smartphone-battery/"><u>Busting the Myth: You May Not Actually Want a Larger Smartphone Battery</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-android-solutions-expert-guide-to-resolving-any-issue/"><u>Comprehensive Android Solutions: Expert Guide to Resolving Any Issue</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-how-to-optimize-and-reduce-glare-achieve-a-dimmer-display-for-your-android-smartphone-or-tablet/"><u>Discover How to Optimize and Reduce Glare: Achieve a Dimmer Display for Your Android Smartphone or Tablet</u></a></li>
<li><a href="https://hardware-help.techidaily.com/discover-the-top-7-utilities-of-samsungs-texting-service/"><u>Discover the Top 7 Utilities of Samsung's Texting Service</u></a></li>
<li><a href="https://hardware-help.techidaily.com/effortless-method-to-deactivate-every-sensor-on-your-android-device-instantly/"><u>Effortless Method to Deactivate Every Sensor on Your Android Device Instantly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/eliminate-the-myth-of-needing-a-task-killer-on-android-expert-tips-for-efficiently-handling-active-processes/"><u>Eliminate the Myth of Needing a Task Killer on Android: Expert Tips for Efficiently Handling Active Processes</u></a></li>
<li><a href="https://hardware-help.techidaily.com/embracing-simplicity-how-my-2019-budget-phone-powers-me/"><u>Embracing Simplicity: How My 2019 Budget Phone Powers Me</u></a></li>
<li><a href="https://hardware-help.techidaily.com/embracing-the-era-of-convergence-the-rise-of-mobile-device-standardization/"><u>Embracing the Era of Convergence: The Rise of Mobile Device Standardization</u></a></li>
<li><a href="https://hardware-help.techidaily.com/examining-the-importance-of-sunlight-visibility-in-modern-phones/"><u>Examining the Importance of Sunlight Visibility in Modern Phones</u></a></li>
<li><a href="https://hardware-help.techidaily.com/experience-the-new-unihertz-featuring-an-impressive-5-inch-screen/"><u>Experience the New UniHertz: Featuring an Impressive 5-Inch Screen</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-tips-for-reconfiguring-wifi-bluetooth-and-mobile-data-settings-on-samsung-smartphones/"><u>Expert Tips for Reconfiguring WiFi, Bluetooth & Mobile Data Settings on Samsung Smartphones</u></a></li>
<li><a href="https://hardware-help.techidaily.com/explained-how-auto-brightness-feature-adapts-screen-lighting-on-your-smartphone-and-laptop/"><u>Explained: How Auto-Brightness Feature Adapts Screen Lighting on Your Smartphone & Laptop</u></a></li>
<li><a href="https://hardware-help.techidaily.com/explore-overlooked-capabilities-the-ultimate-list-of-10-android-13-hidden-gems/"><u>Explore Overlooked Capabilities: The Ultimate List of 10 Android 13 Hidden Gems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/exploring-the-latest-upgrades-enhanced-cameras-and-wellness-tools-on-googles-pixel-devices/"><u>Exploring the Latest Upgrades: Enhanced Cameras & Wellness Tools on Google's Pixel Devices</u></a></li>
<li><a href="https://fox-info.techidaily.com/gigglestv-beginners-guide-to-making-videos/"><u>GigglesTV  Beginner's Guide to Making Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-google-can-make-your-transition-from-iphone-to-samsung-galaxy-effortless/"><u>How Google Can Make Your Transition From iPhone to Samsung Galaxy Effortless</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/iastorasys-bluescreens-no-more-comprehensive-guide-to-fixing-your-pcs-critical-error/"><u>IaStora.sys Bluescreens No More! - Comprehensive Guide to Fixing Your PC's Critical Error</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Infinix Hot 40i? | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/in-depth-analysis-secrets-inside-and-comprehensive-breakdown/"><u>In-Depth Analysis, Secrets Inside, and Comprehensive Breakdown.</u></a></li>
<li><a href="https://hardware-help.techidaily.com/introducing-amazons-latest-marvel-the-mighty-fire-max-11-tablet/"><u>Introducing Amazon's Latest Marvel - The Mighty Fire Max 11 Tablet</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/learn-how-to-lock-stolen-your-apple-iphone-14-plus-properly-by-drfone-ios/"><u>Learn How To Lock Stolen Your Apple iPhone 14 Plus Properly</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-android-settings-how-to-reassign-primary-app-functionality/"><u>Mastering Android Settings: How to Reassign Primary App Functionality</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-customization-adjusting-text-and-icon-sizes-on-android-phones-and-tablets/"><u>Mastering Customization: Adjusting Text & Icon Sizes on Android Phones & Tablets</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-real-time-subtitles-a-guide-to-activating-live-caption-features-on-your-google-pixel-device/"><u>Mastering Real-Time Subtitles: A Guide to Activating Live Caption Features on Your Google Pixel Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-the-benefits-of-reading-mode-a-comprehensive-guide-for-android-users/"><u>Mastering the Benefits of Reading Mode: A Comprehensive Guide for Android Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mobile-magic-learn-how-to-retrieve-written-content-from-photographs-using-your-smartphone/"><u>Mobile Magic: Learn How to Retrieve Written Content From Photographs Using Your Smartphone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/retain-your-data-a-step-by-step-guide-to-reverting-back-to-previous-android-application-versions/"><u>Retain Your Data: A Step-by-Step Guide to Reverting Back to Previous Android Application Versions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-transition-how-simple-it-really-is-to-switch-from-iphone-to-android/"><u>Seamless Transition: How Simple It Really Is to Switch From iPhone to Android</u></a></li>
<li><a href="https://hardware-help.techidaily.com/simple-guide-on-distributing-your-samsung-image-collection-to-others/"><u>Simple Guide on Distributing Your Samsung Image Collection to Others</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/simplifying-creative-workflow-adding-text-to-photography-files/"><u>Simplifying Creative Workflow  Adding Text to Photography Files</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-setting-up-video-live-wallpapers-on-your-android-device/"><u>Step-by-Step Guide: Setting Up Video Live Wallpapers on Your Android Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-tailoring-your-alerts-in-android-applications/"><u>Step-by-Step Guide: Tailoring Your Alerts in Android Applications</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-guide-transferring-android-applications-to-sd-card/"><u>Step-by-Step Guide: Transferring Android Applications to SD Card</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-strategies-for-securing-your-android-smartphone/"><u>Step-by-Step Strategies for Securing Your Android Smartphone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/streamlining-android-interface-design-tips-for-enhancing-usability-among-older-adults/"><u>Streamlining Android Interface Design: Tips for Enhancing Usability Among Older Adults</u></a></li>
<li><a href="https://hardware-help.techidaily.com/switching-to-dark-interface-settings-in-androids-microsoft-office-suite/"><u>Switching to Dark Interface Settings in Android's Microsoft Office Suite</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-case-for-extra-tactile-controls-a-look-at-increasing-button-count-on-smartphones/"><u>The Case for Extra Tactile Controls: A Look at Increasing Button Count on Smartphones</u></a></li>
<li><a href="https://tech-hub.techidaily.com/understanding-chatgpts-maximum-message-length-strategies-to-exceed-the-characters-allowed/"><u>Understanding ChatGPT's Maximum Message Length: Strategies to Exceed the Characters Allowed</u></a></li>
</ul></div>
