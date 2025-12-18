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

## Notes for Seamless Coop

SC is awesome but has some progression related issues in early game when trying to play with friends. 99% of the game works just fine, but here are
some tips to avoid progressions issues, glitches, etc.

1. Spirit calling bell: Ranni will _not_ appear reliably when multiple people are in the game, despite meeting conditions for her to appear in Elleh. This step should be done solo, then you can rejoin friends. I think this step is necessary to kick off her questline, not sure.
2. Evergaols: these are hit and miss, but it is most reliable to have the _host_ activate and enter the evergaol first. All other players should huddle around the host as they activate the gaol, then 9 times out of 10 everyone is teleported in
3. Unable to move in Evergaol: This is common if tip #2 gets screwed up, one or more players will be unable to move once in the gaol. Host should set PvP mode ON, then give each player a whack and this should un-stuck them.
4. Invisible Torrent: this happens, no known fix. Oftentimes it's not that he's invisible, it's that he is actually 10-20 feet up in the air, but thinks he's on the ground.
5. Runes don't drop for everyone: I've had this happen off and on with bosses in SC, and its the main reason for the 1.5x runes multiplier. Sometimes players won't be rewarded runes, this includes the host. Sometimes non-host players get runes and the host doesn't, or vice versa. No known fix.


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
