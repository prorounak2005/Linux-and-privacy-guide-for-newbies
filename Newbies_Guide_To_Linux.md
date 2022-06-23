# Newbies guide to linux

# Table of contents
1. [Introduction](#Introduction)
   1. [What is linux](#What-is-linux)
   2. [Linux Distributions](#Linux-Distributions)
   3. [Desktop Environments](#Desktop-environments)
2. [Installing linux operating system](#Installing-linux-operating-system)
   1. [Installing a distribution](#Installing-a-distribution)
   2. [Prerequisites](#Prerequisites)
   3. [Booting from USB Pendrive](#Booting-from-you-USB-Pendrive)
   4. [Installation](#Installation)
      1. [Partitioning](#Partitioning)

---
## Introduction
This is a guide made for linux newbies. To make them comfortable with linux. You are free to open issue if you have any question regarding this topic.

### What is linux? 
Before installing linux it is always good to know what linux is. If you are not interested about it you can skip this part. 

---

Linux is the [kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)). The linux operating system which we usually use is comprised of [GNU](https://en.wikipedia.org/wiki/GNU)+[LINUX](https://en.wikipedia.org/wiki/Kernel_(operating_system)).
So basically Linux is the kernel whereas the GNU is the extensive collection of free software and thats why many people call it (GNU+LINUX). Here is the link to the copypasta which many people use in linux forums and linux community - https://paste.rs/k0F


#### Linux Distributions 
[Linux Distributions](https://en.wikipedia.org/wiki/Linux_distribution) or linux distros are different operating systems with different collections of
software / [package manager](https://en.wikipedia.org/wiki/Package_manager) / [desktop environment](https://en.wikipedia.org/wiki/Desktop_environment)(which we will cover in the next topic) but all linux distributions have one thing in common. They <strong>use the same [linux kernel](https://en.wikipedia.org/wiki/Kernel_(operating_system)). </strong>. There are many linux distros out there but the ones I recommend are - 

* [Linuxmint](https://linuxmint.com/) - Linux mint was my first linux distro :) I highly recommend you to use this one.
* [Kde neon](https://neon.kde.org/)
* [Kubuntu](https://kubuntu.org/) - Just [ubuntu](https://ubuntu.com/) with Kde desktop environment (ubuntu uses GNOME Desktop environment). See the [Desktop environment](https://gist.github.com/prorounak2005/b4017f48a6b40f0244b7935fa038cc0f#desktop-environments) topic.

#### Desktop environments
[Desktop environments](https://en.wikipedia.org/wiki/Desktop_environment) are graphical user interfaces with their own set of apps (like notepad,calculator file managers). There are many desktop environments in linux, different desktop environment have different [GUIs](https://en.wikipedia.org/wiki/Graphical_user_interface) they also have a different look and feel. 

There are many desktop environments in linux and the most popular ones are - 

* [Kde Plasma](https://kde.org/plasma-desktop/)  {Kde is an international free software community and they made the plasma Desktop environment}
* [Cinnamon](https://linuxmint.com/edition.php?id=292) 
* [Gnome](https://en.wikipedia.org/wiki/GNOME)
* [Xfce](https://en.wikipedia.org/wiki/Xfce)

## Installing linux operating system 
Installing linux operating system is very easy and not that complicated. Many people say that most of the stuff doesn't work on linux, thats really not true but yeah some stuff (like some games, some video editing software) doesn't work on linux. Don't worry because I am going to give you some [free and open source alternatives](https://en.wikipedia.org/wiki/Free_and_open-source_software) to the [proprietary](https://en.wikipedia.org/wiki/Proprietary_software) video editors you often use in windows and trust me these video editors are lot better than the video editors you used in windows. We will discuss it in details in this topic. Nowadays many games like ( Rust, Apex legends, csgo) specially the steam games runs on linux. Many big companies like [Valve](https://en.wikipedia.org/wiki/Valve_Corporation) , [Code Weavers](https://en.wikipedia.org/wiki/CodeWeavers) have made tremendous changes over the past few months, allowing Linux to truly become a viable platform for gaming. Further, more and more indie development teams strive to use cross-platform rendering engines in order to have their game able to compile and run on Linux. You can go to [Proton Db](https://www.protondb.com/) to see which games can run on linux.

### Installing a distribution
First thing you want to do is to choose a linux distribution. Don't worry, installation steps will be same for all linux distributions. In this case I am going to use [Linux Mint](https://linuxmint.com/) you can use other distribtions if you like.

#### Prerequisites

To install linux on you pc you need 

* Download the [.iso](https://en.wikipedia.org/wiki/Optical_disc_image) file from the linux distributions official website. In this case - https://linuxmint.com/download.php ( Make sure to download the cinnamon edition :) )
* You need a Pen drive of at least 4 or 8 gb 
* You have to flash the .iso file of the linux distribution you downloaded to your pendrive ( you have to make a bootable pendrive) for this you have to install a program knows as [Balena etcher](https://www.balena.io/etcher/). I recommend balena because it is available for mac , windows and linux and it is very very simple to use unlike [Rufus](https://rufus.ie/en/) (which you can also use if you want but it is only available for windows).
* When you will install balena etcher and open it, it will look like this - 
       <h2 align="center"> <img src="https://i.imgur.com/0iJF1KJ.png"> </h2> 

* Make sure your pendrive is plugged in and then select the `Flash from file` option. Then select the iso file of the linux distro you downloaded.
* Then click on `Select Target` option and then select your pendrive. 

<strong><bold>❗WARNING: Don't select your hard drive or ssd because doing that will remove everthing from your system including your operating system. Balena etcher already gives us a warning when a user tries to choose any system drives. Make sure to choose your pendrive and not your system drive </bold></strong>
 
 <strong><bold>📜NOTE: Before flashing your pendrive make sure to backup everything on your pendrive as everything in your pendrive will be removed!!</bold></strong>

* Then click on `Flash` and wait for it to complete.

* You have sucessfully installed linux on your pendrive :D 

#### Booting from you USB Pendrive
Now that you have installed linux in a pendrive. To install linux you have to boot from your pendrive but by default your computer will boot from your HDD/SSD. So to boot from your usb temporarily - 

* Reboot your pc 
* When you see the brand of your motherboard / when the computer switches on after shutting down you need to to press a key to acess your boot menu. [Here is the chart](https://www.disk-image.com/faq-bootmenu.htm) which lists the boot menu of different computer brands and laptops. Make sure to press(hold) that button as soon as your computer immediately turns on. 
* Now you will see a boot menu screen. You will be able to see your pendrive name. If you have [UEFI BIOS](https://en.wikipedia.org/wiki/Unified_Extensible_Firmware_Interface) you will see two options. One with "UEFI  <i>your_pendrive_name</i>" and another one will only be your pendrive name. Make sure to choose "UEFI  <i>your_pendrive_name</i>" with up and down arrows and press `ENTER/RETURN` key on your keyboard to boot from it. If you have  [OLD BIOS](https://en.wikipedia.org/wiki/Master_boot_record) you will only see your pendrive name. Make sure to choose that and then press enter. 
* UEFI BIOS uses [GPT](https://en.wikipedia.org/wiki/GUID_Partition_Table) whereas BIOS uses [MBR](https://en.wikipedia.org/wiki/Master_boot_record) to know more about these I recommend you to read this articles - 
  * https://www.maketecheasier.com/differences-between-uefi-and-bios/
  * https://www.maketecheasier.com/differences-between-mbr-and-gpt/
* Now [there will be several options on your screen](https://upload.wikimedia.org/wikipedia/commons/d/df/LM_18_Cinnamon_Bootup_Live_CD.png) make sure to select `Start Linux MInt` option and press enter. 
* Congrats !!!! You now booted into linux mint :D

### Installation 

* Hold on ! You havent installed linux mint yet. It is running through your pendrive so to install linux mint onto your pc (Hard Drive/SSD) you [have to double click on `install linux mint` cd](https://www.how2shout.com/wp-content/uploads/2019/09/Linux-Mint-Live-installation-option.jpg) which is visible on your desktop. Opening it will automatically open the linux mint installer.
* Now A welcome screen will be shown like this - 
<img src="https://i.imgur.com/2Otz2wu.png">

* Select your preffered language and click on `Continue`
* Then choose your keyboard layout. Default is `English (US)` and click on `Continue`
* Tick the checkbox on `Install multimedia codecs` and then click on continue.
---
#### Partitioning
* Now the most important part <strong> Partitioning </strong> - 
<img src="https://i.imgur.com/oPgob4v.png">

* If you have windows or another operating system installed in your pc you will get the option to run windows and linux mint side by side. Basically you boot into both the operating systems if you want. See [Multibooting/Dualbooting](https://en.wikipedia.org/wiki/Multi-booting) for more info. I recommend you to use this one because you should get your feet wet first before jumping into a sea, like I did :) and I am a full time linux user. I don't use windows / mac now. :)
* Second option is  <bold><strong>`Erase disk and install linux mint`</bold></strong> - Self explanatory. It will remove everything including your old operating system.
* <bold><strong>Something else</bold></strong> - If you want to manually partition your disk. See the [Example layouts](https://wiki.archlinux.org/title/Installation_guide#Example_layouts) to get an idea if you want to partition your disk.
  * For people using old bios (LEGACY BIOS) I recommend you to watch this video - https://youtu.be/zuEmhXfBftI (Not the best youtube tutorial ik but still it is ok) 
  *  For people with UEFI BIOS follow these steps -
     * To make efi partition [click on `New partition table` option](https://i.imgur.com/ZpyD3Wx.png)
     * Click on continue
     * [Select the `Free Space`](https://i.imgur.com/fytQXsQ.png)
     * [Click on the plus button below](https://i.imgur.com/WLNOjCB.png)
     * A window will show up
     * Make sure you click the `Primary` button
     * In the Size button make sure to make it to `512 MB` and under the `Use as` option select `EFI` option or something like that and then click on `ok`
     * and then follow the same video https://youtu.be/zuEmhXfBftI
---
* Now select your timezone. Your default timezone will automatically show up. If it doesn't click on the map ( in the region / state where you live) and then click on continue. 
* Type you name ( You can do it yourself :D ) 
* Type your password-

<strong><bold>📜NOTE: Linux is secure because if prompts for a passwrods everytime user tries to install software or do some admin stuff for security reasons. You can click on `Login automatically` option which will log you in automatically but you will still need the password because your pc will prompt for the password when you will try to to admin stuff ( for ex - installing/removing software , editing system files etc etc.) so dont forget the password. </strong></bold>

* Now wait for the system to install everything for you :)
* And then you will prompted with a window where it will ask you to reboot your pc. Reboot it. 
* Congrats! You installed linux. FREEEEEEEEDOOOOOOOOM!! :)
Now you should get a option to boot into linux as well as windows. :) (If you are dualbooting).
