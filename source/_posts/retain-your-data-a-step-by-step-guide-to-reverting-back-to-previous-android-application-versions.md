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


