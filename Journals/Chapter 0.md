[[Ulan Kuzmin]] rushed to his monitoring station and muted the alarm. A powerful signal had been detected coming from Mobius, the black hole around which [[Weyland Outpost]] orbited.

Across the other side of the [[Bitter Zenith]] sector, a huge crystalline Precursor Vault appeared from out of nowhere in the orbit of [[Sapphire]]. The [[Silver Syndicate]] had tight control over all the commerce in the region with many of the major corporation headquarters located on [[Sapphire]]'s wide array of moons. This was all thrown into chaos by the arrival of the vault and most spacers were scared to fly anywhere near it. Vaults had been discovered before in deep space and on uninhabited planets but never so close to civilisation.

The [[Stellar Watchers]] quickly organised an expedition into the vault. The team reported some incredible discoveries but all contact was suddenly lost when the vault began to emit strange signals.

```iron-vault-mechanics
track name="[[Progress\/Learn the mysteries of the vaults.md|Learn the mysteries of the vaults]]" status="added"
```

That's where I come in. I'm Curtis Nadir, previously an agent for the [[Silver Syndicate]], currently a miner operating out of [[Janus Station]], for the [[Obsidian Hammers]]. Five years ago, a precursor vault was discovered on [[Dryad]] and I was sent in as part of the security team for the expedition.

We encountered strange energies and creatures in there that killed the rest of the team. I raced back to our ship, Elara Five which was altered somehow by the vault. There were strange symbols scrawled all over the walls and mysterious data in the nav computer that didn't make any sense. I flew the ship out of the vault moments before it vanished.

After that I just wanted to keep my head down. But these signals have triggered something in the Elara's nav, calling me to the vault.

I take out my black iron combat knife and swear an iron vow to go to [[Sapphire]] and get in that vault. 

```iron-vault-mechanics
track name="[[Progress\/Enter the vault at Sapphire.md|Enter the vault at Sapphire]]" status="added"
move "[Swear an Iron Vow](datasworn:move:starforged\/quest\/swear_an_iron_vow)" {
    roll "Heart" action=3 adds=0 stat=2 vs1=2 vs2=4
}

```
It occurs to me that I might know someone who could get me in...

```iron-vault-mechanics
oracle-group name="Campaign Launch Oracles: New Campaign Launch Oracles" {
    oracle name="[Campaign Launch Oracles \/ Background Assets](datasworn:oracle_rollable:starforged\/campaign_launch\/background_assets)" result="Operative" roll=54
    oracle name="[Campaign Launch Oracles \/ Backstory Prompts](datasworn:oracle_rollable:starforged\/campaign_launch\/backstory_prompts)" result="You are the sole survivor of an attack or calamity" roll=33
    oracle name="[Campaign Launch Oracles \/ Starship History](datasworn:oracle_rollable:starforged\/campaign_launch\/starship_history)" result="Inherited from a relative or mentor" roll=61
    oracle name="[Campaign Launch Oracles \/ Starship Quirks](datasworn:oracle_rollable:starforged\/campaign_launch\/starship_quirks)" result="Strange symbols are scrawled on the deck and bulkheads in the main corridor" roll=89
    oracle name="[Campaign Launch Oracles \/ Starship Quirks](datasworn:oracle_rollable:starforged\/campaign_launch\/starship_quirks)" result="Navigation logs contain coordinates to locations that do not—or should not—exist" roll=45
    oracle name="[Campaign Launch Oracles \/ Sector Trouble](datasworn:oracle_rollable:starforged\/campaign_launch\/sector_trouble)" result="Precursor sites throughout the sector emit strange signals" roll=55
    oracle name="[Campaign Launch Oracles \/ Inciting Incident](datasworn:oracle_rollable:starforged\/campaign_launch\/inciting_incident)" result="Search for a missing expedition in the depths of a precursor vault" roll=82
}
```
