# live · 10.0.2_3484751live

| | |
|---|---|
| Build date | 2026-07-06 19:35 UTC |
| CDN version | `10.0.2_3484751live-1783366515` |
| Key | `10.0.2_live` |
| Compared with | [10.0.1_3483500live](../10.0.1_3483500live/CHANGES.md) (2026-07-03 19:46 UTC) |

## Summary

**2** added · **9** modified · **1** removed · 204 unchanged

## New or updated images

<a href="images/T_UI_CollectionBanner_IronMaiden_Huntress.png"><img src="images/T_UI_CollectionBanner_IronMaiden_Huntress.png" alt="T_UI_CollectionBanner_IronMaiden_Huntress.png" width="240"></a>
<a href="images/T_UI_SpecialPack_IronMaiden_Huntress.png"><img src="images/T_UI_SpecialPack_IronMaiden_Huntress.png" alt="T_UI_SpecialPack_IronMaiden_Huntress.png" width="240"></a>

## Removed files

- `images/T_UI_icon_Event_LaFogata.png`

## Modified files

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
+ $.TOME24.vignettes[id=TOME24_03]
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
+ $.TOME24.TOME24_03
```

### [`archiveQuests/Tome18.json`](archiveQuests/Tome18.json)

[Full line-by-line diff](diffs/archiveQuests/Tome18.json.diff)

```diff
- $.Tome18.level[1].nodes.node_T18_L2_Glyph01.clientInfoId: "WhiteGlyph"
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph01.clientInfoId: "YellowGlyph"
- $.Tome18.level[1].nodes.node_T18_L2_Glyph01.objectives.WhiteGlyph
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph01.objectives.YellowGlyph
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
- $.BulkCost[18].CostList[0].Value[]: 14000
- $.BulkCost[18].CostList[0].Value[]: 19750
- $.BulkCost[18].CostList[0].Value[]: 20500
- $.BulkCost[18].CostList[0].Value[]: 19250
- $.BulkCost[18].CostList[0].Value[]: 21000
- $.BulkCost[18].CostList[0].Value[]: 27500
- $.BulkCost[18].CostList[0].Value[]: 29500
- $.BulkCost[18].CostList[0].Value[]: 27000
- $.BulkCost[18].CostList[0].Value[]: 28250
- $.BulkCost[18].CostList[0].Value[]: 26250
- $.BulkCost[18].CostList[0].Value[]: 28750
- $.BulkCost[18].CostList[0].Value[]: 35250
- $.BulkCost[18].CostList[0].Value[]: 32750
- $.BulkCost[18].CostList[0].Value[]: 32000
- $.BulkCost[18].CostList[0].Value[]: 34750
- $.BulkCost[18].CostList[0].Value[]: 38500
+ $.BulkCost[18].CostList[0].Value[]: 10000
+ $.BulkCost[18].CostList[0].Value[]: 11250
+ $.BulkCost[18].CostList[0].Value[]: 15750
+ $.BulkCost[18].CostList[0].Value[]: 17000
+ $.BulkCost[18].CostList[0].Value[]: 16500
+ $.BulkCost[18].CostList[0].Value[]: 22750
+ $.BulkCost[18].CostList[0].Value[]: 18250
+ $.BulkCost[18].CostList[0].Value[]: 21500
+ $.BulkCost[18].CostList[0].Value[]: 23500
+ $.BulkCost[18].CostList[0].Value[]: 26000
+ $.BulkCost[18].CostList[0].Value[]: 30000
+ $.BulkCost[18].CostList[0].Value[]: 34000
+ $.BulkCost[18].CostList[0].Value[]: 30750
+ $.BulkCost[18].CostList[0].Value[]: 33250
+ $.BulkCost[18].CostList[0].Value[]: 36500
- $.BulkCost[18].CostList[1].Value[]: 14000
- $.BulkCost[18].CostList[1].Value[]: 19750
- $.BulkCost[18].CostList[1].Value[]: 20500
- $.BulkCost[18].CostList[1].Value[]: 19250
- $.BulkCost[18].CostList[1].Value[]: 21000
- $.BulkCost[18].CostList[1].Value[]: 27500
- $.BulkCost[18].CostList[1].Value[]: 27000
- $.BulkCost[18].CostList[1].Value[]: 28250
- $.BulkCost[18].CostList[1].Value[]: 26250
- $.BulkCost[18].CostList[1].Value[]: 31500
- $.BulkCost[18].CostList[1].Value[]: 35250
- $.BulkCost[18].CostList[1].Value[]: 34750
- $.BulkCost[18].CostList[1].Value[]: 38000
+ $.BulkCost[18].CostList[1].Value[]: 10000
+ $.BulkCost[18].CostList[1].Value[]: 11250
+ $.BulkCost[18].CostList[1].Value[]: 15750
+ $.BulkCost[18].CostList[1].Value[]: 17000
+ $.BulkCost[18].CostList[1].Value[]: 16500
+ $.BulkCost[18].CostList[1].Value[]: 18250
+ $.BulkCost[18].CostList[1].Value[]: 22750
+ $.BulkCost[18].CostList[1].Value[]: 23500
+ $.BulkCost[18].CostList[1].Value[]: 24750
+ $.BulkCost[18].CostList[1].Value[]: 30750
+ $.BulkCost[18].CostList[1].Value[]: 33250
+ $.BulkCost[18].CostList[1].Value[]: 36500
- $.BulkCost[18].CostList[2].Value[]: 14000
- $.BulkCost[18].CostList[2].Value[]: 19750
- $.BulkCost[18].CostList[2].Value[]: 20500
- $.BulkCost[18].CostList[2].Value[]: 19250
- $.BulkCost[18].CostList[2].Value[]: 21000
- $.BulkCost[18].CostList[2].Value[]: 27500
- $.BulkCost[18].CostList[2].Value[]: 27000
- $.BulkCost[18].CostList[2].Value[]: 28250
- $.BulkCost[18].CostList[2].Value[]: 26250
- $.BulkCost[18].CostList[2].Value[]: 28750
- $.BulkCost[18].CostList[2].Value[]: 31500
- $.BulkCost[18].CostList[2].Value[]: 35250
- $.BulkCost[18].CostList[2].Value[]: 34750
- $.BulkCost[18].CostList[2].Value[]: 38000
+ $.BulkCost[18].CostList[2].Value[]: 10000
+ $.BulkCost[18].CostList[2].Value[]: 11250
+ $.BulkCost[18].CostList[2].Value[]: 15750
+ $.BulkCost[18].CostList[2].Value[]: 17000
+ $.BulkCost[18].CostList[2].Value[]: 16500
+ $.BulkCost[18].CostList[2].Value[]: 18250
+ $.BulkCost[18].CostList[2].Value[]: 22750
+ $.BulkCost[18].CostList[2].Value[]: 23500
+ $.BulkCost[18].CostList[2].Value[]: 24750
+ $.BulkCost[18].CostList[2].Value[]: 30750
+ $.BulkCost[18].CostList[2].Value[]: 33250
+ $.BulkCost[18].CostList[2].Value[]: 36500
- $.BulkCost[18].CostList[3].Value[]: 14000
- $.BulkCost[18].CostList[3].Value[]: 19750
- $.BulkCost[18].CostList[3].Value[]: 20500
- $.BulkCost[18].CostList[3].Value[]: 19250
- $.BulkCost[18].CostList[3].Value[]: 21000
- $.BulkCost[18].CostList[3].Value[]: 27500
- $.BulkCost[18].CostList[3].Value[]: 27000
- $.BulkCost[18].CostList[3].Value[]: 28250
- $.BulkCost[18].CostList[3].Value[]: 26250
- $.BulkCost[18].CostList[3].Value[]: 28750
- $.BulkCost[18].CostList[3].Value[]: 31500
- $.BulkCost[18].CostList[3].Value[]: 35250
- $.BulkCost[18].CostList[3].Value[]: 34750
- $.BulkCost[18].CostList[3].Value[]: 38000
+ $.BulkCost[18].CostList[3].Value[]: 10000
+ $.BulkCost[18].CostList[3].Value[]: 11250
+ $.BulkCost[18].CostList[3].Value[]: 15750
+ $.BulkCost[18].CostList[3].Value[]: 17000
+ $.BulkCost[18].CostList[3].Value[]: 16500
+ $.BulkCost[18].CostList[3].Value[]: 18250
+ $.BulkCost[18].CostList[3].Value[]: 22750
+ $.BulkCost[18].CostList[3].Value[]: 23500
+ $.BulkCost[18].CostList[3].Value[]: 24750
+ $.BulkCost[18].CostList[3].Value[]: 30750
+ $.BulkCost[18].CostList[3].Value[]: 33250
+ $.BulkCost[18].CostList[3].Value[]: 36500
- $.BulkCost[18].CostList[4].Value[]: 14000
- $.BulkCost[18].CostList[4].Value[]: 19750
- $.BulkCost[18].CostList[4].Value[]: 20500
- $.BulkCost[18].CostList[4].Value[]: 19250
- $.BulkCost[18].CostList[4].Value[]: 21000
- $.BulkCost[18].CostList[4].Value[]: 27500
- $.BulkCost[18].CostList[4].Value[]: 27000
- $.BulkCost[18].CostList[4].Value[]: 28250
- $.BulkCost[18].CostList[4].Value[]: 26250
- $.BulkCost[18].CostList[4].Value[]: 28750
- $.BulkCost[18].CostList[4].Value[]: 31500
- $.BulkCost[18].CostList[4].Value[]: 35250
- $.BulkCost[18].CostList[4].Value[]: 34750
- $.BulkCost[18].CostList[4].Value[]: 38000
+ $.BulkCost[18].CostList[4].Value[]: 10000
+ $.BulkCost[18].CostList[4].Value[]: 11250
+ $.BulkCost[18].CostList[4].Value[]: 15750
+ $.BulkCost[18].CostList[4].Value[]: 17000
+ $.BulkCost[18].CostList[4].Value[]: 16500
+ $.BulkCost[18].CostList[4].Value[]: 18250
+ $.BulkCost[18].CostList[4].Value[]: 21500
+ $.BulkCost[18].CostList[4].Value[]: 22750
+ $.BulkCost[18].CostList[4].Value[]: 23500
+ $.BulkCost[18].CostList[4].Value[]: 24750
+ $.BulkCost[18].CostList[4].Value[]: 30000
+ $.BulkCost[18].CostList[4].Value[]: 26750
+ $.BulkCost[18].CostList[4].Value[]: 30750
+ $.BulkCost[18].CostList[4].Value[]: 33250
+ $.BulkCost[18].CostList[4].Value[]: 36500
- $.BulkCost[18].CostList[5].Value[]: 14000
- $.BulkCost[18].CostList[5].Value[]: 19750
- $.BulkCost[18].CostList[5].Value[]: 20500
- $.BulkCost[18].CostList[5].Value[]: 19250
- $.BulkCost[18].CostList[5].Value[]: 21000
- $.BulkCost[18].CostList[5].Value[]: 27500
- $.BulkCost[18].CostList[5].Value[]: 27000
- $.BulkCost[18].CostList[5].Value[]: 28250
- $.BulkCost[18].CostList[5].Value[]: 26250
- $.BulkCost[18].CostList[5].Value[]: 28750
- $.BulkCost[18].CostList[5].Value[]: 31500
- $.BulkCost[18].CostList[5].Value[]: 35250
- $.BulkCost[18].CostList[5].Value[]: 34750
- $.BulkCost[18].CostList[5].Value[]: 38000
+ $.BulkCost[18].CostList[5].Value[]: 10000
+ $.BulkCost[18].CostList[5].Value[]: 11250
+ $.BulkCost[18].CostList[5].Value[]: 15750
+ $.BulkCost[18].CostList[5].Value[]: 17000
+ $.BulkCost[18].CostList[5].Value[]: 16500
+ $.BulkCost[18].CostList[5].Value[]: 18250
+ $.BulkCost[18].CostList[5].Value[]: 21500
+ $.BulkCost[18].CostList[5].Value[]: 22750
+ $.BulkCost[18].CostList[5].Value[]: 23500
+ $.BulkCost[18].CostList[5].Value[]: 24750
+ $.BulkCost[18].CostList[5].Value[]: 30750
+ $.BulkCost[18].CostList[5].Value[]: 33250
+ $.BulkCost[18].CostList[5].Value[]: 36500
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=BE_Body031]
+ $[id=BE_Mask031]
+ $[id=BE_W031]
+ $[id=RAM_012]
+ $[id=RAM_013]
+ $[id=RAM_BDG_27]
+ $[id=RAM_BNR_18]
+ $[id=RAM_BNR_19]
+ $[id=RAM_BNR_20]
+ $[id=RAM_BNR_21]
+ $[id=SUS_BDG_24]
+ $[id=BE_outfit_031]
+ $[id=10.0.2_Iron_Maiden_Killer_Bundle]
+ $[id=10.0.2_Iron_Maiden_Shirt_Bundle]
+ $[id=10.0.2_IronMaiden_collection_item]
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[69].limitedAvailabilityStartDate: "2026-07-14T15:00:00Z"
+ $.collections[69].visibleBeforeStartDate: false
+ $.collections[69].additionalImages[0]
- $.collections[69].collectionId: "GreekLegends"
+ $.collections[69].collectionId: "10.0.2_IronMaiden"
- $.collections[69].collectionTitle.de: "Griechische Legenden"
+ $.collections[69].collectionTitle.de: "Iron Maiden"
- $.collections[69].collectionTitle.en: "Greek Legends"
+ $.collections[69].collectionTitle.en: "Iron Maiden"
- $.collections[69].collectionTitle.es: "Leyendas griegas"
+ $.collections[69].collectionTitle.es: "Doncella de hierro"
- $.collections[69].collectionTitle["es-MX"]: "Leyendas griegas"
+ $.collections[69].collectionTitle["es-MX"]: "Iron Maiden"
- $.collections[69].collectionTitle.fr: "Légendes grecques"
+ $.collections[69].collectionTitle.fr: "Iron Maiden"
- $.collections[69].collectionTitle.it: "Leggende greche"
+ $.collections[69].collectionTitle.it: "Iron Maiden"
- $.collections[69].collectionTitle.ja: "ギリシャの伝説"
+ $.collections[69].collectionTitle.ja: "アイアンメイデン"
- $.collections[69].collectionTitle.ko: "그리스 전설"
+ $.collections[69].collectionTitle.ko: "아이언 메이든"
- $.collections[69].collectionTitle.pl: "Greckie legendy"
+ $.collections[69].collectionTitle.pl: "Iron Maiden"
- $.collections[69].collectionTitle["pt-BR"]: "Lendas Gregas"
+ $.collections[69].collectionTitle["pt-BR"]: "Iron Maiden"
- $.collections[69].collectionTitle.ru: "Легенды Греции"
+ $.collections[69].collectionTitle.ru: "Железная дева"
- $.collections[69].collectionTitle.th: "ตำนานกรีก"
+ $.collections[69].collectionTitle.th: "เครื่องทรมานสตรีเหล็ก"
- $.collections[69].collectionTitle.tr: "Yunan Efsaneleri"
+ $.collections[69].collectionTitle.tr: "Çivili Tabut"
- $.collections[69].collectionTitle["zh-Hans"]: "希腊传说"
+ $.collections[69].collectionTitle["zh-Hans"]: "铁娘子"
- $.collections[69].collectionTitle["zh-Hant"]: "希臘傳奇"
+ $.collections[69].collectionTitle["zh-Hant"]: "鐵處女"
- $.collections[69].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
+ $.collections[69].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_IronMaiden_Huntress.T_UI_CollectionBanner_IronMaiden_Huntress"
- $.collections[69].inclusionVersion: "7.7.0 PTB"
+ $.collections[69].inclusionVersion: "10.0.2"
- $.collections[69].items[]: "AV_outfit_014"
- $.collections[69].items[]: "DK_outfit_012"
- $.collections[69].items[]: "FM_outfit_012"
- $.collections[69].items[]: "GK_outfit_011"
- $.collections[69].items[]: "GS_outfit_016"
- $.collections[69].items[]: "HK_outfit_011"
- $.collections[69].items[]: "HS_outfit_010"
- $.collections[69].items[]: "K21_outfit_008"
- $.collections[69].items[]: "K26_outfit_009"
- $.collections[69].items[]: "K28_outfit_010"
- $.collections[69].items[]: "KS_outfit_012"
- $.collections[69].items[]: "MK_outfit_013"
- $.collections[69].items[]: "MS_outfit_013"
- $.collections[69].items[]: "NK_outfit_022"
- $.collections[69].items[]: "S24_outfit_009"
- $.collections[69].items[]: "S28_outfit_014"
- $.collections[69].items[]: "S35_outfit_009"
- $.collections[69].items[]: "S36_outfit_009"
- $.collections[69].items[]: "SwedenKiller_outfit_009"
- $.collections[69].items[]: "SwedenSurvivor_outfit_011"
- $.collections[69].items[]: "TN_outfit_013"
- $.collections[69].items[]: "US_outfit_009"
+ $.collections[69].items[]: "AV_Torso021"
+ $.collections[69].items[]: "BE_outfit_031"
+ $.collections[69].items[]: "CM_Torso027"
+ $.collections[69].items[]: "DF_Torso030"
+ $.collections[69].items[]: "DK_Torso021"
+ $.collections[69].items[]: "DO_outfit_019"
+ $.collections[69].items[]: "FM_Torso030"
+ $.collections[69].items[]: "GS_Torso028"
+ $.collections[69].items[]: "HS_Torso022"
+ $.collections[69].items[]: "JP_Torso022"
+ $.collections[69].items[]: "K28_outfit_013"
+ $.collections[69].items[]: "KS_Torso021"
+ $.collections[69].items[]: "MS_Torso022"
+ $.collections[69].items[]: "MT_Torso028"
+ $.collections[69].items[]: "NK_Torso028"
+ $.collections[69].items[]: "S23_Torso026"
+ $.collections[69].items[]: "S24_Torso020"
+ $.collections[69].items[]: "S25_Torso022"
+ $.collections[69].items[]: "S28_Torso022"
+ $.collections[69].items[]: "S29_Torso016"
+ $.collections[69].items[]: "S31_Torso015"
+ $.collections[69].items[]: "S34_Torso016"
+ $.collections[69].items[]: "S35_Torso014"
+ $.collections[69].items[]: "S36_Torso015"
+ $.collections[69].items[]: "S37_Torso014"
+ $.collections[69].items[]: "S41_Torso015"
+ $.collections[69].items[]: "S45_Torso009"
+ $.collections[69].items[]: "S46_Torso011_02"
+ $.collections[69].items[]: "S49_Torso008_01"
+ $.collections[69].items[]: "SwedenKiller_outfit_020"
+ $.collections[69].items[]: "SwedenSurvivor_Torso023"
+ $.collections[69].items[]: "UK_outfit_015"
+ $.collections[69].items[]: "US_Torso022"
- $.collections[69].sortOrder: "-25"
+ $.collections[69].sortOrder: "-241"
- $.collections[69].updatedDate: "2024-03-18T16:00:01Z"
+ $.collections[69].updatedDate: "2026-03-26T13:34:15Z"
- $.collections[70].collectionId: "MeanStreets"
+ $.collections[70].collectionId: "GreekLegends"
- $.collections[70].collectionTitle.de: "Gefährliche Straßen"
+ $.collections[70].collectionTitle.de: "Griechische Legenden"
- $.collections[70].collectionTitle.en: "Mean Streets"
+ $.collections[70].collectionTitle.en: "Greek Legends"
- $.collections[70].collectionTitle.es: "Calles peligrosas"
+ $.collections[70].collectionTitle.es: "Leyendas griegas"
- $.collections[70].collectionTitle["es-MX"]: "Calles peligrosas"
+ $.collections[70].collectionTitle["es-MX"]: "Leyendas griegas"
- $.collections[70].collectionTitle.fr: "Rues dangereuses"
+ $.collections[70].collectionTitle.fr: "Légendes grecques"
- $.collections[70].collectionTitle.it: "Bassifondi"
+ $.collections[70].collectionTitle.it: "Leggende greche"
- $.collections[70].collectionTitle.ja: "意地悪なストリート"
+ $.collections[70].collectionTitle.ja: "ギリシャの伝説"
- $.collections[70].collectionTitle.ko: "비열한 거리"
+ $.collections[70].collectionTitle.ko: "그리스 전설"
- $.collections[70].collectionTitle.pl: "Podła dzielnica"
+ $.collections[70].collectionTitle.pl: "Greckie legendy"
- $.collections[70].collectionTitle["pt-BR"]: "Ruas Cruéis"
+ $.collections[70].collectionTitle["pt-BR"]: "Lendas Gregas"
- $.collections[70].collectionTitle.ru: "Трущобы"
+ $.collections[70].collectionTitle.ru: "Легенды Греции"
- $.collections[70].collectionTitle.th: "ถนนซอมซ่อ"
+ $.collections[70].collectionTitle.th: "ตำนานกรีก"
- $.collections[70].collectionTitle.tr: "Amansız Sokaklar"
+ $.collections[70].collectionTitle.tr: "Yunan Efsaneleri"
- $.collections[70].collectionTitle["zh-Hans"]: "穷街陋巷"
+ $.collections[70].collectionTitle["zh-Hans"]: "希腊传说"
- $.collections[70].collectionTitle["zh-Hant"]: "窮街陋巷"
+ $.collections[70].collectionTitle["zh-Hant"]: "希臘傳奇"
- $.collections[70].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MeanStreets.T_UI_CollectionBanner_MeanStreets"
+ $.collections[70].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
- $.collections[70].items[]: "AV_outfit_010"
- $.collections[70].items[]: "Claudette_outfit_009_01"
- $.collections[70].items[]: "DK_outfit_011"
- $.collections[70].items[]: "HS_outfit_009"
- $.collections[70].items[]: "MT_outfit_012"
- $.collections[70].items[]: "Nea_outfit_008_01"
- $.collections[70].items[]: "US_outfit_008"
+ $.collections[70].items[]: "AV_outfit_014"
+ $.collections[70].items[]: "DK_outfit_012"
+ $.collections[70].items[]: "FM_outfit_012"
+ $.collections[70].items[]: "GK_outfit_011"
+ $.collections[70].items[]: "GS_outfit_016"
+ $.collections[70].items[]: "HK_outfit_011"
+ $.collections[70].items[]: "HS_outfit_010"
+ $.collections[70].items[]: "K21_outfit_008"
+ $.collections[70].items[]: "K26_outfit_009"
+ $.collections[70].items[]: "K28_outfit_010"
+ $.collections[70].items[]: "KS_outfit_012"
+ $.collections[70].items[]: "MK_outfit_013"
+ $.collections[70].items[]: "MS_outfit_013"
+ $.collections[70].items[]: "NK_outfit_022"
+ $.collections[70].items[]: "S24_outfit_009"
+ $.collections[70].items[]: "S28_outfit_014"
+ $.collections[70].items[]: "S35_outfit_009"
+ $.collections[70].items[]: "S36_outfit_009"
+ $.collections[70].items[]: "SwedenKiller_outfit_009"
+ $.collections[70].items[]: "SwedenSurvivor_outfit_011"
+ $.collections[70].items[]: "TN_outfit_013"
+ $.collections[70].items[]: "US_outfit_009"
- $.collections[70].sortOrder: "-3"
+ $.collections[70].sortOrder: "-25"
- $.collections[70].updatedDate: "2024-02-20T20:35:22Z"
+ $.collections[70].updatedDate: "2024-03-18T16:00:01Z"
- $.collections[71].collectionId: "CursedCats"
+ $.collections[71].collectionId: "MeanStreets"
- $.collections[71].collectionTitle.de: "Verfluchte Katzen"
+ $.collections[71].collectionTitle.de: "Gefährliche Straßen"
- $.collections[71].collectionTitle.en: "Cursed Cats"
+ $.collections[71].collectionTitle.en: "Mean Streets"
- $.collections[71].collectionTitle.es: "Gatos malditos"
+ $.collections[71].collectionTitle.es: "Calles peligrosas"
- $.collections[71].collectionTitle["es-MX"]: "Gatos malditos"
+ $.collections[71].collectionTitle["es-MX"]: "Calles peligrosas"
- $.collections[71].collectionTitle.fr: "Chats maudits"
+ $.collections[71].collectionTitle.fr: "Rues dangereuses"
- $.collections[71].collectionTitle.it: "Gatti maledetti"
+ $.collections[71].collectionTitle.it: "Bassifondi"
- $.collections[71].collectionTitle.ja: "呪われた猫"
+ $.collections[71].collectionTitle.ja: "意地悪なストリート"
- $.collections[71].collectionTitle.ko: "저주받은 고양이"
+ $.collections[71].collectionTitle.ko: "비열한 거리"
- $.collections[71].collectionTitle.pl: "Przeklęte koty"
+ $.collections[71].collectionTitle.pl: "Podła dzielnica"
- $.collections[71].collectionTitle["pt-BR"]: "Gatos Amaldiçoados"
+ $.collections[71].collectionTitle["pt-BR"]: "Ruas Cruéis"
- $.collections[71].collectionTitle.ru: "Проклятые коты"
+ $.collections[71].collectionTitle.ru: "Трущобы"
- $.collections[71].collectionTitle.th: "แมวต้องสาป"
+ $.collections[71].collectionTitle.th: "ถนนซอมซ่อ"
- $.collections[71].collectionTitle.tr: "Lanetli Kediler"
+ $.collections[71].collectionTitle.tr: "Amansız Sokaklar"
- $.collections[71].collectionTitle["zh-Hans"]: "诅咒之猫"
+ $.collections[71].collectionTitle["zh-Hans"]: "穷街陋巷"
- $.collections[71].collectionTitle["zh-Hant"]: "詛咒之貓"
+ $.collections[71].collectionTitle["zh-Hant"]: "窮街陋巷"
- $.collections[71].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_CursedCats.T_UI_CollectionBanner_CursedCats"
+ $.collections[71].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MeanStreets.T_UI_CollectionBanner_MeanStreets"
- $.collections[71].items[]: "GK_outfit_016"
… 1934 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[2].downloadStrategy: "preferRemote"
+ $.entries[2].downloadStrategy: "preferPackaged"
- $.entries[3].downloadStrategy: "preferRemote"
+ $.entries[3].downloadStrategy: "preferPackaged"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[5].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[5].contentVersion: "43d348856127eef7569bb87e500916398edb21b9"
- $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_IronMaiden_Huntress.T_UI_CollectionBanner_IronMaiden_Huntress"
- $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[5].uri: "images/T_UI_CollectionBanner_IronMaiden_Huntress.png"
- $.entries[6].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[6].contentVersion: "d94c7a95edf46327051fd320ccbde523e59fb470"
- $.entries[6].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_IronMaiden_Huntress.T_UI_SpecialPack_IronMaiden_Huntress"
- $.entries[6].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[6].uri: "images/T_UI_SpecialPack_IronMaiden_Huntress.png"
- $.entries[7].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[7].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[7].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[7].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[7].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[7].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[8].contentVersion: "1a73827d53e583dd03efaac5b38ab8fb04610088"
+ $.entries[8].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[8].packagedPath: "/DBDUICore/Assets/Common/Event/Community/T_UI_icon_Event_LaFogata.T_UI_icon_Event_LaFogata"
+ $.entries[8].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[8].uri: "images/T_UI_icon_Event_LaFogata.png"
+ $.entries[8].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[9].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
+ $.entries[9].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[9].downloadStrategy: "preferRemote"
+ $.entries[9].downloadStrategy: "preferPackaged"
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
+ $.entries[9].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[9].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
+ $.entries[9].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[10].contentVersion: "45dbc8795086ecc22e3ee59473bb597baae63b7f"
+ $.entries[10].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
- $.entries[10].downloadStrategy: "preferRemote"
+ $.entries[10].downloadStrategy: "preferPackaged"
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_TheLifeRoad.T_UI_CollectionBanner_TheLifeRoad"
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
- $.entries[10].uri: "images/T_UI_CollectionBanner_TheLifeRoad.png"
+ $.entries[10].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
- $.entries[11].contentVersion: "623bb882552904b79446b6e334171fa8ca8d0345"
+ $.entries[11].contentVersion: "45dbc8795086ecc22e3ee59473bb597baae63b7f"
- $.entries[11].downloadStrategy: "preferRemote"
+ $.entries[11].downloadStrategy: "preferPackaged"
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_TheLifeRoad.T_UI_SpecialPack_TheLifeRoad"
+ $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_TheLifeRoad.T_UI_CollectionBanner_TheLifeRoad"
- $.entries[11].uri: "images/T_UI_SpecialPack_TheLifeRoad.png"
+ $.entries[11].uri: "images/T_UI_CollectionBanner_TheLifeRoad.png"
- $.entries[12].contentVersion: "2409a17f4d4c2bacecf8c4904fed4c3dceb64bb1"
+ $.entries[12].contentVersion: "623bb882552904b79446b6e334171fa8ca8d0345"
- $.entries[12].downloadStrategy: "preferRemote"
+ $.entries[12].downloadStrategy: "preferPackaged"
- $.entries[12].enableChecksum: true
+ $.entries[12].enableChecksum: false
- $.entries[12].packagedPath: ""
+ $.entries[12].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_TheLifeRoad.T_UI_SpecialPack_TheLifeRoad"
- $.entries[12].schema: "s3ver://"
+ $.entries[12].schema: "s3verbin://"
- $.entries[12].uri: "catalog.json"
+ $.entries[12].uri: "images/T_UI_SpecialPack_TheLifeRoad.png"
- $.entries[13].contentVersion: "0a0f57d2dd9beed60c28a829a156c197e9d13fa9"
+ $.entries[13].contentVersion: "43d348856127eef7569bb87e500916398edb21b9"
- $.entries[13].downloadStrategy: "preferRemote"
+ $.entries[13].downloadStrategy: "preferPackaged"
- $.entries[13].enableChecksum: true
+ $.entries[13].enableChecksum: false
- $.entries[13].packagedPath: ""
+ $.entries[13].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_IronMaiden_Huntress.T_UI_CollectionBanner_IronMaiden_Huntress"
- $.entries[13].schema: "s3ver://"
+ $.entries[13].schema: "s3verbin://"
- $.entries[13].uri: "bonusPointEventsContent.json"
+ $.entries[13].uri: "images/T_UI_CollectionBanner_IronMaiden_Huntress.png"
- $.entries[14].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
+ $.entries[14].contentVersion: "d94c7a95edf46327051fd320ccbde523e59fb470"
- $.entries[14].downloadStrategy: "preferRemote"
+ $.entries[14].downloadStrategy: "preferPackaged"
- $.entries[14].enableChecksum: true
+ $.entries[14].enableChecksum: false
- $.entries[14].packagedPath: ""
+ $.entries[14].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_IronMaiden_Huntress.T_UI_SpecialPack_IronMaiden_Huntress"
- $.entries[14].schema: "s3ver://"
+ $.entries[14].schema: "s3verbin://"
- $.entries[14].uri: "freetoplay/NA/event.json"
+ $.entries[14].uri: "images/T_UI_SpecialPack_IronMaiden_Huntress.png"
- $.entries[15].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
+ $.entries[15].contentVersion: "6ea57e6eae2adfb581c7e7bfad67e8236b7cc269"
- $.entries[15].uri: "freetoplay/EU/event.json"
+ $.entries[15].uri: "catalog.json"
- $.entries[16].contentVersion: "23b1f95aaea33a5eb00ef8deb32d515af3be02b1"
+ $.entries[16].contentVersion: "7372d3fad174d48180548c72b8bf2f300ab3df69"
- $.entries[16].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[16].uri: "bonusPointEventsContent.json"
- $.entries[17].contentVersion: "60542d2a101497b73a338989942ef496ae13d010"
+ $.entries[17].contentVersion: "1f75c1dc50dee179d18a6fcc69f89e12c9f1d250"
- $.entries[17].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[17].uri: "freetoplay/NA/event.json"
- $.entries[18].contentVersion: "53077fd04e446bfa797e36d08f46746b74d7d514"
+ $.entries[18].contentVersion: "1f75c1dc50dee179d18a6fcc69f89e12c9f1d250"
- $.entries[18].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[18].uri: "freetoplay/EU/event.json"
- $.entries[19].contentVersion: "30f6f91bea1afbf1b488a777cbd35039848da3dd"
+ $.entries[19].contentVersion: "728990dee9d5732a2a4ac75c2c753147bc4e594b"
- $.entries[19].uri: "archiveQuests/CalamariV1.json"
+ $.entries[19].uri: "archiveQuests/Anniversary2022.json"
- $.entries[20].contentVersion: "979deafa6eaa6e239324ae0bb63a325b0b954060"
+ $.entries[20].contentVersion: "c6cd4df2d61da9a5a2f29358564b66457c6e2fc0"
- $.entries[20].uri: "archiveQuests/CalamariV2.json"
+ $.entries[20].uri: "archiveQuests/Anniversary2023.json"
- $.entries[21].contentVersion: "a929110e9b2f53b4ad7d9984a3619abad514c4bc"
+ $.entries[21].contentVersion: "4ee674fb40449e7212c3953661120a74c959baaf"
- $.entries[21].uri: "archiveQuests/CalamariV3.json"
+ $.entries[21].uri: "archiveQuests/Anniversary2024.json"
- $.entries[22].contentVersion: "c4a0c4fb3e9426161dab7bdeb23c586d22c0b1b5"
+ $.entries[22].contentVersion: "7f5868c420eb9c75c1d671358a4ce010d13477d0"
- $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[22].uri: "archiveQuests/CalamariV1.json"
- $.entries[23].contentVersion: "2bc9034be7302a71d8eb0ee4309188a1c7534a99"
+ $.entries[23].contentVersion: "982cb91f4d3437f20b98a8646c5dc9f2a5777efd"
- $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[23].uri: "archiveQuests/CalamariV2.json"
- $.entries[24].contentVersion: "6906a8dc3327bc3dccaab96311adec8bc16eadf4"
+ $.entries[24].contentVersion: "4c4ed86024343728623d42092e7331372bfa4b4b"
- $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[24].uri: "archiveQuests/CalamariV3.json"
- $.entries[25].contentVersion: "c710af6ea9bb8cb30b3487d9ef9f67e06d7ae543"
+ $.entries[25].contentVersion: "aba3db56f0608ce792f5d246d9c7a5029298786e"
- $.entries[25].uri: "archiveQuests/FireflyV1.json"
+ $.entries[25].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[26].contentVersion: "63a7ccd5a00239f68cefc6c661f953642415cbe1"
+ $.entries[26].contentVersion: "d3512d8f6680c63afde0f805716cf913741a1e8d"
- $.entries[26].uri: "archiveQuests/Halloween2021.json"
+ $.entries[26].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[27].contentVersion: "ccda015e7849f072a00bdfa0baf103d2d12583a4"
+ $.entries[27].contentVersion: "993ec614f8414864752cec6fcfa26251229d2529"
- $.entries[27].uri: "archiveQuests/Halloween2022.json"
+ $.entries[27].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[28].contentVersion: "4230b8f8b088ac484ac110c853f8b5f6f9f54c44"
+ $.entries[28].contentVersion: "a1dccb478f49bae14ff62cb51e528b3e94605aa1"
- $.entries[28].uri: "archiveQuests/Halloween2023.json"
+ $.entries[28].uri: "archiveQuests/FireflyV1.json"
- $.entries[29].contentVersion: "bb980e294fd2c9f3f7b3ae1d66156c060dae509d"
+ $.entries[29].contentVersion: "11f1feefc69ad130e47446e4286683ac4ef38c86"
- $.entries[29].uri: "archiveQuests/Halloween2024.json"
+ $.entries[29].uri: "archiveQuests/Halloween2021.json"
- $.entries[30].contentVersion: "d17bed4208ba9cb25cfc5c67e0e9310df60f145e"
+ $.entries[30].contentVersion: "d9eabf8bbfe37939f355b9d81e9cc46d306ce985"
- $.entries[30].uri: "archiveQuests/Spring2024.json"
+ $.entries[30].uri: "archiveQuests/Halloween2022.json"
- $.entries[31].contentVersion: "65ac72211439c2789f3d752d31b8b2c118fccad9"
+ $.entries[31].contentVersion: "27744f4794273b886a07b537f88b700f656e9d54"
- $.entries[31].uri: "archiveQuests/Spring2025.json"
+ $.entries[31].uri: "archiveQuests/Halloween2023.json"
- $.entries[32].contentVersion: "dd54b8656432c2e7b4ffb3e3cedacd5e286cecc7"
+ $.entries[32].contentVersion: "3c57c3992fefc5d75010c9579f49f377162c6858"
- $.entries[32].uri: "archiveQuests/Summer2023.json"
+ $.entries[32].uri: "archiveQuests/Halloween2024.json"
- $.entries[33].contentVersion: "5d021476a155e6e1836e2c3033f74bd63cdbf302"
+ $.entries[33].contentVersion: "7f7378b5489aa78a10d67771dc3eeb037d7893ac"
- $.entries[33].uri: "archiveQuests/Tome01.json"
+ $.entries[33].uri: "archiveQuests/Spring2024.json"
- $.entries[34].contentVersion: "ef56572e18860b56caeee118249e290de8f6df3c"
+ $.entries[34].contentVersion: "201d33519600eb746d842b4d1b365e5eb7344265"
- $.entries[34].uri: "archiveQuests/Tome02.json"
+ $.entries[34].uri: "archiveQuests/Spring2025.json"
- $.entries[35].contentVersion: "ad87d42bbbed21f5b75cb711641f790004064c64"
+ $.entries[35].contentVersion: "30a65bc1126477f48875b5d7a35503c48f499cc6"
- $.entries[35].uri: "archiveQuests/Tome03.json"
+ $.entries[35].uri: "archiveQuests/Summer2023.json"
- $.entries[36].contentVersion: "312a43cd3c9227e4872ecfb5c307fe9e57783a1a"
+ $.entries[36].contentVersion: "fb1cd3e7e4a680a7c478042b6e7493a716aac5ae"
- $.entries[36].uri: "archiveQuests/Tome04.json"
+ $.entries[36].uri: "archiveQuests/Tome01.json"
- $.entries[37].contentVersion: "3b6250799f8db12262ffe9894a6b0ed19e3292a4"
+ $.entries[37].contentVersion: "4d70f6583c2e693a610a81cfca4b52361f7fcfd6"
- $.entries[37].uri: "archiveQuests/Tome05.json"
+ $.entries[37].uri: "archiveQuests/Tome02.json"
- $.entries[38].contentVersion: "854a58485c464e7c45b1c68c9f8544029b074841"
+ $.entries[38].contentVersion: "9c66e52b7f86ec2ef9d60c915ffa561cbb028703"
- $.entries[38].uri: "archiveQuests/Tome06.json"
+ $.entries[38].uri: "archiveQuests/Tome03.json"
- $.entries[39].contentVersion: "19f615c5c71b6d5bed5b777385068ed4fbea7ecf"
+ $.entries[39].contentVersion: "e503ae893f54f9c00180d77a548f6fe746a7a358"
- $.entries[39].uri: "archiveQuests/Tome07.json"
+ $.entries[39].uri: "archiveQuests/Tome04.json"
- $.entries[40].contentVersion: "1288046d48b6aac806a1e2887844cf94d3417725"
+ $.entries[40].contentVersion: "f2db871c64229e76298c78c72173b695e7020027"
- $.entries[40].uri: "archiveQuests/Tome08.json"
+ $.entries[40].uri: "archiveQuests/Tome05.json"
- $.entries[41].contentVersion: "046ffc40cc7b773ee54a9b84b41689852e7aab34"
+ $.entries[41].contentVersion: "df87d7da84f348e8af302ad50561647b8bd256f2"
… 731 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.Killer07
```

### [`narrativeCollections.json`](narrativeCollections.json)

[Full line-by-line diff](diffs/narrativeCollections.json.diff)

```diff
+ $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_08]
+ $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_09]
+ $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_10]
```

