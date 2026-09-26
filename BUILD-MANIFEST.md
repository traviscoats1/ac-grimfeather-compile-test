# AzerothCore Grimfeather compatibility test manifest

Frozen: 2026-09-26

This repository exists only to test whether the planned module stack compiles together.
The SHAs below are intentionally pinned for reproducibility.

## Core and compiled modules

| Component | Repository | Branch | Frozen SHA |
|---|---|---|---|
| AzerothCore core | Grimfeather/azerothcore-wotlk | master | 1a7e71b30226444b8403662b073e5b764535cd10 |
| Playerbots | mod-playerbots/mod-playerbots | master | 7bae1b5c58c76a0aa20381155edc08096d1485b2 |
| Individual Progression | Grimfeather/mod-individual-progression | master | d5e393bdc4624239d432d27d3ad2178abf8b94e9 |
| Character Services | Grimfeather/mod-character-services | main | f43bc2c98aa7a291b673158fd578be304607b5e1 |
| Reagent Bank Account | Grimfeather/mod-reagent-bank-account | master | 80bfaa41ef604c22a0afce93e286f7e043f2b430 |
| AHBot | azerothcore/mod-ah-bot | master | c11d8318cbd8714a9980f9464f78e07d3d48a70a |
| Transmog | azerothcore/mod-transmog | master | 0d85cbc53d63ce2df8527169ce6ae47f5f6f6ba8 |
| Account Mounts | azerothcore/mod-account-mounts | master | 0a3b4c4cc084ebbbb7e7e07f88222a08a70b0dde |
| Account Achievements | azerothcore/mod-account-achievements | master | bfbe3677635feeef823057964e028e023633115a |
| Individual XP | azerothcore/mod-individual-xp | master | 503471f766bc4f21dca0aa05e6a9d3d40718a780 |
| ALE | azerothcore/mod-ale | master | bd74eae623ca63154d3eb49e1d187e872ef13370 |
| Dungeon Clear | jrad7/mod-dungeon-clear | master | 805b909c7286348e75d0561f8cc259750e6ae62b |
| MultiBot Bridge | Wishmaster117/mod-multibot-bridge | main | 1da05982e478cb00e0b6c87314afe7e0e9653ffb |
| AoE Loot | azerothcore/mod-aoe-loot | master | 57279b660a278e9b3a1afa425e7c7a5edc72b7bb |
| Junk to Gold | noisiver/mod-junk-to-gold | master | 2134690bb03899e5c9e44d0682e8e6abf0bbbaf2 |
| NPC Enchanter | azerothcore/mod-npc-enchanter | master | af32add66eafc0e0eb8775999e76ceed75f18b74 |
| NPC Buffer | azerothcore/mod-npc-buffer | master | 532a6ba80c31b673338fcdb747cb2226bec4887e |
| Token Turn-in | Zerathane/mod-token-turnin | master | 73e447c499751559549e129a39c58c42fe661e73 |
| Skip DK Starting Area | azerothcore/mod-skip-dk-starting-area | master | cd0bac42056cc469399487269acbb96264ff813e |

## Deliberately outside the C++ compile test

- DreamCore Paragon Anniversary: ALE/Lua + SQL
- Acore Mall: SQL/world-database content
- MultiBot Chatless: client addon
- PlayerBotManager: client addon
- Dungeon Clear client addon
- MogIt/TransmogTip UI: client addons

A green build means this exact C++ source stack compiled together. It does not claim gameplay/runtime validation.
