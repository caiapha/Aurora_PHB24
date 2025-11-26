# Changelog

All notable changes to this project will be documented in this file.

---

## [1.0.0] – Version 1.0.0 uploaded – 2025-11-26

### ✅ Included in this version
- [X] Classes: 
  - e.g. Barbarian, Bard, Cleric...
- [X] Origins / Species / Backgrounds:
  - e.g. Human, Elf, Soldier, Scholar...
- [X] Feats:
  - e.g. Ability Score Improvements, general feats...
- [ ] Equipment:
  - e.g. weapons, armor, adventuring gear...
- [X] Spells:
  - e.g. spell lists for prepared classes...
- [ ] Other:
  - e.g. rules references, conditions, misc options...

### 🔄 In development / Work in progress
- [X] Standard Items
- [ ] Magic items or special equipment
- [ ] Validation / rules automation
- [ ] Data cleanup and consistency

### 🐛 Known issues / To be fixed

Notes:
- Items are the mere copy of the items from the 2014 rev (thanks to Aurora Legacy), updated in the ID only, to make them integral part of the 2024 package. Fixes could be needed.
- Weapons has been updated to include the Weapon Masteries in the weapon's description. Other specs could need a fix in case of updates with the 2024 versions.
- Regarding the Feats related to spellcasting (e.g. Magic Initaite, Fey-Touched, etc...), the code allows to select the Spellcasting Ability only the when the
  first Spellcasting Feat is selected. The followgin Feats will use the same Spellcasting Ability. The system will create a single Feat Spellcasting list in the sheet,
  with all the spells from all the Feats. This because it is expected a Player will use the same Spellcasting Ability for al the Feats. This solution also allows
  to "compress" all the Feat Spells in one single list, to save space in the Character Sheet.
