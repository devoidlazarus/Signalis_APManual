# Difficulty Changes

SIGNALIS will change the amount of Ammo and Healing items you pick up depending on the Difficulty. Here are the multipliers pulled from the `DyanmicDifficulty` class:

| Difficulty | Ammo Pickup Multiplier | Health Pickup Multiplier |
| --- | --- | --- |
| Casual | 1.5 | 2 |
| Normal | 1 | 1 |
| Survival | 0.5 | 1 |

All Item amounts within the Archipelago pool are referred to as their amounts received in Normal difficulty.

ex: You are playing on Survival difficulty. You receive 10mm Ammo (3) from Archipelago. You would input this command in the debug console to receive the amount of ammo appropriate for Survival difficulty:
- ```give pistolammo 2```

Where ```2``` in this instance is the original 3 10mm ammo multiplied by 0.5, **rounded up**.
