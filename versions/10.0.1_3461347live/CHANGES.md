# live · 10.0.1_3461347live

| | |
|---|---|
| Build date | 2026-06-23 13:34 UTC |
| CDN version | `10.0.1_3461347live-1782221641` |
| Key | `10.0.1_live` |
| Compared with | [10.0.1_3460394live](../10.0.1_3460394live/CHANGES.md) (2026-06-22 20:36 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 211 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_260623]
+ $[id=Recurring_Charm_Bundle_260623]
+ $[id=Recurring_Dev_Bundle_260623]
- $[id=S53].metaData.hiddenIfNotOwned: false
+ $[id=S53].metaData.hiddenIfNotOwned: true
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[12].contentVersion: "4d29eb46d0d874dc430a5b29c71cd3eca4c43511"
+ $.entries[12].contentVersion: "2a835b9bbd7e4f1842e41abf1863f2932d78e7a6"
- $.entries[88].contentVersion: "bae4f06e8f29abda8a4d6fa30e950095d7908bae"
+ $.entries[88].contentVersion: "f13b3cd3a7a1bae87cdd55d3c0804dc9fb1ba889"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.specialsRecommendations[id=Anniversary_Sale]
```

