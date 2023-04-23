# Hero of the Villager

A Minecraft plugin for Spigot servers to prevent zombies killing villagers.

When a zombie would kill a villager, the villager is instead converted to a
zombie villager, with its trades, homes, job location, and reputation preserved.
On Hard difficulty, this is equivalent to the default behaviour. However, on
other difficulties, the vanilla game only zombifies villagers some of the time;
this plugin ensures villagers are always zombified, so you can simply heal them.

## Changelog

### 2.0.0

Forked from [VillagerSaver](https://github.com/MarioFinale/VillagerSaver), revamped build
- Revamped build

### 1.3.2
- Plugin now checks on death events for improved performance (fewer function calls)
- Plugin now uses the *zombify* function (Should fix [#18](https://github.com/MarioFinale/VillagerSaver/issues/18))
- Improved readability

### 1.3.1
- Updated to 1.19.

### 1.2.5
- Updated to 1.18.2.

### 1.2.4
- Updated to 1.18 - 1.18.1.

### 1.2.3
- Fixed logging (now using proper Bukkit logger, fixes [#15]https://github.com/MarioFinale/VillagerSaver/issues/15)).
- Fixed nag message about using stdout.
- Minor code changes to improve readability
- Change plugin messages to better communicate plugin status.
- Add a severe waring message about the plugin being hijacked and advising user to always download the plugin from a trusted source (GitHub). Fixes [#16](https://github.com/MarioFinale/VillagerSaver/issues/16).

### 1.2.2
- Updated to 1.17.1

### 1.2.1
- Updated to 1.17

### 1.2.0
- Fixes [#13](https://github.com/MarioFinale/VillagerSaver/issues/13) (Merges Kasama's fork into main)

### 1.1.6
- Fixes [#10](https://github.com/MarioFinale/VillagerSaver/issues/10) (Many thanks to Kasama)

### 1.1.5
- Spigot support.

### 1.1.4
- Adds [#8](https://github.com/MarioFinale/VillagerSaver/issues/8)

### 1.1.3
- Fixes [#7](https://github.com/MarioFinale/VillagerSaver/issues/7)
- Updated to 1.16.5

### 1.1.2
- Fixes [#6](https://github.com/MarioFinale/VillagerSaver/issues/4)

### 1.1.1:
- World blacklist, usage:
  - /villagersaver blacklistworld {world_name}
  - /villagersaver unblacklistworld {world_name}
- Fixes [#4](https://github.com/MarioFinale/VillagerSaver/issues/4)
- Fixes [#3](https://github.com/MarioFinale/VillagerSaver/issues/3)

The blacklist is saved on /plugins/VillagerSaver/WorldBlackList.yml I do not recommend editing this file manually.



## Support

The maintainers of this fork are not currently accepting donations, but you can
support the author of the original version here:

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/W7W52TMLM)
