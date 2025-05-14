---
name: Curtis Nadir
xp_spent: 0
xp_added: 0
momentum: 2
edge: 0
heart: 0
iron: 0
shadow: 0
wits: 0
health: 5
spirit: 5
supply: 5
Quests_Progress: 0
Quests_XPEarned: 0
Bonds_Progress: 0
Bonds_XPEarned: 0
Discoveries_Progress: 0
Discoveries_XPEarned: 0
iron-vault-kind: character
callsign: Rook
assets:
  - id: asset:starforged/command_vehicle/starship
    abilities:
      - true
      - false
      - false
    controls:
      integrity: 5
      integrity/battered: false
      integrity/cursed: false
    options:
      name: Elara Five
  - id: asset:starforged/path/veteran
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:starforged/path/explorer
    abilities:
      - true
      - false
      - false
    controls: {}
    options: {}
  - id: asset:starforged/path/armored
    abilities:
      - true
      - false
      - false
    controls:
      broken: false
    options: {}
---


```iron-vault-character-info
```

```iron-vault-character-stats
```

```iron-vault-character-meters
```

```iron-vault-character-special-tracks
```

```iron-vault-character-impacts
```

```iron-vault-character-assets
```

```iron-vault-mechanics
oracle-group name="Starship Oracles: New Starship Oracles" {
    oracle name="[Starship Oracles \/ Starship Type](datasworn:oracle_rollable:starforged\/starship\/type)" result="Multipurpose" roll=80
    oracle name="[Starship Oracles \/ Starship Name](datasworn:oracle_rollable:starforged\/starship\/starship_name)" result="Elara Five" roll=19
    oracle name="[Starship Oracles \/ Fleet](datasworn:oracle_rollable:starforged\/starship\/fleet)" result="[Starship Mission](datasworn:oracle_collection:starforged\/starship\/mission)" roll=98
    oracle name="[Starship Oracles \/ Initial Contact](datasworn:oracle_rollable:starforged\/starship\/initial_contact)" result="Familiar" roll=3
    oracle name="[Starship Oracles \/ First Look](datasworn:oracle_rollable:starforged\/starship\/first_look)" result="Intimidating profile" roll=33
    oracle name="[Starship Oracles \/ First Look](datasworn:oracle_rollable:starforged\/starship\/first_look)" result="Modern or advanced design" roll=48
}
```

