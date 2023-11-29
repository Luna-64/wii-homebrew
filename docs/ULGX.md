## USB Loader GX

ULGX (USB Loader GX) is a utility to boot backed up Wii & GameCube games. You can load from HDD or SD card.

ULGX is a homebrew program for the **Wii** It can be installed multiple ways, some easier than others.

## Installing it - Traditional Way

The traditional way to install ULGX is below.

1. Download the ULGX file from [this link](https://hbb1.oscwii.org/hbb/usbloader_gx/usbloader_gx.zip).
2. Connect your SD Card to your PC.
3. Extract the contents of the ULGX zip folder, and copy all the extracted files onto the SD Card.
4. Safely eject the SD Card from your PC.
5. Insert the SD Card into your Wii console.
6. Power on the Wii and navigate to the Homebrew Channel. Launch it.
7. Inside the Homebrew Channel, locate and select the USB Loader GX app to launch it.

## Installing it - Easier Way

?> This requires the Open Shop Channel. You can find a guide [here](osc)

1. Open the Open Shop Channel on your Wii.
2. Click `search`.
3. Search for USB Loader GX.
4. Click `install`.
5. Wait for it to install then open the Homebrew Channel.

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
5. Once you're in the Wii open USB Loader GX.
6. Your games should be there, enjoy playing your favorite Wii games!