# Neo65Cu

## Build Notes

### Physical Config Options used
- PE Sheet
- Foam
- Isolated Top Mount
- Gazzew Boba Black u4 Silant Tacticle (RGB, 63.5g)
- Connecting over 2.4ghz

### Issues/Resolutions
- [X] Spacebar was "sticky" on return
  - Attempted: loosening mount screws. Didn't fix, or not entirely, though did make the key "looser" when held sideways (so gravity wasn't pushing key back down). Instructions note not to over tighten gasket mount screws but like - REALLY don't overtighten them
  - Resolved: Didn't want to disassemble to examine stabs etc. Had a theory that spacebar foam might be causing friction. This was correct - removing spacebar foam IMMEDIATELY fixed the issue - this was able to be slid out without removing the plate. 99% certain that it was jammed up to tightly against stab bar so was causing friction along the entire length. Was able to push the foam back in; left a few mm protruding so that the foam did not contact the stab bar. If the issue returns, can likely remove, and shave a few mm off the foam
- [ ] Need to find Pegaso cap set boxes - need diff height Pgup, PgDn, End keys. Had to use a Right shift from a random set for now.


## Tri-mode Hotswap JSON + Firmware

### Notes
- Full instructions indicate firmware flashing is unnecessary
  - [ ] Note though that the high debounce firmware explicitly says for U4T. Review after using for a bit

### Instructions 2026-04-25-1353
- [JSON](NEO65_0816.json)
- [Firmware](NEO65_via_v1_12_20240308.bin) (flash with [QMKToolbox Beta](https://github.com/qmk/qmk_toolbox/releases/download/beta/qmk_toolbox.exe))
- [high debounce firmware](NEO65_via_v1_12_12ms_Debounce_20240403.bin) (for u4t, flash with [QMKToolbox Beta](https://github.com/qmk/qmk_toolbox/releases/download/beta/qmk_toolbox.exe))
