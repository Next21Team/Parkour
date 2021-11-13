# Parkour

_**English** | [Русский](README.ru.md)_

[![Parkour](https://img.youtube.com/vi/JHpCIqm-8T0/0.jpg)](https://youtu.be/JHpCIqm-8T0)

AMX Mod X plugin for Counter-Strike.

This plugin adds new features with parkour elements for players on your server.

Including:
- Falling hands animation
- Swimming hands animation
- Sprint ability (2 times quickly press W (forward))
- Wall jump ability
- Climb ability

When playing animations, the attack is blocked - after the action ends, it becomes available again.

## Квары
- ```pkr_vip_sprint "0"``` Only players with a specific flag have access to the sprint ability.
- ```pkr_vip_climb "0"``` Only players with a specific flag have access to the climb ability.
- ```pkr_vip_walljump "0"``` Only players with a specific flag have access to the wall jump ability.
- ```pkr_walljump_count "2"``` The maximum number of wall jumps before landing on the ground.
- ```pkr_team "0"``` The player's team for which parkour movements are available (“0″ – for all players, “1″ – only for the terrorist team, “2″ – only for the counter-terrorist team).

The flag for accessing restricted movements is defined by a constant `#define VIP_FLAG`.

In the archive with the plugin there are models with hands from Counter-Strike 1.6 (by default) and Counter-Strike Online. The model is defined by a constant `new const MODEL_V[]`.

## Authors
- [Chrescoe1](https://github.com/Chrescoe1)
