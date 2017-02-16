# ArchCheatSheet
My local Arch Linux Cheat Sheet.

Created in [Zim Desktop Wiki](http://zim-wiki.org/).
You can download the content of this repository, along with Zim, to have a local example of this Cheat Sheet. 
A live example can be found at [sloa.dk](https://sloa.dk/archCheat/Home.html). 

## Good-to-know
This will take you through the steps of getting a stable Arch installation and then further extend the systems functionality.
It is not meant to teach you about the technologies, but rather meant as a reference point to quickly get pointers on installation, configuration and a somewhat loose explanation of the programs usability. 

Having worked in a typical Desktop Environment for many years, I have gotten a little dependent on a lot of typical features you see in such environments. This has been an attempt to mimic what I have come to know as a everyday work environment and somewhere along the way I'm pretty sure the KISS philosophy got lost - so don't expect to much of that. 

This is based on my personal setup on a Asus UX32LN laptop. 
This setup does not necessarily satisfy your needs, and there is no guarantees that the steps will work on your system. 

You might also be interested in my [dotfile repository](https://github.com/Stickano/dotfiles), where my configuration for most of these programs can be found. 

## Included in this Cheat Sheet (16.02.2017)
This sheet has been broken up in 18 major categories (so far at least)
Some of the categories doesn't hold much information, whereas others will take a few hours to go through

* **System Base** <br />
The System Base is what I consider a absolute bare minimum.
  * Arch Installation
  * Network Connectivity (netctl)
  * Sudo privileges
  * Enabling 32bit support
  * Display Server (Xorg)
  * Touchpad
  * Kernels (Zen & lts)
  * Video Driver (Nvidia DKMS, Intel and Bumblebee)
  * AUR Support (Yaourt)
  * i3 Window Manager
* **Extended System Functionality** <br />
This section extends the systems functionality and is still considered pretty basic/minimum.
  * Login (No Display Manager)
  * External Devices (USB/HDD)
  * Display Power Management (Xset)
  * FN-key (Xbindkeys)
  * Bluetooth
  * Sound (PulseAudio)
  * Scheduled Jobs (Cronie)
  * Desktop Notifications (Dunst)
  * Email Notifications (SSMTP)
  * (Additional Packages)
* **Performance Improvements** <br />
Will also reduce the weardown of some hardware components. 
  * Browser Performance (PSD and ASD)
  * Hardware Specific
    * SSD
    * CPU
  * Power Management (laptop)
* **System Tools** <br />
Some tools you will commonly work with - and some not so commonly.
  * Good to know tools
    * Basic tools and General examples
    * ls (Output Explanation)
    * sed
  * Service Manager (Systemd)
  * Package Manager (Pacman)
  * Desktop Entries
  * Mime Types (xdg-utils)
* **Maintenance** <br />
A few pointers on System Maintenance. Some steps will manage themselves, others will need a revisit from time to time.
  * Mirrors (reflector)
  * Pacnew and Pacsave
  * Cleaning the File System (Cache, Orphans, Configurations, Symlinks)
  * Downgrading (Package/Kernel)
* **Users and Groups** <br />
  * User Directories (xdg_user_dirs)
  * Manage Users and Groups
  * Manage Permissions
* **Network Management** <br />
  * netctl
* **Getting Information** <br />
Pointers on where to obtain some vital information.
  * Hardware 
  * Software (Logs, Kernel Modules, Drivers and Applications)
  * Network (mainly ss)
  * System Journal (Journalctl)
* **Terminal and Shell** <br />
We might as well improve the window we'll be spending most our time in
  * Aliases and Functions
  * Zsh and Oh-My-Zsh
  * Urxvt
  * Xresources
  * Gnu Screen
  * Keks and Extras
* **Security** <br />
Some pointers on keeping your system Secure. This will probably not cut it, if you're a high target.
  * Anti Virus (Clamav)
  * Firewall
    * IPtables
    * IPset
    * Fail2Ban
  * Password Manager (KeePass)
  * Security Audit (Lynis)
  * Secure Browsing (Tor)
* **Preferred Software** <br />
We are closing in on that complete system. These are some of my favorite software for everyday tasks.
  * GUI Tools
    * Firefox
    * LibreOffice
  * CLI Tools
    * Text Editor (Vim)
    * File Manager (Ranger)
    * Bookmark Manager (Buku)
    * News
      * Reddit Terminal Viewer
      * Haxor News
    * IRC (Irssi)
    * Video Player (Mplayer)
    * Image Viewer (Feh)
  * And a few random goodies
* **Eye Candy** <br />
Making the system pleasant on the eyes
  * Theming
  * Fonts
  * A few additional eye-gasms
* **Development** <br />
I do a little Web Development, so that is the main focus. 
  * Control (Git)
  * IDE (Sublime)
  * Environment (Apache, MySQL and PHP)
* **Gaming** <br />
Who doesn't like the opportunity, eh?!
  * Steam
* **SSH** <br />
For quick authentication and communication with your server.
  * Server and Client
  * Keys
  * Agent
  * Transfer files via SSH (scp)
* **Cryptography** <br />
We should all try to protect ourself in this modern age.
  * GnuPG
  * Monero Coin (miner)
* **Analysis** <br />
Information is key!
  * Network Scanner (Nmap)
  * Network Packet Monitor (Wireshark)
* **Key Binds** <br />
This is the Throwback section. Here to remind you of some of the wonders your system can do.
  * Navigating the Window Manager (i3 mapping)
  * Text Editor Controls (Vim mapping)
  * Development Controls (Sublime mapping)
  * The Powers in your Terminal
  * Navigating the File Manager (Ranger)
