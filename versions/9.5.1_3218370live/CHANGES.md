# live · 9.5.1_3218370live

| | |
|---|---|
| Build date | 2026-03-31 14:15 UTC |
| CDN version | `9.5.1_3218370live-1774966533` |
| Key | `9.5.1_live` |
| Compared with | [9.5.2_3218394live](../9.5.2_3218394live/CHANGES.md) (2026-03-31 13:47 UTC) |

## Summary

**0** added · **11** modified · **2** removed · 198 unchanged

## Removed files

- `images/T_UI_CollectionBanner_Songkran.png`
- `images/T_UI_SpecialPack_Songkran.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.analytics.detailedScoreTypeBlacklist[]: "GameEvent.Trickster.ThrowKnife"
+ $.analytics.detailedScoreTypeBlacklist[]: "GameEvent.Slasher.Trickster.KnifeThrow.Aim.Start"
+ $.analytics.detailedScoreTypeBlacklist[]: "GameEvent.Slasher.Trickster.KnifeThrow.Aim.End"
- $.krakenRequestAnalyticsLevel: "NetworkError"
+ $.krakenRequestAnalyticsLevel: "HttpError"
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
- $.TOME23.vignettes[id=TOME23_03].entries[8]
- $.TOME23.vignettes[id=TOME23_03].entries[9]
- $.TOME24.vignettes[id=TOME24_01]
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
- $.TOME24.TOME24_01
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=QUI_008]
- $[id=QUI_BNR_11]
- $[id=QUI_BNR_12]
- $[id=S49_Head010]
- $[id=S49_Legs010]
- $[id=S49_Torso010]
- $[id=S49_outfit_010]
+ $[id=S26].eventCostList
+ $[id=S26].metaData.temporaryDiscounts
+ $[id=S27].eventCostList
+ $[id=S27].metaData.temporaryDiscounts
+ $[id=K24].eventCostList
+ $[id=K24].metaData.temporaryDiscounts
+ $[id=K29].eventCostList
+ $[id=K29].metaData.temporaryDiscounts
+ $[id=S32].eventCostList
+ $[id=S32].metaData.temporaryDiscounts
+ $[id=S33].eventCostList
+ $[id=S33].metaData.temporaryDiscounts
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[314].text: "2 대 8"
+ $.locText[314].text: "2V8"
- $.locText[534].text: "2 대 8"
+ $.locText[534].text: "2V8"
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChapterQuests_Quiche.challengeList[0].endDate: "2026-03-24T14:59:00"
+ $.ChapterQuests_Quiche.challengeList[0].endDate: "2026-03-18T15:00:00"
- $.ChapterQuests_Quiche.challengeList[1].endDate: "2026-03-24T14:59:00"
+ $.ChapterQuests_Quiche.challengeList[1].endDate: "2026-03-18T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_HookAsKillerOrAnyKiller].startDate: "2026-03-20T15:00:00"
+ $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_HookAsKillerOrAnyKiller].startDate: "2026-03-17T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_BreakGenAsKillerOrAnyKiller].startDate: "2026-03-20T15:00:00"
+ $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_BreakGenAsKillerOrAnyKiller].startDate: "2026-03-17T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-D_CarryOrEscapeChase].startDate: "2026-03-20T15:00:00"
+ $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-D_CarryOrEscapeChase].startDate: "2026-03-17T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_EarnEmblemsGold].startDate: "2026-03-20T15:00:00"
+ $.ChapterQuests_Quiche.challengeList[2].challenges[id=ChapterQuests_Quiche-Quest_List_2-B_EarnEmblemsGold].startDate: "2026-03-17T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].endDate: "2026-03-24T14:59:00"
+ $.ChapterQuests_Quiche.challengeList[2].endDate: "2026-03-18T15:00:00"
- $.ChapterQuests_Quiche.challengeList[2].startDate: "2026-03-20T15:00:00"
+ $.ChapterQuests_Quiche.challengeList[2].startDate: "2026-03-17T15:00:00"
- $.ChapterQuests_Quiche.endDate: "2026-03-24T15:00:00"
+ $.ChapterQuests_Quiche.endDate: "2026-03-18T15:00:00"
- $.ChapterQuests_Quiche.endDateInMs: 1774364400
+ $.ChapterQuests_Quiche.endDateInMs: 1773846000
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[56].limitedAvailabilityStartDate: "2026-04-13T15:00:00Z"
- $.collections[56].visibleBeforeStartDate: false
- $.collections[56].additionalImages[0]
- $.collections[56].collectionId: "Songkran"
+ $.collections[56].collectionId: "Brazil"
- $.collections[56].collectionTitle.de: "Songkran"
+ $.collections[56].collectionTitle.de: "Brasilien"
- $.collections[56].collectionTitle.en: "Songkran"
+ $.collections[56].collectionTitle.en: "Brazil"
- $.collections[56].collectionTitle.es: "Songkran"
+ $.collections[56].collectionTitle.es: "Brasil"
- $.collections[56].collectionTitle["es-MX"]: "Songkran"
+ $.collections[56].collectionTitle["es-MX"]: "Brasil"
- $.collections[56].collectionTitle.fr: "Songkran"
+ $.collections[56].collectionTitle.fr: "Brésil"
- $.collections[56].collectionTitle.it: "Songkran"
+ $.collections[56].collectionTitle.it: "Brasile"
- $.collections[56].collectionTitle.ja: "ソンクラーン"
+ $.collections[56].collectionTitle.ja: "ブラジル"
- $.collections[56].collectionTitle.ko: "송끄란"
+ $.collections[56].collectionTitle.ko: "브라질"
- $.collections[56].collectionTitle.pl: "Songkran"
+ $.collections[56].collectionTitle.pl: "Brazylia"
- $.collections[56].collectionTitle["pt-BR"]: "Songkran"
+ $.collections[56].collectionTitle["pt-BR"]: "Brasil"
- $.collections[56].collectionTitle.ru: "Сонгкран"
+ $.collections[56].collectionTitle.ru: "Бразилия"
- $.collections[56].collectionTitle.th: "สงกรานต์"
+ $.collections[56].collectionTitle.th: "บราซิล"
- $.collections[56].collectionTitle.tr: "Songkran"
+ $.collections[56].collectionTitle.tr: "Brezilya"
- $.collections[56].collectionTitle["zh-Hans"]: "泼水节"
+ $.collections[56].collectionTitle["zh-Hans"]: "巴西"
- $.collections[56].collectionTitle["zh-Hant"]: "潑水節"
+ $.collections[56].collectionTitle["zh-Hant"]: "巴西"
- $.collections[56].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_Songkran.T_UI_CollectionBanner_Songkran"
+ $.collections[56].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Brazil.T_UI_CollectionBanner_Brazil"
- $.collections[56].inclusionVersion: "9.5.2"
+ $.collections[56].inclusionVersion: "7.7.0 PTB"
- $.collections[56].items[]: "S49_outfit_010"
+ $.collections[56].items[]: "KS_outfit_016"
+ $.collections[56].items[]: "S24_outfit_015"
+ $.collections[56].items[]: "SwedenSurvivor_outfit_019"
- $.collections[56].sortOrder: "-215"
+ $.collections[56].sortOrder: "-22"
- $.collections[56].updatedDate: "2026-01-20T18:36:38.518Z"
+ $.collections[56].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[57].collectionId: "Brazil"
+ $.collections[57].collectionId: "DaringAdventure"
- $.collections[57].collectionTitle.de: "Brasilien"
+ $.collections[57].collectionTitle.de: "Waghalsiges Abenteuer"
- $.collections[57].collectionTitle.en: "Brazil"
+ $.collections[57].collectionTitle.en: "Daring Adventure"
- $.collections[57].collectionTitle.es: "Brasil"
+ $.collections[57].collectionTitle.es: "Aventura intrépida"
- $.collections[57].collectionTitle["es-MX"]: "Brasil"
+ $.collections[57].collectionTitle["es-MX"]: "Aventura osada"
- $.collections[57].collectionTitle.fr: "Brésil"
+ $.collections[57].collectionTitle.fr: "Aventure audacieuse"
- $.collections[57].collectionTitle.it: "Brasile"
+ $.collections[57].collectionTitle.it: "Avventura audace"
- $.collections[57].collectionTitle.ja: "ブラジル"
+ $.collections[57].collectionTitle.ja: "果敢なる冒険"
- $.collections[57].collectionTitle.ko: "브라질"
+ $.collections[57].collectionTitle.ko: "대담한 모험"
- $.collections[57].collectionTitle.pl: "Brazylia"
+ $.collections[57].collectionTitle.pl: "Odważna przygoda"
- $.collections[57].collectionTitle["pt-BR"]: "Brasil"
+ $.collections[57].collectionTitle["pt-BR"]: "Aventura Ousada"
- $.collections[57].collectionTitle.ru: "Бразилия"
+ $.collections[57].collectionTitle.ru: "Отчаянное приключение"
- $.collections[57].collectionTitle.th: "บราซิล"
+ $.collections[57].collectionTitle.th: "การผจญภัยสุดท้าทาย"
- $.collections[57].collectionTitle.tr: "Brezilya"
+ $.collections[57].collectionTitle.tr: "Cesaret İsteyen Macera"
- $.collections[57].collectionTitle["zh-Hans"]: "巴西"
+ $.collections[57].collectionTitle["zh-Hans"]: "大冒险系列"
- $.collections[57].collectionTitle["zh-Hant"]: "巴西"
+ $.collections[57].collectionTitle["zh-Hant"]: "勇敢冒險"
- $.collections[57].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Brazil.T_UI_CollectionBanner_Brazil"
+ $.collections[57].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_DaringAdventure.T_UI_CollectionBanner_DaringAdventure"
- $.collections[57].items[]: "KS_outfit_016"
- $.collections[57].items[]: "S24_outfit_015"
- $.collections[57].items[]: "SwedenSurvivor_outfit_019"
+ $.collections[57].items[]: "UK_outfit_013"
+ $.collections[57].items[]: "US_outfit_017"
- $.collections[57].sortOrder: "-22"
+ $.collections[57].sortOrder: "-23"
- $.collections[58].collectionId: "DaringAdventure"
+ $.collections[58].collectionId: "GreekLegends"
- $.collections[58].collectionTitle.de: "Waghalsiges Abenteuer"
+ $.collections[58].collectionTitle.de: "Griechische Legenden"
- $.collections[58].collectionTitle.en: "Daring Adventure"
+ $.collections[58].collectionTitle.en: "Greek Legends"
- $.collections[58].collectionTitle.es: "Aventura intrépida"
+ $.collections[58].collectionTitle.es: "Leyendas griegas"
- $.collections[58].collectionTitle["es-MX"]: "Aventura osada"
+ $.collections[58].collectionTitle["es-MX"]: "Leyendas griegas"
- $.collections[58].collectionTitle.fr: "Aventure audacieuse"
+ $.collections[58].collectionTitle.fr: "Légendes grecques"
- $.collections[58].collectionTitle.it: "Avventura audace"
+ $.collections[58].collectionTitle.it: "Leggende greche"
- $.collections[58].collectionTitle.ja: "果敢なる冒険"
+ $.collections[58].collectionTitle.ja: "ギリシャの伝説"
- $.collections[58].collectionTitle.ko: "대담한 모험"
+ $.collections[58].collectionTitle.ko: "그리스 전설"
- $.collections[58].collectionTitle.pl: "Odważna przygoda"
+ $.collections[58].collectionTitle.pl: "Greckie legendy"
- $.collections[58].collectionTitle["pt-BR"]: "Aventura Ousada"
+ $.collections[58].collectionTitle["pt-BR"]: "Lendas Gregas"
- $.collections[58].collectionTitle.ru: "Отчаянное приключение"
+ $.collections[58].collectionTitle.ru: "Легенды Греции"
- $.collections[58].collectionTitle.th: "การผจญภัยสุดท้าทาย"
+ $.collections[58].collectionTitle.th: "ตำนานกรีก"
- $.collections[58].collectionTitle.tr: "Cesaret İsteyen Macera"
+ $.collections[58].collectionTitle.tr: "Yunan Efsaneleri"
- $.collections[58].collectionTitle["zh-Hans"]: "大冒险系列"
+ $.collections[58].collectionTitle["zh-Hans"]: "希腊传说"
- $.collections[58].collectionTitle["zh-Hant"]: "勇敢冒險"
+ $.collections[58].collectionTitle["zh-Hant"]: "希臘傳奇"
- $.collections[58].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_DaringAdventure.T_UI_CollectionBanner_DaringAdventure"
+ $.collections[58].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
- $.collections[58].items[]: "UK_outfit_013"
- $.collections[58].items[]: "US_outfit_017"
+ $.collections[58].items[]: "AV_outfit_014"
+ $.collections[58].items[]: "DK_outfit_012"
+ $.collections[58].items[]: "FM_outfit_012"
+ $.collections[58].items[]: "GK_outfit_011"
+ $.collections[58].items[]: "GS_outfit_016"
+ $.collections[58].items[]: "HK_outfit_011"
+ $.collections[58].items[]: "HS_outfit_010"
+ $.collections[58].items[]: "K21_outfit_008"
+ $.collections[58].items[]: "K26_outfit_009"
+ $.collections[58].items[]: "K28_outfit_010"
+ $.collections[58].items[]: "KS_outfit_012"
+ $.collections[58].items[]: "MK_outfit_013"
+ $.collections[58].items[]: "MS_outfit_013"
+ $.collections[58].items[]: "NK_outfit_022"
+ $.collections[58].items[]: "S24_outfit_009"
+ $.collections[58].items[]: "S28_outfit_014"
+ $.collections[58].items[]: "S35_outfit_009"
+ $.collections[58].items[]: "S36_outfit_009"
+ $.collections[58].items[]: "SwedenKiller_outfit_009"
+ $.collections[58].items[]: "SwedenSurvivor_outfit_011"
+ $.collections[58].items[]: "TN_outfit_013"
+ $.collections[58].items[]: "US_outfit_009"
- $.collections[58].sortOrder: "-23"
+ $.collections[58].sortOrder: "-25"
- $.collections[58].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[58].updatedDate: "2024-03-18T16:00:01Z"
- $.collections[59].collectionId: "GreekLegends"
+ $.collections[59].collectionId: "MeanStreets"
- $.collections[59].collectionTitle.de: "Griechische Legenden"
+ $.collections[59].collectionTitle.de: "Gefährliche Straßen"
- $.collections[59].collectionTitle.en: "Greek Legends"
+ $.collections[59].collectionTitle.en: "Mean Streets"
- $.collections[59].collectionTitle.es: "Leyendas griegas"
+ $.collections[59].collectionTitle.es: "Calles peligrosas"
- $.collections[59].collectionTitle["es-MX"]: "Leyendas griegas"
+ $.collections[59].collectionTitle["es-MX"]: "Calles peligrosas"
- $.collections[59].collectionTitle.fr: "Légendes grecques"
+ $.collections[59].collectionTitle.fr: "Rues dangereuses"
- $.collections[59].collectionTitle.it: "Leggende greche"
+ $.collections[59].collectionTitle.it: "Bassifondi"
- $.collections[59].collectionTitle.ja: "ギリシャの伝説"
+ $.collections[59].collectionTitle.ja: "意地悪なストリート"
- $.collections[59].collectionTitle.ko: "그리스 전설"
+ $.collections[59].collectionTitle.ko: "비열한 거리"
- $.collections[59].collectionTitle.pl: "Greckie legendy"
+ $.collections[59].collectionTitle.pl: "Podła dzielnica"
- $.collections[59].collectionTitle["pt-BR"]: "Lendas Gregas"
+ $.collections[59].collectionTitle["pt-BR"]: "Ruas Cruéis"
- $.collections[59].collectionTitle.ru: "Легенды Греции"
+ $.collections[59].collectionTitle.ru: "Трущобы"
- $.collections[59].collectionTitle.th: "ตำนานกรีก"
+ $.collections[59].collectionTitle.th: "ถนนซอมซ่อ"
- $.collections[59].collectionTitle.tr: "Yunan Efsaneleri"
+ $.collections[59].collectionTitle.tr: "Amansız Sokaklar"
- $.collections[59].collectionTitle["zh-Hans"]: "希腊传说"
+ $.collections[59].collectionTitle["zh-Hans"]: "穷街陋巷"
- $.collections[59].collectionTitle["zh-Hant"]: "希臘傳奇"
+ $.collections[59].collectionTitle["zh-Hant"]: "窮街陋巷"
- $.collections[59].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
+ $.collections[59].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MeanStreets.T_UI_CollectionBanner_MeanStreets"
- $.collections[59].items[]: "AV_outfit_014"
- $.collections[59].items[]: "DK_outfit_012"
- $.collections[59].items[]: "FM_outfit_012"
- $.collections[59].items[]: "GK_outfit_011"
- $.collections[59].items[]: "GS_outfit_016"
- $.collections[59].items[]: "HK_outfit_011"
- $.collections[59].items[]: "HS_outfit_010"
- $.collections[59].items[]: "K21_outfit_008"
- $.collections[59].items[]: "K26_outfit_009"
- $.collections[59].items[]: "K28_outfit_010"
- $.collections[59].items[]: "KS_outfit_012"
- $.collections[59].items[]: "MK_outfit_013"
- $.collections[59].items[]: "MS_outfit_013"
- $.collections[59].items[]: "NK_outfit_022"
- $.collections[59].items[]: "S24_outfit_009"
- $.collections[59].items[]: "S28_outfit_014"
… 1984 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].downloadStrategy: "preferPackaged"
+ $.entries[0].downloadStrategy: "preferRemote"
- $.entries[4].contentVersion: "019bd9f78117c22e825d54799ad5a34fbca2abfa"
+ $.entries[4].contentVersion: "708e1e72132c2d543e190599ae531743307f7227"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_Songkran.T_UI_CollectionBanner_Songkran"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_CollectionBanner_Songkran.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "ef596b89f090b384fc3ce9a9ea2157313250f9be"
+ $.entries[5].contentVersion: "2faec738e528579cdb4ce216a6e682823b470805"
- $.entries[5].downloadStrategy: "preferPackaged"
+ $.entries[5].downloadStrategy: "preferRemote"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Songkran.T_UI_SpecialPack_Songkran"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_SpecialPack_Songkran.png"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "0684dc0d146063559a67d8bf5d038b84580e62cb"
+ $.entries[6].contentVersion: "7e235914cb1520954aaf79ed27a227f3d9968c55"
- $.entries[6].uri: "catalog.json"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "00ccec5c57d21b3084d71e55376d5df80b2b4e44"
+ $.entries[7].contentVersion: "7e235914cb1520954aaf79ed27a227f3d9968c55"
- $.entries[7].uri: "bonusPointEventsContent.json"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "4660259350d68d784ff362796b810d90249c934e"
+ $.entries[8].contentVersion: "cc800af79b80d68a97638e8bef9cdd689c439e6e"
- $.entries[8].uri: "freetoplay/NA/event.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "4660259350d68d784ff362796b810d90249c934e"
+ $.entries[9].contentVersion: "d9c6c13fa45df08e71f60e984d0d4d323c600642"
- $.entries[9].uri: "freetoplay/EU/event.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "563ba8863857d87bfce206cca6f3d2bac203f56f"
+ $.entries[10].contentVersion: "4940aa091648dca19a79d9b8aac8dd20dd4ca88d"
- $.entries[10].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "3115f5e7d61a970a71e9a41100a55f046eb9bd48"
+ $.entries[11].contentVersion: "aae9d286e50fc9707620906ff774c4992b2fb326"
- $.entries[11].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "e2dcf644f8525a2ae1a9233bf85b0df55370c5bc"
+ $.entries[12].contentVersion: "848d325a533eca323a1dcd220dd71b419a281873"
- $.entries[12].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "cddf4d17ad3a41bfc299db5d6a90fbced3b21e58"
+ $.entries[13].contentVersion: "eb162419b832ab1ba040667d9689971741929643"
- $.entries[13].uri: "archiveQuests/CalamariV1.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "7d287907649ba3489aeb1dcf64693d3b7616ebce"
+ $.entries[14].contentVersion: "32fd3a92a6cf67463de180d84e2d418613199576"
- $.entries[14].uri: "archiveQuests/CalamariV2.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "87c0d35b78cefcb1e3662e2e2c3f75318d3a3548"
+ $.entries[15].contentVersion: "d60d9b1f27933561f3af2503062e589d11e46641"
- $.entries[15].uri: "archiveQuests/CalamariV3.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "bb3f06a2880e3ff04e3b6238b498422861c71297"
+ $.entries[16].contentVersion: "572c3225bd59a9f10db5dd2b35d973e45136eff7"
- $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "4579ad21e48a50b6a3df083acae1bda30b51b927"
+ $.entries[17].contentVersion: "f354376fa077c2c631fba9ee80a564f31d3aea2d"
- $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "a5fd0fb1270f3c2acdde21598d487e6982e142f8"
+ $.entries[18].contentVersion: "639df7a4422cab03e67a257fdb842f06a90db237"
- $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "3c418e56e731fa6c0bce50fe214afdcbebed4d97"
+ $.entries[19].contentVersion: "633c92a0169a8f5670bde911dc3d9e8b23a821cf"
- $.entries[19].uri: "archiveQuests/FireflyV1.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "ce17656b4f57f9bb4f55a647888e9c131cbffd86"
+ $.entries[20].contentVersion: "2ae3766086526066d40a62ba3e5eda79836f7858"
- $.entries[20].uri: "archiveQuests/Halloween2021.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "31c2ba9e1fc6549a9d87fd8e886cf58a3c6d620b"
+ $.entries[21].contentVersion: "cd039412a0de844521fa41a6d49631c6bee55ea5"
- $.entries[21].uri: "archiveQuests/Halloween2022.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "0920c356f45356ae9a1f8194d39076438f3595e3"
+ $.entries[22].contentVersion: "a5eb2638115f739dc067efe1a1bb03c61ac921ed"
- $.entries[22].uri: "archiveQuests/Halloween2023.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "9298ad2daaa92b1ad66dfc69c159ca51919ab7e9"
+ $.entries[23].contentVersion: "e92659907a52af28df5581d32133520b214b333c"
- $.entries[23].uri: "archiveQuests/Halloween2024.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "e9e019462c7bdc7cac1ec0ff6843f2f3d0d3852b"
+ $.entries[24].contentVersion: "aea5500cc5358a7244630b2a70b7d7306ed22f3d"
- $.entries[24].uri: "archiveQuests/Spring2024.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "bae9534b4da6340edc518860172b367beb402155"
+ $.entries[25].contentVersion: "8e0d36de96fbe9eff1d5644a375b64fbac5bc79d"
- $.entries[25].uri: "archiveQuests/Spring2025.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "1a3c1265f105674a7f30254832f60258fc420487"
+ $.entries[26].contentVersion: "78386cd3f66c6278522305718bdffdd2b0999b0e"
- $.entries[26].uri: "archiveQuests/Summer2023.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "c85645524e7d9462e910271ec5d6c54871a80085"
+ $.entries[27].contentVersion: "ea217f51aab4d533a0b7b219c0cd1e4cf344daf5"
- $.entries[27].uri: "archiveQuests/Tome01.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "c22d11818ccd3e092fa80428aa70dc5f5e531931"
+ $.entries[28].contentVersion: "93a5e14a40afe915f07c00ed30599565763d614e"
- $.entries[28].uri: "archiveQuests/Tome02.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "8516f40e7e71b533193b4bcf03f6bf4675a1f614"
+ $.entries[29].contentVersion: "dab89b7a16d73479922e98745479a3243aa63517"
- $.entries[29].uri: "archiveQuests/Tome03.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "da3a16840f040f646d2581527f85728bc77c71a6"
+ $.entries[30].contentVersion: "ffe94e3a87693351dc0165023707c3fdd6e25f30"
- $.entries[30].uri: "archiveQuests/Tome04.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
- $.entries[31].contentVersion: "c785a3236927daa079873486ebcc9be943275e0d"
+ $.entries[31].contentVersion: "77fbb724a71abf2861f3bb29f1c543023600ebb4"
- $.entries[31].uri: "archiveQuests/Tome05.json"
+ $.entries[31].uri: "archiveQuests/Tome07.json"
- $.entries[32].contentVersion: "31896fd041142a0281c074a1a620bc082bdb7fcc"
+ $.entries[32].contentVersion: "0715950aa0ea5e074ca30a89f8d641349a937b34"
- $.entries[32].uri: "archiveQuests/Tome06.json"
+ $.entries[32].uri: "archiveQuests/Tome08.json"
- $.entries[33].contentVersion: "0e7bc98c8a172224a68df442cad629c50f3d2263"
+ $.entries[33].contentVersion: "42c199804c178d651b49f3b97bcd98b9285b218a"
- $.entries[33].uri: "archiveQuests/Tome07.json"
+ $.entries[33].uri: "archiveQuests/Tome09.json"
- $.entries[34].contentVersion: "53b3bffe8dc8e69a8b919c0039cad926998a77c1"
+ $.entries[34].contentVersion: "370ab40f114500c119cf5c115b27a4e89b15299a"
- $.entries[34].uri: "archiveQuests/Tome08.json"
+ $.entries[34].uri: "archiveQuests/Tome10.json"
- $.entries[35].contentVersion: "92b193719e7e6a3ef4a7cddb5b5f257e8b3ca6b6"
+ $.entries[35].contentVersion: "036fafda3d75d6be515375032c29ab1230cfa2f7"
- $.entries[35].uri: "archiveQuests/Tome09.json"
+ $.entries[35].uri: "archiveQuests/Tome11.json"
- $.entries[36].contentVersion: "8019c83df30590a9f11775419702a982729dd36a"
+ $.entries[36].contentVersion: "a38e382ec351bf09248518120e0c9ff9b28b30b3"
- $.entries[36].uri: "archiveQuests/Tome10.json"
+ $.entries[36].uri: "archiveQuests/Tome12.json"
- $.entries[37].contentVersion: "9c768db3fd3a0d1e0cb0a054b2e93b9d2e282358"
+ $.entries[37].contentVersion: "1a9ac0fa07c4f1ab99256a91e3e172ffe119a1fb"
- $.entries[37].uri: "archiveQuests/Tome11.json"
+ $.entries[37].uri: "archiveQuests/Tome13.json"
- $.entries[38].contentVersion: "1a3a7f351fad029d5e28068ecca6a7863bfc5b8d"
+ $.entries[38].contentVersion: "723eec9734d95153ce89e82a3a46829990db16b4"
- $.entries[38].uri: "archiveQuests/Tome12.json"
+ $.entries[38].uri: "archiveQuests/Tome14.json"
- $.entries[39].contentVersion: "640e5ef5cd6bf2a3ac0055c90dd3ac6f92ef3e7e"
+ $.entries[39].contentVersion: "773e58d4c8355ea19fc79925d0c5808065c29a74"
- $.entries[39].uri: "archiveQuests/Tome13.json"
+ $.entries[39].uri: "archiveQuests/Tome15.json"
- $.entries[40].contentVersion: "aa930adaaa69ce8aa6e0ae6e1a3260f576f7ea0c"
+ $.entries[40].contentVersion: "e0f110c0b14cb248a60e5b00477d51d5d46d3e6c"
- $.entries[40].uri: "archiveQuests/Tome14.json"
+ $.entries[40].uri: "archiveQuests/Tome16.json"
- $.entries[41].contentVersion: "8aee24cc2400360420fde89d27ac73ae05740436"
+ $.entries[41].contentVersion: "04b7d2860505bb2d30095fe7a9d86092549119a4"
- $.entries[41].uri: "archiveQuests/Tome15.json"
+ $.entries[41].uri: "archiveQuests/Tome17.json"
- $.entries[42].contentVersion: "7614d564125b17a010356a86905e6ba03c461319"
+ $.entries[42].contentVersion: "fa0517621c23bbc60678f7a7604c37cbe718bd14"
- $.entries[42].uri: "archiveQuests/Tome16.json"
+ $.entries[42].uri: "archiveQuests/Tome18.json"
- $.entries[43].contentVersion: "ff1cc2fbb6efd1e09790a974b8312ecc60c221e1"
+ $.entries[43].contentVersion: "755043ebcd3e94612def8277e81f6762fcad7523"
- $.entries[43].uri: "archiveQuests/Tome17.json"
+ $.entries[43].uri: "archiveQuests/Tome19.json"
- $.entries[44].contentVersion: "264f2f3c7283a0bb28bdf83b3f8db8f158b72d01"
+ $.entries[44].contentVersion: "be113f1b8d6950261abb711f6ff50ed420dbfd58"
- $.entries[44].uri: "archiveQuests/Tome18.json"
+ $.entries[44].uri: "archiveQuests/Tome20.json"
- $.entries[45].contentVersion: "7cd0657aa5fd150bb1965e0a48514996aa65e0dc"
+ $.entries[45].contentVersion: "027d769d99efc3830d62aea71c0fedd6c5b2c404"
- $.entries[45].uri: "archiveQuests/Tome19.json"
+ $.entries[45].uri: "archiveQuests/Tome21.json"
- $.entries[46].contentVersion: "a0ea7c64c85706c8ad2ede9fe679d081e8a24489"
+ $.entries[46].contentVersion: "159f90c4b83c1a953a904145969087b448fefe6b"
- $.entries[46].uri: "archiveQuests/Tome20.json"
+ $.entries[46].uri: "archiveQuests/Tome22.json"
- $.entries[47].contentVersion: "17adaa14ec53415b0ae007633fddd3cad7a616b2"
+ $.entries[47].contentVersion: "a08880bcd21eda9d5258a824eb83594141eb0cc2"
- $.entries[47].uri: "archiveQuests/Tome21.json"
+ $.entries[47].uri: "archiveQuests/Winter2022.json"
- $.entries[48].contentVersion: "75aa843d775fbe07b82e19e38fb72e6cedfc7f66"
+ $.entries[48].contentVersion: "3e580a2c3e448bfa1efcc2b1795874fdc01275c5"
- $.entries[48].uri: "archiveQuests/Tome22.json"
+ $.entries[48].uri: "archiveQuests/Winter2023.json"
- $.entries[49].contentVersion: "10e12ff746ab8a1c7cd1f5189ba19d39f1ccc2d6"
+ $.entries[49].contentVersion: "2729ab656163a1d44369e10602ac5ef07418fcd1"
… 656 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.WereGonnaLiveForever
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCustomizationRecommendations[id=Quiche_W4]
- $.featuredCustomizationRecommendations[id=Quiche_W5]
- $.featuredCustomizationRecommendations[id=Quiche_W6]
- $.featuredCustomizationRecommendations[id=Quiche_W7]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[67].mainEndTime: "2026-03-24T15:00:00"
+ $.specialEvents[67].mainEndTime: "2026-03-18T15:00:00"
- $.specialEvents[67].postEndTime: "2026-03-24T15:00:00"
+ $.specialEvents[67].postEndTime: "2026-03-18T15:00:00"
```

