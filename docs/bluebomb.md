# Bluebomb

?> For support in English, ask in the discord [server](https://discord.gg/QvGQqx8Mns)

!> Modding does not come with a warranty, and we are not responsible for any damage done to your Wii.

!> For the RVL-001 and RVL-101 model Wiis, it is not recommend to use BlueBomb if you intend to install the Homebrew Channel and BootMii, as there are more convenient exploits available.

# Running the Exploit

#### Requirements

- A Linux machine
	- A Virtual Machine might work, but it is not recommended due to its complexity in getting Bluetooth passthrough working. If possible, please use a LiveUSB as described below.
	- If you have a Raspberry Pi, you can also use that because it may already have Linux installed already.
	- A Windows Subsystem for Linux or a Chromebook running Linux mode will not work as they don’t have direct access to the Bluetooth adapter or USB ports.
	- If you do not have a Linux OS, [Ubuntu](https://ubuntu.com/download/desktop) is the most user-friendly option and can be ran on computers running Windows or Mac.
		- 32-bit devices will require [Ubuntu 16.04](http://releases.ubuntu.com/16.04/).
		- For 64-bit devices it is recommended to use the LTS edition due to its stability, but the latest release works as well.
	- You can [flash a Linux Live environment to a USB flash drive](https://ubuntu.com/tutorials/tutorial-create-a-usb-stick-on-windows#1-overview) instead of installing it to your computer.
- A Bluetooth adapter.
	- An internal Bluetooth adapter will work. If you do not have one, make sure to get one compatible with Linux.
- A USB drive formatted as FAT32. This will be a different drive that will be plugged into the Wii or Wii Mini.

#### Performing the exploit
1. Download the HackMii installer from the [BootMii website](https://bootmii.org/download/).
- (If attempting to fix a brick, you should also copy the homebrew app you wish to use to /apps/)
2. Extract it and place the `boot.elf` file on the root of your drive. 
- (do not use bootmini.elf, even on a Wii Mini. It will **not** work. bootmini.elf is the hackmii installer that runs on MINI, through bootmii's SD menu.)
3. Connect the drive to the console. For a Wii mini, there is only one USB port on the back. For a normal Wii, use the bottom port, or the right port if it is set vertical.
4. Turn on your console and navigate to the settings menu. In the top right corner, you will see your System Menu version and region. This will be needed later. Afterwards, turn your console off.
5. Start your Linux OS, and connect to the internet.
6. Open the Terminal
7. Run the following commands:
```bash
wget https://wii.guide/assets/files/bluebomb-helper.sh
chmod +x bluebomb-helper.sh
./bluebomb-helper.sh
```
8. The helper will download the required files and ask for information about your console.
  - If you selected a Wii mini, you will be asked to type in your region. It is located in the system menu settings in the top right and indicated by a letter next to the system menu version.
  - If you selected a Wii, you will be asked to type in your Wii Menu Version (What you determined in step 4)
9. Turn on your console and **do not** connect any Wii Remotes.
10. Press the Sync button and the terminal should show `got connection handle`. This could take numerous attempts, so don't give up.

- [Coninue to the Hackmii installer page](/hackmii-installer)