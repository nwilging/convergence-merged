# Elden Ring Convergence

**Original Mod Link:** https://www.nexusmods.com/eldenring/mods/3419

## About

This repository stores a configuration of ER Convergence with additional mods added/merged into `regulation.bin`.

## Installation

1. Clone or download repository anywhere on your computer (`git clone git@github.com:nwilging/convergence-merged.git`)
2. Extract archive (if downloaded zip)
3. Setup `ersc_settings.ini`: copy `SeamlessCoop/ersc_settings.ini.example` to `SeamlessCoop/ersc_settings.ini`
4. Open `SeamlessCoop/ersc_settings.ini` and set a value in `cooppassword` (e.g. `cooppassword = test`)
5. Double click on `Start_Convergence.bat`

## Mod List

* [Convergence](https://www.nexusmods.com/eldenring/mods/3419)
* [Armor and Weapon Dyes](https://www.nexusmods.com/eldenring/mods/6927)
* [Transmogrify Armor](https://www.nexusmods.com/eldenring/mods/3596)
* 1.5x Runes Multiplier (custom parameter edit)


## Adding a Mod

### Merged `regulation.bin` mods
The `regulation.bin` file is located in the `mod/` directory

1. Create a backup of `regulation.bin` replacing `regulation.bin.prev`
2. Open your game in Smithbox
3. Make desired edits
4. Save and close
5. Test that game works
6. Submit pull request with changelist

### Adding DLL mods
DLL mods must be located in the `mod/` directory

1. Add the DLL file to `mod/`
2. Test that game works and mod is active
3. Submit pull request with changelist
