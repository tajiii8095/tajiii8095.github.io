# Krone MegaLiner KDLC - 1.62 Fix

Fix for the **"Krone MegaLiner ADDON KRONE DLC"** mod (`krone_mega_kdlc_1.41` + `krone_mega_kdlc_1.43_fix`) for **ETS2 1.62**.

## Requirements

- DLC Krone Trailer Pack
- Original `krone_mega_kdlc_1.41`
- `krone_mega_kdlc_1.43_fix`

## Load order in Mod Manager

Order from top to bottom (the fix must be on top, above both original packages):

1. **Krone MegaLiner KDLC - 1.62 Fix**
2. **krone_mega_kdlc_1.43_fix**
3. **Krone MegaLiner ADDON KRONE DLC**

Download Sogard3´s mod here:https://forum.scssoft.com/viewtopic.php?t=260235

## Fixes

- Material errors: "aux[1] not supported" removed from all `/automat/` and vehicle materials (1.62 shaders)
- ADR plates: purple texture (missing `adr_labels/potassium.tobj` in 1.62) replaced with a bundled orange ADR plate texture
- Dead paint job mask path (`krone_profiliner/profiliner/pjm_at_0x0_size_16x4.tobj`)
- Duplicate `flare.vehicle.lp` unit (conflict with base game)
- Side skirts disappearing when switching to HCT / double (`suitable_for[]` entries were on one line)
- Side skirts now come as default on the 3-axle and double chassis, so all HCT trailers have them
- Missing icon for HCT 3+2+2 configuration
- 2-axle chassis (2nd trailer in HCT 3+2+2 / double) now gets side skirts as default (`side_skirt_02`)
- Raised body (`megalinerm`, used in HCT/double) now gets the reflective side banner (`s_banner/whitem`) as default

## Credits

- **SCS Software**
- **Sogard3**

All original models and textures belong to their authors.
