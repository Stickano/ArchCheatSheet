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

## Included in this Cheat Sheet (20.02.2017)
This sheet has been broken up in 18 major categories (so far at least).
Some of the categories doesn't hold much information, whereas others will take a few hours to go through.
Below you will find a rough overview of the configuration steps and additional packages.

* [**System Base**](#system-base) <br />
  * Arch Installation
  * Network Connectivity 
  * Sudo 
  * Enabling 32bit Support
  * Display Server 
  * Touchpad
  * Kernels 
  * Video Driver 
  * AUR Support 
  * Window Manager
* [**Extended System Functionality**](#extended-system-functionality) <br />
  * Login 
  * External Devices 
  * Display Power Management 
  * Keyboard
  * Bluetooth
  * Sound 
  * Scheduled Jobs 
  * Email Notifications 
  * Desktop Notifications
  * Additional Packages
* [**Performance Improvements**](#performance-improvements) <br />
  * Browser Performance 
  * Hardware Specific
    * SSD
    * CPU
    * Laptop
* [**System Tools**](#system-tools) <br />
  * Good to know tools
    * Basic Tools and General Examples
    * ls 
    * sed
  * Service Manager 
  * Package Manager 
  * Desktop Entries
  * Mime Types 
* [**Network Management**](#network-management) <br />
  * Netctl
* [**Users and Groups**](#users-and-groups) <br />
  * User Directories 
  * Manage Users and Groups
  * Manage Permissions
* [**Maintenance**](#maintenance) <br />
  * Mirrors 
  * Pacnew and Pacsave
  * Cleaning the File System 
  * Downgrade
* [**Getting Information**](#getting-information) <br />
  * Hardware 
  * Software 
  * Network 
  * Journalctl
* [**Terminal and Shell**](#terminal-and-shell) <br />
  * Aliases and Functions
  * Zsh and Oh-My-Zsh
  * Urxvt
  * Xresources
  * Wrapper
  * Keks and Extras
* [**Security**](#security) <br />
  * Anti Virus 
  * Firewall
    * IPtables
    * IPset
    * Fail2Ban
  * Password Manager 
  * Security Audit 
  * Secure Browsing
* [**Preferred Software**](#preffered-software) <br />
  * GUI Tools
    * Web Browser
    * Office Suite
  * CLI Tools
    * Text Editor 
    * File Manager
    * Bookmark Manager
    * News
    * IRC 
    * Video Player
    * Image Viewer
  * And a few random goodies
* [**Eye Candy**](#eye-candy) <br />
  * Theming
  * Fonts
  * A few additional eye-gasms
* [**Development**](#development) <br />
  * Control 
  * IDE 
  * LAMP
  * Design
* [**Gaming**](#gaming) <br />
  * Steam
  * Game Specific Troubleshoots
* [**SSH**](#ssh) <br />
  * Server and Client
  * Keys
  * Agent
  * Transfer via SSH
* [**Cryptography**](#cryptography) <br />
  * GPG
  * Currency 
* [**Analysis**](#analysis) <br />
  * Network
    * Nmap
    * WireShark 
* [**Key Binds**](#key-binds) <br />
  * Window Manager 
  * Text Editor
  * IDE
  * The Powers in your Terminal
  * File Manager

<br /><br />
## System Base
**The System Base is what I consider a absolute bare minimum.**

#### Arch Installation
  * On UEFI/GPT

#### Network Connectivity

#### Creating a new User

#### Sudo
  * Granting sudo rights to our newly created user
  * Running X-applications as sudo
  * Tips and Tricks
  
#### Enable 32bit support

#### Display Server
  * Xorg
    * Securing
    * Autostart Applications

#### Touchpad
Touchpad worked mad out of the box - it will be configured early

#### Kernels
  * Zen
  * Long Time Support
  
#### DKMS
  * Nvidia Driver

#### Display Driver
  * Intel HD (mesa)
  * Nvidia Utilities
  * Bumblebee
  
#### AUR Support
  * Yaourt
    * Configuration
    * Usage
    
#### Window Manager
  * i3
    * Configuration
    * Save and Load workspace layouts
    * Additional Packages
      * Rofi
      * Polkit
      * Polkit-gnome
      * xss-lock
      * Imagemagick
      * Scrot
      * lm_sensors
      * acpi
      * sysstat
      * i3block
      * Font Awesome
      * i3-gaps
   
<br /><br />    
## Extended System Functionality
This section extends the systems functionality and is still considered pretty basic/minimum.

#### Login 
  * No Display Manager is Used
    * Welcome Message
    * Tips and Tricks
      * Auto Login

#### External Devices 
  * Auto mount external devices
  * NTFS and FAT support
  
#### Display Power Management
  * Xset
    * Usage
  
#### Keyboard
  * Fn-Key
    * Screen Backlight Control
    * Xbindkeys
      * Volume Control
      * Keyboard Backlight Control
      * Toggle Touchpad
    
#### Bluetooth
  * Bluez
    * Usage
    * Troubleshoot
  
#### Sound
  * PulseAudio
    * Default Device
    * Additional Packages
      * PavuControl
      * PulseAudio-ctl
        * Usage
    * Bluetooth Speaker
      * Tips and Tricks
        * Auto Connect

#### Scheduled Jobs
  * Cronie
    * Usage
    * Examples
  
#### Email Notifications
  * SSMTP
    * Configuration
    * Usage
  
#### Desktop Notifications
  * Dunst
    * Usage
    * Creating Notifications

#### Additional Useful Software
  * Clipboard Manager
    * Xclip

<br /><br />
## Performance Improvements
Reducing weardown and improving the system in general.

#### Browser Performance
  * \[Profile/Anything\]-sync-daemon
    * Configuration
  
#### SSD
  * HDparm
    * Configuration
  * I/O Top
  * Smartmontools
    * Usage
    * Monitor Daemon
      * Email Notification
  * TRIM
  * FStab atime
  * Swappiness
  * Zswap

#### CPU
  * Thermald
  * i7z
  * Cpu Power (Frequency Scaling)

#### Laptop
  * Power Management
    * Powertop
    * TLP
      * Usage
  * Disable Power/Suspend/Hibernate buttons

<br /><br />
## System Tools
Some tools you will commonly work with - and some not so commonly.

#### Basic Tools and General Examples
  * Locate (mlocate)
  * Htop
  * Creating Bootable USBs
    * dd
  * Symlinks
  * Tail
  * Wget

#### ls
  * Output Explained

#### sed
  * Various Examples

#### Service Manager
  * Systemd
    * Usage

#### Package Manager
  * Pacman
    * Configuration
    * Usage
    * Unofficial Keys
    * Tips and Tricks
    * Hooks
      * Writing Hooks
      * Useful Hooks
    * Troubleshoot

#### Desktop Entries
  * Manage Entries
  * Writing Entries

#### Kernel Modules
  * Obtaining Information
  * Manual Handling
  * Handling at Boot
    * Loading 
    * Setting Options
    * Blacklisting
  * Tainted Kernel

#### Mime Types
  * Mimeo
    * Usage
    * Examples

<br /><br />
## Network Management
Various network information can be found throughout - This is only for managing connectivity

#### Netctl
  * Wifi
  * Ethernet
  * Automatic Connectivity

<br /><br />
## Users and Groups
The opportunity to set up more users is available.

#### Creating User Directories
  * xdg-user-dirs

#### Managing Users and Groups
  * Users
    * Adding Users
    * Deleting Users
    * Changing Usernames
    * Changing Home Direcotires
    * Adding Users to Groups
    * Removing Users from Groups
    * Expiring Passwords
  * Groups
    * General Usage
    * General User Groups
  
#### Permissions
  * Explanation
  * General Examples
  * Bulk Chmod
  * Change Ownership

<br /><br />
## Maintenance
A few pointers on System Maintenance. Some steps will manage themselves, others will need a revisit from time to time.

#### Mirrors
  * European Servers
  * Automatic Mirror Upgrade
    * Reflector
  
#### Pac\[new/save\]
  * Locating New Files

#### Clean The Filesystem
  * Package Cache
  * Orphans
  * Old Configuration Files
  * Broken Symlinks
  * Review Installed Packages
  * Tips and Tricks
    * BleachBit
  
#### Downgrade
  * Package
  * Kernel

<br /><br />
## Getting Information
Pointers on where to obtain some vital information.

#### Hardware
  * PCI Busses
  * Memory 
  * Battery
  * Disk
  * CPU
  * Additional Packages
    * lshw
    * hwinfo
    * dmidecode
  * Tips and Trick
    * /proc
      * CPU
      * Memory
      * Kernel (out of category, but hey)

#### Software
  * Logs
  * Dmesg
  * Kernel
  * GPU Driver
  * Applications
  * Additional Packages
    * tldr
  
#### Network
  * Local Information
  * Host/Domain Information
  * SS Network Tool
    * Analysis Example
    * Basic Usage
  
#### Journalctl
  * Usage

<br /><br />
## Terminal and Shell
We might as well improve the window we'll be spending most our time in.

#### Aliases
  * System General
  * Keks

#### Functions
  * Extract
  * Copy/move and goto dir
  * Arch RSS Feed
  * Toggle Monitor Blank
  * Weather Forecast

#### Zsh
  * Configuration
  * Oh My Zsh
    * Plugins
  
#### Urxvt
  * Extensions

#### Xresources 
  * Syntax Explanation

#### Gnu Screen
  * Usage

#### Additional Terminal Packages
  * Neofetch
  * Clockywock
  * sl
  * figlet
  * Asciiquarium
  * Unclutter
  * Task

#### Terminal Keks
  * Fortune
  * Cowsay
  * Lolcat

<br /><br />
## Security
Some pointers on keeping your system Secure. This is based on Single Machine security.

#### Anti Virus
  * Clamav
    * Additional Definitions
    * Usage
    * Troubleshoot
  
#### Firewall
  * IPtables
    * A Little Explanation
    * Usage
    * Setting Up a Single Machine Firewall
    * IPv6
  * 25 Common IPtable Rules
    * https://gist.github.com/virtualstaticvoid/1024546
  * IPset
    * Usage
    * Blocklists
      * Daily Update   
  * Fail2Ban
    * Configuration

#### Password Manager
  * KeePass
    * Using With Firefox
    * Troubleshoot
  
#### Security Audith
  * Lynis
    * Usage
  
#### Browsing
  * Tor
    * Configuration
    * Using Tor with other Applications
      * Firefox

<br /><br />
## Preferred Software
We are closing in on that complete system. These are some of my favorite software for everyday tasks.

#### Browser
  * Firefox
    * Configuration
    * Preferred Addons
    * Netflix, Viaplay etc
    * Tips and Tricks
    * Troubleshoot
  
#### Office Suite
  * LibreOffice
    * Configuration
  
#### Text Editor
  * Vim
    * Configuration
    * Modelines
    * Plugins
  
#### File Manager
  * Ranger
    * Configuration
    * Themes
    * Troubleshoot
    * Additional Packages
      * Atool (extract/compress)
      * w3w (image preview in terminal)
      * zfz (search)
    
#### Bookmark Manager
  * Buku
    * Usage
  
#### News
  * Haxor News
    * Usage
  * Reddit Terminal Viewer
    * Usage
  
#### IRC
  * Irssi
    * Configuration
    * Scripts
    * Usage
  
#### Video Player
  * Mplayer ***needs revisit***
    * Key Binds
    * Creating and Playing Playlists
    * Additional Options 
  
#### Music Player
  * Cmus
    * Scripts
    * Usage
    * Tips and Tricks
      * Cava
    
#### Image Viewer
Feh is also used for displaying the Desktop Wallpaper
  * Feh 
  
#### Additional Badass Software
  * Record My Desktop
  * MuPDF
  * Zim
  * Dropbox
  * Rednotebook
  
<br /><br />
## Eye Candy
Making the system pleasant on the eyes^

#### Theming 
  * Lxappearance
  * Theme Collection (Or it will be hopefully)
    * Window Themes
    * Cursor Themes
    * Grub2
    
#### Fonts
I've made the decission not to use Infinality - I do miss those smooth fonts though..
  * Sweet Fonts
  * Configuration
  
#### Additional Sweetass Software
  * Compton
  * Redshift

<br /><br />
## Development
I do a little Web Development, so that is the main focus. 

#### Version Control
  * Git
    * Usage
      * A Few Typical Examples

#### IDE
  * Sublime
    * Plugins
    
#### LAMP
  * Apache
  * PHP
  * MySQL
    * Adminer
    
#### Design
  * Gimp
    * Configuration
    
<br /><br />  
## Gaming
Who doesn't like the opportunity, eh?!

#### Steam
  * Configuration
  
#### Game Specific Troubleshoot
  * Wasteland 2
  
<br /><br />
## SSH
For quick authentication and communication with your server(s) and services.

#### Server and Client
  * Client 
    * Usage
    * Configuration
  * Server
    * Configuration
    * Key Authentication
    * Running the Daemon
    * Tips and Tricks
    
#### Keys
  * Quick Info
  * Generating Keys
  
#### Agent
  * Starting with Bash
  
#### Transfer via SSH
  * SCP
    * Usage
      * Basic Examples
   
<br /><br /> 
## Cryptography
We should all try to protect ourself in this modern age.

#### GPG
  * GnuPG
    * Setting Up
    * Signatures
    * Usage
    * Tips and Tricks
    
#### Currency
  * Monero
  * Wallet (not monero specific, but hey)
    * Creating
    * Using
  * Mining
  
<br /><br />
## Analysis
  Information is key!
  
#### Nmap 
  * Usage
    * Evading Firewalls
    * Scripts
      
#### WireShark
  * Filters
  
<br /><br />
## Key Binds
This is the Throwback section. Here to remind you of some of the wonders your system can do.

#### Window Manager
Binds for i3
  * System
    * Log out / Shutdown Options
    * Open Applications
    * HDMI Controls
  * Navigating
  * Scratchpad
  * Containers
  
#### Editor 
Binds and Commands for Vim
  * Command 
    * Find and Replace
  * Normal
    * Formatting
    * Navigating
    * Folkds
    * Color Scheme
  * Visual 
    * Selecting Text
    * Copying
    * Switch Case
    * Indent
  * Plugin Features
    
#### IDE
Binds and Commands for Sublime 
  * Smart Selecting
  * Smart Moving
  * Merging Lines
  * Sorting Aplhabetic
  * Browsing CSS
  * Toggle Spellcheck
  * Distraction Free Environment
  * Navigating Files, Classes or Linenumbers
  * Command
    * Syntax Highligh
    * Renaming
    * Snippet Examples
  * Plugin Features
