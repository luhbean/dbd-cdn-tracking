# live · 8.6.2_2430333live

| | |
|---|---|
| Build date | 2025-05-02 14:46 UTC |
| CDN version | `8.6.2_2430333live-1746197194` |
| Key | `8.6.2_live` |
| Compared with | [8.6.1_2410955live](../8.6.1_2410955live/CHANGES.md) (2025-04-17 12:44 UTC) |

## Summary

**0** added · **7** modified · **0** removed · 178 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.contentVersion.clientNewContentRebootMaxSeconds: 60.0
+ $.contentVersion.clientNewContentRebootMaxSeconds: 300.0
```

### [`archiveRewardData/content.json`](archiveRewardData/content.json)

[Full line-by-line diff](diffs/archiveRewardData/content.json.diff)

```diff
- $.Tome22.starsEarnedPerLevel: 1
+ $.Tome22.starsEarnedPerLevel: 2
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=AV_Head026]
+ $[id=AV_Legs026]
+ $[id=AV_Torso026]
+ $[id=DO_Body026]
+ $[id=DO_Head026]
+ $[id=DO_W026]
+ $[id=FM_Head038]
+ $[id=FM_Legs038]
+ $[id=FM_Torso038]
+ $[id=K31_Body017]
+ $[id=K31_Head017]
+ $[id=K31_W017]
+ $[id=S23_Head031]
+ $[id=S23_Legs031]
+ $[id=S23_Torso031]
+ $[id=AV_outfit_026]
+ $[id=DO_outfit_026]
+ $[id=FM_outfit_038]
+ $[id=K31_outfit_017]
+ $[id=S23_outfit_031]
+ $[id=Techwear_Bundle]
+ $[id=From_The_Rift_Bundle_250422]
+ $[id=From_The_Rift_Bundle_250429]
+ $[id=From_The_Rift_Bundle_250506]
+ $[id=Recurring_Charm_Bundle_250422]
+ $[id=Recurring_Charm_Bundle_250429]
+ $[id=Recurring_Charm_Bundle_250506]
+ $[id=Recurring_Dev_Bundle_250422]
+ $[id=Recurring_Dev_Bundle_250429]
+ $[id=Recurring_Dev_Bundle_250506]
+ $[id=Recurring_Killer_Bundle_250422]
+ $[id=Recurring_Killer_Bundle_250429]
+ $[id=Recurring_Killer_Bundle_250506]
+ $[id=Recurring_Survivor_Bundle_250422]
+ $[id=Recurring_Survivor_Bundle_250429]
+ $[id=Recurring_Survivor_Bundle_250506]
- $[id=From_The_Rift_Bundle_250401].metaData.imageComposition.maxItemCount: 3
+ $[id=From_The_Rift_Bundle_250401].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_250408].metaData.imageComposition.maxItemCount: 3
+ $[id=From_The_Rift_Bundle_250408].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_250415].metaData.imageComposition.maxItemCount: 3
+ $[id=From_The_Rift_Bundle_250415].metaData.imageComposition.maxItemCount: 2
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[4].additionalImages[0]
- $.collections[4].collectionId: "Hanami"
+ $.collections[4].collectionId: "Techwear"
- $.collections[4].collectionTitle.de: "Hanami "
+ $.collections[4].collectionTitle.de: "Techbekleidung"
- $.collections[4].collectionTitle.en: "Hanami "
+ $.collections[4].collectionTitle.en: "Techwear"
- $.collections[4].collectionTitle.es: "Hanami "
+ $.collections[4].collectionTitle.es: "Colección de Equipo técnico"
- $.collections[4].collectionTitle["es-MX"]: "Hanami "
+ $.collections[4].collectionTitle["es-MX"]: "Colección Indumentaria tecnológica"
- $.collections[4].collectionTitle.fr: "Hanami "
+ $.collections[4].collectionTitle.fr: "Technovêtements"
- $.collections[4].collectionTitle.it: "Hanami "
+ $.collections[4].collectionTitle.it: "Collezione Techwear"
- $.collections[4].collectionTitle.ja: "花見 "
+ $.collections[4].collectionTitle.ja: "テックウェア"
- $.collections[4].collectionTitle.ko: "벚꽃 축제 "
+ $.collections[4].collectionTitle.ko: "테크웨어 컬렉션"
- $.collections[4].collectionTitle.pl: "Hanami "
+ $.collections[4].collectionTitle.pl: "Kolekcja odzieży technicznej"
- $.collections[4].collectionTitle["pt-BR"]: "Hanami "
+ $.collections[4].collectionTitle["pt-BR"]: "Coleção da Roupa Tecnológica"
- $.collections[4].collectionTitle.ru: "Ханами "
+ $.collections[4].collectionTitle.ru: "Коллекция «Техно»"
- $.collections[4].collectionTitle.th: "ฮานามิ "
+ $.collections[4].collectionTitle.th: "อุปกรณ์เทคโนโลยี"
- $.collections[4].collectionTitle.tr: "Hanami "
+ $.collections[4].collectionTitle.tr: "Teknolojik Kıyafet Koleksiyonu"
- $.collections[4].collectionTitle["zh-Hans"]: "花见 "
+ $.collections[4].collectionTitle["zh-Hans"]: "机能服装系列"
- $.collections[4].collectionTitle["zh-Hant"]: "賞花 "
+ $.collections[4].collectionTitle["zh-Hant"]: "機能服飾收藏"
- $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
+ $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
- $.collections[4].inclusionVersion: "7.7.0 PTB"
+ $.collections[4].inclusionVersion: "7.7.0"
- $.collections[4].items[]: "MS_outfit_016"
- $.collections[4].items[]: "SwedenSurvivor_outfit_015"
- $.collections[4].items[]: "HK_outfit_014"
+ $.collections[4].items[]: "MT_outfit_023"
+ $.collections[4].items[]: "S25_outfit_015"
+ $.collections[4].items[]: "S28_outfit_018"
+ $.collections[4].items[]: "S34_outfit_011"
+ $.collections[4].items[]: "KK_outfit_025"
+ $.collections[4].items[]: "K23_outfit_021"
+ $.collections[4].items[]: "US_Outfit_023"
+ $.collections[4].items[]: "DK_outfit_022"
+ $.collections[4].items[]: "GS_outfit_029"
+ $.collections[4].items[]: "NK_outfit_029"
+ $.collections[4].items[]: "S29_outfit_017"
+ $.collections[4].items[]: "FM_outfit_038"
+ $.collections[4].items[]: "S23_outfit_031"
+ $.collections[4].items[]: "AV_outfit_026"
+ $.collections[4].items[]: "K31_outfit_017"
+ $.collections[4].items[]: "DO_outfit_026"
- $.collections[4].sortOrder: "-13"
+ $.collections[4].sortOrder: "-105"
- $.collections[4].updatedDate: "2024-02-01T17:19:10Z"
+ $.collections[4].updatedDate: "2025-04-21T13:25:07.469Z"
- $.collections[5].collectionId: "Rockabilly"
+ $.collections[5].collectionId: "Hanami"
- $.collections[5].collectionTitle.de: "Rockabilly"
+ $.collections[5].collectionTitle.de: "Hanami "
- $.collections[5].collectionTitle.en: "Rockabilly"
+ $.collections[5].collectionTitle.en: "Hanami "
- $.collections[5].collectionTitle.es: "Rockabilly"
+ $.collections[5].collectionTitle.es: "Hanami "
- $.collections[5].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[5].collectionTitle["es-MX"]: "Hanami "
- $.collections[5].collectionTitle.fr: "Rockabilly"
+ $.collections[5].collectionTitle.fr: "Hanami "
- $.collections[5].collectionTitle.it: "Rockabilly"
+ $.collections[5].collectionTitle.it: "Hanami "
- $.collections[5].collectionTitle.ja: "ロカビリー "
+ $.collections[5].collectionTitle.ja: "花見 "
- $.collections[5].collectionTitle.ko: "로커빌리"
+ $.collections[5].collectionTitle.ko: "벚꽃 축제 "
- $.collections[5].collectionTitle.pl: "Rockabilly"
+ $.collections[5].collectionTitle.pl: "Hanami "
- $.collections[5].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[5].collectionTitle["pt-BR"]: "Hanami "
- $.collections[5].collectionTitle.ru: "Рокабилли"
+ $.collections[5].collectionTitle.ru: "Ханами "
- $.collections[5].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[5].collectionTitle.th: "ฮานามิ "
- $.collections[5].collectionTitle.tr: "Rockabilly"
+ $.collections[5].collectionTitle.tr: "Hanami "
- $.collections[5].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[5].collectionTitle["zh-Hans"]: "花见 "
- $.collections[5].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[5].collectionTitle["zh-Hant"]: "賞花 "
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
- $.collections[5].items[]: "AV_outfit_015"
- $.collections[5].items[]: "MS_outfit_014"
- $.collections[5].items[]: "GS_outfit_014"
- $.collections[5].items[]: "MT_outfit_015"
- $.collections[5].items[]: "NK_outfit_014"
- $.collections[5].items[]: "S23_outfit_016"
- $.collections[5].items[]: "S24_outfit_013"
+ $.collections[5].items[]: "MS_outfit_016"
+ $.collections[5].items[]: "SwedenSurvivor_outfit_015"
+ $.collections[5].items[]: "HK_outfit_014"
- $.collections[5].sortOrder: "-14"
+ $.collections[5].sortOrder: "-13"
- $.collections[5].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[5].updatedDate: "2024-02-01T17:19:10Z"
- $.collections[6].collectionId: "SpringEnsembles"
+ $.collections[6].collectionId: "Rockabilly"
- $.collections[6].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[6].collectionTitle.de: "Rockabilly"
- $.collections[6].collectionTitle.en: "Spring Ensembles"
+ $.collections[6].collectionTitle.en: "Rockabilly"
- $.collections[6].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[6].collectionTitle.es: "Rockabilly"
- $.collections[6].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[6].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[6].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[6].collectionTitle.fr: "Rockabilly"
- $.collections[6].collectionTitle.it: "Completi primaverili"
+ $.collections[6].collectionTitle.it: "Rockabilly"
- $.collections[6].collectionTitle.ja: "春のアンサンブル"
+ $.collections[6].collectionTitle.ja: "ロカビリー "
- $.collections[6].collectionTitle.ko: "봄의 조화"
+ $.collections[6].collectionTitle.ko: "로커빌리"
- $.collections[6].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[6].collectionTitle.pl: "Rockabilly"
- $.collections[6].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[6].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[6].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[6].collectionTitle.ru: "Рокабилли"
- $.collections[6].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[6].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[6].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[6].collectionTitle.tr: "Rockabilly"
- $.collections[6].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[6].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[6].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[6].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
- $.collections[6].items[]: "Ace_outfit_008_01"
- $.collections[6].items[]: "HillBilly_outfit_008_01"
- $.collections[6].items[]: "FM_outfit_011"
- $.collections[6].items[]: "FM_outfit_011_01"
- $.collections[6].items[]: "S28_outfit_011"
- $.collections[6].items[]: "US_outfit_015"
- $.collections[6].items[]: "K21_outfit_010"
- $.collections[6].items[]: "K26_outfit_007"
- $.collections[6].items[]: "GK_outfit_013"
- $.collections[6].items[]: "S29_outfit_008"
+ $.collections[6].items[]: "AV_outfit_015"
+ $.collections[6].items[]: "MS_outfit_014"
+ $.collections[6].items[]: "GS_outfit_014"
+ $.collections[6].items[]: "MT_outfit_015"
+ $.collections[6].items[]: "NK_outfit_014"
+ $.collections[6].items[]: "S23_outfit_016"
+ $.collections[6].items[]: "S24_outfit_013"
- $.collections[6].sortOrder: "-15"
+ $.collections[6].sortOrder: "-14"
- $.collections[6].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[6].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[7].collectionId: "PopSuperstar"
+ $.collections[7].collectionId: "SpringEnsembles"
- $.collections[7].collectionTitle.de: "Superpopstar"
+ $.collections[7].collectionTitle.de: "Frühlings-Ensembles"
- $.collections[7].collectionTitle.en: "Pop Superstar"
+ $.collections[7].collectionTitle.en: "Spring Ensembles"
- $.collections[7].collectionTitle.es: "Superestrella del pop"
+ $.collections[7].collectionTitle.es: "Conjuntos de primavera"
- $.collections[7].collectionTitle["es-MX"]: "Superestrella del pop"
+ $.collections[7].collectionTitle["es-MX"]: "Conjuntos de primavera"
- $.collections[7].collectionTitle.fr: "Superstar de la pop"
+ $.collections[7].collectionTitle.fr: "Ensembles printaniers"
- $.collections[7].collectionTitle.it: "Superstar pop"
+ $.collections[7].collectionTitle.it: "Completi primaverili"
- $.collections[7].collectionTitle.ja: "ポップスター"
+ $.collections[7].collectionTitle.ja: "春のアンサンブル"
- $.collections[7].collectionTitle.ko: "팝 슈퍼스타"
+ $.collections[7].collectionTitle.ko: "봄의 조화"
- $.collections[7].collectionTitle.pl: "Supergwiazda popu"
+ $.collections[7].collectionTitle.pl: "Wiosenne stroje"
- $.collections[7].collectionTitle["pt-BR"]: "Estrela Pop"
+ $.collections[7].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
- $.collections[7].collectionTitle.ru: "Поп-суперзвезда"
+ $.collections[7].collectionTitle.ru: "Весенний ансамбль"
- $.collections[7].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
+ $.collections[7].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
- $.collections[7].collectionTitle.tr: "Popçu Süperstar"
+ $.collections[7].collectionTitle.tr: "Bahar Kreasyonu"
- $.collections[7].collectionTitle["zh-Hans"]: "流行巨星"
+ $.collections[7].collectionTitle["zh-Hans"]: "春日套装"
- $.collections[7].collectionTitle["zh-Hant"]: "流行巨星"
+ $.collections[7].collectionTitle["zh-Hant"]: "春天靈魂"
- $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
+ $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
- $.collections[7].items[]: "FM_outfit_020"
- $.collections[7].items[]: "GS_outfit_020"
- $.collections[7].items[]: "S25_outfit_013"
… 1180 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "793e4b09374873b0468c2f5dd84e2b7e43da3732"
+ $.entries[0].contentVersion: "260a0617beb48350aebadd55978418630fc12a9c"
- $.entries[0].downloadStrategy: "preferRemote"
+ $.entries[0].downloadStrategy: "preferPackaged"
- $.entries[0].enableChecksum: true
+ $.entries[0].enableChecksum: false
- $.entries[0].packagedPath: ""
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
- $.entries[0].schema: "s3ver://"
+ $.entries[0].schema: "s3verbin://"
- $.entries[0].uri: "catalog.json"
+ $.entries[0].uri: "images/T_UI_CollectionBanner_Techwear_2.png"
- $.entries[1].contentVersion: "4cd33aba517b8b8a7fa6877fd494526884f8364e"
+ $.entries[1].contentVersion: "73375dcf0e664697725a8d6fa73b8f8053a98033"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].enableChecksum: true
+ $.entries[1].enableChecksum: false
- $.entries[1].packagedPath: ""
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
- $.entries[1].schema: "s3ver://"
+ $.entries[1].schema: "s3verbin://"
- $.entries[1].uri: "bonusPointEventsContent.json"
+ $.entries[1].uri: "images/T_UI_SpecialPack_Techwear.png"
- $.entries[2].contentVersion: "4125975f3943d22d7246bf9af44fc9a0c5596559"
+ $.entries[2].contentVersion: "13d64d0013547d3391ace5877b1307231062e2cf"
- $.entries[2].uri: "freetoplay/NA/event.json"
+ $.entries[2].uri: "catalog.json"
- $.entries[3].contentVersion: "4125975f3943d22d7246bf9af44fc9a0c5596559"
+ $.entries[3].contentVersion: "808ede4e12ff2d4ece6f2e067535a46322de9ccb"
- $.entries[3].uri: "freetoplay/EU/event.json"
+ $.entries[3].uri: "bonusPointEventsContent.json"
- $.entries[4].contentVersion: "61bc64ae3c2fc0e5d3872cadfab175a069a23860"
+ $.entries[4].contentVersion: "f06f7b4ad5e3efe599a7a923e6d484d6a9f99a75"
- $.entries[4].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[4].uri: "freetoplay/NA/event.json"
- $.entries[5].contentVersion: "2f943b1e5d7a89cb3d569e42a910e93916fd44a0"
+ $.entries[5].contentVersion: "f06f7b4ad5e3efe599a7a923e6d484d6a9f99a75"
- $.entries[5].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[5].uri: "freetoplay/EU/event.json"
- $.entries[6].contentVersion: "b15b829efd42a31b9b643ab24640e3e2f578790e"
+ $.entries[6].contentVersion: "a6078019755c78cff394ca2c39ab04a6a375e99f"
- $.entries[6].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[6].uri: "archiveQuests/Anniversary2022.json"
- $.entries[7].contentVersion: "c69a306055471515cb0154c9e62d55a15516cd83"
+ $.entries[7].contentVersion: "43784920126224bbbe326d768831b57e4a7e1bc9"
- $.entries[7].uri: "archiveQuests/CalamariV1.json"
+ $.entries[7].uri: "archiveQuests/Anniversary2023.json"
- $.entries[8].contentVersion: "f958205af461f830e2a3a104c3def596d683a980"
+ $.entries[8].contentVersion: "82c4514754b7f6e0739d210139ceaede3984e79c"
- $.entries[8].uri: "archiveQuests/CalamariV2.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2024.json"
- $.entries[9].contentVersion: "a2921ce10b6f3c16246e98412f7f3922c336719b"
+ $.entries[9].contentVersion: "6665cc5d8b6a8c1b7f88490d3c99397f6c2cf3a8"
- $.entries[9].uri: "archiveQuests/CalamariV3.json"
+ $.entries[9].uri: "archiveQuests/CalamariV1.json"
- $.entries[10].contentVersion: "762821e10055479599ff39f96c5d82e8fec26765"
+ $.entries[10].contentVersion: "462bac629c399f32268d77d40534d049c54e873a"
- $.entries[10].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[10].uri: "archiveQuests/CalamariV2.json"
- $.entries[11].contentVersion: "3db5488f1bcf06fe78fe5712185820847af25ea0"
+ $.entries[11].contentVersion: "aa34d51c2f0178a667bd402b5c845810289391c7"
- $.entries[11].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[11].uri: "archiveQuests/CalamariV3.json"
- $.entries[12].contentVersion: "445d13d71a47f2fad55fd1a9c3f0ccd21a78e86f"
+ $.entries[12].contentVersion: "23afeef4be969d96dc56225e3b9fcc28928fffbc"
- $.entries[12].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[13].contentVersion: "e17b936e6b55d953ad87a87ae7db266f91a9000c"
+ $.entries[13].contentVersion: "adedaf00e25f4fc3386d7c94abaab0990cda27b4"
- $.entries[13].uri: "archiveQuests/FireflyV1.json"
+ $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[14].contentVersion: "d867825306c24bc50f369574bfecb5023a1d37ca"
+ $.entries[14].contentVersion: "67dfef8a2054da2ec9b2e2ac89bc99b3aa606398"
- $.entries[14].uri: "archiveQuests/Halloween2021.json"
+ $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[15].contentVersion: "72873acdaebdaa0a73d2178b5527a977f1348a62"
+ $.entries[15].contentVersion: "bb073f0a03e97999ba59b1f9ddee9878414bbfd5"
- $.entries[15].uri: "archiveQuests/Halloween2022.json"
+ $.entries[15].uri: "archiveQuests/FireflyV1.json"
- $.entries[16].contentVersion: "b17ad79f0c6b63ef87178339188db9c23b8db7f3"
+ $.entries[16].contentVersion: "f3f0e07f1f20d589ac89296f260a0eed8d49d185"
- $.entries[16].uri: "archiveQuests/Halloween2023.json"
+ $.entries[16].uri: "archiveQuests/Halloween2021.json"
- $.entries[17].contentVersion: "53dd9bb84d63b98549b38326cb07c536f470b408"
+ $.entries[17].contentVersion: "2c035c5a92570b8ff142ac2d501fb375e4e28eed"
- $.entries[17].uri: "archiveQuests/Halloween2024.json"
+ $.entries[17].uri: "archiveQuests/Halloween2022.json"
- $.entries[18].contentVersion: "978fedd5a3f4773d905bf8c076cbd87eb1490da5"
+ $.entries[18].contentVersion: "8308c191b9dd6b1b7fea34dc1c6be05cef7cdf13"
- $.entries[18].uri: "archiveQuests/Spring2024.json"
+ $.entries[18].uri: "archiveQuests/Halloween2023.json"
- $.entries[19].contentVersion: "5312b5af502869d0d2f9d5d7b90bd6aea38d07cf"
+ $.entries[19].contentVersion: "d280a807b23e2e9842643adbd574303459e1222d"
- $.entries[19].uri: "archiveQuests/Spring2025.json"
+ $.entries[19].uri: "archiveQuests/Halloween2024.json"
- $.entries[20].contentVersion: "d7f435b85643523a68382b8193059fcd7fa4a692"
+ $.entries[20].contentVersion: "6032b70c40b4aee0dbd1b3b1e58035cab0c5d2b3"
- $.entries[20].uri: "archiveQuests/Summer2023.json"
+ $.entries[20].uri: "archiveQuests/Spring2024.json"
- $.entries[21].contentVersion: "49284ee5911c0bafc97a2b18a5c6c98cf7f2e158"
+ $.entries[21].contentVersion: "aa766e97d6cff1b711974f7b44d33abd7929a91e"
- $.entries[21].uri: "archiveQuests/Tome01.json"
+ $.entries[21].uri: "archiveQuests/Spring2025.json"
- $.entries[22].contentVersion: "2d85487fd401f6259f5518753e6de5a7bda93146"
+ $.entries[22].contentVersion: "f3bb83ad36b7d831616a80b3f6c67390b2071fda"
- $.entries[22].uri: "archiveQuests/Tome02.json"
+ $.entries[22].uri: "archiveQuests/Summer2023.json"
- $.entries[23].contentVersion: "7e325bafc3b94a4042c4a83cc1abc3e5305acb6e"
+ $.entries[23].contentVersion: "736197229f73584973ce0eb060c6d2739beb7a3e"
- $.entries[23].uri: "archiveQuests/Tome03.json"
+ $.entries[23].uri: "archiveQuests/Tome01.json"
- $.entries[24].contentVersion: "c54ea06d71fb91e99c5b90c14cac1a1dc39a9af6"
+ $.entries[24].contentVersion: "98e8ccf1289ed156fed049019c7a3607ccd44548"
- $.entries[24].uri: "archiveQuests/Tome04.json"
+ $.entries[24].uri: "archiveQuests/Tome02.json"
- $.entries[25].contentVersion: "22ec12fb7cad825acf9e1ac04bce21fea47f2278"
+ $.entries[25].contentVersion: "08dde1e72d8e97692bf94663c5065985bfa1872d"
- $.entries[25].uri: "archiveQuests/Tome05.json"
+ $.entries[25].uri: "archiveQuests/Tome03.json"
- $.entries[26].contentVersion: "304655612ce159884edc8d9161dcdd70a8614e55"
+ $.entries[26].contentVersion: "8c582dbb5062abbdd04dc73d6ec7b103706058b8"
- $.entries[26].uri: "archiveQuests/Tome06.json"
+ $.entries[26].uri: "archiveQuests/Tome04.json"
- $.entries[27].contentVersion: "81f248c470c37a5ccf24a7b3f4c873f7e24f4b5c"
+ $.entries[27].contentVersion: "8b6e558850b3eb4fdfec552bce0c59b99fd6e890"
- $.entries[27].uri: "archiveQuests/Tome07.json"
+ $.entries[27].uri: "archiveQuests/Tome05.json"
- $.entries[28].contentVersion: "74cd4fc12c9872c85addf7e6d80ffebe73c0334f"
+ $.entries[28].contentVersion: "e923f0d1790bb74d6ec7c3ad075630a6bcaf4af3"
- $.entries[28].uri: "archiveQuests/Tome08.json"
+ $.entries[28].uri: "archiveQuests/Tome06.json"
- $.entries[29].contentVersion: "8131af10e8e0b503fe563a20299c7d2ccb45ba22"
+ $.entries[29].contentVersion: "c79c8bb5de80f8e28145ff325de25cf96d6f5d9f"
- $.entries[29].uri: "archiveQuests/Tome09.json"
+ $.entries[29].uri: "archiveQuests/Tome07.json"
- $.entries[30].contentVersion: "7c0489f396782dffc2d681bafb581a32ff0333df"
+ $.entries[30].contentVersion: "9d8dd948c425e6fbc6b463df59329297263b3317"
- $.entries[30].uri: "archiveQuests/Tome10.json"
+ $.entries[30].uri: "archiveQuests/Tome08.json"
- $.entries[31].contentVersion: "b6343f87d5ae6c9c27f73416ddb51f0249b8e0c6"
+ $.entries[31].contentVersion: "332cc293b4e4575673d71baac4821adfd9464223"
- $.entries[31].uri: "archiveQuests/Tome11.json"
+ $.entries[31].uri: "archiveQuests/Tome09.json"
- $.entries[32].contentVersion: "26aa66d15dbb8385cb62f09df3db469a96957a74"
+ $.entries[32].contentVersion: "e043e3b6ccba5ecc9f956694cbf636802dfde026"
- $.entries[32].uri: "archiveQuests/Tome12.json"
+ $.entries[32].uri: "archiveQuests/Tome10.json"
- $.entries[33].contentVersion: "0539c5b2218893f3253961b71ed0e0387c588764"
+ $.entries[33].contentVersion: "d9dc7af9f11d66ead44c156c6d9ede3e9dc238e1"
- $.entries[33].uri: "archiveQuests/Tome13.json"
+ $.entries[33].uri: "archiveQuests/Tome11.json"
- $.entries[34].contentVersion: "a365964a76fac7f07c6b444146ebe906b6467ef3"
+ $.entries[34].contentVersion: "3874a62ca18ec788700af1e8ca3d52eb9ccfeb9c"
- $.entries[34].uri: "archiveQuests/Tome14.json"
+ $.entries[34].uri: "archiveQuests/Tome12.json"
- $.entries[35].contentVersion: "dcee58350135b360039a0fa4ed3bd785e55929fc"
+ $.entries[35].contentVersion: "e786ed7b9bfdeb1a3284d651f30b1d78bb85b320"
- $.entries[35].uri: "archiveQuests/Tome15.json"
+ $.entries[35].uri: "archiveQuests/Tome13.json"
- $.entries[36].contentVersion: "ffabe462f4b9983292ba69c730ecd72176087f9b"
+ $.entries[36].contentVersion: "cf3845b031651abe89509fc5f13240293e9c5570"
- $.entries[36].uri: "archiveQuests/Tome16.json"
+ $.entries[36].uri: "archiveQuests/Tome14.json"
- $.entries[37].contentVersion: "d239cffbfcdbad8b224ec02af52e4416a302d78f"
+ $.entries[37].contentVersion: "7f48a26b05e959112a5d289f7b0faa7b2e00749c"
- $.entries[37].uri: "archiveQuests/Tome17.json"
+ $.entries[37].uri: "archiveQuests/Tome15.json"
- $.entries[38].contentVersion: "06244c2cd397c3a46e189fcf664274d8704f70cf"
+ $.entries[38].contentVersion: "dc54b21473c81281312d717e3d1a54d186976ad9"
- $.entries[38].uri: "archiveQuests/Tome18.json"
+ $.entries[38].uri: "archiveQuests/Tome16.json"
- $.entries[39].contentVersion: "03ebfb1907514c96b70429b4cd3927da234de763"
+ $.entries[39].contentVersion: "503e640005e5fd302441636e3895b5bb6b8fa422"
- $.entries[39].uri: "archiveQuests/Tome19.json"
+ $.entries[39].uri: "archiveQuests/Tome17.json"
- $.entries[40].contentVersion: "c9cb3f06c587f2321e3e8f8d9bd3307577474d1f"
+ $.entries[40].contentVersion: "26e6f2868726c52a3c7167c3a96b0e5b18bf4362"
- $.entries[40].uri: "archiveQuests/Tome20.json"
+ $.entries[40].uri: "archiveQuests/Tome18.json"
- $.entries[41].contentVersion: "7058ea6ff5379a2b4c9b7360cbe0303c580ca202"
+ $.entries[41].contentVersion: "e1c001a56045abbf858eaa1bd3d028df638c70b0"
- $.entries[41].uri: "archiveQuests/Tome21.json"
+ $.entries[41].uri: "archiveQuests/Tome19.json"
- $.entries[42].contentVersion: "172873602d26cab93521c83a124015edbbc5bc5e"
+ $.entries[42].contentVersion: "b4da99b2cb6d17657338e3915b3f6c57df54209b"
- $.entries[42].uri: "archiveQuests/Tome22.json"
+ $.entries[42].uri: "archiveQuests/Tome20.json"
- $.entries[43].contentVersion: "b85804240b9199ae30147ef55c999a2332e0138f"
+ $.entries[43].contentVersion: "fa44259ad63dcd4c25665fd47f668bd0982dcca1"
- $.entries[43].uri: "archiveQuests/Winter2022.json"
+ $.entries[43].uri: "archiveQuests/Tome21.json"
- $.entries[44].contentVersion: "59634a2d4b637e34fe5f2aea63608f00d99c7140"
+ $.entries[44].contentVersion: "6021062212e8ee11a3080edb1f6878fd14f6a1c0"
- $.entries[44].uri: "archiveQuests/Winter2023.json"
+ $.entries[44].uri: "archiveQuests/Tome22.json"
- $.entries[45].contentVersion: "af91a4a3077db81fd68032c5a819b448cadc1815"
+ $.entries[45].contentVersion: "bcb0d752f3c8643d0f7c2bed385ec47e38995606"
- $.entries[45].uri: "archiveQuests/Winter2024.json"
+ $.entries[45].uri: "archiveQuests/Winter2022.json"
… 642 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=IcecreamW3]
+ $.featuredCard[id=IcecreamW4]
+ $.featuredCustomizationRecommendations[id=IceCreamW3]
+ $.featuredCustomizationRecommendations[id=IceCreamW4]
+ $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=S28_outfit_021]
+ $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=NK_outfit_027]
+ $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=BE_outfit_018]
- $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=CM_outfit_030].weight: 55
+ $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=CM_outfit_030].weight: 16
- $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=S45_outfit_011].weight: 54
+ $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=S45_outfit_011].weight: 15
- $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K26_outfit_019].weight: 53
+ $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K26_outfit_019].weight: 14
- $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K30_outfit_012].weight: 52
+ $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K30_outfit_012].weight: 13
- $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K38_outfit_007].weight: 51
+ $.featuredCustomizationRecommendations[id=IceCreamW2].recommendations[id=K38_outfit_007].weight: 12
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[47]
- $.specialEventsData[11].eventId: "ChocolateBoxV1"
+ $.specialEventsData[11].eventId: "ChocolateBoxIcecream"
- $.specialEventsData[12].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[12].eventId: "ChocolateBoxV1"
- $.specialEventsData[12].lteData.affectsMMR: false
+ $.specialEventsData[12].lteData.affectsMMR: true
- $.specialEventsData[12].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[12].lteData.gameModeQueue: "ChocolateBox"
- $.specialEventsData[12].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[12].lteData.gameType: "ChocolateBox"
- $.specialEventsData[13].eventId: "FireflyV1"
+ $.specialEventsData[13].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[13].lteData.gameModeQueue: "Firefly"
+ $.specialEventsData[13].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[13].lteData.gameType: "Firefly"
+ $.specialEventsData[13].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[14].lteData
- $.specialEventsData[14].eventId: "Halloween2022"
+ $.specialEventsData[14].eventId: "FireflyV1"
- $.specialEventsData[14].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[15].eventId: "Halloween2023"
+ $.specialEventsData[15].eventId: "Halloween2022"
- $.specialEventsData[15].milestoneRewards[0]
- $.specialEventsData[15].milestoneRewards[1]
- $.specialEventsData[15].milestoneRewards[2]
+ $.specialEventsData[15].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[16].lteData
- $.specialEventsData[16].eventId: "Halloween2024"
+ $.specialEventsData[16].eventId: "Halloween2023"
- $.specialEventsData[16].eventPeriods[id=Halloween2024]
- $.specialEventsData[16].milestoneRewards[0].rewards[id=FU_012]
+ $.specialEventsData[16].milestoneRewards[0].rewards[id=XR_037]
- $.specialEventsData[16].milestoneRewards[1].rewards[id=FU_BDG_18]
+ $.specialEventsData[16].milestoneRewards[1].rewards[id=MT_Head027]
- $.specialEventsData[16].milestoneRewards[2].pointsCost: 20
+ $.specialEventsData[16].milestoneRewards[2].pointsCost: 21
- $.specialEventsData[16].milestoneRewards[2].rewards[id=FU_BNR_12]
+ $.specialEventsData[16].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[17].lteData
- $.specialEventsData[17].eventId: "Lunar2022"
+ $.specialEventsData[17].eventId: "Halloween2024"
+ $.specialEventsData[17].eventPeriods[id=Halloween2024]
+ $.specialEventsData[17].milestoneRewards[0]
+ $.specialEventsData[17].milestoneRewards[1]
+ $.specialEventsData[17].milestoneRewards[2]
- $.specialEventsData[17].miscRewards[id=killerStaticReward]
- $.specialEventsData[17].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[17].scoreEventRewards[0]
- $.specialEventsData[17].scoreEventRewards[1]
- $.specialEventsData[17].scoreEventRewards[2]
- $.specialEventsData[17].scoreEventRewards[3]
- $.specialEventsData[17].scoreEventRewards[4]
- $.specialEventsData[17].scoreEventRewards[5]
- $.specialEventsData[17].scoreEventRewards[6]
- $.specialEventsData[17].scoreEventRewards[7]
- $.specialEventsData[18].eventId: "Lunar2023"
+ $.specialEventsData[18].eventId: "Lunar2022"
- $.specialEventsData[18].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
+ $.specialEventsData[18].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
- $.specialEventsData[18].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[18].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[18].scoreEventRewards[2].weight: 15
+ $.specialEventsData[18].scoreEventRewards[2].weight: 20
- $.specialEventsData[18].scoreEventRewards[3].weight: 25
+ $.specialEventsData[18].scoreEventRewards[3].weight: 20
- $.specialEventsData[18].scoreEventRewards[5].weight: 20
+ $.specialEventsData[18].scoreEventRewards[5].weight: 15
- $.specialEventsData[18].scoreEventRewards[6].weight: 10
+ $.specialEventsData[18].scoreEventRewards[6].weight: 8
- $.specialEventsData[18].scoreEventRewards[7].weight: 5
+ $.specialEventsData[18].scoreEventRewards[7].weight: 2
- $.specialEventsData[19].eventId: "Spring2024"
+ $.specialEventsData[19].eventId: "Lunar2023"
- $.specialEventsData[19].eventTrackerObjectives[id=main]
+ $.specialEventsData[19].miscRewards[id=killerStaticReward]
+ $.specialEventsData[19].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[19].scoreEventRewards[0]
+ $.specialEventsData[19].scoreEventRewards[1]
+ $.specialEventsData[19].scoreEventRewards[2]
+ $.specialEventsData[19].scoreEventRewards[3]
+ $.specialEventsData[19].scoreEventRewards[4]
+ $.specialEventsData[19].scoreEventRewards[5]
+ $.specialEventsData[19].scoreEventRewards[6]
+ $.specialEventsData[19].scoreEventRewards[7]
- $.specialEventsData[20].lteData
- $.specialEventsData[20].eventId: "Spring2025"
+ $.specialEventsData[20].eventId: "Spring2024"
- $.specialEventsData[20].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
- $.specialEventsData[20].eventTrackerObjectives[id=main].questEventConditions
- $.specialEventsData[20].eventTrackerObjectives[id=main].questEvents
+ $.specialEventsData[20].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
+ $.specialEventsData[20].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
- $.specialEventsData[20].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
+ $.specialEventsData[20].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[4]
- $.specialEventsData[20].eventTrackerObjectives[id=main].milestones[5]
- $.specialEventsData[20].milestoneRewards[0]
- $.specialEventsData[20].milestoneRewards[1]
- $.specialEventsData[20].milestoneRewards[2]
+ $.specialEventsData[21].lteData
- $.specialEventsData[21].eventId: "Winter2023"
+ $.specialEventsData[21].eventId: "Spring2025"
+ $.specialEventsData[21].eventTrackerObjectives[id=main]
- $.specialEventsData[21].milestoneRewards[0].rewards[id=YE_005]
+ $.specialEventsData[21].milestoneRewards[0].rewards[id=IC_001]
- $.specialEventsData[21].milestoneRewards[1].pointsCost: 6
+ $.specialEventsData[21].milestoneRewards[1].pointsCost: 8
- $.specialEventsData[21].milestoneRewards[1].rewards[id=YE_BDG_01]
+ $.specialEventsData[21].milestoneRewards[1].rewards[id=IC_BDG_03]
- $.specialEventsData[21].milestoneRewards[2].pointsCost: 9
+ $.specialEventsData[21].milestoneRewards[2].pointsCost: 15
- $.specialEventsData[21].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[21].milestoneRewards[2].rewards[id=IC_BNR_03]
- $.specialEventsData[21].milestoneRewards[3]
- $.specialEventsData[21].milestoneRewards[4]
- $.specialEventsData[22].lteData
- $.specialEventsData[22].eventId: "Winter2024"
+ $.specialEventsData[22].eventId: "Winter2023"
- $.specialEventsData[22].eventPeriods[id=Winter2024]
- $.specialEventsData[22].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[22].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[22].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[22].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[22].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[22].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[22].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[22].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[22].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[22].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[22].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[22].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[22].milestoneRewards[3]
+ $.specialEventsData[22].milestoneRewards[4]
+ $.specialEventsData[23]
```

## Could not download

- `images/T_UI_CollectionBanner_Techwear_2.png (HTTP 404)`
- `images/T_UI_SpecialPack_Techwear.png (HTTP 404)`
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

