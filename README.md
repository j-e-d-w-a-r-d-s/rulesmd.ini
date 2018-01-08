# rulesmd.ini
This is probably *not* what you're looking for.  A custom rulesmd.ini that I use, completely unbalanced in America's favor.

## General
* `ChronoDelay=0`
* `ChronoTrigger=no`
* `ChronoMinimumDelay=0`
* `ChronoRangeMinimum=1`
* `PurifierBonus=.5`
* `V3Warhead=NUKE`

***

## Units
### Allied GI: `E1`
* `Sight=10`
* `Speed=10`
### Allied Engineer: `ENGINEER`
* `Locomotor={4A582747-9839-11d1-B709-00A024DDAFD1}`
* `MoveToShroud=yes`
* `Teleporter=yes`
### Allied Guardian GI: `GGI`
* `Sight=10`
* `Speed=10`
### Allied Rocketeer: `JUMPJET`
* `Primary=Blimpbomb`
* `Secondary=RedEye2`
* `PrimaryElite=BlimpbombE`
### Allied Spy: `SPY`
* `Locomotor={4A582747-9839-11d1-B709-00A024DDAFD1}`
* `MoveToShroud=yes`
* `Teleporter=yes`
### Allied Chrono Commando: `GHOST`
* `MoveToShroud=yes`
### British Sniper: `SNIPE`
* `;RequiredHouses=British`
* `Locomotor={4A582747-9839-11d1-B709-00A024DDAFD1}`
* `MoveToShroud=yes`
* `Teleporter=yes`
* `C4=yes`
### Libyan Terrorist: `TERROR`
* `;Prerequisite=NAHAND,RADAR`
* `Owner=Russians,Confederation,Africans,Arabs,Americans`
* `RequiredHouses=Americans`
* `Locomotor={4A582747-9839-11d1-B709-00A024DDAFD1}`
* `MoveToShroud=yes`
* `Teleporter=yes`

***

## Vehicles
### Grizzly Tank: `MTNK`
* `Secondary=RedEye2`
* `Sight=10`
* `Speed=10`
* `Locomotor={4A582742-9839-11d1-B709-00A024DDAFD1}`
* `MovementZone=Amphibious`
* `SpeedType=Hover`
* `Primary=120mmx`
* `ElitePrimary=120mmxE`
### Prism Tank: `SREF`
* `Sight=10`
* `Speed=10`
* `Locomotor={4A582742-9839-11d1-B709-00A024DDAFD1}`
* `MovementZone=Amphibious`
* `SpeedType=Hover`
### Battle Fortress: `BFRT`
* `Sight=10`
* `Speed=10`
### Allied MCV: `AMCV`
* `Locomotor={4A582742-9839-11d1-B709-00A024DDAFD1}`
* `MovementZone=Amphibious`
* `SpeedType=Hover`
### Aircraft Carrier: `CARRIER`
* `SpawnsNumber=10`
* `Locomotor={4A582742-9839-11d1-B709-00A024DDAFD1}`
* `MovementZone=Amphibious`
* `SpeedType=Hover`
### Tank Destroyer: `TNKD`
* `;RequiredHouses=Germans`
### V3 Launcher: `V3`
* `;Prerequisite=NAWEAP,NARADR`
* `SpawnsNumber=3`
* `Owner=Russians,Confederation,Africans,Arabs,Americans`
* `RequiredHouses=Americans`
* `V3EliteWarhead=NUKE`
* `V3Warhead=NUKE`
### Soviet MCV: `SMCV`
* `;Prerequisite=NAWEAP,NADEPT`
* `Owner=Russians,Confederation,Africans,Arabs,Americans`
### Yuri MCV: `PCV`
* `;Prerequisite=YAWEAP,YAGRND;YADEPT`
* `Owner=YuriCountry,Americans`
### Intruder: `ORCA`
* `ROT=10`
* `Ammo=8`
### Harvester: `CMIN`
* `Sight=10`
* `Speed=10`
* `ROT=10`
* `Storage=40`

*** 

## Buildings
### Allied Power: `GAPOWR`
* `Adjacent=10`
* `Sight=10`
* `Power=2000`
### Allied Barracks: `GAPILE`
* `Adjacent=10`
### Allied Ore Processor: `GAOREP`
* `;BuildLimit=1`
### Allied Wall: `GAWALL`
* `Adjacent=10`
* `GuardRange=10`
### Patriot Missle: `NASAM`
* `Adjacent=20`
* `ROT=20`
### Prism Tower: `ATESLA`
* `Adjacent=10`
### Grand Cannon: `GTGCAN`
* `Adjacent=10`
* `;RequiredHouses=French`
* `ROT=10`
### Yuri's Cloning Vats: `NACLON`
* `;BuildLimit=1`
### Paris Tower: `CAPARS01`
* `Capturable=true`
### Soviet Construction Yard: `NACNST`
* `Unsellable=yes`
### Oil Derrick: `CAOILD`
* `Sight=10
* `ProduceCashStartup=10000`
* `ProduceCashAmount=200`
### Allied Construction Yard: `GACNST`
* `Sight=10`

***

## Weapons
### Terrorist: `TerrorBomb`
* `Warhead=NUKE`
### Anti-Aircraft: `RedEye2`
* `Damage=200`
* `ROF=10`
* `Range=14`
### Sniper: `AWP`
* `ROF=40`
### Grand Cannon: `GrandCannonWeapon`
* `Damage=500`
* `ROF=10`
* `Speed=100`
### Sniper Elite: `AWPE`
* `ROF=20`
