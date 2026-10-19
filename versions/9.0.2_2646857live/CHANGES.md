# live · 9.0.2_2646857live

| | |
|---|---|
| Build date | 2025-07-25 14:13 UTC |
| CDN version | `9.0.2_2646857live-1753452798` |
| Key | `9.0.2_live` |
| Compared with | [9.0.2_2636464live](../9.0.2_2636464live/CHANGES.md) (2025-07-22 18:15 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 198 unchanged

## Modified files

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
- $.disconnectionPenalty.reasons[]: "None"
+ $.disconnectionPenalty.reasons[]: "leave_game"
+ $.disconnectionPenalty.reasons[]: "afk_killer"
+ $.disconnectionPenalty.reasons[]: "afk_survivor"
+ $.disconnectionPenalty.reasons[]: "invalid_ownership"
+ $.disconnectionPenalty.reasons[]: "go_next"
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle["zh-Hans"]: "@#Boulet_Brothers_Bundle_Title"
+ $[id=Boulet_Brothers_Bundle].metaData.specialPackTitle["zh-Hans"]: "布蕾兄弟组合包"
- $[id=Waterfront_Massacre_Bundle].metaData.specialPackTitle["zh-Hans"]: "@#Waterfront_Massacre_Bundle_Title"
+ $[id=Waterfront_Massacre_Bundle].metaData.specialPackTitle["zh-Hans"]: "滨水屠杀组合包"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[15].collectionTitle["zh-Hans"]: "布莱特兄弟"
+ $.collections[15].collectionTitle["zh-Hans"]: "布蕾兄弟"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[6].contentVersion: "3c47f338761cc9b8af1b26a03bef6250bd5a1575"
+ $.entries[6].contentVersion: "6bf0f2abd93b6b2313f2f898c996d4e346e6785e"
- $.entries[174].contentVersion: "1c8200bad34c8412d07b7461e55472ca70a8b991"
+ $.entries[174].contentVersion: "f2b0eff9c3028e9cf198d89d5f814cb2acf44cfc"
```

## Could not download

- `images/T_UI_CollectionBanner_BouletBrothers.png (HTTP 404)`
- `images/T_UI_CollectionBanner_WaterfrontMassacreXenomorph.png (HTTP 404)`
- `images/T_UI_SpecialPack_BouletBrothers.png (HTTP 404)`
- `images/T_UI_SpecialPack_WaterfrontMassacreBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_WaterfrontMassacreXenomorph.png (HTTP 404)`
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

