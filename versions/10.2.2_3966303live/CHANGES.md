# live · 10.2.2_3966303live

| | |
|---|---|
| Build date | 2026-11-09 19:05 UTC |
| CDN version | `10.2.2_3966303live-1794251154` |
| Key | `10.2.2_live` |
| Compared with | [10.2.2_3957877live](../10.2.2_3957877live/CHANGES.md) (2026-11-05 21:08 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 214 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=Recurring_Dev_Bundle_261110]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[19].contentVersion: "01fc0c68a94a71ab930f642e8ef80915bd0c06b5"
+ $.entries[19].contentVersion: "9fe90a3e525f81803b8380847b23ddc76de85c0a"
- $.entries[96].contentVersion: "7a7d8c4eed97af439840893e6813b852de811705"
+ $.entries[96].contentVersion: "d17eaf8c17577e3e2e239de840d524bfd2f780ff"
- $.entries[187].contentVersion: "fc77299e41b66390709295b70996803894ecf560"
+ $.entries[187].contentVersion: "37e0de66100e2484640b501a2ec8c007e937643c"
```

### [`gameplayTunables.json`](gameplayTunables.json)

[Full line-by-line diff](diffs/gameplayTunables.json.diff)

```diff
+ $.data["Firefly:TrackMMRScore"]: true
+ $.data["f:/K34/Data/Game/K34_TunableValue.K34_TunableValue:crawlduration"]: 0.8
- $.data["f:/K20/Data/Game/K20_TunableDB.K20_TunableDB:attacktrail_timeintervalbetweenpoint"]: 0.001
+ $.data["f:/K20/Data/Game/K20_TunableDB.K20_TunableDB:attacktrail_timeintervalbetweenpoint"]: 0.015
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=Vanilla_W6].recommendations[id=S45_outfit_017]
- $.featuredCustomizationRecommendations[id=Vanilla_W6].recommendations[id=K26_outfit_022].weight: 61
+ $.featuredCustomizationRecommendations[id=Vanilla_W6].recommendations[id=K26_outfit_022].weight: 58
+ $.featuredCustomizationRecommendations[id=Vanilla_W7].recommendations[id=S45_outfit_017]
- $.featuredCustomizationRecommendations[id=Vanilla_W7].recommendations[id=K26_outfit_022].weight: 58
+ $.featuredCustomizationRecommendations[id=Vanilla_W7].recommendations[id=K26_outfit_022].weight: 55
+ $.featuredCustomizationRecommendations[id=Vanilla_W8].recommendations[id=S45_outfit_017]
- $.featuredCustomizationRecommendations[id=Vanilla_W8].recommendations[id=K26_outfit_022].weight: 58
+ $.featuredCustomizationRecommendations[id=Vanilla_W8].recommendations[id=K26_outfit_022].weight: 55
```

