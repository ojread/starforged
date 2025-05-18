```iron-vault-mechanics
oracle name="[Precursor Vault Oracles \/ Interior \/ Inner First Look](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/first_look)" result="Damage and debris" roll=19
```

There are signs of some kind of struggle in here, some discarded equipment and damaged crystals. 

I set the ship's sensors to scan the interior to plan my exploration. 

```iron-vault-mechanics
move "[Secure an Advantage](datasworn:move:starforged\/adventure\/secure_an_advantage)" {
    roll "Wits" action=3 adds=0 stat=3 vs1=1 vs2=10
    track name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" status="added"
}
move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
    add 1 "Scanned"
    roll "Wits" action=5 adds=1 stat=3 vs1=6 vs2=3
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="Vertical shaft" roll=85
progress from=0 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="dangerous" steps=1

```

I leave the landing pad and walk down a wide corridor that the sensors showed going deeper into the vault. Sure enough I come across a vertical shaft descending deep into the structure.

```iron-vault-mechanics
move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
    roll "Wits" action=6 adds=0 stat=3 vs1=4 vs2=1
    progress from=4 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="formidable" steps=1
}

```

I leap into the shaft and allow the jets on my EVA suit to control my descent.

```iron-vault-mechanics
move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=4 vs2=10
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="Narrowing or widening path" roll=53
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Peril](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/peril)" result="Radioactive hot spot" roll=63
progress from=8 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="formidable" steps=1

```


At the bottom, the corridor continues but narrows considerably. My suit detects a radiative hot spot that I rush through.

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:starforged\/suffer\/endure_harm)" {
    roll "Health" action=5 adds=0 stat=4 vs1=9 vs2=8
}
move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
    add 1 "explorer"
    roll "Wits" action=1 adds=1 stat=3 vs1=7 vs2=6
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="Mazelike passages" roll=47
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Peril](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/peril)" result="Toxic atmosphere" roll=88
progress from=12 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="formidable" steps=1

```

The passage branches off into all directions and I get lost in a mazelike section. Then I hear a hissing as a toxic gas descends onto the area. This place is trying to kill me! 

```iron-vault-mechanics
move "[Endure Harm](datasworn:move:starforged\/suffer\/endure_harm)" {
    roll "Health" action=1 adds=0 stat=4 vs1=6 vs2=6
}
```
My suit fails to stop it in time and I choke down the toxic gas. I vomit on the spot and run through the maze, choking.

I take a moment to try and heal these injuries. 

```iron-vault-mechanics
move "[Heal](datasworn:move:starforged\/recover\/heal)" {
    roll "Wits" action=6 adds=0 stat=3 vs1=4 vs2=6
}
```
Back to full heath, I continue to explore the vault.

```iron-vault-mechanics
move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
    add 1 "explorer"
    roll "Wits" action=4 adds=1 stat=3 vs1=4 vs2=1
}
```
I find some discarded supplies from the previous expedition. I'm heading the right way at least.

```iron-vault-mechanics
move "[Undertake an Expedition](datasworn:move:starforged\/exploration\/undertake_an_expedition)" {
    roll "Wits" action=4 adds=0 stat=3 vs1=7 vs2=3
    burn from=9 to=2
    progress from=16 name="[[Progress\/Find the missing expedition.md|Find the missing expedition]]" rank="formidable" steps=1
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Feature](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/feature)" result="Clinging mist" roll=14
move "[Explore a Waypoint](datasworn:move:starforged\/exploration\/explore_a_waypoint)" {
    add 1 "explorer"
    roll "Wits" action=3 adds=1 stat=3 vs1=1 vs2=7
}
oracle name="[Precursor Vault Oracles \/ Interior \/ Interior Peril](datasworn:oracle_rollable:starforged\/precursor_vault\/interior\/peril)" result="Tempting location or object holds hidden dangers" roll=81

```

I explore an area filled with clinging mist and come across a raised podium in the centre. On it is some kind of weird alien device, crystalline but with a multicolored blinking light. I take it, thinking of [[Characters/Ulan Kuzmin|Ulan Kuzmin]] but it triggers a rumbling sound, the mist begins to thin and I see something approach.

```iron-vault-mechanics
oracle-group name="Creature: New Creature" {
    oracle name="[Creature Oracles \/ Environment](datasworn:oracle_rollable:starforged\/creature\/environment)" result="Interior" roll=11
    oracle name="[Basic form](datasworn:oracle_rollable:starforged\/creature\/basic_form\/interior)" result="Snake \/ eel" roll=67
    oracle name="[Creature Oracles \/ Scale](datasworn:oracle_rollable:starforged\/creature\/scale)" result="Small (dog-sized)" roll=12
    oracle name="[Creature Oracles \/ Creature First Look](datasworn:oracle_rollable:starforged\/creature\/first_look)" result="Fangs or rows of teeth" roll=44
    oracle name="[Creature Oracles \/ Creature First Look](datasworn:oracle_rollable:starforged\/creature\/first_look)" result="Ridges or plates" roll=86
    oracle name="[Creature Oracles \/ Encountered Behavior](datasworn:oracle_rollable:starforged\/creature\/encountered_behavior)" result="Camouflager" roll=16
}
```

A large fanged snake with plate like scales emerges from the mist. When it sees me its scales all shimmer and it becomes almost invisible against the mist.

```iron-vault-mechanics
move "[Enter the Fray](datasworn:move:starforged\/combat\/enter_the_fray)" {
    roll "Wits" action=4 adds=0 stat=3 vs1=10 vs2=8
    track name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" status="added"
    position from="out of combat" to="in a bad spot"
}
move "[React Under Fire](datasworn:move:starforged\/combat\/react_under_fire)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=6 vs2=6
}

```
My armour deflects the snake's bite and breaks one of its teeth. 
```iron-vault-mechanics
position from="in a bad spot" to="in control"
move "[Strike](datasworn:move:starforged\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=2 vs1=3 vs2=1
    burn from=8 to=2
    progress from=0 name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" rank="formidable" steps=2
}

```
I open fire with my rifle and injure the snake. I try to position myself behind the podium to keep some distance between us. 
```iron-vault-mechanics
move "[Gain Ground](datasworn:move:starforged\/combat\/gain_ground)" {
    add 1 "veteran"
    roll "Wits" action=5 adds=1 stat=3 vs1=6 vs2=1
    progress from=8 name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" rank="formidable" steps=1
}
move "[Gain Ground](datasworn:move:starforged\/combat\/gain_ground)" {
    roll "Wits" action=6 adds=0 stat=3 vs1=6 vs2=2
    progress from=12 name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" rank="formidable" steps=1
}
move "[Strike](datasworn:move:starforged\/combat\/strike)" {
    roll "Edge" action=1 adds=0 stat=2 vs1=6 vs2=2
    burn from=7 to=2
    progress from=16 name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" rank="formidable" steps=2
}

```
I adjust my eyepiece to detect the snake's body temperature and score another strong hit.
```iron-vault-mechanics
move "[Strike](datasworn:move:starforged\/combat\/strike)" {
    add 1 "veteran"
    roll "Edge" action=1 adds=1 stat=2 vs1=9 vs2=5
}
```
My armour presets that to a 4 for a weak hit so I hurt it but the snake slithers around me. 
```iron-vault-mechanics
progress from=24 name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" rank="formidable" steps=2
position from="in control" to="in a bad spot"
move "[React Under Fire](datasworn:move:starforged\/combat\/react_under_fire)" {
    roll "Wits" action=2 adds=0 stat=3 vs1=5 vs2=6
}

```
My armour doesn't protect me this time and the snake bites my leg. 
```iron-vault-mechanics
move "[Endure Harm](datasworn:move:starforged\/suffer\/endure_harm)" {
    roll "Health" action=5 adds=0 stat=3 vs1=1 vs2=9
}
move "[React Under Fire](datasworn:move:starforged\/combat\/react_under_fire)" {
    roll "Wits" action=4 adds=0 stat=3 vs1=4 vs2=10
}

```
The snake curls around me and roars in my face. 
```iron-vault-mechanics
move "[Endure Stress](datasworn:move:starforged\/suffer\/endure_stress)" {
    roll "Spirit" action=6 adds=0 stat=4 vs1=2 vs2=8
}
```
This only spurs me on! 
```iron-vault-mechanics
move "[React Under Fire](datasworn:move:starforged\/combat\/react_under_fire)" {
    roll "Wits" action=1 adds=0 stat=3 vs1=4 vs2=4
}
```
My armour resists the snake's constriction and I throw it away from me. 
```iron-vault-mechanics
position from="in a bad spot" to="in control"
move "[Take Decisive Action](datasworn:move:starforged\/combat\/take_decisive_action)" {
    progress-roll name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" score=8 vs1=3 vs2=6
}

```
I open fire and hit it in the head. The camouflage shimmers and it all becomes visible. Victory!
```iron-vault-mechanics
track name="[[Progress\/Escape the camouflaged snake.md|Escape the camouflaged snake]]" status="removed"
position from="in control" to="out of combat"

```
I pocket the alien device for [[Progress/Ulan Kuzmin|Ulan Kuzmin]] and move on. 
