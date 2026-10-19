# live · 9.1.0_2658184live

| | |
|---|---|
| Build date | 2025-07-31 14:59 UTC |
| CDN version | `9.1.0_2658184live-1753973985` |
| Key | `9.1.0_live` |
| Compared with | [9.1.0_2655894live](../9.1.0_2655894live/CHANGES.md) (2025-07-30 18:47 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 200 unchanged

## Modified files

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[310].text: "Accomplissez toutes les quêtes de {0}."
+ $.locText[310].text: "Accomplissez toutes les {0} quêtes."
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].MapsWeight.Fin_Hideout: "1000"
+ $.schedule[0].MapsWeight.Fin_Hideout: "0"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[164].contentVersion: "7d175212a08bd68526cad99bb77c5d98be4497b2"
+ $.entries[164].contentVersion: "1c942d4f735ef85a622dd4a161e00466ad4c9433"
- $.entries[168].contentVersion: "bdf6e522c4399807a4d5ed6adedfdb3fd0ec02ba"
+ $.entries[168].contentVersion: "a66664427bea36d7218f7987c6849a545099423a"
- $.entries[190].contentVersion: "2efde7af320108146ddbc51d22d676c8d961463c"
+ $.entries[190].contentVersion: "14e61cd90b09d5f4de68e2fca1b0c1e7a2ed59a3"
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.Jigsawpiece
```

