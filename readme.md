# Billy's New Clean Install Windows 10 Setup Guide

This is a checklist for me with the options I like. Usually I use this for wiping and resetting a Windows machine for development work. Your mileage may vary.

## Prepare USB installer  Install Windows

- Get the [Windows 10 media creation program](https://www.microsoft.com/en-us/software-download/windows10)
 - This is a windows EXE. If you are on a Mac, it only gives you an ISO option. Use Parallels or another Windows box. 
- Get USB drive at least 8GB
- Create a bootable Windows 10 installer

## Boot From USB

- You may need to go into BIOS and change boot order.
- Google the make/model, find the key you need to press to launch boot menu or go into BIOS. Common keys: [ESC], [F2] [F8], [F9]
- Boot from the USB device

## Install Windows 10

- Remove all the partitions, and install windows
- Join a wireless network
- Choose an "Offline Account"
- "No to device sync
- Disable Cortana
  - "*Get Help from Digital Assistant"* -> *"Decline"*
- Enable Strong Privacy Settings
 - All privacy options (Location, Ad, etc) -> set to *"no"*


## Apply All Updates

Depending how old the Windows 10 installer is, you may be quite behind on Updates.

 Settings -> Update & Security -> Check for Updates

Windows will automatically download and install what it needs. Some updates cannot be done in parallel.

1. Let Windows apply updates
2. Reboot
3. Go back into *Update & Security*
4. If more updates, GOTO 1.

## Decluttering Windows 10

Windows comes with a ton of programs and outright ads all over the desktop, start menu. and task bar. Let's clean that up. 

### Run Windows 10 Debloater

This deletes all that free-to-play bullshit and spam/crap-ware.

- Go to [Windows10Debloater on Github](https://github.com/Sycnex/Windows10Debloater)
- Download the ZIP and run `Windows10DebloaterGUI.ps1`
- Click "Remove All Bloatware"
- Click "Stop Edge PDF Takeover"
- Click "Uninstall OneDrive"
- Click "Disable Telemetry/Tasks"
- Click "Unpin Tiles from Start Menu"
- Click "Remove Bloatware Regkeys"

Manually check the start menu and uninstall anything that was missed.

- Netflix
- Adobe Photo elements
- XBox
- Hulu

### Clean up taskbar

Windows starts with a bunch on junk in the taskbar.

#### Remove taskbar features.
- *Right-click* on taskbar
	- Toolbars -> Uncheck all Toolbars
	- Search -> Check *"Hidden"*
	- Uncheck *"Show Cortana button"*
	- Uncheck *"Show Task View button*
	- Uncheck *"Show Windows Ink Workspace button"

#### Remove pinned apps

Mail, Edge, etc. Just right click and "unpin"

#### Muting Action Center

Deaden some annoyance of Action center

- Right-click on Action Center
	- Check "Don't show app icons"
	- Check "Don't show number of new notifications"

### Clean up Desktop

Delete shortcuts for anything you don't want (Edge, Bing, etc)


## Settings

The default settings of Windows are less than ideal.


###  Windows Lock Screen
- Settings -> Lockscreen
	- Turn "off" "Get fun facts, tips, and tricks on lock screen"
	- Set a background image

### Fixing Time Zones

- Settings => Time & Language -> Timezone
	- Turn "on" Set time zone automatically

### Activate Windows

If you want something more then Windows 10 Home, you need an OEM key.

## Configure Windows Explorer

Make Windows Explorer options sane

- Expand the ribbon
- View -> Options -> View
 - Check "Show the full path in the title bar"
 - Uncheck "Hide Extensions for known file types"
 - Uncheck "Use check boxes to select items"
 - Navigation Pane
  - Check "Expand to open folder"
  - Check "Show all folders"


## Programs

Things I need to get work done:

### Google Chrome

- Download [Google Chrome](https://www.google.com/chrome/)
- Bookmarks -> Show Bookmarks bar
- Settings -> Show Home Button -> New Tab
- Settings -> On Startup -> Continue where you left off
- Extensions:
	- [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
  
- Make Chrome the default browser
	- Settings -> Default apps -> Web Browser -> Set to *"Google Chrome"*

### Last Pass

Get the [universal installer](https://lastpass.com/download/cdn/lpmacosx.zip) so it installs in all browsers

### Other Programs

- [Notepad++](https://notepad-plus-plus.org/download)
- [Github Desktop](https://desktop.github.com/)