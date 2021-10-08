# ION FURY: ANGER MANAGEMENT (WIP 2.0 UPGRADE)

<img src="https://imgur.com/Y2q9K4B.png"/>

## INTRODUCTION
- Welcome to Anger Management, an Ion Fury mod made to improve gameplay in various ways as well as providing some new content for the creative mappers out there. Below you can find a list of features in detail.

## INSTALLATION

- Go to "Clone or Download" then select "Download Zip".
- Simply export all the folders in the zip file into your main Ion Fury folder under steam.
- This is typically the following folder: C:/Steam/steamapps/common/Ion Fury/
- Dump all the files provided in the zip to this folder. Make sure to backup any folder that has the same name as the ones in here!
- To uninstall simply remove these folders.

## FEATURES

## Weapons
----------

* Loverboy fire sound changed with a beefier one.
* Shotgun fire sound changed with a beefier one.
* Fire damage of SMG increased by 1 over time, and chance for enemies to catch fire increased a tiny bit.
* Loverboy aim fuckup halved.
* SMG now deals its regular damage when used akimbo rather than 80% of it.
* SMG no longer has bullets going awkwardly to the sides once held for long, however it has randomized spread with angles growing the longer you hold fire. Area is rectangular.
* Weapons have their clip values shown on hud.
* Grenade launcher is removed from it's own slot and made into a "custom ammo type" menu for the shotgun. You need to bind a key for this under options.
	- You can select regular, grenade or explosive shells. You will be prompted with the ammo selection menu when you press that key.
* Shotgun can now fire explosive shells. These spawn randomly in place of regular shells with 25% chance. If you don't want these to randomly appear, comment out the "include scripts/am_mutator_i.con" in "am.con" (Double // at the beginning).
* Minigun shots penetrate fleshy enemies. (Regular cultists etc., not Brutes or Skinjobs)


## Enemies
----------

* Brute napalm ball does radius damage now.
* Brute and Skinjob flames spread a bit more, there are a bit more flames around and the flames linger 33% longer.
* Brute melee damage scales with game skill, lowest is 10, maximum 28.
* Brutalizer twins have different attacks now. Enjoy the surprise!
* Diopede and Zombie GDF damage increased by 50% on average.
* There are new Cultist types now.
	- One that shoots firey energy blasts (similar to the Drone) instead of bullets. This has a 30% chance to appear in place of a regular cultist.
		+ Additionally, you can place this in maps. Palette 15 on a cultist will make it into this version.
	- One that fires unless the line of sight is broken. Palette 78 will make a cultist into this type. This has a 10% chance to appear in place of a regular cultist. Also has a little more health.
	- NOTE: If you don't want these to randomly appear, comment out the "include scripts/am_mutator_e.con" line in "am.con" (Double // at the beginning). That's the enemy mutator file.
* There is a new Diopede type that spits acid in more areas at once and has more overall health. It has palette 137 and is a bit bigger than the regular diopede.
* You can now place enemies with different palette colors in your maps. The default colors will be instantiated if palette is left as is, which is 0.
* Added a new enemy: Seeker Drone (Tile 11744). Acts a bit like the drones but they are weaker, and can sometimes move to dodge while firing. They do area damage when dead.
* Added a new enemy: Cultist Commander (Tile 12843). Highly modified human wearing an exoskeleton. Can be very tough, place sparingly. Does following:
	1. Shoot four times with an auto shotgun if player is close. At very close ranges he won't stop and will be more accurate.
	2. Shoot with a precise railgun (telegraphed) if player is far away. Take cover!
	3. If hurt, activate a shield that blocks every shot, but has a set health. When the shield is active, certain weapons do less damage.
	4. Certain attacks are more powerful against it, and certain ones are very weak.
	- There's another variant of this, pal 128 that has a flamethrower for close range and a grenade launcher for longer ranges, and starts with more health.


## Pickups
----------

* Overstacking health no longer degenerates.
* Radars have 33% chance to be replaced by a backpack that boosts your ammo capacities by 10% on pickup.
* Portable medkits have 20% chance to be replaced by a syringe that permanently boosts maximum health capacity by 5.
* New pickup: Buddy. Create a robot buddy around you that shoots enemies and follows you around. You need to bind a new key for this.
	- Has 25% chance to spawn in place of a medkit. If you don't want these to randomly appear, comment out the "include scripts/am_mutator_i.con" in "am.con" (Double // at the beginning).
* New pickup: Deflector. Deflect back all projectiles while completely nullifying hitscan damage. You need to bind a new key for this.
	- Has 25% chance to spawn in place of a medkit. If you don't want these to randomly appear, comment out the "include scripts/am_mutator_i.con" in "am.con" (Double // at the beginning).
	

## Miscellaneous
----------------

* Third person Shelly run animation made a little faster.
* Player screen flashes the right colors when harmed by something after being harmed by slime / acid damage.


## CONTACT
- You can contact me in Discord under DrkKsy#9327.