# live · 8.7.2_2485436live

| | |
|---|---|
| Build date | 2025-06-02 18:34 UTC |
| CDN version | `8.7.2_2485436live-1748889244` |
| Key | `8.7.2_live` |
| Compared with | [8.7.2_2485095live](../8.7.2_2485095live/CHANGES.md) (2025-06-02 15:22 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 199 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.contentVersion.clientNewContentRebootMaxSeconds: 300.0
+ $.contentVersion.clientNewContentRebootMaxSeconds: 600.0
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_250603]
+ $[id=From_The_Rift_Bundle_250610]
+ $[id=Recurring_Charm_Bundle_250603]
+ $[id=Recurring_Charm_Bundle_250610]
+ $[id=Recurring_Dev_Bundle_250603]
+ $[id=Recurring_Dev_Bundle_250610]
+ $[id=Recurring_Killer_Bundle_250603]
+ $[id=Recurring_Killer_Bundle_250610]
+ $[id=Recurring_Survivor_Bundle_250603]
+ $[id=Recurring_Survivor_Bundle_250610]
+ $[id=Recurring_Survivor_Bundle_2_250603]
+ $[id=Kate].eventCostList
+ $[id=Kate].metaData.temporaryDiscounts
+ $[id=S28].eventCostList
+ $[id=S28].metaData.temporaryDiscounts
+ $[id=K26].eventCostList
+ $[id=K26].metaData.temporaryDiscounts
+ $[id=K30].eventCostList
+ $[id=K30].metaData.temporaryDiscounts
+ $[id=S34].eventCostList
+ $[id=S34].metaData.temporaryDiscounts
+ $[id=S41].eventCostList
+ $[id=S41].metaData.temporaryDiscounts
+ $[id=TheWitcherBundle].consumptionReward[id=JE_BNR_01]
- $[id=TheWitcherBundle].defaultCost[0].price: 5832
+ $[id=TheWitcherBundle].defaultCost[0].price: 5952
- $[id=TheWitcherBundle].metaData.fullPrice[0].price: 7290
+ $[id=TheWitcherBundle].metaData.fullPrice[0].price: 7440
- $[id=TheWitcherBundle].metaData.sortOrder: 300
+ $[id=TheWitcherBundle].metaData.sortOrder: 1000
- $[id=TheWitcherCharacterBundle].metaData.sortOrder: 295
+ $[id=TheWitcherCharacterBundle].metaData.sortOrder: 900
- $[id=Recurring_Dev_Bundle_250520].defaultCost[0].price: 1524
+ $[id=Recurring_Dev_Bundle_250520].defaultCost[0].price: 1525
- $[id=Recurring_Dev_Bundle_250520].metaData.discount: 0.4
+ $[id=Recurring_Dev_Bundle_250520].metaData.discount: 0.399997
- $[id=Recurring_Dev_Bundle_250520].metaData.endDate: "2025-05-29T15:00:00"
+ $[id=Recurring_Dev_Bundle_250520].metaData.endDate: "2025-05-27T15:00:00"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[7].contentVersion: "590b76a9837977d9acc05771c2ff868a8fc21693"
+ $.entries[7].contentVersion: "c48ecf501a97dabef66443235ea32d42c78e20c7"
```

## Could not download

- `images/T_UI_CollectionBanner_CatsAndDogs_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_Chrysalis_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_CatsAndDogs.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherCharacters.png (HTTP 404)`
- `news/versionedNews.json (HTTP 404)`
- `news/versionedNews_de.json (HTTP 404)`
- `news/versionedNews_en.json (HTTP 404)`
- `news/versionedNews_es-MX.json (HTTP 404)`
- `news/versionedNews_es.json (HTTP 404)`
- `news/versionedNews_fr.json (HTTP 404)`
- `news/versionedNews_it.json (HTTP 404)`
- `news/versionedNews_ja.json (HTTP 404)`
- `news/versionedNews_ko.json (HTTP 404)`
- `news/versionedNews_pl.json (HTTP 404)`
- `news/versionedNews_pt-BR.json (HTTP 404)`
- `news/versionedNews_ru.json (HTTP 404)`
- `news/versionedNews_th.json (HTTP 404)`
- `news/versionedNews_tr.json (HTTP 404)`
- `news/versionedNews_zh-Hans.json (HTTP 404)`
- `news/versionedNews_zh-Hant.json (HTTP 404)`

