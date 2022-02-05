# performer
Simple Fabric modpack with exclusively performance, bugfix, utility and some
UI mods.

This is the server version of the modpack.

## Mods
### General Bugfix & Tweak Mods
- [Carpet](https://www.curseforge.com/minecraft/mc-mods/carpet)
- [Carpet Extra](https://www.curseforge.com/minecraft/mc-mods/carpet-extra)
- [Fabrication](https://www.curseforge.com/minecraft/mc-mods/fabrication)

### Bugfixes
- [FabricCrossDimTPFix](https://modrinth.com/mod/fabriccrossdimtpfix)
- [Keep Head Names](https://www.curseforge.com/minecraft/mc-mods/keepheadnames)
- [Multi World Borders](https://modrinth.com/mod/worldborderfix)
- [AntiShulkerDupe](https://modrinth.com/mod/antishulkerdupe/versions)
- [Wither Cage Fix](https://www.curseforge.com/minecraft/mc-mods/wither-cage-fix)
- [Fix Experience Bug](https://www.curseforge.com/minecraft/mc-mods/fix-experience-bug)
- [AttributeFix](https://www.curseforge.com/minecraft/mc-mods/attributefix)
- [NetherPortalFix](https://www.curseforge.com/minecraft/mc-mods/netherportalfix-fabric)
- [Boat Fall](https://modrinth.com/mod/boat-fall)
- [Dimension Fix](https://www.curseforge.com/minecraft/mc-mods/dimension-fix-some-forge-patches-ported)
- [Advancements Debug](https://www.curseforge.com/minecraft/mc-mods/advancements-debug)
- [XL Packets Fabric](https://www.curseforge.com/minecraft/mc-mods/xl-packets-fabric)
- [CleanCut](https://www.curseforge.com/minecraft/mc-mods/cleancut)

### Bugfixes - Server Only
- [Illegal Stack Fixer](https://www.curseforge.com/minecraft/mc-mods/illegal-stack-fixer)

### Performance
- [Starlight](https://www.curseforge.com/minecraft/mc-mods/starlight)
- [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium)
- [FerriteCore](https://www.curseforge.com/minecraft/mc-mods/ferritecore-fabric)
- [FastBench](https://www.curseforge.com/minecraft/mc-mods/fastbench-for-fabric)
- [Fast Furnace](https://www.curseforge.com/minecraft/mc-mods/fast-furnace-for-fabric)
- [LazyDFU](https://www.curseforge.com/minecraft/mc-mods/lazydfu)
- [Krypton](https://www.curseforge.com/minecraft/mc-mods/krypton)
- [Alternate Current](https://www.curseforge.com/minecraft/mc-mods/alternate-current)
- [Clumps](https://www.curseforge.com/minecraft/mc-mods/clumps)
- [ServerCore](https://www.curseforge.com/minecraft/mc-mods/servercore)

### Server Administration
- [JLine for Dedicated Server](https://www.curseforge.com/minecraft/mc-mods/jline-for-minecraft-dedicated-server)

### Utilities
- [Inventory Sorting](https://www.curseforge.com/minecraft/mc-mods/inventory-sorting)
- [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes)
- [BadStdOut](https://www.curseforge.com/minecraft/mc-mods/badstdout)
- [Textile Backup](https://www.curseforge.com/minecraft/mc-mods/textile-backup)
- [Notify](https://www.curseforge.com/minecraft/mc-mods/notify)

### User Interface
- [Roughly Enough Items](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items)
- [AppleSkin](https://www.curseforge.com/minecraft/mc-mods/appleskin)
- [Clickable advancements](https://www.curseforge.com/minecraft/mc-mods/clickable-advancements)
- [Styled Player List](https://www.curseforge.com/minecraft/mc-mods/styled-player-list)
- [Drogtor the Nickinator](https://www.curseforge.com/minecraft/mc-mods/drogtor)
- [ItemFlexer](https://www.curseforge.com/minecraft/mc-mods/itemflexer)

### Libraries
- [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api)
- [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config)
- [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric)
- [Balm](https://www.curseforge.com/minecraft/mc-mods/balm-fabric)

## Configuration
### Carpet
Check the github of [Carpet](https://github.com/gnembon/fabric-carpet) and
[Carpet Fixes](https://github.com/gnembon/carpet-extra) for a list of all settings.
To configure the mod, type `/carpet setDefault <setting> <value>` in the server
command line. You can also use the configuration included in this modpack by copying
the content of config/carpet/default_carpet.conf to world/carpet.conf. If the file
world/carpet.conf doesn't exist, create it.

<details>
  <summary>Bugfixes:</summary>

  - ctrlQCraftingFix true
  - leadFix true
  - lightningKillsDropsFix true
  - placementRotationFix true
  - updateSuppressionCrashFix true
</details>

<details>
  <summary>Optimizations:</summary>

  - lagFreeSpawning true
  - maxEntityCollisions 40
  - optimizedTNT true
</details>

<details>
  <summary>Utilities:</summary>

  - antiCheatDisabled true
  - cleanLogs true
</details>

### Carpet Extra
<details>
  <summary>Bugfixes:</summary>

  - doubleRetraction true
  - hopperMinecart8gtCooldown true
  - hopperMinecartItemTransfer true
  - reloadSuffocationFix true
  - repeaterPriorityFix true
</details>

### Fabrication
To configure Fabrication, join your server as op, find Fabrication in the mod
menu, and select server in the top right of your screen. Then enable/disable
whatever options you want.

<details>
  <summary>General:</summary>

  - profile green
</details>

<details>
  <summary>Fixes:</summary>

  - adventure_tags_in_survival true
  - fix_superflat_bad_structures true
  - furnace_minecart_pushing true
  - silverfish_step true
  - stable_cacti true
  - sync_attacker_yaw true
</details>

<details>
  <summary>Utility:</summary>

  - extra.chat_markdown true
  - hide_armor true
  - legacy_command_syntax true
  - mods_command true
  - ping_privacy true
</details>

<details>
  <summary>Tweaks:</summary>

  - alt_absorption_sound true
  - cracking_spawn_eggs true
  - ghast_panic true
</details>

<details>
  <summary>Unsafe:</summary>

  - disable_breaking_speed_check true
  - disable_moved_too_quickly true
</details>
