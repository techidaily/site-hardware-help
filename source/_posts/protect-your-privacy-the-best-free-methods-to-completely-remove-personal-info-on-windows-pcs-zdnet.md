---
title: "Protect Your Privacy: The Best Free Methods to Completely Remove Personal Info on Windows PCs | ZDNet"
date: 2024-10-29T23:46:32.802Z
updated: 2024-11-05T20:53:13.045Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/32523e559641d9ec27c8a10ab7be14cb0b35f831c8a7be2e764f2665633793d5.jpg
---

## Protect Your Privacy: The Best Free Methods to Completely Remove Personal Info on Windows PCs

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

[The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")

[Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")

[My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")

[5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

* [The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")
* [Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")
* [My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")
* [5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

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
<li><a href="https://youtube-docs.techidaily.com/n-2024-unison-video-visionaries-finding-your-cms/"><u>[New] In 2024, Unison Video Visionaries Finding Your CMS</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-top-8-montage-apps-for-your-androidiphone/"><u>[New] Top 8 Montage Apps for Your Android/iPhone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-a-deep-dive-into-sns-hdr-does-it-justify-its-cost/"><u>[Updated] A Deep Dive Into SNS HDR Does It Justify Its Cost?</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-the-complete-guide-to-video-content-creation-for-modern-marketers/"><u>2024 Approved The Complete Guide to Video Content Creation for Modern Marketers</u></a></li>
<li><a href="https://win-blog.techidaily.com/cambie-de-mef-a-imagenes-jpeg-sin-costo-utilizando-la-herramienta-en-linea-de-movavi/"><u>Cambie De MEF a Imagenes JPEG Sin Costo Utilizando La Herramienta en Linea De Movavi</u></a></li>
<li><a href="https://hardware-help.techidaily.com/chronic-headaches-with-neurological-deficits-can-be-associated-with-tumors-strokes-or-demyelinating-diseases-like-multiple-sclerosis/"><u>Chronic Headaches with Neurological Deficits Can Be Associated with Tumors, Strokes, or Demyelinating Diseases Like Multiple Sclerosis</u></a></li>
<li><a href="https://article-files.techidaily.com/chucklechief-easy-meme-design-tool-for-2024/"><u>ChuckleChief Easy Meme Design Tool for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-analysis-reveals-recurring-crash-problems-with-intel-powered-laptop-computers/"><u>Expert Analysis Reveals Recurring Crash Problems with Intel-Powered Laptop Computers</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-download-compatible-drivers-and-setup-software-for-logitech-wireless-mice-on-windows-1087/"><u>Free Download: Compatible Drivers and Setup Software for Logitech Wireless Mice on Windows 10/8/7</u></a></li>
<li><a href="https://win-data.techidaily.com/free-microsoft-surface-cleanup-utility-securely-erase-your-data/"><u>Free Microsoft Surface Cleanup Utility: Securely Erase Your Data</u></a></li>
<li><a href="https://hardware-help.techidaily.com/getting-started-with-your-new-epson-scanner-essential-driver-downloads/"><u>Getting Started with Your New Epson Scanner: Essential Driver Downloads</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-your-logitech-c92e-webcam-driver-for-windows-versions-11-10-and-8/"><u>How to Update Your Logitech C92e Webcam Driver for Windows Versions: 11, 10 and 8</u></a></li>
<li><a href="https://hardware-help.techidaily.com/mastering-gamers-needs-the-definitive-guide-to-choosing-a-high-performance-gaming-cpu/"><u>Mastering Gamers' Needs: The Definitive Guide to Choosing a High-Performance Gaming CPU</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/rediscovering-retro-gaming-identifying-the-most-advanced-gb-console-emulation-programs/"><u>Rediscovering Retro Gaming Identifying the Most Advanced GB Console Emulation Programs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/step-by-step-tutorial-to-install-sound-blaster-z-drivers-on-modern-windows-os/"><u>Step-by-Step Tutorial to Install Sound Blaster Z Drivers on Modern Windows OS</u></a></li>
<li><a href="https://hardware-help.techidaily.com/the-definitive-guide-to-upgrading-your-corsair-gaming-headset-drivers-in-microsoft-windows/"><u>The Definitive Guide to Upgrading Your Corsair Gaming Headset Drivers in Microsoft Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-clarity-of-communication-with-the-midland-gxt1000vp4-transceiver/"><u>Unveiling the Clarity of Communication with the Midland GXT1000VP4 Transceiver</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

