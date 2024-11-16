---
title: "ChromeOS Tweaks: How to Install Custom DNS Servers for Enhanced Security and Privacy | Digital Trends"
date: 2024-11-15T05:27:37.655Z
updated: 2024-11-15T18:13:49.528Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/acf1543a08c93a8277bd32ca8ca0045c1e81ebd5061ccbafdfe3582cd05fb8bf.jpg
---

## How to Securely and Efficiently Remove All Personal Information From Your Windows Laptop: A Comprehensive Guide

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
<li><a href="https://twitter-clips.techidaily.com/new-digital-dialogue-diaries-the-full-year-tweets-summary-for-2024/"><u>[New] Digital Dialogue Diaries The Full-Year Tweets Summary for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-the-ultimate-guide-to-sj-cam-s6s-superiority/"><u>[Updated] 2024 Approved The Ultimate Guide to SJ-CAM S6's Superiority</u></a></li>
<li><a href="https://hardware-help.techidaily.com/canon-mg3022-driver-update-guide-get-the-newest-software-now/"><u>Canon MG3022 Driver Update Guide - Get the Newest Software Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-canon-printer-software-mp560-drivers-fast-simple-steps/"><u>Download and Update Canon Printer Software: MP560 Drivers - Fast, Simple Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ensure-seamless-connectivity-get-the-latest-lenovo-bluetooth-drivers-for-your-pc-guaranteed-safe/"><u>Ensure Seamless Connectivity: Get the Latest Lenovo Bluetooth Drivers for Your PC (Guaranteed Safe)</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-advice-on-how-to-resolve-a-livekernelevent-error-144/"><u>Expert Advice on How to Resolve a LiveKernelEvent Error 144</u></a></li>
<li><a href="https://hardware-help.techidaily.com/fast-track-get-your-asus-tablets-touchscreen-drivers-up-and-running-in-windows-11/"><u>Fast Track: Get Your ASUS Tablet's Touchscreen Drivers Up and Running in Windows 11</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-your-windows-computers-audio-upgrade-free-sound-card-driver-downloads/"><u>Get Your Windows Computer's Audio Upgrade: Free Sound Card Driver Downloads</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-foremost-6-networks-fostering-profitable-partnerships/"><u>In 2024, Foremost 6 Networks Fostering Profitable Partnerships</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-download-hp-stream-printer-drivers-get-them-fast/"><u>Quick Download: HP Stream Printer Drivers - Get Them Fast</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/reconhecer-abrecos-e-boas-vindas-em-portugues/"><u>Reconhecer Abreços E Boas-Vindas Em Português</u></a></li>
<li><a href="https://hardware-help.techidaily.com/reliable-and-protected-sades-headset-software-for-windows-get-your-free-download-now/"><u>Reliable and Protected Sades Headset Software for Windows - Get Your Free Download Now</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-instructions-for-updating-broadcom-netlink-gigabit-ethernet-driver-on-windows-11/"><u>Step-by-Step Instructions for Updating Broadcom NETLink Gigabit Ethernet Driver on Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-memory-issues-on-god-of-war-game-console-complete-guide/"><u>Troubleshooting Memory Issues on God of War Game Console - Complete Guide</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-merge-wmv-videos-without-cost-top-free-tools/"><u>Updated Merge WMV Videos Without Cost Top Free Tools</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

