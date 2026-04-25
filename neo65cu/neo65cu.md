# Neo65Cu

## Build Notes

### Physical Config Options used
- PE Sheet
- Foam
- Isolated Top Mount
- Gazzew Boba Black U4 Silent Tactile (RGB, 63.5g)
- Connecting over 2.4ghz

### Issues/Resolutions
- [X] Spacebar was "sticky" on return
  - Attempted: loosening mount screws. Didn't fix, or not entirely, though did make the key "looser" when held sideways (so gravity wasn't pushing key back down). Instructions note not to over tighten gasket mount screws but like - REALLY don't overtighten them
  - Resolved: Didn't want to disassemble to examine stabs etc. Had a theory that spacebar foam might be causing friction. This was correct - removing spacebar foam IMMEDIATELY fixed the issue - this was able to be slid out without removing the plate. 99% certain that it was jammed up to tightly against stab bar so was causing friction along the entire length. Was able to push the foam back in; left a few mm protruding so that the foam did not contact the stab bar. If the issue returns, can likely remove, and shave a few mm off the foam
- [ ] TODO: Need to find Pegaso cap set boxes - May need diff height Ins, PgUp, PgDn keys. Might be able to use some novelties or something. Had to use a Right shift from a random set for now.

### VIA config notes
- IMPORTANT: Factory Reset Default is Fn + Del for 3 seconds, I've moved that to Fn + Backspace
- Switched from having far right col be default Del-PgUp-PgDn-End to my preferred Del-Ins-PgUp-PgDn with PgUp-PgDn as Home-End in Layer 1
- Media in Layer 1: Fn + Del = Play, FN + Up/Dn = Volume, Fn + Left/Right = Skip
- [ ] TODO: Need to review against work keeb (Tofu65) - may want to make some changes there to these layer functions. This isn't a 1-1 match, and I've been meaning to mix those up anyway.

### Misc
- [ ] TODO: The U4Ts are probably much more my speed than the bobagum linears I've been running at work. Get another bag for the Tofu65


## Tri-mode Hotswap JSON + Firmware

### Notes
- Full instructions indicate firmware flashing is unnecessary

### Instructions 2026-04-25-1353
- Tri-mode
  - [JSON](Neo65Cu_trimode.json)
  - [firmware](Neo_65Cu-v1.01.bin) (flash with [QMKToolbox Beta](https://github.com/qmk/qmk_toolbox/releases/download/beta/qmk_toolbox.exe))

