---
title: 3DS | GBA games save management via GodMode9
categories: [3DS, GBAon3DS]
tags: [save management, gm9]
---

>NOTE: this method was tested using GBA games installed via CIA files.

### GodMode9

First of all, it's a relative new feature, so be sure to have GM9 updated.

To update it, you can follow the process over [GM9](https://github.com/d0k3/GodMode9/releases) github page. Alternatively, it is possible to update it via [Universal Updater](https://universal-team.net/projects/universal-updater) Homebrew, which I consider way easier.

	

### Backup and inject

To make a backup/inject a save, you need to have that game installed.
Run the game until it sarts (until it is playable) and close it / turn the power off.
This step is **EXTREMELY** important. Imagine it as if you were injecting the cartridge to the console.

Now, pressing the START button, turn your system on to launch GM9.

#### BACKUP

To backup the previous opened game, choose ***SYSNAND VIRTUAL -> agbsave.bin***.
The lower screen should have ***AGBSAVE options...*** option. Select it and ***Dump GBA VC save***.
The backup file can be found at the ***/gm9/out/*** directory on your SD's root.

#### INJECT

To inject a save to a game, considering you already have the ***.sav*** file somewhere inside your SD, navigate to it under ***SDCARD***. Press Y on top of the selected ***.sav*** file to copy it to clipboard.
Now navigate back to the GM9 root screen and select ***SYSNAND VIRTUAL -> agbsave.bin***.
The lower screen should have ***AGBSAVE options...*** option. Select it and ***Inject GBA VC save***.

>Reference: [3DS GBA Save Backup and Restore with GodMode9](https://digiex.net/threads/3ds-gba-save-backup-and-restore-with-godmode9.15395/)