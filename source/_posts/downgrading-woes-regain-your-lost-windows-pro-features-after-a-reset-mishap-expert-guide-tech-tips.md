---
title: "Downgrading Woes: Regain Your Lost Windows Pro Features After a Reset Mishap - Expert Guide Tech Tips"
date: 2024-11-13T00:38:50.600Z
updated: 2024-11-16T00:03:53.094Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b8fca16a34b5411c86475482e61fa021f5aeb02943a66dd5dba0e650f0e39da1.jpg
---

## Protecting Your Privacy: Expert Tips on Completely Wiping a Windows Computer Without Spending - Free Advice

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
<li><a href="https://visual-screen-recording.techidaily.com/new-how-to-blur-background-in-zoom-with-ease-an-ultimate-guide/"><u>[New] How to Blur Background in Zoom with Ease An Ultimate Guide</u></a></li>
<li><a href="https://article-files.techidaily.com/new-professional-advice-how-to-attach-srt-to-video-media-2024/"><u>[New] Professional Advice How to Attach SRT to Video Media 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/6-proven-ways-to-unlock-realme-11-proplus-phone-when-you-forget-the-password-by-drfone-android/"><u>6 Proven Ways to Unlock Realme 11 Pro+ Phone When You Forget the Password</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723262282456-amd-ryzen-5-7600x-available-at-just-174-on-newegg-limited-time-offer/"><u>AMD Ryzen 5 7600X Available At Just $174 On Newegg - Limited Time Offer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/comprehensive-analysis-of-amds-zen-5-architecture-ryzen-9000-series-and-ai-300-performance-with-insights-on-rdna-35-gpu-and-xdna-evolution/"><u>Comprehensive Analysis of AMD's Zen 5 Architecture: Ryzen 9000 Series & AI 300 Performance with Insights on RDNA 3.5 GPU & XDNA Evolution</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-updated-brother-hl-2240-driver-now-perfect-for-windows-users/"><u>Download Updated Brother HL-2ˈ240 Driver Now: Perfect for Windows Users</u></a></li>
<li><a href="https://hardware-help.techidaily.com/enhance-your-gaming-obtain-official-rtx-2060-super-drivers-for-windows-11/"><u>Enhance Your Gaming: Obtain Official RTX 2060 Super Drivers for Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/expert-evaluations-with-tom-comprehensive-hardware-guides/"><u>Expert Evaluations with Tom - Comprehensive Hardware Guides</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/from-buffer-to-broadcast-learn-how-to-convert-your-youtube-viewing-into-a-screenshot-for-free-for-2024/"><u>From Buffer to Broadcast Learn How to Convert Your YouTube Viewing Into a Screenshot for Free. For 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/intel-hit-by-criticism-as-game-publisher-reports-total-system-failures-on-latest-gen-cpus/"><u>Intel Hit by Criticism as Game Publisher Reports Total System Failures on Latest-Gen CPUs</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722969603490-speedy-and-simple-asus-z1710-pro-graphics-card-drivers-download-guide/"><u>Speedy and Simple ASUS Z17지10 Pro Graphics Card Drivers Download Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-guide-capturing-screenshots-on-your-hp-laptop/"><u>Step-by-Step Guide: Capturing Screenshots on Your HP Laptop</u></a></li>
<li><a href="https://win-able.techidaily.com/step-by-step-instructions-for-recording-screenshots-with-sound-on-microsofts-latest-operating-systems/"><u>Step-by-Step Instructions for Recording Screenshots with Sound on Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1723262312779-the-new-intel-kingpin-core-i7-14700k-shines-with-a-7-single-core-supremacy-over-competitor-core-ultra-7-arrow-lake-chip-dominates-benchmarks/"><u>The New Intel Kingpin: Core I7-14700K Shines with a 7% Single-Core Supremacy over Competitor Core Ultra 7 - Arrow Lake Chip Dominates Benchmarks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/troubleshooting-windows-11-fixing-common-bluetooth-driver-problems/"><u>Troubleshooting Windows 11: Fixing Common Bluetooth Driver Problems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleash-the-power-of-chatgpt-in-your-excel-workflows/"><u>Unleash the Power of ChatGPT in Your Excel Workflows</u></a></li>
<li><a href="https://games-able.techidaily.com/unlocking-peak-performance-in-online-gaming-intels-role/"><u>Unlocking Peak Performance in Online Gaming - Intel's Role</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

