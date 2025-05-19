With the snake in the mist defeated, I continue to explore the vault. 

```iron-vault-mechanics
move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
    roll "Wits" action=3 adds=0 stat=3 vs1=3 vs2=4
    progress from=20 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="formidable" steps=1
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="Unintelligible whispers" roll=78

```
I follow the trail where I think the expedition must have gone but hear what sounds like whispering in the darkness. 
```iron-vault-mechanics
move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
    add 1 "explorer"
    roll "Wits" action=1 adds=1 stat=3 vs1=6 vs2=3
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="[Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor) + [Focus](datasworn:oracle_rollable:starforged\/core\/focus)" roll=95 {
    oracle name="[Core Oracles \/ Descriptor](datasworn:oracle_rollable:starforged\/core\/descriptor)" result="Constructed" roll=22
    oracle name="[Core Oracles \/ Focus](datasworn:oracle_rollable:starforged\/core\/focus)" result="Creation" roll=19
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Peril](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/peril)" result="Mechanical trap" roll=49

```
A series of crystalline spikes shoot out of the walls, floor and ceiling. I try to dive out of the way. 
```iron-vault-mechanics
move "[Face Danger](datasworn:move:starforged\/adventure\/face_danger)" {
    roll "Edge" action=5 adds=0 stat=2 vs1=9 vs2=8
}
move "[Endure Harm](datasworn:move:starforged\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=3 vs1=4 vs2=8
    burn from=7 to=2
}

```

