---
'@capawesome/capacitor-haptics': patch
---

fix(android): play `playPattern(...)` events at their requested times by measuring primitive durations, which requires Android 12 (API level 31)
