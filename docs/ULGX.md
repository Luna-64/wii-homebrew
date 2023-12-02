## USB Loader GX

ULGX (USB Loader GX) is a utility to boot backed-up Wii & GameCube games. You can load from a Hard Drive or SD card.

ULGX is a homebrew program for the **Wii** It can be installed multiple ways, some easier than others.

?> You must dump your games if you want to use USB loader GX, You can find a guide [here.](https://wiki.hacks.guide/wiki/Wii:Dump_Games)
### You will need:
 * An SD card formatted to FAT32
 * A Wii
 * [USB Loader GX](https://hbb1.oscwii.org/hbb/usbloader_gx/usbloader_gx.zip)

## Installation
1. Copy the ```apps``` folder from the ```.zip``` you downloaded, and copy it onto the root of your SD card.
## Usage
1. On your PC, acquire your game in the `.wbfs` file format.
2. On the root of your SD card or USB drive, make a folder named `wbfs`.
3. Create a new folder inside of the `wbfs` named whatever your game is, and then the game ID for your game. 
    - You can find game ID's [here](https://www.gametdb.com/)
4. Inside of that folder, put your `.wbfs` game and name the game your ID.
    - Your files should look like the example below
    ```
    📁 wbfs
    ↪️ 
    📁Metal Slug Anthology [RMLEH4]
    📁Metroid Prime Trilogy [R3ME01]
    📁Mortal Kombat - Armageddon [RKME5D]
    ↪️ 
    📄RKME5D.wbfs

    Split game example
    📁Super Smash Bros. Brawl [RSBE01]
    ↪️ 
    📄RSBE01.wbf1
    📄RSBE01.wbfs
    ```
5. Once you're in the Wii, Open the Homebrew Channel and launch USB Loader GX from the list of homebrew, your games should be there.

