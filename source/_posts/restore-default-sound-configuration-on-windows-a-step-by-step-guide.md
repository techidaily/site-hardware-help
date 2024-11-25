---
title: "Restore Default Sound Configuration on Windows: A Step-by-Step Guide"
date: 2024-11-18T16:13:29.226Z
updated: 2024-11-25T16:34:19.282Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/19c73d13dc30898f49d32d8c5d0e6badbf2d50aea1c634709fd828dcee42d79c.jpg
---

## Securely Erase Sensitive Information From Your Windows PC: A Step-by-Step Guide to Protecting Privacy Without Cost - Insights

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
<li><a href="https://visual-screen-recording.techidaily.com/new-premier-video-call-alternatives-zooms-rivalry-explained-for-2024/"><u>[New] Premier Video Call Alternatives Zoom's Rivalry Explained for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-image-editing-remove-background-in-picsart-guide/"><u>2024 Approved Navigating Image Editing Remove Background in Picsart Guide</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-shape-business-visions-no-money-just-templates/"><u>2024 Approved Shape Business Visions - No Money, Just Templates</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-nokia-c22-frp-bypass-by-drfone-android/"><u>About Nokia C22 FRP Bypass</u></a></li>
<li><a href="https://hardware-help.techidaily.com/brother-mfc-7860dw-driver-download-and-update-in-windows/"><u>Brother MFC-7860DW Driver Download & Update in Windows</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-update-for-scansnap-ix5n-series-drivers-on-windows-operating-system/"><u>Easy Update for ScanSnap iX5n Series Drivers on Windows Operating System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exclusive-review-prime-cars-surveillance-devices/"><u>Exclusive Review Prime Cars Surveillance Devices</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722962132130-get-your-gigabyte-audio-drivers-now-free-offer/"><u>Get Your Gigabyte Audio Drivers Now – FREE Offer</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-effortlessly-obtain-and-implement-your-usb-camera-drivers-now/"><u>How to Effortlessly Obtain & Implement Your USB Camera Drivers Now!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-get-the-latest-ricoh-printer-drivers-installed-on-your-windows-pc/"><u>How To Get The Latest Ricoh Printer Drivers Installed On Your Windows PC</u></a></li>
<li><a href="https://hardware-help.techidaily.com/hp-driver-downloads-made-simple-easy-setup-tutorials-inside/"><u>HP Driver Downloads Made Simple – Easy Setup Tutorials Inside</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlining-youtube-video-transformations-into-mpegs/"><u>In 2024, Streamlining YouTube Video Transformations Into MPEGs</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/kompletter-leitfaden-zum-aufrusten-des-samsung-series-9-ssds-modell-np900x4c/"><u>Kompletter Leitfaden Zum Aufrüsten Des Samsung Series 9 SSDs (Modell NP900x4C)</u></a></li>
<li><a href="https://tech-revival.techidaily.com/revolutionizing-site-discovery-how-machine-learning-is-reshaping-seo-and-web-content-strategies/"><u>Revolutionizing Site Discovery: How Machine Learning Is Reshaping SEO and Web Content Strategies</u></a></li>
<li><a href="https://hardware-help.techidaily.com/rtx-2080-updated-drivers-download-latest-version-compatible-with-win10win7win8/"><u>RTX 2080 Updated Drivers: Download Latest Version Compatible with Win10/Win7/Win8</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/the-ultimate-guide-to-moto-z2s-smart-capabilities-for-2024/"><u>The Ultimate Guide to Moto Z2's Smart Capabilities for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722969907642-update-to-newest-nvidia-drivers-for-windows-10-simple-steps-and-links/"><u>Update to Newest NVIDIA Drivers for Windows 10: Simple Steps & Links!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/upgraded-brother-mfc-7360n-printer-support-effortless-driver-download-and-update-for-all-windows-versions/"><u>Upgraded Brother MFC-7360N Printer Support: Effortless Driver Download and Update for All Windows Versions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/zdnet-unveils-superior-productivity-laptop-for-primes-exclusive-300-discount-not-thinkpad-or-macbook/"><u>ZDNet Unveils Superior Productivity Laptop for Primes - Exclusive $300 Discount! (Not ThinkPad or MacBook)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

