# live · 9.2.0_2781061live

| | |
|---|---|
| Build date | 2025-09-29 19:09 UTC |
| CDN version | `9.2.0_2781061live-1759172971` |
| Key | `9.2.0_live` |
| Compared with | [9.2.0_2778761live](../9.2.0_2778761live/CHANGES.md) (2025-09-26 15:58 UTC) |

## Summary

**0** added · **6** modified · **0** removed · 199 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.enableGPUBreadcrumbs: 1
+ $.enabledGPUBreadcrumbsHardware
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_250930]
+ $[id=Recurring_Charm_Bundle_250930]
+ $[id=Recurring_Dev_Bundle_250930]
+ $[id=Recurring_Killer_Bundle_250930]
+ $[id=Recurring_Survivor_Bundle_250930]
+ $[id=AP_BDG_01].defaultCost
+ $[id=AP_BDG_02].defaultCost
+ $[id=AP_BDG_05].defaultCost
+ $[id=AP_BDG_06].defaultCost
+ $[id=AP_BDG_07].defaultCost
+ $[id=AP_BDG_08].defaultCost
+ $[id=AP_BNR_01].defaultCost
+ $[id=AP_BNR_02].defaultCost
+ $[id=AP_BNR_03].defaultCost
+ $[id=AP_BNR_06].defaultCost
+ $[id=BA_BDG_01].defaultCost
+ $[id=BA_BDG_02].defaultCost
+ $[id=BA_BDG_03].defaultCost
+ $[id=BA_BDG_05].defaultCost
+ $[id=BA_BDG_06].defaultCost
+ $[id=BA_BDG_07].defaultCost
+ $[id=BA_BDG_08].defaultCost
+ $[id=BA_BDG_09].defaultCost
+ $[id=BA_BDG_10].defaultCost
+ $[id=BA_BDG_11].defaultCost
+ $[id=BA_BNR_01].defaultCost
+ $[id=BA_BNR_04].defaultCost
+ $[id=BA_BNR_05].defaultCost
+ $[id=BA_BNR_06].defaultCost
+ $[id=BA_BNR_08].defaultCost
+ $[id=BA_BNR_09].defaultCost
+ $[id=BA_BNR_10].defaultCost
+ $[id=CH_005].defaultCost
+ $[id=CH_006].defaultCost
+ $[id=CH_007].defaultCost
+ $[id=CH_008].defaultCost
+ $[id=CH_009].defaultCost
+ $[id=CH_BDG_01].defaultCost
+ $[id=CH_BDG_02].defaultCost
+ $[id=CH_BDG_03].defaultCost
+ $[id=CH_BDG_04].defaultCost
+ $[id=CH_BNR_01].defaultCost
+ $[id=CH_BNR_02].defaultCost
+ $[id=CH_BNR_03].defaultCost
+ $[id=DO_BDG_18].defaultCost
+ $[id=YE_BDG_03].defaultCost
+ $[id=YE_BDG_04].defaultCost
+ $[id=YE_BNR_03].defaultCost
+ $[id=YE_BNR_04].defaultCost
+ $[id=ZO_BDG_03].defaultCost
+ $[id=ZO_BDG_04].defaultCost
+ $[id=ZO_BDG_05].defaultCost
+ $[id=ZO_BDG_06].defaultCost
+ $[id=ZO_BDG_07].defaultCost
+ $[id=ZO_BDG_08].defaultCost
+ $[id=ZO_BDG_10].defaultCost
+ $[id=ZO_BDG_11].defaultCost
+ $[id=ZO_BDG_12].defaultCost
+ $[id=ZO_BDG_13].defaultCost
+ $[id=ZO_BNR_01].defaultCost
+ $[id=ZO_BNR_02].defaultCost
+ $[id=ZO_BNR_03].defaultCost
+ $[id=ZO_BNR_04].defaultCost
+ $[id=ZO_BNR_05].defaultCost
+ $[id=ZO_BNR_06].defaultCost
+ $[id=ZO_BNR_08].defaultCost
+ $[id=ZO_BNR_09].defaultCost
+ $[id=ZO_BNR_10].defaultCost
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[8].text: "Hit {0} Survivors with a basic attack"
+ $.locText[8].text: "Hit {0} Survivor(s) with a basic attack"
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[8].text: "Frapper {0} survivants différents avec une attaque de base"
+ $.locText[8].text: "Frapper {0} survivants avec une attaque de base"
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[403].text: "扮演{0}，破坏{1}台发电机"
+ $.locText[403].text: "扮演{1}，破坏{0}台发电机"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[11].contentVersion: "2caf9ad308ee3f8c6cf300122aecb55c8a10d730"
+ $.entries[11].contentVersion: "81206bb8a704c17f8088b96c259e78b04876a848"
- $.entries[198].contentVersion: "80119569f54a44baa8c09fbd97aed7667cc503f3"
+ $.entries[198].contentVersion: "8de8389eed02ff233a237a2a2c9d503ece704cf6"
- $.entries[202].contentVersion: "7cdbc4b4d391f98a21c8e4fc56301a64a8b414f3"
+ $.entries[202].contentVersion: "802b65c1920bf4a56720e3a13cbd82a13a924fec"
- $.entries[211].contentVersion: "f7a385e0a4450a065452e0fe6f2fe4763657ddf5"
+ $.entries[211].contentVersion: "23ed81e3126e260eeb3cfdbd45bf6921a2fcf1d2"
```

## Could not download

- `images/T_UI_ChapterBundle_SinisterGrace.png (HTTP 404)`
- `images/T_UI_CollectionBanner_NOTLC.png (HTTP 404)`
- `images/T_UI_CollectionBanner_PartyHard.png (HTTP 404)`
- `images/T_UI_CollectionBanner_SinisterGrace.png (HTTP 404)`
- `images/T_UI_SpecialPack_NOTLC.png (HTTP 404)`
- `images/T_UI_SpecialPack_PartyHard.png (HTTP 404)`
- `images/T_UI_SpecialPack_SinisterGrace.png (HTTP 404)`
- `images/T_UI_SpecialPack_Tome5.png (HTTP 404)`
- `images/T_UI_SpecialPack_Tome6.png (HTTP 404)`
- `images/T_UI_Specialpack_FallFashion.png (HTTP 404)`

