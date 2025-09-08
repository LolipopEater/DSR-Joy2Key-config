# DSR-Joy2Key-config
DSR Joy2Key config
# JoyToKey (Joy2Key) Profile for **Digimon Super Rumble** on **ROG Ally**

Community-ready JoyToKey configuration that enables controller play in *Digimon Super Rumble* on Windows.
This repo/post includes the actual `.cfg` and quick instructions so anyone can import and play fast.

note this is made for the Rog ally handheld, so other keys are not mapped, as you  can use the touchscreen to select skills mid-fight and enemy digimons.

You may change it as you wish, and it's it is most comfortable for you

> Tested on Windows 11 + JoyToKey v6.x (ROG Ally).  
> Last updated: 2025-09-08

---

## Download

- Config file: `dsr (2).cfg` (JoyToKey profile)

---

## Quick Start

1. Install **JoyToKey** – https://joytokey.net/
2. Run JoyToKey **as Administrator** (some games require elevated input).
3. **Import the profile**  
   - JoyToKey → **File → Import** → select `dsr (2).cfg`, or  
   - Copy the `.cfg` into your JoyToKey profiles folder and restart JoyToKey.
4. Launch *Digimon Super Rumble* (borderless window or fullscreen windowed recommended).
5. In JoyToKey, select the imported profile and play.

---

## Controller Layout (Xbox-style labels)

Below table shows common **Xbox** / **ROG Ally** names (A/B/X/Y, LB/RB, etc.) alongside the numeric index from JoyToKey.

**Buttons**

| Controller | Index | Action |
|---|---:|---|
| A | B1 | `1, 46:00:00:00, 0.000, 0, 0  ##interact` |
| B | B2 | `1, 1B:00:00:00, 0.000, 0, 0  ##escape` |
| X | B3 | `1, 31:00:00:00, 0.000, 0, 0  ##item1` |
| Y | B4 | `1, 32:00:00:00, 0.000, 0, 0  ##item2` |
| LB | B5 | `1, 56:00:00:00, 0.000, 0, 0  ##digivice menu` |
| RB | B6 | `1, 54:00:00:00, 0.000, 0, 0  ##tamer` |
| Back | B7 | `1, 4D:00:00:00, 0.000, 0, 0  ##map` |
| Start | B8 | `1, 49:00:00:00, 0.000, 0, 0  ##inventory` |
| L3 | B9 | `1, 09:00:00:00, 0.000, 0, 0  ##change chat` |
| R3 | B10 | `1, 4C:00:00:00, 0.000, 1, 0  ##event reward center` |
| Guide | B11 | `1, 11:00:00:00, 0.000, 0, 0  ##ctrl to multi select` |
| B12 | B12 | `1, 201:00:00:00, 0.000, 0, 0  ##left click` |


> Note: Some devices report different button indices. If one or two labels feel swapped, tell me which ones and I’ll update the mapping.

---

## Notes & Tips

- **Focus quirks**: If the game loses focus (e.g., after a fight), `Alt+Tab` back once.
- **Sensitivity**: Tune in-game camera sensitivity and JoyToKey stick-to-mouse speed.
- **Per-game profile**: Link this profile to the game EXE so it auto-activates when focused.
- **Anti-cheat / ToS**: Input mapping tools can be restricted by some titles; use at your discretion.

---

## Troubleshooting

- **Game ignores inputs** → Run JoyToKey as **Administrator**; check correct profile; ensure window focus.
- **Buttons off** → Verify controller numbering in JoyToKey (`Button 1`, `Button 2`, …). On some pads, indices differ.
- **Sticks too fast/slow** → Adjust Axis X/Y mouse speed in JoyToKey.

---

## License / Credits

**License:** MIT – modify and share freely with attribution.  
Config and testing by ❤️ Feedback welcome!
