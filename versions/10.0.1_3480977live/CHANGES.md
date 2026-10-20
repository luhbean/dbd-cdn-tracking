# live · 10.0.1_3480977live

| | |
|---|---|
| Build date | 2026-07-02 18:57 UTC |
| CDN version | `10.0.1_3480977live-1783018633` |
| Key | `10.0.1_live` |
| Compared with | [10.0.2_3480390live](../10.0.2_3480390live/CHANGES.md) (2026-07-02 17:51 UTC) |

## Summary

**1** added · **10** modified · **0** removed · 203 unchanged

## New or updated images

<a href="images/T_UI_icon_Event_LaFogata.png"><img src="images/T_UI_icon_Event_LaFogata.png" alt="T_UI_icon_Event_LaFogata.png" width="240"></a>

## Modified files

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
- $.TOME24.vignettes[id=TOME24_03]
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
- $.TOME24.TOME24_03
```

### [`archiveQuests/Tome18.json`](archiveQuests/Tome18.json)

[Full line-by-line diff](diffs/archiveQuests/Tome18.json.diff)

```diff
- $.Tome18.level[1].nodes.node_T18_L2_Glyph01.clientInfoId: "YellowGlyph"
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph01.clientInfoId: "WhiteGlyph"
- $.Tome18.level[1].nodes.node_T18_L2_Glyph01.objectives.YellowGlyph
+ $.Tome18.level[1].nodes.node_T18_L2_Glyph01.objectives.WhiteGlyph
```

### [`bonusPointEventsContent.json`](bonusPointEventsContent.json)

[Full line-by-line diff](diffs/bonusPointEventsContent.json.diff)

```diff
- $.bonusPointEvents[0].endTime: "2026-06-16T14:59:00"
+ $.bonusPointEvents[0].endTime: "2026-07-07T14:59:00"
- $.bonusPointEvents[0].startTime: "2026-06-09T15:00:00"
+ $.bonusPointEvents[0].startTime: "2026-07-03T15:00:00"
- $.bonusPointEvents[1].endTime: "2025-11-04T15:59:00"
+ $.bonusPointEvents[1].endTime: "2026-06-16T14:59:00"
- $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[1].multiplier: 1.5
+ $.bonusPointEvents[1].multiplier: 2.0
- $.bonusPointEvents[1].startTime: "2025-10-28T15:00:00"
+ $.bonusPointEvents[1].startTime: "2026-06-09T15:00:00"
- $.bonusPointEvents[2].endTime: "2025-06-17T14:59:00"
+ $.bonusPointEvents[2].endTime: "2025-11-04T15:59:00"
- $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[2].multiplier: 2.0
+ $.bonusPointEvents[2].multiplier: 1.5
- $.bonusPointEvents[2].startTime: "2025-06-03T15:00:00"
+ $.bonusPointEvents[2].startTime: "2025-10-28T15:00:00"
- $.bonusPointEvents[3].endTime: "2025-03-31T14:59:00"
+ $.bonusPointEvents[3].endTime: "2025-06-17T14:59:00"
- $.bonusPointEvents[3].startTime: "2025-03-18T15:00:00"
+ $.bonusPointEvents[3].startTime: "2025-06-03T15:00:00"
- $.bonusPointEvents[4].endTime: "2025-02-10T15:59:00"
+ $.bonusPointEvents[4].endTime: "2025-03-31T14:59:00"
- $.bonusPointEvents[4].startTime: "2025-02-04T16:00:00"
+ $.bonusPointEvents[4].startTime: "2025-03-18T15:00:00"
- $.bonusPointEvents[5].endTime: "2025-01-28T15:59:00"
+ $.bonusPointEvents[5].endTime: "2025-02-10T15:59:00"
- $.bonusPointEvents[5].startTime: "2025-01-21T16:00:00"
+ $.bonusPointEvents[5].startTime: "2025-02-04T16:00:00"
- $.bonusPointEvents[6].endTime: "2025-01-07T15:59:00"
+ $.bonusPointEvents[6].endTime: "2025-01-28T15:59:00"
- $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[6].multiplier: 3.0
+ $.bonusPointEvents[6].multiplier: 2.0
- $.bonusPointEvents[6].startTime: "2024-12-26T16:00:00"
+ $.bonusPointEvents[6].startTime: "2025-01-21T16:00:00"
- $.bonusPointEvents[7].endTime: "2024-12-26T15:59:00"
+ $.bonusPointEvents[7].endTime: "2025-01-07T15:59:00"
- $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[7].multiplier: 2.0
+ $.bonusPointEvents[7].multiplier: 3.0
- $.bonusPointEvents[7].startTime: "2024-12-19T16:00:00"
+ $.bonusPointEvents[7].startTime: "2024-12-26T16:00:00"
- $.bonusPointEvents[8].endTime: "2024-11-28T16:00:00"
+ $.bonusPointEvents[8].endTime: "2024-12-26T15:59:00"
- $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[8].multiplier: 3.0
+ $.bonusPointEvents[8].multiplier: 2.0
- $.bonusPointEvents[8].startTime: "2024-11-22T20:00:00"
+ $.bonusPointEvents[8].startTime: "2024-12-19T16:00:00"
- $.bonusPointEvents[9].endTime: "2024-10-01T15:00:00"
+ $.bonusPointEvents[9].endTime: "2024-11-28T16:00:00"
- $.bonusPointEvents[9].startTime: "2024-09-24T15:00:00"
+ $.bonusPointEvents[9].startTime: "2024-11-22T20:00:00"
- $.bonusPointEvents[10].endTime: "2024-09-12T15:00:00"
+ $.bonusPointEvents[10].endTime: "2024-10-01T15:00:00"
- $.bonusPointEvents[10].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[10].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[10].multiplier: 2.0
+ $.bonusPointEvents[10].multiplier: 3.0
- $.bonusPointEvents[10].startTime: "2024-09-05T15:00:00"
+ $.bonusPointEvents[10].startTime: "2024-09-24T15:00:00"
- $.bonusPointEvents[11].endTime: "2024-06-13T15:00:00"
+ $.bonusPointEvents[11].endTime: "2024-09-12T15:00:00"
- $.bonusPointEvents[11].startTime: "2024-06-03T15:00:00"
+ $.bonusPointEvents[11].startTime: "2024-09-05T15:00:00"
- $.bonusPointEvents[12].endTime: "2024-05-21T15:00:00"
+ $.bonusPointEvents[12].endTime: "2024-06-13T15:00:00"
- $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[12].multiplier: 3.0
+ $.bonusPointEvents[12].multiplier: 2.0
- $.bonusPointEvents[12].startTime: "2024-05-14T16:00:00"
+ $.bonusPointEvents[12].startTime: "2024-06-03T15:00:00"
- $.bonusPointEvents[13].endTime: "2024-02-20T16:00:00"
+ $.bonusPointEvents[13].endTime: "2024-05-21T15:00:00"
- $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[13].multiplier: 1.5
+ $.bonusPointEvents[13].multiplier: 3.0
- $.bonusPointEvents[13].startTime: "2024-02-14T16:00:00"
+ $.bonusPointEvents[13].startTime: "2024-05-14T16:00:00"
- $.bonusPointEvents[14].endTime: "2023-09-19T15:00:00"
+ $.bonusPointEvents[14].endTime: "2024-02-20T16:00:00"
- $.bonusPointEvents[14].startTime: "2023-09-12T15:00:00"
+ $.bonusPointEvents[14].startTime: "2024-02-14T16:00:00"
- $.bonusPointEvents[15].endTime: "2023-07-13T15:00:00"
+ $.bonusPointEvents[15].endTime: "2023-09-19T15:00:00"
- $.bonusPointEvents[15].startTime: "2023-07-07T15:00:00"
+ $.bonusPointEvents[15].startTime: "2023-09-12T15:00:00"
- $.bonusPointEvents[16].endTime: "2023-05-30T15:00:00"
+ $.bonusPointEvents[16].endTime: "2023-07-13T15:00:00"
- $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[16].multiplier: 2.0
+ $.bonusPointEvents[16].multiplier: 1.5
- $.bonusPointEvents[16].startTime: "2023-05-23T15:00:00"
+ $.bonusPointEvents[16].startTime: "2023-07-07T15:00:00"
- $.bonusPointEvents[17].endTime: "2022-11-29T16:00:00"
+ $.bonusPointEvents[17].endTime: "2023-05-30T15:00:00"
- $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[17].startTime: "2022-11-22T16:00:00"
+ $.bonusPointEvents[17].startTime: "2023-05-23T15:00:00"
- $.bonusPointEvents[18].endTime: "2022-06-27T15:00:00"
+ $.bonusPointEvents[18].endTime: "2022-11-29T16:00:00"
- $.bonusPointEvents[18].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[18].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[18].startTime: "2022-06-23T15:00:00"
+ $.bonusPointEvents[18].startTime: "2022-11-22T16:00:00"
- $.bonusPointEvents[19].endTime: "2022-05-30T15:00:00"
+ $.bonusPointEvents[19].endTime: "2022-06-27T15:00:00"
- $.bonusPointEvents[19].startTime: "2022-05-23T15:00:00"
+ $.bonusPointEvents[19].startTime: "2022-06-23T15:00:00"
- $.bonusPointEvents[20].endTime: "2022-03-07T16:00:00"
+ $.bonusPointEvents[20].endTime: "2022-05-30T15:00:00"
- $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[20].multiplier: 1.5
+ $.bonusPointEvents[20].multiplier: 2.0
- $.bonusPointEvents[20].startTime: "2022-02-28T16:00:00"
+ $.bonusPointEvents[20].startTime: "2022-05-23T15:00:00"
- $.bonusPointEvents[21].endTime: "2022-01-21T16:00:00"
+ $.bonusPointEvents[21].endTime: "2022-03-07T16:00:00"
- $.bonusPointEvents[21].startTime: "2022-01-14T16:00:00"
+ $.bonusPointEvents[21].startTime: "2022-02-28T16:00:00"
- $.bonusPointEvents[22].endTime: "2021-11-29T16:00:00"
+ $.bonusPointEvents[22].endTime: "2022-01-21T16:00:00"
- $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[22].multiplier: 2.0
+ $.bonusPointEvents[22].multiplier: 1.5
- $.bonusPointEvents[22].startTime: "2021-11-25T16:00:00"
+ $.bonusPointEvents[22].startTime: "2022-01-14T16:00:00"
- $.bonusPointEvents[23].endTime: "2021-08-03T15:00:00"
+ $.bonusPointEvents[23].endTime: "2021-11-29T16:00:00"
- $.bonusPointEvents[23].startTime: "2021-07-29T15:00:00"
+ $.bonusPointEvents[23].startTime: "2021-11-25T16:00:00"
- $.bonusPointEvents[24].endTime: "2021-01-22T16:00:00"
+ $.bonusPointEvents[24].endTime: "2021-08-03T15:00:00"
- $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[24].multiplier: 1.5
+ $.bonusPointEvents[24].multiplier: 2.0
- $.bonusPointEvents[24].startTime: "2021-01-15T16:00:00"
+ $.bonusPointEvents[24].startTime: "2021-07-29T15:00:00"
- $.bonusPointEvents[25].endTime: "2020-11-02T16:29:59"
+ $.bonusPointEvents[25].endTime: "2021-01-22T16:00:00"
- $.bonusPointEvents[25].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[25].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[25].multiplier: 2.0
+ $.bonusPointEvents[25].multiplier: 1.5
- $.bonusPointEvents[25].startTime: "2020-10-29T15:00:00"
+ $.bonusPointEvents[25].startTime: "2021-01-15T16:00:00"
- $.bonusPointEvents[26].endTime: "2020-04-15T15:00:00"
+ $.bonusPointEvents[26].endTime: "2020-11-02T16:29:59"
- $.bonusPointEvents[26].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[26].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[26].multiplier: 1.5
+ $.bonusPointEvents[26].multiplier: 2.0
- $.bonusPointEvents[26].startTime: "2020-03-25T15:00:00"
+ $.bonusPointEvents[26].startTime: "2020-10-29T15:00:00"
- $.bonusPointEvents[27].endTime: "2020-01-06T16:00:00"
+ $.bonusPointEvents[27].endTime: "2020-04-15T15:00:00"
- $.bonusPointEvents[27].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[27].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[27].multiplier: 2.0
+ $.bonusPointEvents[27].multiplier: 1.5
- $.bonusPointEvents[27].startTime: "2020-01-02T16:00:00"
+ $.bonusPointEvents[27].startTime: "2020-03-25T15:00:00"
- $.bonusPointEvents[28].endTime: "2019-11-04T15:00:00"
+ $.bonusPointEvents[28].endTime: "2020-01-06T16:00:00"
- $.bonusPointEvents[28].startTime: "2019-10-31T15:00:00"
+ $.bonusPointEvents[28].startTime: "2020-01-02T16:00:00"
- $.bonusPointEvents[29].endTime: "2019-09-30T15:00:00"
+ $.bonusPointEvents[29].endTime: "2019-11-04T15:00:00"
- $.bonusPointEvents[29].startTime: "2019-09-26T15:00:00"
+ $.bonusPointEvents[29].startTime: "2019-10-31T15:00:00"
- $.bonusPointEvents[30].endTime: "2019-06-20T18:00:00"
+ $.bonusPointEvents[30].endTime: "2019-09-30T15:00:00"
- $.bonusPointEvents[30].startTime: "2019-06-14T18:00:00"
+ $.bonusPointEvents[30].startTime: "2019-09-26T15:00:00"
- $.bonusPointEvents[31].endTime: "2019-05-06T18:00:00"
+ $.bonusPointEvents[31].endTime: "2019-06-20T18:00:00"
- $.bonusPointEvents[31].startTime: "2019-05-02T18:00:00"
+ $.bonusPointEvents[31].startTime: "2019-06-14T18:00:00"
- $.bonusPointEvents[32].endTime: "2019-01-03T19:00:00"
+ $.bonusPointEvents[32].endTime: "2019-05-06T18:00:00"
- $.bonusPointEvents[32].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
+ $.bonusPointEvents[32].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[32].startTime: "2018-12-27T19:00:00"
+ $.bonusPointEvents[32].startTime: "2019-05-02T18:00:00"
- $.bonusPointEvents[33].endTime: "2018-11-12T19:00:00"
+ $.bonusPointEvents[33].endTime: "2019-01-03T19:00:00"
… 35 more change(s) — see the commit diff for everything
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=BE_Body031]
- $[id=BE_Mask031]
- $[id=BE_W031]
- $[id=RAM_012]
- $[id=RAM_013]
- $[id=RAM_BDG_27]
- $[id=RAM_BNR_18]
- $[id=RAM_BNR_19]
- $[id=RAM_BNR_20]
- $[id=RAM_BNR_21]
- $[id=SUS_BDG_24]
- $[id=BE_outfit_031]
- $[id=10.0.2_Iron_Maiden_Killer_Bundle]
- $[id=10.0.2_Iron_Maiden_Shirt_Bundle]
- $[id=SilentHillMega_collection_item]
+ $[id=From_The_Rift_Bundle_260630]
+ $[id=Recurring_Charm_Bundle_260630]
+ $[id=Recurring_Dev_Bundle_260630]
+ $[id=FM_Head040].defaultCost[1]
+ $[id=FM_Legs040].defaultCost[1]
+ $[id=FM_Torso040].defaultCost[1]
+ $[id=HS_Head030].defaultCost[1]
+ $[id=HS_Legs030].defaultCost[1]
+ $[id=HS_Torso030].defaultCost[1]
+ $[id=K28_Body019].defaultCost[1]
+ $[id=K28_Head019].defaultCost[1]
+ $[id=K28_W019].defaultCost[1]
- $[id=Armored_Bundle].defaultCost[0].price: 5616
+ $[id=Armored_Bundle].defaultCost[0].price: 2808
- $[id=Armored_Bundle].metaData.discount: 0.0
+ $[id=Armored_Bundle].metaData.discount: 0.5
- $[id=NewPlayer_Killers].defaultCost[0].price: 334
+ $[id=NewPlayer_Killers].defaultCost[0].price: 250
- $[id=NewPlayer_Killers].metaData.discount: 0.333334
+ $[id=NewPlayer_Killers].metaData.discount: 0.5
- $[id=NewPlayer_Survivors].defaultCost[0].price: 334
+ $[id=NewPlayer_Survivors].defaultCost[0].price: 250
- $[id=NewPlayer_Survivors].metaData.discount: 0.333334
+ $[id=NewPlayer_Survivors].metaData.discount: 0.5
- $[id=War_Hammer_Bundle].defaultCost[0].price: 5616
+ $[id=War_Hammer_Bundle].defaultCost[0].price: 2808
- $[id=War_Hammer_Bundle].metaData.discount: 0.0
+ $[id=War_Hammer_Bundle].metaData.discount: 0.5
- $[id=From_The_Rift_Bundle_260616].metaData.imageComposition.maxItemCount: 2
+ $[id=From_The_Rift_Bundle_260616].metaData.imageComposition.maxItemCount: 3
- $[id=From_The_Rift_Bundle_260623].metaData.imageComposition.maxItemCount: 2
+ $[id=From_The_Rift_Bundle_260623].metaData.imageComposition.maxItemCount: 3
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[30].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_SilentHill2_BC.T_UI_SpecialPack_SilentHill2_BC"
+ $.collections[30].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_Castlevania_Richter.T_UI_SpecialPack_Castlevania_Richter"
- $.collections[30].collectionId: "SilentHillMega"
+ $.collections[30].collectionId: "Castlevania"
- $.collections[30].collectionTitle.de: "Silent Hill"
+ $.collections[30].collectionTitle.de: "Castlevania"
- $.collections[30].collectionTitle.en: "Silent Hill"
+ $.collections[30].collectionTitle.en: "Castlevania"
- $.collections[30].collectionTitle.es: "Silent Hill"
+ $.collections[30].collectionTitle.es: "Castlevania"
- $.collections[30].collectionTitle["es-MX"]: "Silent Hill"
+ $.collections[30].collectionTitle["es-MX"]: "Castlevania"
- $.collections[30].collectionTitle.fr: "Silent Hill"
+ $.collections[30].collectionTitle.fr: "Castlevania"
- $.collections[30].collectionTitle.it: "Silent Hill"
+ $.collections[30].collectionTitle.it: "Castlevania"
- $.collections[30].collectionTitle.ja: "サイレントヒル"
+ $.collections[30].collectionTitle.ja: "悪魔城ドラキュラ"
- $.collections[30].collectionTitle.ko: "사일런트 힐"
+ $.collections[30].collectionTitle.ko: "캐슬바니아"
- $.collections[30].collectionTitle.pl: "Silent Hill"
+ $.collections[30].collectionTitle.pl: "Castlevania"
- $.collections[30].collectionTitle["pt-BR"]: "Silent Hill"
+ $.collections[30].collectionTitle["pt-BR"]: "Castlevania"
- $.collections[30].collectionTitle.ru: "Сайлент Хилл"
+ $.collections[30].collectionTitle.ru: "Castlevania"
- $.collections[30].collectionTitle.th: "ไซเลนต์ฮิล"
+ $.collections[30].collectionTitle.th: "Castlevania"
- $.collections[30].collectionTitle.tr: "Silent Hill"
+ $.collections[30].collectionTitle.tr: "Castlevania"
- $.collections[30].collectionTitle["zh-Hans"]: "寂静岭"
+ $.collections[30].collectionTitle["zh-Hans"]: "恶魔城"
- $.collections[30].collectionTitle["zh-Hant"]: "沉默之丘"
+ $.collections[30].collectionTitle["zh-Hant"]: "惡魔城"
- $.collections[30].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SilentHill.T_UI_CollectionBanner_SilentHill"
+ $.collections[30].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_Castlevania_Richter.T_UI_CollectionBanner_Castlevania_Richter"
- $.collections[30].inclusionVersion: "7.7.0 PTB"
+ $.collections[30].inclusionVersion: "8.2.0"
- $.collections[30].items[]: "FM_outfit_022"
- $.collections[30].items[]: "K20_outfit_006"
- $.collections[30].items[]: "K20_outfit_007"
- $.collections[30].items[]: "K20_outfit_008"
- $.collections[30].items[]: "K20_outfit_009"
- $.collections[30].items[]: "K20_outfit_010"
- $.collections[30].items[]: "KK_outfit_016"
- $.collections[30].items[]: "KK_outfit_016_01"
- $.collections[30].items[]: "KK_outfit_016_02"
- $.collections[30].items[]: "KK_outfit_016_03"
- $.collections[30].items[]: "S22_outfit_006"
- $.collections[30].items[]: "S22_outfit_007"
- $.collections[30].items[]: "S22_outfit_008"
- $.collections[30].items[]: "S22_outfit_010"
- $.collections[30].items[]: "S22_outfit_011"
- $.collections[30].items[]: "S22_outfit_012"
- $.collections[30].items[]: "S22_outfit_013"
- $.collections[30].items[]: "S22_outfit_02"
- $.collections[30].items[]: "S22_outfit_02_01"
- $.collections[30].items[]: "S22_Torso01_01"
- $.collections[30].items[]: "S22_Torso01_02"
- $.collections[30].items[]: "S22_Torso01_03"
- $.collections[30].items[]: "S22_Torso01_04"
- $.collections[30].items[]: "S22_Torso01_05"
- $.collections[30].items[]: "S22_Torso01_06"
+ $.collections[30].items[]: "GS_outfit_032"
+ $.collections[30].items[]: "K37_outfit_006"
+ $.collections[30].items[]: "K37_outfit_007"
+ $.collections[30].items[]: "K37_outfit_008"
+ $.collections[30].items[]: "K37_outfit_009"
+ $.collections[30].items[]: "S23_outfit_029"
+ $.collections[30].items[]: "S28_outfit_027"
+ $.collections[30].items[]: "S44_outfit_006"
+ $.collections[30].items[]: "S44_outfit_007"
+ $.collections[30].items[]: "S44_outfit_008"
+ $.collections[30].items[]: "S44_outfit_009"
+ $.collections[30].items[]: "S44_outfit_011"
+ $.collections[30].items[]: "SwedenSurvivor_outfit_027"
+ $.collections[30].items[]: "TN_outfit_021"
- $.collections[30].sortOrder: "-178"
+ $.collections[30].sortOrder: "-179"
- $.collections[30].updatedDate: "2025-10-23T16:36:27.198Z"
+ $.collections[30].updatedDate: "2025-10-23T16:36:58.015Z"
- $.collections[31].additionalImages[0]
- $.collections[31].collectionId: "Castlevania"
+ $.collections[31].collectionId: "CozyBreak"
- $.collections[31].collectionTitle.de: "Castlevania"
+ $.collections[31].collectionTitle.de: "Gemütliche Auszeit"
- $.collections[31].collectionTitle.en: "Castlevania"
+ $.collections[31].collectionTitle.en: "Cozy Break"
- $.collections[31].collectionTitle.es: "Castlevania"
+ $.collections[31].collectionTitle.es: "Tregua cómoda"
- $.collections[31].collectionTitle["es-MX"]: "Castlevania"
+ $.collections[31].collectionTitle["es-MX"]: "Descanso acogedor"
- $.collections[31].collectionTitle.fr: "Castlevania"
+ $.collections[31].collectionTitle.fr: "Vacances douillettes"
- $.collections[31].collectionTitle.it: "Castlevania"
+ $.collections[31].collectionTitle.it: "Pausa relax"
- $.collections[31].collectionTitle.ja: "悪魔城ドラキュラ"
+ $.collections[31].collectionTitle.ja: "くつろぐ休暇"
- $.collections[31].collectionTitle.ko: "캐슬바니아"
+ $.collections[31].collectionTitle.ko: "아늑한 휴식"
- $.collections[31].collectionTitle.pl: "Castlevania"
+ $.collections[31].collectionTitle.pl: "Przytulna przerwa"
- $.collections[31].collectionTitle["pt-BR"]: "Castlevania"
+ $.collections[31].collectionTitle["pt-BR"]: "Férias Relaxantes"
- $.collections[31].collectionTitle.ru: "Castlevania"
+ $.collections[31].collectionTitle.ru: "Уютный отдых"
- $.collections[31].collectionTitle.th: "Castlevania"
+ $.collections[31].collectionTitle.th: "พักสบายๆ"
- $.collections[31].collectionTitle.tr: "Castlevania"
+ $.collections[31].collectionTitle.tr: "Tatil Molası"
- $.collections[31].collectionTitle["zh-Hans"]: "恶魔城"
+ $.collections[31].collectionTitle["zh-Hans"]: "舒适歇息"
- $.collections[31].collectionTitle["zh-Hant"]: "惡魔城"
+ $.collections[31].collectionTitle["zh-Hant"]: "閒適小憩"
- $.collections[31].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_Castlevania_Richter.T_UI_CollectionBanner_Castlevania_Richter"
+ $.collections[31].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_CozyBreak.T_UI_CollectionBanner_CozyBreak"
- $.collections[31].inclusionVersion: "8.2.0"
+ $.collections[31].inclusionVersion: "7.7.0 PTB"
- $.collections[31].items[]: "GS_outfit_032"
- $.collections[31].items[]: "K37_outfit_006"
- $.collections[31].items[]: "K37_outfit_007"
- $.collections[31].items[]: "K37_outfit_008"
- $.collections[31].items[]: "K37_outfit_009"
- $.collections[31].items[]: "S23_outfit_029"
- $.collections[31].items[]: "S28_outfit_027"
- $.collections[31].items[]: "S44_outfit_006"
- $.collections[31].items[]: "S44_outfit_007"
- $.collections[31].items[]: "S44_outfit_008"
- $.collections[31].items[]: "S44_outfit_009"
- $.collections[31].items[]: "S44_outfit_011"
- $.collections[31].items[]: "SwedenSurvivor_outfit_027"
- $.collections[31].items[]: "TN_outfit_021"
+ $.collections[31].items[]: "AV_outfit_019"
+ $.collections[31].items[]: "FM_outfit_017"
+ $.collections[31].items[]: "GS_outfit_026"
+ $.collections[31].items[]: "HK_outfit_022"
+ $.collections[31].items[]: "KK_outfit_035"
+ $.collections[31].items[]: "KS_outfit_019"
+ $.collections[31].items[]: "MS_outfit_026"
+ $.collections[31].items[]: "S23_outfit_014"
+ $.collections[31].items[]: "S24_outfit_018"
+ $.collections[31].items[]: "S25_outfit_011"
+ $.collections[31].items[]: "S28_outfit_010"
+ $.collections[31].items[]: "S29_outfit_006"
+ $.collections[31].items[]: "S35_outfit_017"
+ $.collections[31].items[]: "S36_outfit_018"
+ $.collections[31].items[]: "S41_outfit_020"
- $.collections[31].sortOrder: "-179"
+ $.collections[31].sortOrder: "-180"
- $.collections[31].updatedDate: "2025-10-23T16:36:58.015Z"
+ $.collections[31].updatedDate: "2025-10-23T16:37:34.791Z"
+ $.collections[32].additionalImages[0]
- $.collections[32].collectionId: "CozyBreak"
+ $.collections[32].collectionId: "TheWalkingDead"
- $.collections[32].collectionTitle.de: "Gemütliche Auszeit"
+ $.collections[32].collectionTitle.de: "The Walking Dead"
- $.collections[32].collectionTitle.en: "Cozy Break"
+ $.collections[32].collectionTitle.en: "The Walking Dead"
- $.collections[32].collectionTitle.es: "Tregua cómoda"
+ $.collections[32].collectionTitle.es: "The Walking Dead"
- $.collections[32].collectionTitle["es-MX"]: "Descanso acogedor"
+ $.collections[32].collectionTitle["es-MX"]: "The Walking Dead"
- $.collections[32].collectionTitle.fr: "Vacances douillettes"
+ $.collections[32].collectionTitle.fr: "The Walking Dead"
- $.collections[32].collectionTitle.it: "Pausa relax"
+ $.collections[32].collectionTitle.it: "The Walking Dead"
- $.collections[32].collectionTitle.ja: "くつろぐ休暇"
+ $.collections[32].collectionTitle.ja: "ウォーキング・デッド"
- $.collections[32].collectionTitle.ko: "아늑한 휴식"
+ $.collections[32].collectionTitle.ko: "워킹 데드"
- $.collections[32].collectionTitle.pl: "Przytulna przerwa"
+ $.collections[32].collectionTitle.pl: "The Walking Dead"
- $.collections[32].collectionTitle["pt-BR"]: "Férias Relaxantes"
+ $.collections[32].collectionTitle["pt-BR"]: "The Walking Dead"
- $.collections[32].collectionTitle.ru: "Уютный отдых"
+ $.collections[32].collectionTitle.ru: "Ходячие мертвецы"
- $.collections[32].collectionTitle.th: "พักสบายๆ"
+ $.collections[32].collectionTitle.th: "The Walking Dead"
- $.collections[32].collectionTitle.tr: "Tatil Molası"
+ $.collections[32].collectionTitle.tr: "The Walking Dead"
- $.collections[32].collectionTitle["zh-Hans"]: "舒适歇息"
+ $.collections[32].collectionTitle["zh-Hans"]: "《The Walking Dead》"
- $.collections[32].collectionTitle["zh-Hant"]: "閒適小憩"
+ $.collections[32].collectionTitle["zh-Hant"]: "《陰屍路》"
- $.collections[32].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_CozyBreak.T_UI_CollectionBanner_CozyBreak"
+ $.collections[32].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_TWD_Rick.T_UI_CollectionBanner_TWD_Rick"
- $.collections[32].inclusionVersion: "7.7.0 PTB"
+ $.collections[32].inclusionVersion: "9.1.0 PTB"
- $.collections[32].items[]: "AV_outfit_019"
- $.collections[32].items[]: "FM_outfit_017"
- $.collections[32].items[]: "GS_outfit_026"
- $.collections[32].items[]: "HK_outfit_022"
- $.collections[32].items[]: "KK_outfit_035"
- $.collections[32].items[]: "KS_outfit_019"
- $.collections[32].items[]: "MS_outfit_026"
- $.collections[32].items[]: "S23_outfit_014"
- $.collections[32].items[]: "S24_outfit_018"
- $.collections[32].items[]: "S25_outfit_011"
- $.collections[32].items[]: "S28_outfit_010"
- $.collections[32].items[]: "S29_outfit_006"
… 4728 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].downloadStrategy: "preferPackaged"
+ $.entries[0].downloadStrategy: "preferRemote"
- $.entries[1].downloadStrategy: "preferPackaged"
+ $.entries[1].downloadStrategy: "preferRemote"
- $.entries[2].downloadStrategy: "preferPackaged"
+ $.entries[2].downloadStrategy: "preferRemote"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[8].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
+ $.entries[8].contentVersion: "1a73827d53e583dd03efaac5b38ab8fb04610088"
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
+ $.entries[8].packagedPath: "/DBDUICore/Assets/Common/Event/Community/T_UI_icon_Event_LaFogata.T_UI_icon_Event_LaFogata"
- $.entries[8].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
+ $.entries[8].uri: "images/T_UI_icon_Event_LaFogata.png"
- $.entries[9].contentVersion: "45dbc8795086ecc22e3ee59473bb597baae63b7f"
+ $.entries[9].contentVersion: "491d730fa3e6382e368680fcd716f0478ea742ee"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_TheLifeRoad.T_UI_CollectionBanner_TheLifeRoad"
+ $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_Black_Banquet.T_UI_SpecialPack_Black_Banquet"
- $.entries[9].uri: "images/T_UI_CollectionBanner_TheLifeRoad.png"
+ $.entries[9].uri: "images/T_UI_SpecialPack_Black_Banquet.png"
- $.entries[10].contentVersion: "623bb882552904b79446b6e334171fa8ca8d0345"
+ $.entries[10].contentVersion: "45dbc8795086ecc22e3ee59473bb597baae63b7f"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_TheLifeRoad.T_UI_SpecialPack_TheLifeRoad"
+ $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Sushi/T_UI_CollectionBanner_TheLifeRoad.T_UI_CollectionBanner_TheLifeRoad"
- $.entries[10].uri: "images/T_UI_SpecialPack_TheLifeRoad.png"
+ $.entries[10].uri: "images/T_UI_CollectionBanner_TheLifeRoad.png"
- $.entries[11].contentVersion: "e9fcd07c22bb0944e55984bacc5a39c80e769d83"
+ $.entries[11].contentVersion: "623bb882552904b79446b6e334171fa8ca8d0345"
- $.entries[11].enableChecksum: true
+ $.entries[11].enableChecksum: false
- $.entries[11].packagedPath: ""
+ $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Sushi/T_UI_SpecialPack_TheLifeRoad.T_UI_SpecialPack_TheLifeRoad"
- $.entries[11].schema: "s3ver://"
+ $.entries[11].schema: "s3verbin://"
- $.entries[11].uri: "catalog.json"
+ $.entries[11].uri: "images/T_UI_SpecialPack_TheLifeRoad.png"
- $.entries[12].contentVersion: "6e40fe362ab49668264ac7dc6c9e6edb65c25f9f"
+ $.entries[12].contentVersion: "2409a17f4d4c2bacecf8c4904fed4c3dceb64bb1"
- $.entries[12].uri: "bonusPointEventsContent.json"
+ $.entries[12].uri: "catalog.json"
- $.entries[13].contentVersion: "1f75c1dc50dee179d18a6fcc69f89e12c9f1d250"
+ $.entries[13].contentVersion: "0a0f57d2dd9beed60c28a829a156c197e9d13fa9"
- $.entries[13].uri: "freetoplay/NA/event.json"
+ $.entries[13].uri: "bonusPointEventsContent.json"
- $.entries[14].contentVersion: "1f75c1dc50dee179d18a6fcc69f89e12c9f1d250"
+ $.entries[14].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
- $.entries[14].uri: "freetoplay/EU/event.json"
+ $.entries[14].uri: "freetoplay/NA/event.json"
- $.entries[15].contentVersion: "728990dee9d5732a2a4ac75c2c753147bc4e594b"
+ $.entries[15].contentVersion: "898051766e5a8c40db1b33642c972d78dda97739"
- $.entries[15].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[15].uri: "freetoplay/EU/event.json"
- $.entries[16].contentVersion: "c6cd4df2d61da9a5a2f29358564b66457c6e2fc0"
+ $.entries[16].contentVersion: "23b1f95aaea33a5eb00ef8deb32d515af3be02b1"
- $.entries[16].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[16].uri: "archiveQuests/Anniversary2022.json"
- $.entries[17].contentVersion: "4ee674fb40449e7212c3953661120a74c959baaf"
+ $.entries[17].contentVersion: "60542d2a101497b73a338989942ef496ae13d010"
- $.entries[17].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[17].uri: "archiveQuests/Anniversary2023.json"
- $.entries[18].contentVersion: "7f5868c420eb9c75c1d671358a4ce010d13477d0"
+ $.entries[18].contentVersion: "53077fd04e446bfa797e36d08f46746b74d7d514"
- $.entries[18].uri: "archiveQuests/CalamariV1.json"
+ $.entries[18].uri: "archiveQuests/Anniversary2024.json"
- $.entries[19].contentVersion: "982cb91f4d3437f20b98a8646c5dc9f2a5777efd"
+ $.entries[19].contentVersion: "30f6f91bea1afbf1b488a777cbd35039848da3dd"
- $.entries[19].uri: "archiveQuests/CalamariV2.json"
+ $.entries[19].uri: "archiveQuests/CalamariV1.json"
- $.entries[20].contentVersion: "4c4ed86024343728623d42092e7331372bfa4b4b"
+ $.entries[20].contentVersion: "979deafa6eaa6e239324ae0bb63a325b0b954060"
- $.entries[20].uri: "archiveQuests/CalamariV3.json"
+ $.entries[20].uri: "archiveQuests/CalamariV2.json"
- $.entries[21].contentVersion: "aba3db56f0608ce792f5d246d9c7a5029298786e"
+ $.entries[21].contentVersion: "a929110e9b2f53b4ad7d9984a3619abad514c4bc"
- $.entries[21].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[21].uri: "archiveQuests/CalamariV3.json"
- $.entries[22].contentVersion: "d3512d8f6680c63afde0f805716cf913741a1e8d"
+ $.entries[22].contentVersion: "c4a0c4fb3e9426161dab7bdeb23c586d22c0b1b5"
- $.entries[22].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[23].contentVersion: "993ec614f8414864752cec6fcfa26251229d2529"
+ $.entries[23].contentVersion: "2bc9034be7302a71d8eb0ee4309188a1c7534a99"
- $.entries[23].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[24].contentVersion: "a1dccb478f49bae14ff62cb51e528b3e94605aa1"
+ $.entries[24].contentVersion: "6906a8dc3327bc3dccaab96311adec8bc16eadf4"
- $.entries[24].uri: "archiveQuests/FireflyV1.json"
+ $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[25].contentVersion: "11f1feefc69ad130e47446e4286683ac4ef38c86"
+ $.entries[25].contentVersion: "c710af6ea9bb8cb30b3487d9ef9f67e06d7ae543"
- $.entries[25].uri: "archiveQuests/Halloween2021.json"
+ $.entries[25].uri: "archiveQuests/FireflyV1.json"
- $.entries[26].contentVersion: "d9eabf8bbfe37939f355b9d81e9cc46d306ce985"
+ $.entries[26].contentVersion: "63a7ccd5a00239f68cefc6c661f953642415cbe1"
- $.entries[26].uri: "archiveQuests/Halloween2022.json"
+ $.entries[26].uri: "archiveQuests/Halloween2021.json"
- $.entries[27].contentVersion: "27744f4794273b886a07b537f88b700f656e9d54"
+ $.entries[27].contentVersion: "ccda015e7849f072a00bdfa0baf103d2d12583a4"
- $.entries[27].uri: "archiveQuests/Halloween2023.json"
+ $.entries[27].uri: "archiveQuests/Halloween2022.json"
- $.entries[28].contentVersion: "3c57c3992fefc5d75010c9579f49f377162c6858"
+ $.entries[28].contentVersion: "4230b8f8b088ac484ac110c853f8b5f6f9f54c44"
- $.entries[28].uri: "archiveQuests/Halloween2024.json"
+ $.entries[28].uri: "archiveQuests/Halloween2023.json"
- $.entries[29].contentVersion: "7f7378b5489aa78a10d67771dc3eeb037d7893ac"
+ $.entries[29].contentVersion: "bb980e294fd2c9f3f7b3ae1d66156c060dae509d"
- $.entries[29].uri: "archiveQuests/Spring2024.json"
+ $.entries[29].uri: "archiveQuests/Halloween2024.json"
- $.entries[30].contentVersion: "201d33519600eb746d842b4d1b365e5eb7344265"
+ $.entries[30].contentVersion: "d17bed4208ba9cb25cfc5c67e0e9310df60f145e"
- $.entries[30].uri: "archiveQuests/Spring2025.json"
+ $.entries[30].uri: "archiveQuests/Spring2024.json"
- $.entries[31].contentVersion: "30a65bc1126477f48875b5d7a35503c48f499cc6"
+ $.entries[31].contentVersion: "65ac72211439c2789f3d752d31b8b2c118fccad9"
- $.entries[31].uri: "archiveQuests/Summer2023.json"
+ $.entries[31].uri: "archiveQuests/Spring2025.json"
- $.entries[32].contentVersion: "fb1cd3e7e4a680a7c478042b6e7493a716aac5ae"
+ $.entries[32].contentVersion: "dd54b8656432c2e7b4ffb3e3cedacd5e286cecc7"
- $.entries[32].uri: "archiveQuests/Tome01.json"
+ $.entries[32].uri: "archiveQuests/Summer2023.json"
- $.entries[33].contentVersion: "4d70f6583c2e693a610a81cfca4b52361f7fcfd6"
+ $.entries[33].contentVersion: "5d021476a155e6e1836e2c3033f74bd63cdbf302"
- $.entries[33].uri: "archiveQuests/Tome02.json"
+ $.entries[33].uri: "archiveQuests/Tome01.json"
- $.entries[34].contentVersion: "9c66e52b7f86ec2ef9d60c915ffa561cbb028703"
+ $.entries[34].contentVersion: "ef56572e18860b56caeee118249e290de8f6df3c"
- $.entries[34].uri: "archiveQuests/Tome03.json"
+ $.entries[34].uri: "archiveQuests/Tome02.json"
- $.entries[35].contentVersion: "e503ae893f54f9c00180d77a548f6fe746a7a358"
+ $.entries[35].contentVersion: "ad87d42bbbed21f5b75cb711641f790004064c64"
- $.entries[35].uri: "archiveQuests/Tome04.json"
+ $.entries[35].uri: "archiveQuests/Tome03.json"
- $.entries[36].contentVersion: "f2db871c64229e76298c78c72173b695e7020027"
+ $.entries[36].contentVersion: "312a43cd3c9227e4872ecfb5c307fe9e57783a1a"
- $.entries[36].uri: "archiveQuests/Tome05.json"
+ $.entries[36].uri: "archiveQuests/Tome04.json"
- $.entries[37].contentVersion: "df87d7da84f348e8af302ad50561647b8bd256f2"
+ $.entries[37].contentVersion: "3b6250799f8db12262ffe9894a6b0ed19e3292a4"
- $.entries[37].uri: "archiveQuests/Tome06.json"
+ $.entries[37].uri: "archiveQuests/Tome05.json"
- $.entries[38].contentVersion: "a227c9ef57835f62e5442e6e8bb2fbde30e29d76"
+ $.entries[38].contentVersion: "854a58485c464e7c45b1c68c9f8544029b074841"
- $.entries[38].uri: "archiveQuests/Tome07.json"
+ $.entries[38].uri: "archiveQuests/Tome06.json"
- $.entries[39].contentVersion: "76f696c23feacbd2f39899ae8d369032c936125a"
+ $.entries[39].contentVersion: "19f615c5c71b6d5bed5b777385068ed4fbea7ecf"
- $.entries[39].uri: "archiveQuests/Tome08.json"
+ $.entries[39].uri: "archiveQuests/Tome07.json"
- $.entries[40].contentVersion: "faecf4cab0c69d0454f9d6b5dd75e774786723dd"
+ $.entries[40].contentVersion: "1288046d48b6aac806a1e2887844cf94d3417725"
- $.entries[40].uri: "archiveQuests/Tome09.json"
+ $.entries[40].uri: "archiveQuests/Tome08.json"
- $.entries[41].contentVersion: "4e57058d5edab427a4e047d6559fe5f942d1e006"
+ $.entries[41].contentVersion: "046ffc40cc7b773ee54a9b84b41689852e7aab34"
- $.entries[41].uri: "archiveQuests/Tome10.json"
+ $.entries[41].uri: "archiveQuests/Tome09.json"
- $.entries[42].contentVersion: "875972e34b54f9a3517b583f61aa2fd22138371c"
+ $.entries[42].contentVersion: "91006859e78ee3a9b4f88ec352c48aa08c8d3645"
- $.entries[42].uri: "archiveQuests/Tome11.json"
+ $.entries[42].uri: "archiveQuests/Tome10.json"
- $.entries[43].contentVersion: "fc7470e5ba0fc9434cecd46122c539b29d695c97"
+ $.entries[43].contentVersion: "4ab8cc9d5789677d4a05d2f2e0f5a28e3958eb1e"
- $.entries[43].uri: "archiveQuests/Tome12.json"
+ $.entries[43].uri: "archiveQuests/Tome11.json"
- $.entries[44].contentVersion: "bd7d058543fbd55f830a7ef4ac09a1e257dac738"
+ $.entries[44].contentVersion: "49deaadc0578ee33ccf3cb42ef57de339fbde90c"
- $.entries[44].uri: "archiveQuests/Tome13.json"
+ $.entries[44].uri: "archiveQuests/Tome12.json"
- $.entries[45].contentVersion: "8e762dfab44b8d8d6dd3e7e92abfd5d3339cdac0"
+ $.entries[45].contentVersion: "5539a19968493d5bffc7d38f78797afbd4bec4e7"
- $.entries[45].uri: "archiveQuests/Tome14.json"
+ $.entries[45].uri: "archiveQuests/Tome13.json"
- $.entries[46].contentVersion: "90267d35a49559b86218afa3968374a5555e50ae"
+ $.entries[46].contentVersion: "945d0c66c914f06bd1961c4302b8e7297a681f37"
- $.entries[46].uri: "archiveQuests/Tome15.json"
+ $.entries[46].uri: "archiveQuests/Tome14.json"
- $.entries[47].contentVersion: "6ddb4edc8cc09c1b70c4b384a3df0d227f78d938"
+ $.entries[47].contentVersion: "df5c7c0b034694ae35cd3fedfaa8e2c7417cb3ed"
- $.entries[47].uri: "archiveQuests/Tome16.json"
+ $.entries[47].uri: "archiveQuests/Tome15.json"
- $.entries[48].contentVersion: "607c6450ef9763c653dd26e7eb716ad71b70b538"
+ $.entries[48].contentVersion: "8a505ba157e2361de0abf53cbb0c81e49aae6652"
- $.entries[48].uri: "archiveQuests/Tome17.json"
+ $.entries[48].uri: "archiveQuests/Tome16.json"
- $.entries[49].contentVersion: "4d812d19bc152cbf2612bd474fda5d984ee2089f"
+ $.entries[49].contentVersion: "ed1700a157013be81af5571ea80834ef2a09f7ca"
- $.entries[49].uri: "archiveQuests/Tome18.json"
+ $.entries[49].uri: "archiveQuests/Tome17.json"
- $.entries[50].contentVersion: "e13cddb1b34db3010a756327b056cfd4285764f5"
+ $.entries[50].contentVersion: "bafc72caf68b90de075e7e39a34d77fe80444383"
- $.entries[50].uri: "archiveQuests/Tome19.json"
+ $.entries[50].uri: "archiveQuests/Tome18.json"
- $.entries[51].contentVersion: "9f73adbc0834a01310903a00cd0251aaa853fc3a"
+ $.entries[51].contentVersion: "a18c1899e8f9331a9804c8c4fdceca390306238e"
… 673 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.Killer07
```

### [`narrativeCollections.json`](narrativeCollections.json)

[Full line-by-line diff](diffs/narrativeCollections.json.diff)

```diff
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_08]
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_09]
- $.DefaultChunk.collections[id=COLL_001].collectibles[id=COLL_001_10]
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Sushi_W3]
+ $.featuredCustomizationRecommendations[id=Sushi_W3]
```

