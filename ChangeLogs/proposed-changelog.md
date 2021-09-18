# TCG's Chill Pack  
## Proposed Changelog  
### Release 2.2.0 - Major Configuration changes and mod updates  
### Mods Added  
- N/A

### Mods Removed  
- N/A  

### Mods Updated  
- CodeChickenCore (1.7.10-1.0.7.47-universal > CodeChickenCore-1.7.10-1.0.7.48-universal)  
- ExtraPlanets (1.7.10-2.1.3 > 1.7.10-2.1.4)  

### Configuration Changes  
- Normalized ore generation to prevent multiple ores of same type from spawning, allowing for easier storage.
- Forestry: Disabled copper and tin  
- Galacticraft: Disabled Overworld generation of copper, Aluminum and tin  
- Railcraft: Disabled update checking, disabled generation of copper, gold, iron, lead, and tin  
- IndustrialCraft 2: Disabled Copper, Tin, Lead  
- Immersive Engineering: Disabled Silver, Nickel, Lead, Copper, Aluminum (Bauxite)  
- MUD: Set update checker to false  
- Mekanism: Disabled copper, tin generation  
- Tinker's Construct: Disabled copper, Aluminum and tin ores  

### Release 2.1.2 - Minor Configuration Changes and Mod Updates  
### Mods Added  
- N/A  

### Mods Removed  
- N/A  

### Mods Updated  
- AE2 Stuff (rv3-0.5.1.9 > 0.5.1.61)  
- Extra Planets (2.1.2 > 2.1.3)  

### Configuration Changes  
- CustomMainMenu: Updated configs to reflect new support system  

### Other Notes  
- N/A  

### Release 2.1.1 - Mod Updates and Configuration Changes  
### ExtraUtilities 2 causes opening issues in other launchers, only Twitch launcher is currently officially supported, open bug reports to report success of pack launch "as-is" (no disabled/removed mods) and testing to confirm will add that launcher to the list of 'supported' launchers  
### Potentially world-destroying update! Anytime a mod is added/removed it has the potential to destroy existing worlds, update at your own risk!  
### Mods Added:  
- N/A  

### Mods Removed:  
- BetterStorage, already plenty of blocks from other mods for storage  
- Ender Compass (project deleted from CurseForge entirely)  

### Mods Updated:  
- Carpenter's Blocks (3.3.8.1 > 3.3.8.2)  
- ExtraPlanets (2.0.6 > 2.1.2)  
- IronTanks (1.1.16 > 1.1.16.16)  

### Resource Pack(s) Updated:  
- Soartex Fanver - Modded  

### Configuration Changes:  
- Disabled the use of the Aether Menu System to allow the custom title screen to be the default  
- Set AgriCraft to only create water pads while sneaking (QoL change); whitelisted Forestry humus for AgriCraft crops   
- Disabled Aroma1997's version checking, no need to dial home and waste bandwidth  
- Toned down yellorium generation a little bit  
- Increased landmass percentage to 30 in BoP terraingen  
- In cofh core, increased FlatBedrock layers from 2 to 3, just in case  
- Decided to use the alternate model for the EnderIO dimensional transceiver; put a 5 second cooldown on travel anchors; increased max distance to 64; increased the default farming area for double- and octadic-equipped farming stations  
- Added some additional fortunes to EnderIO addons  
- Increased the base health modifier in hardmode for EnderZoo from 1.1 to 1.5; increased range of dire wolf from 4.0 to 6.0; increased damage modifier for dire wolf in hard mode to 1.5; set enderminy minimum Y spawn level to 15; allow enderminies to spawn in lit areas  
- Increased Galacticraft rocket fuel factor to 5 to account for infinite oil/fuel capabilities in the pack  
- Enabled alternative crafting mats in ProjectE (require a nether star instead of a diamond in some recipes); added in a 60 tick cooldown for ProjectE projectile weapons  
- Increased dimlet stack size from 16 to 64; changed dungeonChance to 75 from 100; disabled the limit on maximum dimensions per player (this will be changed for servers)  
- Disabled the Backpack 3d model  
- Increased chunks allow to be loaded via ChickenChunks; changed away timeout to infinite (will be different for server pack); disabled update check since it checks for latest available regardless of MC version; set maximum chunks per chunkloader to op maximum (open a ticket if this causes issues in ssp only, server configs will be different)  
- Increased particle tick rate to 100 for Chisel blocks; enabled chiseling to/from vanilla leaves; disabled velocity multiplier for concrete (who the hell finds this not annoying?!); made concrete a full block; increased marble gem from 7 to 8  
- Disabled CodeChickenCore dial-home feature (update check); leaves now only replace air when growing  
- Changed http_whitelist for computercraft to pastebin, github, and computercraft.info  
- Disabled update check for EnderStorage; increased inventory size to 6x9  
- Enabled minimal textures for ExtraTIC, hopefully increases client performance for potatoes  
- Disable Forge's version check (I mean seriously); decreased defaultSpawnFuzz from 20 to 2  
- Deleted an unused category in Headcrumbs  
- Increased maximum and minimum baby heatscar spiders on Spider death; blacklisted sulfur clouds from overworld  
- increased the emc value of alchemical coins (if enough complaints about breaking 'balance' are received will change back) in ProjectE Aether addon  
- Blanked guid for server in pluginmetrics; disabled reporting for ssp  
- Increased StorageDrawers controller range to 36 (for even bigger storage setups!)  
- Disabled particles from activated waystones; halved warp stone cooldown  
- Disabled update checks for wireless crafting terminal  

### Notes:
- A lot of these configs are to increase performance client-side. Any server-side mods (or mods that only serve a purpose on a server) will be removed, there will be separate configs optimized for being on a server (client-side only mods will not be in server-pack)  
- Yes, potentially a new server pack is in the works for people who like playing on older versions of modded Minecraft (I know I do from time to time)  
- Will potentially be creating a custom background for the options menu (set via randomthings)  

### Release 2.1.0 - Mod Update
### Mods Added:  
- N/A  

### Mods Removed:  
- N/A  

### Mods Updated:  
- ExtraPlanets(1.7.10-2.0.4 > 1.7.10-2.0.6)


### Release 2.0.2 - Config Update  
### Mods Added:  
- N/A  

### Mods Removed:  
- ExtraGolemsMetalAddon (author removed it from CurseForge)  

### Mods Updated:  
- ExtraPlanets (2.0.1 > 2.0.4)  
- Waystones (1.0.10 > 1.0.12)  

### Config Changes:  
- Updated CMM to reflect new Discord community.

### Release 2.0.1 - Config Fix  
### Mods Added:  
- N/A  

### Mods Removed:  
- N/A  

### Mods Updated:  
- N/A  

### Config Changes:  
- Brought the server configs to single-player, sorry about forgetting it in last update.

### Release 2.0 - Final Release
### Mods Added:  
- Iron Chests (yes, I'm readding them, hush)  

### Mods Removed:  
- N/A  

Mods Updated:  
- DiscordIntegration (3.0.4 > 3.0.5)  
- ExtraPlanets (1.9.4 > 2.0.1)  
- IronTanks (1.1.15.65 > 1.1.16)  
- Waystones (1.0.5 > 1.0.10)  

### Notes: This is going to be the final regular release of this version of Chill Pack. I have moved on to working on Chill Pack 2 (1.10.2) and Chill Pack 3 (1.12.2). The only updates from here on out will be bug fix updates for any mods still updating. I appreciate all of the support from my friends (Tadakino, Broot, theleftmouseknop, MjolnirsRevenge, animorphed, BlockheadTrouble and many others) and the community. I hope everyone continues to enjoy this version of Chill Pack, 1.7.10 was definitely the Golden Age of modded and was one of the reasons I started here. Now onward toward the present!  The server.dat is also removed because I am no longer hosting a server. There will also be no new server packs. Too many instabilities to make it worth multiplayer.  

### Release 1.5  
### Mods Added:  
- Unidict  
- AE2 Stuff  
- Hardcore Ender Expansion  
- Gendustry  
- Immersive Engineering  
- NEI Addons  
- AgriCraft  
- Magical Crops  


### Mods Removed:  
- Hopper Ducts  
- Iron Chests  
- Iron Chest Minecarts  
- NetherPortalFix  
- Eureka  
- Backlytra  
- BetterFps  


### Updated:  
- ExtraPlanets (1.8.9 > 1.9.0)  

### Configs Changed:  
- Ender IO powered spawner settings changed for wither skeleton, wireless charger range set to 0  
- Iguana's Tinker Tweaks tweaked  
- Changed displayed power units in Applied Energistics to RF  
- Made BigReactors funny  
- Disabled MineFactoryReloaded Auto-Spawner, disabled MFR chunk loader, doubled the energy cost for the Rancher, enabled bright rednet colors  
- Disabled vanilla ender chests in EnderStorage  
- Turned down oil gen factor to 0.5 from 2.0, enabled CoFHCore worldgen features, increased boss difficulty to 3.0, turned on hard difficulty, turned up rocket fuel factor to 3, disabled update check (since it always fails anyway), enabled space race manager pop up, disabled rocket launching from the mining dimension  
- Enabled OP interaction with chunkloaders on ChickenChunks, disabled dimension reloading (Mystcraft not installed anwyay), limited max chunks to 200 per chunk loader, limited players to only 500 chunks, set chunkloaders to require players to be logged in to keep chunks loaded, set timeout to 30 minutes  
- Set Gravestones so only owner can break blocks (to prevent griefing and theft)  
- Increased maximum heatscar spiders on death from 4 to 8, increased minimum from 2 to 3  
- Enabled EnderIO and BuildCraft integration for Simply Jetpacks  
- Disabled Nether Ores explosion, halved pigmen aggro range to 16  
- Enabled ProjectE Tome of Knowledge to be crafted  
- Enabled TConstruct connected textures  
- Adjust global spawn rate in Moo Fluids from 8 (matching vanilla cows) to 6  
