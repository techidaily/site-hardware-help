---
title: Extend Your MacBook's Battery Life Throughout the Day - Expert Tips From ZDNet
date: 2024-10-22T02:53:19.312Z
updated: 2024-10-25T01:48:37.538Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://www.zdnet.com/a/img/resize/40c93d2434b3b6e6d5fc71136b3ddc175b5af04a/2022/11/07/457a36ec-88ff-4576-98a1-244e342b8628/macbook-pro1.jpg?auto=webp&fit=crop&frame=1&height=172&width=306
---

## How to Completely Remove Your Data From a Windows PC Safely and Without Cost - Expert Tips & Tricks

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
<li><a href="https://techtrends.techidaily.com/aol-mail-status-undergoing-maintenance-or-experiencing-outages/"><u>AOL Mail Status: Undergoing Maintenance or Experiencing Outages?</u></a></li>
<li><a href="https://win11.techidaily.com/circumvent-unauthorized-windows-login-errors-easy-guide/"><u>Circumvent Unauthorized Windows Login Errors (Easy Guide)</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/clear-obstacle-youtube-tweets-on-google-chrome/"><u>Clear Obstacle YouTube Tweets on Google Chrome</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easily-install-targus-docking-station-software-now/"><u>Easily Install Targus Docking Station Software Now</u></a></li>
<li><a href="https://extra-information.techidaily.com/exclusive-access-download-your-own-tailored-tracks/"><u>Exclusive Access Download Your Own Tailored Tracks</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/expert-strategies-for-developing-captivating-audio-visual-teasers-for-2024/"><u>Expert Strategies for Developing Captivating Audio-Visual Teasers for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-thrustmaster-t150-stealth-plus-gamepad-up-and-running-fast-driver-downloads/"><u>Get Your Thrustmaster T150 Stealth Plus Gamepad Up and Running - Fast Driver Downloads</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-revive-your-bricked-oneplus-nord-3-5g-in-minutes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Revive Your Bricked OnePlus Nord 3 5G in Minutes | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-xiaomi-13t-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Xiaomi 13T by Phone Number | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-or-fix-lgs-usb-driver-problem-in-windows-1011-8-and-7/"><u>How to Update or Fix LG's USB Driver Problem in Windows 10/11, 8, and 7</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-cut-costs-not-quality-final-cut-pro-education-bundle-offers-for-2024/"><u>New Cut Costs, Not Quality Final Cut Pro Education Bundle Offers for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-low-cost-film-production-software-top-picks-for-emerging-creators/"><u>New Low-Cost Film Production Software Top Picks for Emerging Creators</u></a></li>
<li><a href="https://hardware-help.techidaily.com/new-release-download-updated-nvidia-drivers-for-improved-gaming-and-productivity/"><u>New Release! Download Updated Nvidia Drivers for Improved Gaming and Productivity</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-how-to-swiftly-acquire-dell-latitude-e6420-drivers/"><u>Step by Step: How to Swiftly Acquire Dell Latitude E6420 Drivers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-and-solving-hp-p2035-printer-driver-errors-in-windows-easily/"><u>Troubleshooting and Solving HP P2035 Printer Driver Errors in Windows Easily</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-or-fresh-install-of-nvidia-graphics-card-drivers-made-easy/"><u>Update or Fresh Install of NVIDIA Graphics Card Drivers Made Easy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/windows-users-rejoice-how-to-get-the-latest-hp-scanner-driver-installed/"><u>Windows Users Rejoice: How to Get the Latest HP Scanner Driver Installed!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087395/7443" target="_top" id="2087395">
  <img src="//a.impactradius-go.com/display-ad/7443-2087395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

