# live · 10.0.0_3447582live

| | |
|---|---|
| Build date | 2026-06-17 14:32 UTC |
| CDN version | `10.0.0_3447582live-1781706743` |
| Key | `10.0.0_live` |
| Compared with | [10.0.0_3445033live](../10.0.0_3445033live/CHANGES.md) (2026-06-16 16:18 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 217 unchanged

## Modified files

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[5].LinkedEventId: "MapShowcaseSushi01"
- $.schedule[5].Description: "MapShowcase Map List"
+ $.schedule[5].Description: "Killswitch"
- $.schedule[5].GameModes[]: "MapShowcase"
+ $.schedule[5].GameModes[]: "Online"
+ $.schedule[5].GameModes[]: "KillYourFriends"
+ $.schedule[5].GameModes[]: "SecretBotMatch"
+ $.schedule[5].GameModes[]: "TutorialBotMatch"
+ $.schedule[5].GameModes[]: "ChocolateBox"
+ $.schedule[5].GameModes[]: "SeasonalEvent"
+ $.schedule[5].GameModes[]: "SeasonalEvent_FuelGenerator"
- $.schedule[5].MapsWeight.Jnk_GasStation: "1000"
+ $.schedule[5].MapsWeight.Eng_Street_01: "0"
+ $.schedule[5].MapsWeight.Swp_GrimPantry: "0"
+ $.schedule[5].MapsWeight.Swp_PaleRose: "0"
- $.schedule[6]
- $.schedule[7]
- $.schedule[8]
- $.schedule[9]
- $.schedule[10]
- $.schedule[11]
- $.schedule[12]
- $.schedule[13]
- $.schedule[14]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[186].contentVersion: "24fe05231d23f90580326d1afeedfe42b7e4f407"
+ $.entries[186].contentVersion: "c0a0762d550c017d3837daf190abb46aff43916c"
- $.entries[190].contentVersion: "0bbe526926f46bcad39669cf06745b9e02e1bb46"
+ $.entries[190].contentVersion: "c3abd8bcef9ce93f1fc845d737827f597c99b0b7"
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.GranmasCookbook
+ $.disabledItems.ThePiedPiper
```

