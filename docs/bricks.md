# Types of bricks

When modding a Wii, there's always a chance for it to get **bricked**. Some bricks are less dangerous than others, and they will all be covered in this guide.

!> To avoid bricks, make sure to always install brick protection, with apps such as **Priiloader** and **BootMii**.

## Banner bricks
A banner brick can happen when a bad .WAD file has been installed onto the Wii. (Usually because of a bad banner size, hence the name.) Commonly, this brick shows an error message saying: `The system files are corrupted. Please refer to the Wii Operations Manual for help troubleshooting.`

**How to check:** In the Health and Safety screen, hold `+` and `-` when pressing `A`. If the system still doesn't boot, that's a banner brick. If it boots, it's a mail brick (covered below)

**How to fix:** You need Priiloader in order to fix this brick. 
1. If you have it, hold the `Reset` button when powering on your Wii. This will boot you into the Priiloader menu.
2. From there, select the `Homebrew Channel` option.
3. Now, load the app in which you installed the .WAD file, and uninstall said file.

## Mail bricks
Similiar to banner bricks, this one shows the error message `The system files are corrupted...`. This brick happens if there is too much mail or if there is a corrupted mail in your mailbox.
*Maintenance Mode* still lets you boot your system, since it disables Wii Mail.

**How to check:** In the Health and Safety screen, hold `+` and `-` when pressing `A`. If the system boots, you've confirmed it is a mail brick. If it doesn't, it's a banner brick.

**How to fix:** You don't need Priiloader or BootMii to fix this brick.
1. Boot the Wii into Maintenance Mode. (Hold `+` and `-` on the Health and Safety screen, then press `A`)
2. Launch the Homebrew Channel. From there, you can launch mail deletion software.

?> This brick is also fixable by factory resetting the Wii.

## IOS bricks
This happens when the System Menu's IOS is corrupted. It can only be fixed with BootMii installed as **boot2**, as other homebrew tools require the now corrupted IOS to function.

?> This brick will also happen if your WiFi module is broken, or if you install normal cIOS on a Wii Mini.

**How to check:** The Wii gives a black screen, not showing any signal.

**How to fix:** You need BootMii installed as boot2 to fix this, as well as your NAND backup. Alternatively, you can use a modchip.
1. Turn on your Wii with your SD card containing the BootMii files inserted.
2. Use the `POWER` button (or left and right on the Control Pad of a GameCube controller) to navigate to the button with gears. Then press `RESET` on your Wii to proceed. (`A` on a GCN controller)
3. Using the same buttons, select the button with the red arrow to restore your NAND.
4. After that, follow the directions on your Wii.

!> Make sure to NOT turn off your Wii when restoring a NAND backup!

## Error 003 bricks
This brick is not really accidental. It only happens if you install a system menu with a version higher than 4.1 on a region changed Korean Wii, or you add the Korean key on a non Korean Wii. This can be done with [KoreanKii](koreankii).

**How to check:** On start-up, the Wii displays the `Error 003: anouthorized device detected`.

**How to fix:** You need either Priiloader or BootMii as boot2 to fix this.
1. If you have Priiloader, hold `RESET` while turning on your Wii access Priiloader.
2. From that, launch the Homebrew Channel. Then, launch KoreanKii.
3. You now can use [KoreanKii](koreankii) to remove the Korean key.

?> If you have BootMii instead, you can restore a NAND backup to fix this brick.

## Semibricks
This happens when an update from the wrong region is installed to a Wii. The settings menu will show an Opera error instead of opening normally.

**How to check:** The settings display an Opera error when opened.

**How to fix:** You need the Homebrew Channel to fix this.
1. Boot up the Homebrew Channel.
2. Launch [Wii Mod Lite](https://hbb1.oscwii.org/api/v3/contents/WiiModLite/WiiModLite.zip).
3. Go to "Display System information" and check your region.
4. Go to "Region Changer" and change your region to the one displayed in the info tab.

## System menu bricks / Full bricks
The system menu will refuse to boot in this brick. This can happen for many reasons.

**How to check:** The wii gives no signal, or displays an Opera error instead of the Health and Safety screen. Both cases can be fixed with BootMii as boot2 by restoring a NAND backup, but in the case of an Opera error, Bluebomb can be used to fix it.

**How to fix:** You can either restore a NAND backup (BootMii as boot2 only) or if the screen displays an Opera error, you can use [Bluebomb](bluebomb).
