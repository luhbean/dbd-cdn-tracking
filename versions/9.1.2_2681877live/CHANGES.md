# live · 9.1.2_2681877live

| | |
|---|---|
| Build date | 2025-08-18 17:59 UTC |
| CDN version | `9.1.2_2681877live-1755539943` |
| Key | `9.1.2_live` |
| Compared with | [9.1.2_2678656live](../9.1.2_2678656live/CHANGES.md) (2025-08-15 13:30 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 197 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.analyticsRulesHVS.PartycreatedAnalytics: "HVSStrict"
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[260].text: "Complete 1 Trial as The Huntress"
+ $.locText[260].text: "Complete {0} Trial as {1}"
- $.locText[283].text: "Complete 1 Trial as Meg Thomas"
+ $.locText[283].text: "Complete {0} Trial as {1}"
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[260].text: "ハントレスとして1回の儀式を完了する"
+ $.locText[260].text: "{1}として{0}回の儀式を完了する"
- $.locText[283].text: "メグ・トーマスとして1回の儀式を完了する"
+ $.locText[283].text: "{1}として{0}回の儀式を完了する"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[1].MapsWeight.Apl_Square_Calamari: "500"
+ $.schedule[1].MapsWeight.Apl_Square_Calamari: "700"
- $.schedule[1].MapsWeight.Hos_Hospital_Calamari: "500"
+ $.schedule[1].MapsWeight.Hos_Hospital_Calamari: "700"
- $.schedule[1].MapsWeight.Qtm_ShatteredSqr_Calamari: "500"
+ $.schedule[1].MapsWeight.Qtm_ShatteredSqr_Calamari: "700"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[174].contentVersion: "e4c7ab1156bce830e77254719d681eb57b8acf6b"
+ $.entries[174].contentVersion: "816c56d1f06cabf6a0c1cf28f7d1e2d046c0d353"
- $.entries[192].contentVersion: "47fc8639a343e9f6ed75298f89695d9ba0c87929"
+ $.entries[192].contentVersion: "2755fef5be92403fb8d12d8abf73e062c1a01ad2"
- $.entries[198].contentVersion: "81ae456af9dd313f03cff92fdaefad4e1d27bbff"
+ $.entries[198].contentVersion: "a96dc4ac3f7c517e1f05ee2e46e6d8f4e1576e9b"
```

## Could not download

- `images/T_UI_CollectionBanner_PartyHard.png (HTTP 404)`
- `images/T_UI_SpecialPack_ModernBaroque.png (HTTP 404)`
- `images/T_UI_SpecialPack_PartyHard.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_chest.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_generator.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

