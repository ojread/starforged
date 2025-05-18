I call my old colleague who organised the expedition five years ago, [[Ulan Kuzmin]]. He says he can get me security clearance to approach the vault but I must agree to bring him any artefacts that I find inside and I swear an iron vow to do so.

```iron-vault-mechanics
move "[Swear an Iron Vow](datasworn:move:starforged\/quest\/swear_an_iron_vow)" {
    add 1 "Connection"
    roll "Heart" action=5 adds=1 stat=2 vs1=1 vs2=10
}
```

He doesn't elaborate on what these artefacts are or what they might do but I have a way forward. He transfers the security codes to the Elara Five and I set a course for [[Sapphire]]. 

```iron-vault-mechanics
move "[Set a Course](datasworn:move:starforged\/exploration\/set_a_course)" {
    roll "Supply" action=4 adds=0 stat=5 vs1=1 vs2=6
}
```

I reach Sapphire without incident and my clearance is recognised by the local security force. They even escort me to the the vault.

This vault is huge; bigger than any I've seen before. Its blue and purple crystalline surface outshining even Sapphire's vast oceans.

```iron-vault-mechanics
oracle name="[Templates \/ Action + Theme](datasworn:oracle_rollable:starforgedsupp\/templates\/actiontheme)" result="Uphold Price" roll=48 {
    oracle name="[Core Oracles \/ Action](datasworn:oracle_rollable:starforged\/core\/action)" result="Uphold" roll=98
    oracle name="[Core Oracles \/ Theme](datasworn:oracle_rollable:starforged\/core\/theme)" result="Price" roll=64
}
```

As I approach I receive a message from [[Characters/Ulan Kuzmin|Ulan Kuzmin]] saying he expects to get some useful artefacts and there might be more work if I can. 

I guide the ship through a gaping hole in the vault's surface and land on a large flat area inside. 

```iron-vault-mechanics
move "[Fulfill Your Vow](datasworn:move:starforged\/quest\/fulfill_your_vow)" {
    progress-roll name="[[Progress\/Enter the vault at Sapphire.md|Enter the vault at Sapphire]]" score=8 vs1=7 vs2=2
}
```



