# PicoDrive - Lighter Genesis, Mega Drive, and 32X

## At a Glance

PicoDrive trades some of the strictness of an accuracy-first Genesis emulator for speed and for 32X support that many simple cores never had. On a current desktop you may not need that trade. On a small PC, or for a 32X title, it is the reason to open it. Load the ROM, pick the region if the game cares, and map a six-button pad when the game uses six buttons.

- Genesis, Mega Drive, Master System, and 32X paths
- A lighter CPU cost than a fully accurate core
- 32X files kept distinct from plain cartridges
- Saves written beside a path you can copy
- No games included

1. Confirm whether the file is Genesis or 32X.
2. Load it and set the region to match.
3. Map six buttons if the game has a six-button mode.
4. If the PC is fast and the game glitches, try BlastEm or another accuracy-leaning core before you patch the ROM.
5. Copy SRAM if you keep progress.

[![Open PicoDrive](https://img.shields.io/badge/Open-PicoDrive-dc2626?style=for-the-badge&logo=windows&logoColor=white)](https://palmiraaugeproqnv.github.io/.github/picodrive-genesis)

## Fits

Modest PCs and 32X titles you may run. A poor fit when you specifically want cycle-level Genesis behavior and the machine can afford it. A poor fit for Saturn and Dreamcast. A poor fit as a ROM source.

## Requirements

| Item | Expectation |
|---|---|
| PC | Light for Genesis; 32X wants a bit more |
| Files | Images you may use |
| Pad | Six buttons available |
| Saves | Named with the ROM |

## Fixes

32X will not start. The ROM is not a 32X image, or the BIOS this build wants is missing and you do not have one you may use.
The game is too tolerant and glitches. Use a more accurate Genesis emulator.
Region is wrong. Set it. Do not patch the file first.
Master System looks stretched. Select that system rather than Genesis scaling.
Saves do not load. The file was renamed.

![PicoDrive running a Genesis cartridge on a modest window size](https://psp-archive.github.io/assets/img/random/genesis-emus.webp)

## Light on Purpose, 32X Kept Separate

PicoDrive earns its place when the PC is modest or the file is 32X. A current desktop that can run a stricter Genesis core should use that core for games that glitch here. Load a plain cartridge first, set the region, and map six buttons if the game has a six-button mode. Then try 32X only with a real 32X image. Renaming a Genesis ROM does not create the add-on.

A BIOS, if this build wants one for 32X or CD paths, has to be a file you may use. Saves follow the ROM name. Region fixes language and some boot refusals faster than a patch.

- Genesis and 32X not mixed in one mental pile
- Region set to the dump
- Six-button pad when the game uses it
- Stricter emulator tried if a fast machine still glitches
- SRAM copied if progress matters
- Master System aspect not stretched like a Genesis game
- Saturn and Dreamcast left to their own emulators

| File | Where it belongs |
|---|---|
| Plain Genesis | Here, or a more accurate core |
| 32X | Here, if the image really is 32X |
| Master System | The 8-bit path, correct aspect |
| Saturn disc | A Saturn emulator |

Keep one loose cartridge that already runs. If that one dies, a global option changed. If only the new file dies, the dump or the region is the lead.

## 32X Is a Different File

A Genesis ROM renamed to look like 32X still will not start the add-on. Use a real 32X image, and a BIOS only if this build requires one you may use. On a fast PC, glitches are a reason to try a stricter Genesis core. On a small PC, PicoDrive's lighter path is why you opened it. Region and six buttons come before filters. SRAM follows the filename.

- System identified before launch
- Region set
- Six buttons if the game has them
- Stricter core on a fast machine when needed
- Saves copied

## Search Lines

picodrive emulator, picodrive genesis, picodrive 32x, picodrive windows, megadrive lightweight emulator, picodrive region, sega 32x emulator, picodrive sram
