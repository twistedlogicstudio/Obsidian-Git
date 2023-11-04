#DailyNotes  #SORT
- - -
# Notes
## Reselling Vs Dropshipping
[What is the difference between reselling and DropShipping?](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjxhNmY3On_AhUkVmwGHQhMA94QFnoECBsQAw&url=https%3A%2F%2Fwww.avasam.com%2Fwhat-is-the-difference-between-reselling-and-dropshipping%2F%23%3A~%3Atext%3DWhat%2520are%2520resellers%2520and%2520DropShippers%2Cthat%2520they%2520don%27t%2520own.&usg=AOvVaw2N1_4MXxKQcHLWo2V8bY6R&opi=89978449)

[Dropshipping: Does It Actually Work? (Pros + Cons)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjxhNmY3On_AhUkVmwGHQhMA94QFnoECDMQAQ&url=https%3A%2F%2Fwww.bigcommerce.com.au%2Fblog%2Fdropshipping%2F&usg=AOvVaw30ir2LjNYyy2G1veRaCLuY&opi=89978449)

[How To Start a Reselling Business Online + 5 Examples (2023)](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjxhNmY3On_AhUkVmwGHQhMA94QFnoECA8QAQ&url=https%3A%2F%2Fwww.shopify.com%2Fau%2Fblog%2Freseller-business&usg=AOvVaw3vxxBTKUaTNN7PuCsxphQh&opi=89978449)

- - - 

## Pi Screen
[SmartiPi Touch 2 Case | The Pi Hut](https://thepihut.com/products/smartipi-touch-2)

[Official Raspberry Pi 7" Touchscreen Display | The Pi Hut](https://thepihut.com/products/official-raspberry-pi-7-touchscreen-display)

## Random Dump
[100% Offline ChatGPT Alternative? - YouTube](https://www.youtube.com/watch?v=Coj72EzmX20)

[Why I switched from Obsidian to Apple Notes | by Oscar Lagrosen | Medium](https://thetotalliving.medium.com/why-i-switched-from-obsidian-to-apple-notes-5e53088eb879)

[The WaveShare 11.9" HDMI Touch Monitor Is Perfect For Cool DIY Projects! Pi4, WIndows - YouTube](https://www.youtube.com/watch?v=mACXnrMqhFM)

[How I'd Learn Web Development (If I Could Start Over) - YouTube](https://www.youtube.com/watch?v=TG6XSFeOT3g)

## Design Brainstorm
[How Brands Use Design & Marketing to Control Your Mind - YouTube](https://www.youtube.com/watch?v=p6aF5ma7BiM)

## Home NAS
[Using a Raspberry Pi as a NAS macOS Time Machine | JeremyCollins.net](https://www.jeremycollins.net/using-a-raspberry-pi-as-a-nas-mac-os-time-machine)

### Possible Linux / Server Platforms
NETATALK
[Netatalk - Networking Apple Macintosh through Open Source](https://netatalk.sourceforge.io/)
[GitHub - Netatalk/netatalk: Netatalk is a freely-available Open Source AFP fileserver. A UNIX, Linux or BSD system running Netatalk is capable of serving many Macintosh clients simultaneously as an AppleShare file server (AFP)](https://github.com/Netatalk/netatalk)

### Project Send & PWNDROP
[linuxserver/projectsend - Docker Image | Docker Hub](https://hub.docker.com/r/linuxserver/projectsend)
[GitHub - linuxserver/docker-pwndrop](https://github.com/linuxserver/docker-pwndrop)

**SFTPGo**
[GitHub - drakkan/sftpgo: Fully featured and highly configurable SFTP server with optional HTTP/S, FTP/S and WebDAV support - S3, Google Cloud Storage, Azure Blob](https://github.com/drakkan/sftpgo)

**NAS Setup** 
[How to make a Raspberry Pi NAS - A NAS-Berry that Runs Open Media Vault - Tutorial Australia](https://core-electronics.com.au/guides/how-to-raspberry-pi-nas/)

[ProjectSend Installed in Docker - File Hosting & Sharing - YouTube](https://www.youtube.com/watch?v=ohkpCf9DrCI)

- - -


## NextCloud
[**How to create your own personal cloud with Nextcloud on a Raspberry Pi 2021**](https://youtube.com/watch?v=yJBM9of4KBQ&feature=share)

## Full System Reset
![[../../4. Archives/Media/Images/Banner Random.webp|Banner Random.webp]]

While you are on Uni Break, you have a little more time than you normally do to get the things you need to organised. Here’s the full outline of everything you need to do.

### Why?
You messed around and low-key fucked up your system by both:
- Installing the MacOS Beta onto your main Drive
- Loading the system up with a whole bunch of cracked software

Both these things lead a major screwup in the system, from a whole bunch of VST’s not working, to losing a bunch of work, as well as a complete slow-down of the system from loading up a multitude of unneeded bloatware.

So to maintain a good working system speed & optimal performance especially when doing anything music related, I need to do:

- [ ] A full clean install of the laptop
- [ ] Install only the necessary software (definitely refrain from cracked plugins from now on)
- [ ] Have a proper backup system for both Time Machine & your files / work
- [ ] Build a bootable USB / SSD Drive of MacOS - Mainly for future times where I’d want to try out some Beta software
- [ ] Have a proper File / Folder structure - as well as a proper system where you archive things you aren’t currently using etc.

### System Backup / NAS Setup
Will have another note explaining the full protocol for backing up your files, projects, media etc located here. Backup Protocol

Main idea here though is to mainly setting up the NAS (in what configuration is yet to be decided) so that I can fully backup all possible files, as well as setup Time Machine snapshots incase things don’t work out.

- Once this is done - **you can cancel your Google One Subscription!** 

**Remember:**
To check the speed of how the NAS Works over both LAN & USB. This will inform where you’ll be setting up the NAS Enclosure (If USB is faster - Near Desk / If LAN is faster - Near Router)

- A good thing to test out as well is how different the speed is for each Router (Main / Access Point)

While this is all going, remember to setup the Homebridge system as well. Links below:

### NAS Drive Structure
[DiskStation® DS923+ | Synology Inc.](https://www.synology.com/en-us/products/DS923+)
![[../../4. Archives/Media/Images/DS923+.png|DS923+.png]]

The Setup for the NAS will have the 2x SATA SSD’s that I already have slotted into the first 2 bays. These drives will mainly be used for Audio & Music Production projects, as they have the fastest read/write speeds.

The next drive will be used for backup & archiving purposes, where a large NAS HDD drive (probably 4TB) will be attached. Depending on how this does in terms of space, the last drive might either be used for a second NAS HDD backup drive, or another speedier SSD drive.
![[../../4. Archives/Media/Images/NAS unit annotations.png|NAS unit annotations.png]]

Further down the line, the 10Gigabit Ethernet extension card can be added, but before this is done (purchased) more research is needed, where the use cases, and what the best/most applicable application in the setup might be.

The external USB 3.1 port might also be a good way to connect the NAS to the computer desk system.

[Need some clarifications on 10GBPS speed : synology](https://www.reddit.com/r/synology/comments/108ryx1/need_some_clarifications_on_10gbps_speed/)

![[../../4. Archives/Media/Images/NAS_backpanel_03@2x.png|NAS_backpanel_03@2x.png]]

2x M.2 SSD Drives can also be attached, if & when this is attached, they will then become the main drives used for Audio, Music, Video & Graphic production. If this does become the case, the SSD’s will then become the Archive & Backup drives for media, assets, etc.

### ApplicationReintegration
After the initial backup _system_ is setup & implemented, start the backup process (this will probably take a while) then go through and note down all of the things that you want to carry over into the new system / re-install.

The shortlist (one you should be adding to) located here.

**Apps & Others**
- Obsidian - Only if the document migration hasn’t been finished yet

**Audio / Video & Graphic**
- VST’s
- Fab Filter Plugins
- Clean shot X

**Maybe Install (Yet to Decide)**

- Sleeve for Spotify
- Chronicle Finance ?
- Debit & Credit Finance ?
- Dbpoweramp
- Draw.io - or equivalent
- Minimeters 
- Loopback 
- Soundsource 
- Permute maybe
- Mos for smooth scrolling
- Final Cut Pro - maybe
- Mullvad browser
- Popclip 
- Tor browser

**Safari Web Apps**

When MacOS Sonoma is installed, the Safari App has a new Web App feature. Add certain websites as Web Apps, put them into a folder and link that folder in the Dock. Here are some of the websites where you could as Web Apps: 

- Google Drive
- Synology DSM
- Other Streaming Apps
- Homebridge (either through DSM or Mac, whichever one you end up using)
- Coles Online ?
- My Fines
- Banking Apps (ANZ / ING / UBANK)
- Instructables
- SAE Dashboard
- TLA - Homepage
- Squarespace

### MacOS Sonoma Beta (External SSD)
Once we have another M.2 external SSD (& its enclosure) have it as a seperate Bootable Drive - install the new MacOS Sonoma Beta on there. 

Maybe partition the drive in 2 - so that you can still use the other half as a drive for other files etc. Or keep this drive purely as a bootable - where you can have all of your pirate / cracked software, that way it can be seperate to the main computer & drive - hopefully not weighing everything down like it has the last time.

Might be worth it checking if there’s a way to migrate the system (from your partition) onto the drive.

[How To Install MacOS Sonoma On External Drive](https://www.androidphonesoft.com/blog/how-to-install-macos-sonoma-on-external-drive/)
[How to create a bootable USB installer for macOS Sonoma](https://www.idownloadblog.com/2023/06/08/how-to-create-bootable-usb-installer-macos-sonoma/)
[How To Create a macOS Sonoma Beta USB Boot Disk in 5 Minutes! - YouTube](https://www.youtube.com/watch?v=01ozJX9bCoQ)

### Folder & File Structure
Before you fully go into the Full System Reset, you should figure out a good folder / file structure, from how you keep all of your project files, as well as your Archives & backup systems, etc.

[Adding 10GbE To MacBook Pro And Simplifying - Bits and Bytes - Audiophile Style](https://audiophilestyle.com/ca/bits-and-bytes/adding-10gbe-to-macbook-pro-and-simplifying-r1174/)

- - -


## TAGS
[finder tag - Tags - best practice for using tags to replace hierarchical folder structure - Ask Different](https://apple.stackexchange.com/questions/251139/tags-best-practice-for-using-tags-to-replace-hierarchical-folder-structure)

## NOOKI Names
**Mixtape / Beat-Tape / Album Names**
Examination Tapes
Specimens Vol.#
Experiment Tapes 

**Artist Names**
LABRAT
2TONE
2TONNE
HALF TIME

## Crooked Concepts
### **What Is It?**
The main idea behind Crooked Concepts is to start a little indie clothing label thing, to learn some things about the industry, marketing, types of production like screen printing ect. 

To also have a new avenue to use some of your creative juices as well as hopefully have another revenue stream.

### **Ideals Behind The Brand**
- Think about the main idea / concept / message behind the brand, the things you stand for, as well as some of the goals you want to achieve through this.

### **Style & Aesthetic**

### Research & Brainstorming
[Here's Everything You Need To Start Screen Printing? - YouTube](https://www.youtube.com/watch?v=7FGAdSk3Nh8)
[SCREEN PRINTING Multi Color Designs! Tips & Tricks Exposed! - YouTube](https://www.youtube.com/watch?v=oyh6aE61yVQ)
[How To Screen Print For Dummies Step By Step!](https://www.youtube.com/watch?v=Fa3jnIh8_vk)



- - -
## Learn Melodyne
[Melodyne in Pro Tools mit ARA](https://helpcenter.celemony.com/M5/doc/melodyneEssential5/de/M5tour_ProTools_ARA_IntroHub?lang=en&env=live)

## Ultimate Portfolio Brainstorm
**Info Dump**
Sick UX (User Experience)
Learn how to code
Learn a bit more about design

## Ferro-fluid Project
- Watch Veritasium YT Vid - Strongest Magnet
- Somehow convert magnetism XY config & somehow use Ferro-fluid to visualise

## Dumped From Apple Notes - Needs Sorting
- To figure out the best way to save research / best way to do reading list - safari
- Check out - SSL Plugin / God Particle Plugin
- Figure out how to use fleeting notes extension
- Make instagram reels for your beats!!! Find slo mi aesthetic videos - caption shit like - tag someone who’d kill this beat
- 
![[Attachment.jpeg|Attachment.jpeg]]

![[../../4. Archives/Media/Images/Ideas Dump.png|Ideas Dump.png]]


- - -

![[../../4. Archives/Media/Images/Brain Dump Notes 1.png|Brain Dump Notes 1.png]]


- - -

# Brain Dump SORT

## Twisted Logic Audio
- Write up the product / company - **MISSION STATEMENT**
- Clothing Brand Ideas - 4th Eye Apparel / piss take of ‘3rd eye’

## **Dakota Johnson Cold Call**
Off of Cha Cha Real Smooth

Best quote from movie - selling your time is insane

From that sell the idea that you want to sell you time right, quit the bartending job you’re at and shoot your shot to the ether.

- - -
# Quick Meeting Notes - Tegan
- Get your plan sorted & sussed out first 
- Get someone to do the first prototype 
- Get the trademarking sorted out

- Find someone that’s like 4th year lawyer - maybe they can help you sort out your trademarking for free / low cost

- Once these things done, get shot ready to pitch the idea.

Now remember what he was saying about why to do each of the steps

- - -
# Paid Font Ideas
[Lufga Font Family | Sans Serif Fonts ~ Creative Market](https://creativemarket.com/AdamLadd/5634020-Lufga-Font-Family#fullscreen)
[Captura Now Core Edition | Sans Serif Fonts ~ Creative Market](https://creativemarket.com/TypeThisStudio/10849130-Captura-Now-Core-Edition)
[Visby CF Geometric Sans Font ver.4 | Sans Serif Fonts ~ Creative Market](https://creativemarket.com/connary/184499-Visby-CF-Geometric-Sans-Font-ver.4)
[Biennale | Sans Serif Fonts ~ Creative Market](https://creativemarket.com/Latinotype/4452865-Biennale)
[Dallas | A Vintage Sans | Sans Serif Fonts ~ Creative Market](https://creativemarket.com/jenwagnerco/2423920-Dallas-A-Vintage-Sans)

- - -
# Cody Cork - Random Note
- When learning new thing or skill, should try making it a challenge - w/ hours 
- Track challenge through hours / what can I do after learning this new skill for 100 hours.

Hit up Keeley maybe for some references or ideas for audio work

_Check out music video -_ Klungs - clap your hands

## Reading / Research
[The Producer's Guide to File & Sample Organization - EDMProd](https://www.edmprod.com/file-sample-organization/)
[5 Tips To Create An Organized File Structure Like A Pro](https://www.extensis.com/blog/5-tips-for-setting-up-an-organized-folder-structure-like-a-pro)

- - -
# Apps to Get
[Mixed In Key: Software for DJs and Music Producers - Mixed In Key](https://mixedinkey.com/)
[dBpoweramp Music Converter & CD Ripper](https://secure.dbpoweramp.com/store_combi.aspx?c=9)
[Rogue Amoeba | Purchase Loopback](https://rogueamoeba.com/loopback/buy.php)
[Rogue Amoeba | Purchase SoundSource](https://rogueamoeba.com/soundsource/buy.php)
[CleanShot X – Buy a new license](https://cleanshot.com/buy)

- - -
# Project Ideas
## Hackintosh
[GUIDE - How to Install macOS Ventura on PC [Intel/AMD] | EliteMacx86 Forum](https://elitemacx86.com/threads/how-to-install-macos-ventura-on-pc-intel-amd.920/)
[**Hackintosh Instructions, Hackintosh How To Guides: Hackintosh.com**](https://hackintosh.com/)

- - -
# Shopping
## Keyboard Shit
[[Keychron K2] My second mod. Nordic DSA keycaps by KBDFans : r/MechanicalKeyboards](https://www.reddit.com/r/MechanicalKeyboards/comments/fecam9/keychron_k2_my_second_mod_nordic_dsa_keycaps_by/)
[keychron k2 DSA keycaps - Google Search](https://www.google.com/search?client=safari&rls=en&q=keychron+k2+DSA+keycaps&ie=UTF-8&oe=UTF-8)

## YUBIKEY - Touch ID
[Which YubiKey is right for you | Quiz | Yubico](https://www.yubico.com/quiz/)

## Altronics & Smart Home
[Silicon Chip Magazine LED Musicolour Light Controller Kit - Altronics](https://www.altronics.com.au/p/k5804-led-musicolour-light-controller-kit/)
[Zip-Rack 1U 12 Way 'D' Series Connector 19" Patch Rack Panel - Altronics](https://www.altronics.com.au/p/h5171-1u-xlr-12-way-patch-panel-19-inch-rack-panel/)
[4 Megapixel Fish Eye Lens Wi-Fi IP PoE Dome Camera - Altronics](https://www.altronics.com.au/p/s9109-4-megapixel-wi-fi-dome-camera-fish-eye-lens-with-poe/)
[7” LCD 800 x 480 HDMI Touchscreen For Raspberry Pi - Altronics](https://www.altronics.com.au/p/z6514-7-inches-lcd-touchscreen-800x480-for-raspberry-pi/)
- Raspberry Pi Cameras - use these to build cheap Smart Home Cameras
[Buy Kogan SmarterHome™ TV LED Back Light with HDMI Sync Box Online | Kogan.com. .](https://www.kogan.com/au/buy/kogan-smarterhome-tv-led-back-light-with-hdmi-sync-box/)
[Flic 2 Smart Button | Shop Flic 2, Flic Hub, and Flic Accessories here](https://flic.io/shop)
[Arlec Grid Connect Smart Home Button - Bunnings Australia](https://www.bunnings.com.au/arlec-grid-connect-smart-home-button_p0434998)

## Studio & Rack Mount Gear
[Karyn Wooden Hallway Console Hall Table W/ 1-Door - Walnut - Bunnings Australia](https://www.bunnings.com.au/karyn-wooden-hallway-console-hall-table-w-1-door-walnut_p0492737)
[Designer Cabinet Bench Storage Organiser Wooden - Walnut - Bunnings Australia](https://www.bunnings.com.au/designer-cabinet-bench-storage-organiser-wooden-walnut_p0436169)
[Neutrik NZP1RU-12 PANEL 1RU D-Shape Housing - Koala Audio](https://koalaaudio.com.au/collections/rack-accessories/products/neutrik-nu-nzp1ru-12-panel-1ru-d-shape-housing?variant=39870077698117)
[Penn Elcom 4U Rack Mount Wall Bracket With Hinged Rack Rail R2520-4U - Koala Audio](https://koalaaudio.com.au/collections/rack-accessories/products/penn-elcom-4u-rack-mount-wall-bracket-with-hinged-rack-rail-r2520-4u?variant=40016069656645)
[KALLAX Shelving unit with 4 inserts, white, 77x147 cm - IKEA](https://www.ikea.com/au/en/p/kallax-shelving-unit-with-4-inserts-white-s39278308/)
[Zip-Rack 1U 12 Way 'D' Series Connector 19" Patch Rack Panel - Altronics](https://www.altronics.com.au/p/h5171-1u-xlr-12-way-patch-panel-19-inch-rack-panel/)
[Zip-Rack 1U Black Steel 19" Rack Panel - Altronics](https://www.altronics.com.au/p/h5141a-1u-black-steel-19-inch-rack-panel/)
[Zip-Rack 19" 1U Brush Cable Entry Rack Panel - Altronics](https://www.altronics.com.au/p/h5179-19-inch-1u-rack-panel-with-brush-cable-entry/)
[Zip-Rack 19" 1U Brush Cable Snap In Rack Panel - Altronics](https://www.altronics.com.au/p/h5177-19-inch-1u-brush-cable-snap-in-rack-panel/#/)
[Serveredge 8 Port Switched PDU (8) IEC C13 Output & (1) IEC C14 Input 10A 240V | PLE Computers](https://www.ple.com.au/Products/622288/serveredge-8-port-switched-pdu-8-iec-c13-output-1-iec-c14-input-10a-240v)

- - -
# Coding & RPi
[Responsive Portfolio Website From Scratch - YouTube](https://www.youtube.com/watch?v=ldwlOzRvYOU)
[How to Use the Linux Shell/Terminal for Raspberry Pi | Linux | Maker Pro](https://maker.pro/linux/tutorial/how-to-use-linux-shell-terminal-for-raspberry-pi)
[Use a Raspberry Pi 4 for Time Machine Backups (works with macOS 13 Ventura) | by Sascha Eggenberger | Medium](https://saschaeggi.medium.com/use-a-raspberry-pi-4-for-time-machine-works-with-big-sur-1e66a9650789)
[The 25 Best Raspberry Pi Pico Projects of 2023 | All3DP](https://all3dp.com/2/raspberry-pi-pico-projects/)
[Mandelbrot Set on Pi Pico / ILI9341 : 4 Steps (with Pictures) - Instructables](https://www.instructables.com/Mandelbrot-Set-on-Pi-Pico-ILI9341/)
[PicoLight - Minimalist Light for Product Shots | Hackaday.io](https://hackaday.io/project/182069-picolight-minimalist-light-for-product-shots)
[Raspberry Pi Pico Matrix Touchscreen Keyboard : 8 Steps (with Pictures) - Instructables](https://www.instructables.com/Raspberry-Pi-Pico-Matrix-Touchscreen-Keyboard/
[Low-Power IoT Intruder Detector with RPi4 + Pico - Hackster.io](https://www.hackster.io/spartacoos/low-power-iot-intruder-detector-with-rpi4-pico-4c37a9)
[DIY Multifunctional control knob using Pi Pico - YouTube](https://www.youtube.com/watch?v=M6K8vwzZrYs)
[Raspberry Pico Macro Pad by sepro - Thingiverse](https://www.thingiverse.com/thing:4816077)
[Beginner Projects for Raspberry Pi Pico : 6 Steps - Instructables](https://www.instructables.com/Beginner-Projects-for-Raspberry-Pi-Pico/)
[nixos-apple-silicon/docs/uefi-standalone.md at main · tpwrules/nixos-apple-silicon · GitHub](https://github.com/tpwrules/nixos-apple-silicon/blob/main/docs/uefi-standalone.md)
[HELP: MX Live-Usb Maker – MX Linux](https://mxlinux.org/wiki/help-files/help-mx-live-usb-maker/)
[Download Nix / NixOS | Nix & NixOS](https://nixos.org/download.html#nix-install-docker)
[Use a Raspberry Pi 4 for Time Machine Backups (works with macOS 13 Ventura) | by Sascha Eggenberger | Medium](https://saschaeggi.medium.com/use-a-raspberry-pi-4-for-time-machine-works-with-big-sur-1e66a9650789)
[RaspberryPi Home NAS for both Mac & PC! Tutorial + Speed Test! | 4K TUTORIAL - YouTube](https://www.youtube.com/watch?v=Ff96FPJHq5o)

- - -
# Raycast Search
[Raycast Manual](https://manual.raycast.com/)
[GitHub - raycast/script-commands: Script Commands let you tailor Raycast to your needs. Think of them as little productivity boosts throughout your day.](https://github.com/raycast/script-commands)

- - -
# Notes Dump Cont.
![[../../4. Archives/Media/Images/Random Note 2.png|Random Note 2.png]]

- - -
![[../../4. Archives/Media/Images/Random Note.png|Random Note.png]]


- - -
![[../../4. Archives/Media/Images/Thoughts - Notes.png|Thoughts - Notes.png]]

- - -
![[../../4. Archives/Media/Images/Twisted Logic MIDI Con Note.png|Twisted Logic MIDI Con Note.png]]


- - -
![[../../4. Archives/Media/Images/Habit Tracker Random Note.png|Habit Tracker Random Note.png]]


- - -


# TLA Dump
