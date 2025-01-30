---
title: "How to Securely Erase All Personal Information From Your Windows Laptop: A Step-by-Step Guide, Completely Gratis"
date: 2025-01-27T18:38:46.196Z
updated: 2025-01-30T18:27:20.419Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c5954b26aae847d226df8714f23c02a4ef32990ac98d6db24e45432fb84625b4.png
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
<li><a href="https://youtube-tips.techidaily.com/n-2024-stand-out-on-youtube-logo-tips-for-visibility/"><u>[New] In 2024, Stand Out on YouTube Logo Tips for Visibility</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-amusement-ringers-curated-list-of-comical-downloads/"><u>[Updated] 2024 Approved Amusement Ringers Curated List of Comical Downloads</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-a-comprehensive-guide-to-smoothly-flip-movies-in-vlc-for-2024/"><u>[Updated] A Comprehensive Guide to Smoothly Flip Movies in VLC for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/clarifying-misinformation-the-non-existence-of-official-chatgpt-for-windows-and-its-rogue-counterparts/"><u>Clarifying Misinformation: The Non-Existence of Official ChatGPT for Windows, and Its Rogue Counterparts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dell-sm-bus-controller-software-enhancement-tips-and-procedures/"><u>Dell SM Bus Controller Software Enhancement Tips and Procedures</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722976511329-download-and-update-free-wi-fi-drivers-compatible-with-windows-7-simple-steps/"><u>Download & Update: Free Wi-Fi Drivers Compatible with Windows 7 - Simple Steps</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-instantly-ultimate-usb-webcam-drivers-get-set-up-fast/"><u>Download Instantly: Ultimate USB Webcam Drivers - Get Set Up Fast</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722958692600-get-your-canon-mx49n-printer-up-to-date-with-new-windows-drivers-here/"><u>Get Your Canon MX49n Printer Up-to-Date with New Windows Drivers Here</u></a></li>
<li><a href="https://win11.techidaily.com/getting-icloud-running-effortlessly-on-your-windows-machine/"><u>Getting iCloud Running Effortlessly on Your Window's Machine</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-seamlessly-update-standard-sataahci-driver-software-quickly/"><u>How to Seamlessly Update Standard SATA/AHCI Driver Software Quickly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-reset-your-vivo-v27-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Vivo V27 Lock Screen Password</u></a></li>
<li><a href="https://tech-hub.techidaily.com/is-it-time-to-switch-analyzing-performance-differences-between-m3-and-m1-macbook-pro-models/"><u>Is It Time to Switch? Analyzing Performance Differences Between M3 & M1 MacBook Pro Models</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-hp-audio-driver-updates-available-at-no-cost-download-now/"><u>Quick HP Audio Driver Updates Available at No Cost – Download Now!</u></a></li>
<li><a href="https://fox-tips.techidaily.com/reinstalling-network-adapter-drivers-on-windows-10-a-step-by-step-guide/"><u>Reinstalling Network Adapter Drivers on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/resolved-windows-11-now-comes-with-built-in-printer-and-scanner-support/"><u>Resolved: Windows 11 Now Comes With Built-In Printer And Scanner Support</u></a></li>
<li><a href="https://win-solutions.techidaily.com/top-strategies-for-preventing-alan-wake-2-game-crashes/"><u>Top Strategies for Preventing Alan Wake 2 Game Crashes</u></a></li>
<li><a href="https://facebook.techidaily.com/unlocking-facebooks-potential-for-work-related-client-expansion/"><u>Unlocking Facebook's Potential for Work-Related Client Expansion</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-and-install-hp-elitebook-8460p-drivers-on-windows-a-step-by-step-guide/"><u>Update and Install HP EliteBook 8460P Drivers on Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-help.techidaily.com/updating-your-toshiba-satellite-easy-guide-to-fresh-graphic-drivers-on-windows-pcs/"><u>Updating Your Toshiba Satellite: Easy Guide to Fresh Graphic Drivers on Windows PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

