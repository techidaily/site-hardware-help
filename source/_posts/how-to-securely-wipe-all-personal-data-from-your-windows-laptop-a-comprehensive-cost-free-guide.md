---
title: "How to Securely Wipe All Personal Data From Your Windows Laptop: A Comprehensive, Cost-Free Guide"
date: 2024-10-30T18:24:27.236Z
updated: 2024-11-05T22:52:42.942Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## How to Securely Wipe Your Windows Laptop: The No-Cost Method to Protect Your Private Information – Step by Step Guide

![delete key on keyboard](https://www.zdnet.com/a/img/resize/d63e45ef5eb131dc96ab27bda73125ed344a82c5/2024/09/29/d681f9f6-c785-48e5-b76d-2d11b529a893/gettyimages-172972238.jpg?auto=webp&width=1280)

monkeypics/Getty Images

When you replace your old but still functional Windows PC with a shiny new model, you have several options for that gently used device. You can give it away to a friend or family member. You can donate it to a charitable organization like Goodwill (which partners with [Dell Reconnect](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fen-us%2Fdt%2Fcorporate%2Fsocial-impact%2Fadvancing-sustainability%2Fhow-to-recycle%2Ffaq.htm%23tab0%3D1)). You can even trade it in for credit or sell it on a third-party site like [Swappa](https://swappa.com/sell/laptop) or [Back Market](https://www.awin1.com/awclick.php?mid=18275&id=423585&clickref=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp&ued=https%3A%2F%2Fwww.backmarket.com%2Fen-us%2Fbuyback%2Fhome). 

**Also: [Microsoft to start charging for Windows 10 updates next year. Here's how much](https://www.zdnet.com/article/microsoft-to-start-charging-for-windows-10-updates-next-year-heres-how-much/)**

Whichever course of action you take, though, your most important task is to **_permanently delete all your personal files_** from that PC before you pass it along. With a desktop PC, that might be as easy as swapping out the system drive for a new one. But that's usually not an option with a laptop, where replacing storage can be impossible or prohibitively expensive. 

For laptops and for desktops where you aren't replacing the system drive, the simplest route is to reset the PC, choosing the option to remove personal files and reinstall Windows. On a PC running Windows 10, go to Settings > Update & Security > Recovery. On a Windows 11 device, the Reset PC option is under Settings > System > Recovery. Make sure you choose the Remove Everything option, as shown here.

When you're resetting a PC to give away or sell, be sure to choose the Remove Everything option.

Screenshot by Ed Bott/ZDNET

It takes several prompts before you get to the actual reset option (you don't want to do this accidentally, after all) and if you dig through the settings you can find a Clean Disk option designed to remove all data in addition to removing your files. As an alternative, you can boot from Windows installation media, remove all existing disk partitions, and then perform a clean install.

Either option removes existing personal files, but Microsoft's documentation cautions that "the data erasure functionality is targeted at consumers and does not meet government and industry data erasure standards." As a result, it's possible that someone with advanced technical skills could use forensic tools or data recovery software to access some of the deleted information.

**Also: [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/)**

On modern systems with solid-state drives, you can often find a management utility that includes a Secure Erase command. For Samsung SSDs, use the [Samsung Magician](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fsemiconductor.samsung.com%2Fconsumer-storage%2Fmagician%2F) program. For Intel SSDs, download and install the [Intel Memory and Storage Tool](https://www.intel.com/content/www/us/en/download/19543/intel-memory-and-storage-tool-gui.html?v=t). SSDs from Crucial use the [Crucial Storage Executive utility](https://www.crucial.com/support/storage-executive). Microsoft Surface devices support a custom tool called the [Microsoft Surface Data Eraser](https://learn.microsoft.com/en-us/surface/surface-it-toolkit-data-eraser); check the download links in that article to determine whether you need the newer IT Toolkit or the Legacy version for older Surface devices.

Some third-party partition management tools include the option to wipe a disk completely. My favorite for this task is [MiniTool Partition Wizard](https://www.partitionwizard.com/), which includes the Wipe Disk option in free and paid versions.

**Also: [Ditch the Wi-Fi: How to add a wired network to your home without Ethernet cable](https://www.zdnet.com/home-and-office/work-life/ditch-the-wi-fi-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)**

You also can use Windows' built-in encryption tools to ensure that the entire system drive, including unused disk space, is encrypted before performing a clean install. That extra step requires some additional time, but it ensures that any data recovered from anywhere on the drive will be unreadable. And you don't need any third-party software to get the job done.

Your system drive is fully encrypted by default if you've signed in to Windows with a Microsoft account on a modern device that supports BitLocker Device Encryption (BDE). To confirm that your device supports BDE, run the System Information utility (Msinfo32.exe) as an administrator and check the Device Encryption Support entry at the bottom of the System Summary page.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

On a system running Windows 10 Pro or Windows 11 Pro, you can use the Manage BitLocker utility (type BitLocker in the search box to find it) to encrypt the system drive and any data drives. Be sure to choose the option to encrypt the entire drive and not just the space that currently contains data.

**Also: [Where's your BitLocker recovery key? How to save a copy before the next Windows meltdown](https://www.zdnet.com/article/wheres-your-bitlocker-recovery-key-how-to-save-a-copy-before-the-next-windows-meltdown/)**

If Device Encryption isn't available, open a command prompt using the Run As Administrator option and enter this command:

**Cipher /W:C:\\**

That command "zeroes out" unused disk space, overwriting it so that it can't be recovered. This process can take a long time, so consider letting it run overnight while you concentrate on more important tasks.

_This article was originally published on May 12, 2022, and last updated on September 29, 2024\._ 

#### Featured

[Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")

[Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")

[Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")

[Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

* [Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")
* [Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")
* [Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")
* [Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-harmonizing-tracks-in-youtube-music/"><u>[New] 2024 Approved Harmonizing Tracks in YouTube Music</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-effortless-download-and-installation-of-wacom-intuos-pro-drivers-windows-10/"><u>[Step-by-Step Tutorial]: Effortless Download & Installation of Wacom Intuos Pro Drivers (Windows 10)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-unveil-the-untouched-best-of-insta-stories/"><u>[Updated] 2024 Approved Unveil the Untouched Best of Insta Stories</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-scrutinizing-high-dynamic-range-insights-from-luminance/"><u>[Updated] Scrutinizing High Dynamic Range Insights From Luminance</u></a></li>
<li><a href="https://extra-tips.techidaily.com/augmented-realities-transforming-movie-production/"><u>Augmented Realities Transforming Movie Production</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-guide-to-hp-officejet-pro-8610-drivers-compatible-with-multiple-windows-versions/"><u>Download and Update Guide to HP Officejet Pro #8610 Drivers Compatible with Multiple Windows Versions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-canon-mx490-printer-drivers-for-windows-10-8-and-7-step-by-step-guide/"><u>Download Canon MX490 Printer Drivers for Windows 10, 8 & 7: Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-updated-wireless-1535-driver-now-resolved-issues/"><u>Download the Updated Wireless 1535 Driver - Now Resolved Issues</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-amd-radeon-hd-amoled-6350-driver-support-on-windows-os/"><u>Get the Latest AMD Radeon HD Amoled 6350 Driver Support on Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-logitech-g602-mice-software-for-windows-computers/"><u>Get the Latest Logitech G602 Mice Software for Windows Computers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-newest-netgear-a61n-driver-update-package-for-microsoft-windows-systems/"><u>Get the Newest Netgear A61n Driver Update Package for Microsoft Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-overwatch-cannot-find-assets-issue-effectively/"><u>How to Fix 'Overwatch' Cannot Find Assets Issue Effectively</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-intel-irisplus-graphics-driver-version-update-for-quick-and-smooth-setup/"><u>Latest Intel Iris+ Graphics Driver Version [Update] for Quick & Smooth Setup</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-education-exclusive-get-final-cut-pro-at-an-unbeatable-price/"><u>New Education Exclusive Get Final Cut Pro at an Unbeatable Price</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/tips-for-recording-high-quality-video-in-zoom-for-2024/"><u>Tips for Recording High-Quality Video in Zoom for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/ultimate-guide-to-repairing-and-restoring-audio-functionality-on-windows-10-systems/"><u>Ultimate Guide to Repairing and Restoring Audio Functionality on Windows 10 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-oppo-a2-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Oppo A2 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

