# Shrek Club

Adds two Shrek clubs with SOMEBODY sounds.


## How to install
1. Install [Equipment Fix](https://github.com/ColdSpirit0/MordhauMod-EquipmentFix) mod.
2. Create the directory `.../MORDHAUEditor/Mordhau/Mods/ShrekClub`.
3. Move to the directory and open the command prompt.
4. Write `git clone https://github.com/ColdSpirit0/MordhauMod-ShrekClub.git .`


## Config example

```ini
[/Script/Mordhau.MordhauGameSession]
Mods=2708655 ; https://mod.io/g/mordhau/m/shrek-club

[EquipmentLoader]
LoadEquipment=/ShrekClub/Weapons/BP_ShrekClub.BP_ShrekClub_C
LoadEquipment=/ShrekClub/Weapons/BP_SomebodyClub.BP_SomebodyClub_C
```