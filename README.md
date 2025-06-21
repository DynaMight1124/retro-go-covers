# About

This repository contains cover art to be used with [Retro-Go](https://github.com/ducalex/retro-go).

Download this repository and place its content in the romart folder on your sd card.

Note: the rom files need to be unzipped to allow CRC validation to complete properly.


# Romart types

Theres two types of romart, either boxart or mix. Boxart is obviously an image of the games original box, the size will vary from console to console. Mix is a screenshot of the game with a logo, it will give an indication of the game type.

Examples:

Boxart: ![1AA3A207](https://github.com/user-attachments/assets/d2dec24b-beaf-4485-af92-4d698a89a9ed)
![0B29830A](https://github.com/user-attachments/assets/6337e703-63df-45d3-b09a-c8a9462404da)
![046F4B70](https://github.com/user-attachments/assets/0d8896af-432b-4258-a827-7a8c1cd1d03a)
![0BFDCA70](https://github.com/user-attachments/assets/97be6b4b-1fbd-411d-a308-6bf373747927)


Mix: ![0A44819B](https://github.com/user-attachments/assets/e7947c93-afc8-49c1-a7f9-9535e06add35)
![6C41D3CD](https://github.com/user-attachments/assets/41d41de5-0032-4c28-bca4-2c3cd27b3562)
![04405423](https://github.com/user-attachments/assets/3a40b862-7a8a-4f65-83de-e72bc04a5527)
![00DC2D51](https://github.com/user-attachments/assets/f14e5674-7b22-4c64-869f-b107d96c8944)

The Mix romart is in the folder called 'mix romart' so if you choose that option just copy the contents of that folder to your romart directory, if you choose boxart then delete the mix romart directory and then copy to your romart directory.

# Format

The preferred format is paletted PNG with dimensions of 160x160. Dimensions may vary but try to be consistent in any given system.


# Naming

File names are 8 digit uppercase hexadecimal numbers used as unique game identifiers.
See table below to learn how they are calculated.

| System | Folder | Algorithm |
|--------|--------|-----------|
| Colecovision | col | CRC32 of the entire game rom |
| DOOM | doom | Name of the WAD file |
| Gameboy | gb | CRC32 of the entire game rom |
| Gameboy Color | gbc | CRC32 of the entire game rom |
| Gamegear | gg | CRC32 of the entire game rom |
| Game & Watch | gw | CRC32 of the entire game rom |
| Lynx | lnx | CRC32 of the entire game rom excluding the first 64 bytes |
| MSX | msx | CRC32 of the entire game rom |
| NES | nes | CRC32 of the entire game rom excluding the first 16 bytes |
| PC-Engine | pce | CRC32 of the entire game rom |
| Sega Master System | sms | CRC32 of the entire game rom |
| Sega Megadrive | md | CRC32 of the entire game rom |
| SNES | snes | CRC32 of the entire game rom |
