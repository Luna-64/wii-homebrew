# USB Loaders

- The Wii has 2 main USB Loaders; USB Loader GX, and Wiiflow Lite.

## Differences

- While it is mainly down to personal preferance, there are a few differences between the loaders.

### USB Loader GX
- It is themed after the Wii Menu
- There are more themes available

### Wiiflow Lite
- More advanced interface
- Plugin System
- Less file name requirements

## File Naming

?> [Wii Backup Manager](/wiibackupmanager) can rename and transfer the files automatically

- File name
 ```
💾SD card or USB:
 ┗ 📂wbfs
    ┣ 📂GameName [GameID]
    ┃  ┗ 📜gameid.wbfs (for non-split titles)
    ┗ 📂GameName [GameID]
       ┣ 📜gameid.wbfs
       ┗ 📜gameid.wbf1
```

- Example game: Mario Kart Wii (NTSC-U)
 ```
💾SD card or USB:
 ┗ 📂wbfs
    ┣ 📂Mario Kart Wii [RMCE01]
      ┗ 📜RMCE01.wbfs
```

- Example Split Game: Super Smash Bros Brawl (NTSC-U)
 ```
💾SD card or USB:
 ┗ 📂wbfs
    ┗ 📂Super Smash Bros Brawl [RSBE01]
       ┣ 📜RSBE01.wbfs
       ┗ 📜RSBE01.wbf1
```

- Game IDs can be found at [GameTDB](https://gametdb.com)

## Getting the Loader
1. Download either [USB Loader GX](https://hbb1.oscwii.org/api/v3/contents/usbloader_gx/usbloader_gx.zip) or [Wiiflow Lite](https://hbb1.oscwii.org/api/v3/contents/wiiflow/wiiflow.zip) and extract the files to your SD card.
2. Go to the homebrew channel and launch your preferred USB loader.

## Common Issues

### I am sent to the homebrew channel when I run a game.
- This means that you do not have cIOS installed. Please visit our [cIOS guide](/cIOS) for information on cIOS installation.
- If it still doesn't work, change the loader IOS in your loader's settings.

### I am sent to the Wii Menu
- This means that your file names are incorrect. View above for information on how your files should be named.