# live · 10.0.0_3445033live

| | |
|---|---|
| Build date | 2026-06-16 16:18 UTC |
| CDN version | `10.0.0_3445033live-1781626700` |
| Key | `10.0.0_live` |
| Compared with | [10.0.0_3444682live](../10.0.0_3444682live/CHANGES.md) (2026-06-16 14:25 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 216 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=GS_Torso036_01].purchasable: false
+ $[id=GS_Torso036_01].purchasable: true
- $[id=KS_Torso025_01].purchasable: false
+ $[id=KS_Torso025_01].purchasable: true
+ $[id=10.0.0_IceNineKills_collection_item].collectionItemIds[]: "GS_Torso036_01"
+ $[id=10.0.0_IceNineKills_collection_item].collectionItemIds[]: "KS_Torso025_01"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[63].items[]: "GS_Torso036_01"
+ $.collections[63].items[]: "KS_Torso025_01"
- $.collections[63].updatedDate: "2026-03-26T13:30:27.895Z"
+ $.collections[63].updatedDate: "2026-06-16T15:57:55.957Z"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[22].contentVersion: "1d0347a052fc578ce794d6a180d184438bc68f29"
+ $.entries[22].contentVersion: "b5101faf3bed40ad29feeae6a66a015ec4b3aeda"
- $.entries[98].contentVersion: "5865d23626904b06e1b4f49c8bf0acde20596be9"
+ $.entries[98].contentVersion: "4d6e3b48d46ba690eb3a7f183632f34b0091156c"
- $.entries[193].contentVersion: "1b34feeaa213ba0dc853d93ce0228fc7e8329ed7"
+ $.entries[193].contentVersion: "f3d2494bef660b584e70df4ecd5147b6ea835356"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso025_01]
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso036_01]
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso021_05].weight: 15
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=KS_Torso021_05].weight: 13
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso028_05].weight: 14
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=GS_Torso028_05].weight: 12
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S49_Torso008_02].weight: 13
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S49_Torso008_02].weight: 11
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S25_Torso022_05].weight: 12
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=S25_Torso022_05].weight: 10
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=MT_Torso028_04].weight: 11
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=MT_Torso028_04].weight: 9
- $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=DF_Torso030_04].weight: 10
+ $.featuredCustomizationRecommendations[id=Sushi_W1].recommendations[id=DF_Torso030_04].weight: 8
```

