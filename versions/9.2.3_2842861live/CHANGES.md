# live · 9.2.3_2842861live

| | |
|---|---|
| Build date | 2025-10-31 14:52 UTC |
| CDN version | `9.2.3_2842861live-1761922355` |
| Key | `9.2.3_live` |
| Compared with | [9.2.3_2840921live](../9.2.3_2840921live/CHANGES.md) (2025-10-31 13:44 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 208 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=LicensorBundle_Halloween].consumptionReward[id=LS_Head006]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=LS_Torso006]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=LS_Legs006]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=MM_Body02]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=MM_W02_01]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=MM_W02_02]
+ $[id=LicensorBundle_Halloween].consumptionReward[id=MM_W02_03]
- $[id=LicensorBundle_Halloween].defaultCost[0].price: 1000
+ $[id=LicensorBundle_Halloween].defaultCost[0].price: 2280
+ $[id=LicensorBundle_Halloween].metaData.endDate: "2025-11-14T16:00:00"
+ $[id=LicensorBundle_Halloween].metaData.imagePath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Halloween.T_UI_ChapterBundle_Halloween"
+ $[id=LicensorBundle_Halloween].metaData.startDate: "2025-10-31T15:00:00"
- $[id=LicensorBundle_Halloween].metaData.discount: 0.0
+ $[id=LicensorBundle_Halloween].metaData.discount: 0.4
- $[id=LicensorBundle_Halloween].metaData.fullPrice[0].price: 1000
+ $[id=LicensorBundle_Halloween].metaData.fullPrice[0].price: 3800
- $[id=LicensorBundle_Halloween].metaData.sortOrder: 0
+ $[id=LicensorBundle_Halloween].metaData.sortOrder: 2000
- $[id=LicensorBundle_Halloween].purchasable: false
+ $[id=LicensorBundle_Halloween].purchasable: true
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[6].contentVersion: "05ce8f1c6c78485019c3092626fd6c9c853396ce"
+ $.entries[6].contentVersion: "23115d24173b948347c8c2d95a467ab2145d4b4f"
- $.entries[82].contentVersion: "a2621ad218f1f94fefe149538c24a8732cb92b49"
+ $.entries[82].contentVersion: "98c16c60f93024ec01151158ec7fc6b1e296ba06"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Maple_W7].entries[1].entryId: "TheWalkingDead"
+ $.featuredCard[id=Maple_W7].entries[1].entryId: "LicensorBundle_Halloween"
- $.featuredCard[id=Maple_W7].entries[1].type: "Collection"
+ $.featuredCard[id=Maple_W7].entries[1].type: "SpecialPack"
- $.featuredCard[id=Maple_W7].entries[2].entryId: "Rift_3_Bundle"
+ $.featuredCard[id=Maple_W7].entries[2].entryId: "TheWalkingDead"
- $.featuredCard[id=Maple_W7].entries[2].type: "SpecialPack"
+ $.featuredCard[id=Maple_W7].entries[2].type: "Collection"
- $.featuredCard[id=Maple_W7].entries[2].weight: 15
+ $.featuredCard[id=Maple_W7].entries[2].weight: 18
+ $.featuredCard[id=Maple_W7].entries[3]
```

