# live · 8.7.0_2444932live

| | |
|---|---|
| Build date | 2025-05-12 15:53 UTC |
| CDN version | `8.7.0_2444932live-1747065217` |
| Key | `8.7.0_live` |
| Compared with | [8.7.0_2443350live](../8.7.0_2443350live/CHANGES.md) (2025-05-12 12:12 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 199 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.analyticsRules.KA[]: "EndpointLatencyAnalytics"
+ $.analyticsRules.KAL[]: "EndpointLatencyAnalytics"
- $.enableDeniedStateTransition: true
+ $.enableDeniedStateTransition: false
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S46].metaData.characterStartingInventory[itemId=Item_Camper_WornoutToolbox]
- $[id=S46].metaData.characterStartingInventory[itemId=Addon_Toolbox_001]
+ $[id=S46].metaData.characterStartingInventory[itemId=Addon_Medkit_001]
+ $[id=S46].metaData.characterStartingInventory[itemId=Item_Camper_BeigeMap]
- $[id=S46].metaData.characterStartingInventory[itemId=Item_Camper_MedKit].autoEquip: false
+ $[id=S46].metaData.characterStartingInventory[itemId=Item_Camper_MedKit].autoEquip: true
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[6].contentVersion: "a1853724f8c00265d0eceaf7894a9890c74f45b9"
+ $.entries[6].contentVersion: "64f1f576db920c28e94a001719c99af3bccc8f5d"
```

## Could not download

- `images/T_UI_ChapterBundle_SteadyPulse.png (HTTP 404)`
- `images/T_UI_CollectionBanner_GuardiansAndShadows.png (HTTP 404)`
- `images/T_UI_CollectionBanner_SteadyPulse.png (HTTP 404)`
- `images/T_UI_SpecialPack_GuardiansAndShadows.png (HTTP 404)`
- `images/T_UI_SpecialPack_Rift1.png (HTTP 404)`
- `images/T_UI_SpecialPack_SteadyPulse.png (HTTP 404)`
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

