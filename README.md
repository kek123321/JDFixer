# JDFixer

Based on NjsFixer by Kylemc1413 (https://github.com/Kylemc1413/NjsFixer)

I wanted a stripped down mod that focused only on JD modification to fix floaty maps, and that doesn't include NJS/BPM modification since I don't use those features. 
Works in multiplayer.
Score submission is unaffected.

New Features:
- The map's original JD is displayed in the Mod menu. You can easily decide if you want to use the JDFixer without having to play the map to feel it.
- The behavior of the Preferences has also been changed to selecting the NJS-JD pair that is equal or lower to the selected map's NJS. This allows you to cover large ranges without having to add many values, and also handles the rare non-integer NJS
- There is an added heuristic in the Preferences, where if the selected map's original JD is lower than the JD in the matching NJS-JD pair, the map will run at its original JD. If you don't like this feature, you can still use the slider which will force JD as much as possible.
- Also included are Upper and Lower NJS Thresholds where Preferences will be ignored: If a map's NJS is at or above the upper threshold, the map will run at its original JD (and vice versa for lower threshold)

How To Use:
- Place JDFixer.dll in Plugins folder
- Upper and Lower NJS Thresholds can be set in JDFixer.json
- Min and Max range in the JD slider can be edited in JDFixer.json
- Preferences for NJS-JD pairs are set in-game like original Njsfixer mod
- Enabling Preferences will override the JD value in the slider
