# Driver Station Setup Log

Why is it stinky?

## BIOS

- Why is it in legacy instead of UEFI
- Dimmed keyboard backlight
- Computrace is disabled
- Intel SGX is disabled
- Have not yet set asset tag

## Windows

- Installed Some updates
- Reset PC from Windows Advanced Startup, quick wiping files, & reinstalling Windows

## Windows Setup

- United Sates
- US Keyboard only
- Home network
- Username: FRC6506
- Password: [blank]
- Cortona personal info access disabled
- Relevant ads, speech recognition, Tailor experiences with diagnostic data off

## Settings

- Ran Windows Update

## Task manager

- Switched to expanded view

### Startup tab

- Disabled Microsoft OneDrive

## Stat Menu

- Unpinned useless shortcuts
- Rearranged and pinned useful shortcuts

## Settings > Display

- Switched Scale from 150% to 125%

## Taskbar

- Unpinned unneeded apps and hid people toolbar

## Settings > System

### Notification & actions > Quick Actions

- Removed some unneeded settings from quick actions menu

### Power & Sleep

- Set screen timeout to 10 minutes
- Set battery sleep to after 20 minutes
- Plugged in sleep after 30 minutes

### Battery'

- Battery saver is set to come on below 20% charge

### Shared experiences

- Disabled

### About

- renamed PC from "DESKTOP-F49LF5T" to "FRC6506-Driver-Station"
- OS: Windows 10 Pro Education

## Settings > Devices

### Bluetooth & Other Devices

- Turned Bluetooth off when going through quick settling
- Removed home printer

### AutoPlay

- Switched to "Ask me every time"

## Windows Update Round 2 Electric Boogaloe

Updates seems to be hung, so I restarted and it said they failed to install.  I'll leave it be this time and change any settings.  Haven't had issues like this in a wile though.  Ran the Windows update troubleshooter when it didn't seem to be downloading and retired updates.  I tried to install something else and didn't work.  Ran DISM, SFC, & CHKDSK (graphically), as well as troubleshooter again.  DISM says it worked on the image, but nothing else seems to have succeeded at anything.  Now 20H2 says installing, but WMC says it stopped working.

## Windows Setup 2

- Disabled optional diagnostic data
- Enabled find my device (Did not add Microsoft accounts thought)
- Disabled Inking & Typing data

## window's Update

- Checked for updates again

## Settings > System 2

Reviewing settings after major updates while waiting for more updates to install

### Notification & actions

- Dilated "Suggest ways I can finish settings up my device..."

### Focus Assist

- Enabled "Show me a summary of what I missed while focus assist was one"

## Devices 2

### Bluetooth & Other Devices 2

- Removed home printer again

### AutoPlay 2

- Switched to "Ask me every time" again

## Settings > Personalization

### Lock screen

- Disabled things that don't make sense for us on lock screen

### Start

- Change which folder appears in start
- Add Windows Defender to system tray

### Taskbar 2

- Enabled peak to preview the desktop

## Taskbar 3

- Hid news and interests

## Settings > Apps

### Apps & features

Uninstalled:

- HP Smart
- Microsoft Onedrive
- Mail and Calendar
- Skype
- Xbox Console Companion
- Xbox Live

I left:

- Groove Music, despite it coming with Windows Media Player (I ran it and selected recommended options))
- Microsoft Office (Unneeded, but they allow Navy Pilots to use it on their tablets while flying)
- Onenote (Useful for drivers?)
- Microsoft Solitaire Collection
- Weather

### Offline Maps

I did not configure this.

## Settings > Accounts

I have not configured a password yet.

### Your info

- Set profile picture to GitHub profile picture

## Settings > Time & Language

### Date & Time

- Enabled "Set time zone automatically"

## Settings > Gaming

Left Xbox game bar enabled

## Settings > Privacy

### Inking & typing personalization

- disabled

### Background Apps

- disabled some apps

## Settling > Windows Update

### Windows Update

- Changed Active hours to 7:00 AM to 6:00 PM
- Enabled "s update for other Microsoft products when you update Windows"
- Enabled update notifications
- Paused updates until 3/27

### Delivery Optimization

Was going to disable uploading, but it was grayed out

### Troubleshoot

- Switched recommend troubleshooter mode to "ask me before running..." from "Don't run..."

### Find my device

- Enabled, but requires Microsoft account to set up

## File Explorer > Options

- Enabled view file name extensions
- Enabled Show libraries

## Windows Security

- Left Controlled folder access disabled because it's a pain

## Settings > Devices > Touched

- Switched touchpad scrolling so that down scrolls down (Who uses Austrian mode?!?)

## Dell Command Update

- Download x64-bit Windows 8.1 and 10 version (Not WP Eww!)) to manage driver and firmware updates (Support Assist is fancier and has troubleshooting but is known to have issues sometimes)
- Default setting
- Checked for and installed all updates

## Intel Graphics Command Center > Preferences

- Disabled promotions

## Device Manger

- Updated broken audio driver

## Microsoft Store > Settings

- Disabled Live tile promotion
- Disabled Video Auto-play
- Installed all updates

- Also hid HP Smart in All Owned Apps

## Settings > Personalization > Themes > Desktop Icon Settings

- Un-hid some useful icons

## Windows Security 2

### App and browser control

- Enabled potentially unwanted app blocking

### Device security

- Enabled memory integrity in core isolation

## BIOS 2

### Intel(R) Software Guard Extensions^TM

- Set to Software controlled

## Troubleshooting the TPM

- Installed powershell help updates
- I can't fix this but I also don't want to disable warnings, just click continue

## Edge Settings

I would install Firefox, but we really shouldn't use the ds for web browsing.  I also did not install any extensions.
I did bookmark some useful websites (Like this one)

### Profiles

- Disabled Microsoft Rewards > Show Rewards in Microsoft Edge
- Disabled Passwords > Offer to save passwords
- Left Show alerts when passwords are found in an online leak disabled
- Disabled Payment info > Save and fill payment info

### Privacy, search, and services

- Disabled "Allow site to check if you have payment methods saved"
- Left "Enhance your security on the web" disabled
- Disabled "Save time and money with Shopping in Microsoft Edge"
- Disabled "Show opportunities to support causes and nonprofits you care abut"
- Switched Search Engine to Google
- Switched Search on new tabs to address bar in order to use Google

### Appearance

- Set Show favorites bar to Always
- Enabled Home Button
- Enabled show downloads button
- Left Collections button on

### Start, home, and new tab

- Set When Edge starts to open these pages: `https://frc65o6.github.io/docs/driverStation/driverStation` & `edge://newtab`
- Set home button to frc65o6.github.io/docs/driverStation/driverStation

### New tab page customization

- Set to focus preset
- Left it as 1 row quick shortcuts
- Disabled promoted links
- Disabled content
  
### Downloads

- Left Ask me what to do with each file disabled
  
### Family

- Set kids mode to 9-12 years old, although it's disabled

### System and Performance

- Disabled Microsoft Edge as startup item in task manger
- Disabled startup boost
- Left low battery economy mode disabled

## Installed programs

- Downloaded portable (no install) copy of HWInfo, extracted 64-bit version to Desktop/Utilities folder, added shortcut in start menu and pinned to start (via %appdata%/Microsoft/Windows/Star Menu/Programs)
- Installed FRC Game Tools 2022 (using offline installer) (including disabling fast startup)), update Start Menu Pins, Desktop Icons, & taskbar pins, setup driver stations

## Password

- Removed account password again

## Control Panel > Hardware and Sound

### Power Options > System Settings > Edit Plan Settings

- Dibbled USB Selective suspend as per [here](https://docs.wpilib.org/en/stable/docs/software/driverstation/driver-station-best-practices.html)
- Left hibernate after 180 minutes on
- Left turn off hard disk as after 10 minutes
- Left critical battery action as hibernate

## WPILib Tools

- Installed WPILib tools to get shuffleboard and smart dashboard

<br>

Authored by @BobSaidHi 3/2022
