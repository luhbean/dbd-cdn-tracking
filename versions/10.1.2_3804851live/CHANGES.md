# live · 10.1.2_3804851live

| | |
|---|---|
| Build date | 2026-09-22 14:38 UTC |
| CDN version | `10.1.2_3804851live-1790087888` |
| Key | `10.1.2_live` |
| Compared with | [10.1.2_3800571live](../10.1.2_3800571live/CHANGES.md) (2026-09-21 15:04 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 208 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=AutumnFashion_collection_item]
- $[id=10.1.2_Autumn_Fashion].metaData.sortOrder: 0
+ $[id=10.1.2_Autumn_Fashion].metaData.sortOrder: 1999
- $[id=SAW_Bundle].metaData.sortOrder: 1001
+ $[id=SAW_Bundle].metaData.sortOrder: 2001
- $[id=Tome_8_Bundle].metaData.sortOrder: 1000
+ $[id=Tome_8_Bundle].metaData.sortOrder: 1998
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[21].limitedAvailabilityEndDate: "2026-04-28T15:00:00Z"
+ $.collections[21].visibleAfterEndDate: false
- $.collections[21].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_Specialpack_FallFashion.T_UI_Specialpack_FallFashion"
+ $.collections[21].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Maple/T_UI_SpecialPack_AttackOnTitan.T_UI_SpecialPack_AttackOnTitan"
- $.collections[21].collectionId: "AutumnFashion"
+ $.collections[21].collectionId: "AttackOnTitan"
- $.collections[21].collectionTitle.de: "Herbstmode"
+ $.collections[21].collectionTitle.de: "Attack On Titan"
- $.collections[21].collectionTitle.en: "Autumn Fashion"
+ $.collections[21].collectionTitle.en: "Attack on Titan"
- $.collections[21].collectionTitle.es: "Moda otoñal"
+ $.collections[21].collectionTitle.es: "Ataque a los Titanes"
- $.collections[21].collectionTitle["es-MX"]: "Moda otoñal"
+ $.collections[21].collectionTitle["es-MX"]: "Attack on Titan"
- $.collections[21].collectionTitle.fr: "Mode d'automne"
+ $.collections[21].collectionTitle.fr: "L'Attaque des Titans"
- $.collections[21].collectionTitle.it: "Moda autunnale"
+ $.collections[21].collectionTitle.it: "Attack on Titan"
- $.collections[21].collectionTitle.ja: "秋のファッション"
+ $.collections[21].collectionTitle.ja: "進撃の巨人"
- $.collections[21].collectionTitle.ko: "가을 패션"
+ $.collections[21].collectionTitle.ko: "진격의 거인"
- $.collections[21].collectionTitle.pl: "Jesienna moda"
+ $.collections[21].collectionTitle.pl: "Attack on Titan"
- $.collections[21].collectionTitle["pt-BR"]: "Moda Outono"
+ $.collections[21].collectionTitle["pt-BR"]: "Ataque dos Titãs"
- $.collections[21].collectionTitle.ru: "Стиль осени"
+ $.collections[21].collectionTitle.ru: "Атака титанов"
- $.collections[21].collectionTitle.th: "แฟชั่นฤดูใบไม้ร่วง"
+ $.collections[21].collectionTitle.th: "ผ่าพิภพไททัน"
- $.collections[21].collectionTitle.tr: "Sonbahar Modası"
+ $.collections[21].collectionTitle.tr: "Attack on Titan"
- $.collections[21].collectionTitle["zh-Hans"]: "秋日时尚"
+ $.collections[21].collectionTitle["zh-Hans"]: "《进击的巨人》"
- $.collections[21].collectionTitle["zh-Hant"]: "秋季時尚"
+ $.collections[21].collectionTitle["zh-Hant"]: "進擊的巨人"
- $.collections[21].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Eclair/T_UI_CollectionBanner_AutumnFashion.T_UI_CollectionBanner_AutumnFashion"
+ $.collections[21].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_AttackOnTitan.T_UI_CollectionBanner_AttackOnTitan"
- $.collections[21].inclusionVersion: "8.2.0"
+ $.collections[21].inclusionVersion: "9.2.0"
- $.collections[21].items[]: "FM_outfit_035"
- $.collections[21].items[]: "GS_outfit_038"
- $.collections[21].items[]: "K28_outfit_015"
- $.collections[21].items[]: "KK_outfit_039"
- $.collections[21].items[]: "S25_outfit_026"
- $.collections[21].items[]: "S28_outfit_032"
- $.collections[21].items[]: "S46_outfit_012"
+ $.collections[21].items[]: "AV_outfit_017"
+ $.collections[21].items[]: "DF_outfit_020"
+ $.collections[21].items[]: "GS_outfit_019"
+ $.collections[21].items[]: "HK_outfit_016"
+ $.collections[21].items[]: "JP_outfit_018"
+ $.collections[21].items[]: "MT_outfit_019"
+ $.collections[21].items[]: "S23_outfit_018"
+ $.collections[21].items[]: "SwedenKiller_outfit_012"
+ $.collections[21].items[]: "SwedenSurvivor_outfit_017"
+ $.collections[21].items[]: "US_outfit_016"
- $.collections[21].limitedAvailabilityStartDate: "2024-09-03T15:00:00Z"
+ $.collections[21].limitedAvailabilityStartDate: "2025-10-09T15:00:00Z"
- $.collections[21].sortOrder: "-169"
+ $.collections[21].sortOrder: "-170"
- $.collections[21].updatedDate: "2025-10-06T20:22:53.266Z"
+ $.collections[21].updatedDate: "2025-10-08T13:41:42.263Z"
- $.collections[22].limitedAvailabilityEndDate: "2026-04-28T15:00:00Z"
- $.collections[22].visibleAfterEndDate: false
- $.collections[22].additionalImages[0]
- $.collections[22].collectionId: "AttackOnTitan"
+ $.collections[22].collectionId: "VoidTouched"
- $.collections[22].collectionTitle.de: "Attack On Titan"
+ $.collections[22].collectionTitle.de: "Die Leere"
- $.collections[22].collectionTitle.en: "Attack on Titan"
+ $.collections[22].collectionTitle.en: "The Void"
- $.collections[22].collectionTitle.es: "Ataque a los Titanes"
+ $.collections[22].collectionTitle.es: "El Vacío"
- $.collections[22].collectionTitle["es-MX"]: "Attack on Titan"
+ $.collections[22].collectionTitle["es-MX"]: "El Vacío"
- $.collections[22].collectionTitle.fr: "L'Attaque des Titans"
+ $.collections[22].collectionTitle.fr: "Le Vide"
- $.collections[22].collectionTitle.it: "Attack on Titan"
+ $.collections[22].collectionTitle.it: "Il Vuoto"
- $.collections[22].collectionTitle.ja: "進撃の巨人"
+ $.collections[22].collectionTitle.ja: "虚無"
- $.collections[22].collectionTitle.ko: "진격의 거인"
+ $.collections[22].collectionTitle.ko: "보이드"
- $.collections[22].collectionTitle.pl: "Attack on Titan"
+ $.collections[22].collectionTitle.pl: "Pustka"
- $.collections[22].collectionTitle["pt-BR"]: "Ataque dos Titãs"
+ $.collections[22].collectionTitle["pt-BR"]: "O Vácuo"
- $.collections[22].collectionTitle.ru: "Атака титанов"
+ $.collections[22].collectionTitle.ru: "Пустота"
- $.collections[22].collectionTitle.th: "ผ่าพิภพไททัน"
+ $.collections[22].collectionTitle.th: "ความว่างเปล่า"
- $.collections[22].collectionTitle.tr: "Attack on Titan"
+ $.collections[22].collectionTitle.tr: "Hiçlik"
- $.collections[22].collectionTitle["zh-Hans"]: "《进击的巨人》"
+ $.collections[22].collectionTitle["zh-Hans"]: "虚空"
- $.collections[22].collectionTitle["zh-Hant"]: "進擊的巨人"
+ $.collections[22].collectionTitle["zh-Hant"]: "虛空"
- $.collections[22].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Maple/T_UI_CollectionBanner_AttackOnTitan.T_UI_CollectionBanner_AttackOnTitan"
+ $.collections[22].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_Void_BC.T_UI_CollectionBanner_Void_BC"
- $.collections[22].inclusionVersion: "9.2.0"
+ $.collections[22].inclusionVersion: "7.7.0 PTB"
- $.collections[22].items[]: "AV_outfit_017"
- $.collections[22].items[]: "DF_outfit_020"
- $.collections[22].items[]: "GS_outfit_019"
- $.collections[22].items[]: "HK_outfit_016"
- $.collections[22].items[]: "JP_outfit_018"
- $.collections[22].items[]: "MT_outfit_019"
- $.collections[22].items[]: "S23_outfit_018"
- $.collections[22].items[]: "SwedenKiller_outfit_012"
- $.collections[22].items[]: "SwedenSurvivor_outfit_017"
- $.collections[22].items[]: "US_outfit_016"
+ $.collections[22].items[]: "DK_outfit_019"
+ $.collections[22].items[]: "GS_outfit_033"
+ $.collections[22].items[]: "HS_outfit_025"
+ $.collections[22].items[]: "MK_outfit_017"
+ $.collections[22].items[]: "S25_outfit_019"
+ $.collections[22].items[]: "S31_outfit_013"
+ $.collections[22].items[]: "US_outfit_025"
- $.collections[22].limitedAvailabilityStartDate: "2025-10-09T15:00:00Z"
+ $.collections[22].limitedAvailabilityStartDate: "2025-10-14T15:00:00Z"
- $.collections[22].sortOrder: "-170"
+ $.collections[22].sortOrder: "-173"
- $.collections[22].updatedDate: "2025-10-08T13:41:42.263Z"
+ $.collections[22].updatedDate: "2024-09-19T19:13:53Z"
+ $.collections[23].limitedAvailabilityEndDate: "2025-11-04T15:00:00Z"
+ $.collections[23].visibleAfterEndDate: false
- $.collections[23].collectionId: "VoidTouched"
+ $.collections[23].collectionId: "MidnightGrove"
- $.collections[23].collectionTitle.de: "Die Leere"
+ $.collections[23].collectionTitle.de: "Der Mitternachtshain"
- $.collections[23].collectionTitle.en: "The Void"
+ $.collections[23].collectionTitle.en: "The Midnight Grove"
- $.collections[23].collectionTitle.es: "El Vacío"
+ $.collections[23].collectionTitle.es: "Arboleda de medianoche"
- $.collections[23].collectionTitle["es-MX"]: "El Vacío"
+ $.collections[23].collectionTitle["es-MX"]: "El bosque nocturno"
- $.collections[23].collectionTitle.fr: "Le Vide"
+ $.collections[23].collectionTitle.fr: "Le Bosquet de minuit"
- $.collections[23].collectionTitle.it: "Il Vuoto"
+ $.collections[23].collectionTitle.it: "Bosco notturno"
- $.collections[23].collectionTitle.ja: "虚無"
+ $.collections[23].collectionTitle.ja: "真夜中の森"
- $.collections[23].collectionTitle.ko: "보이드"
+ $.collections[23].collectionTitle.ko: "자정의 숲"
- $.collections[23].collectionTitle.pl: "Pustka"
+ $.collections[23].collectionTitle.pl: "Północny gaj"
- $.collections[23].collectionTitle["pt-BR"]: "O Vácuo"
+ $.collections[23].collectionTitle["pt-BR"]: "O Bosque da Meia-Noite"
- $.collections[23].collectionTitle.ru: "Пустота"
+ $.collections[23].collectionTitle.ru: "Полуночная роща"
- $.collections[23].collectionTitle.th: "ความว่างเปล่า"
+ $.collections[23].collectionTitle.th: "สวนเที่ยงคืน"
- $.collections[23].collectionTitle.tr: "Hiçlik"
+ $.collections[23].collectionTitle.tr: "Gece Yarısı Korusu"
- $.collections[23].collectionTitle["zh-Hans"]: "虚空"
+ $.collections[23].collectionTitle["zh-Hans"]: "午夜林地"
- $.collections[23].collectionTitle["zh-Hant"]: "虛空"
+ $.collections[23].collectionTitle["zh-Hant"]: "午夜樹林"
- $.collections[23].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_Void_BC.T_UI_CollectionBanner_Void_BC"
+ $.collections[23].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MidnightGrove_BC.T_UI_CollectionBanner_MidnightGrove_BC"
- $.collections[23].inclusionVersion: "7.7.0 PTB"
+ $.collections[23].inclusionVersion: "8.3.0"
- $.collections[23].items[]: "DK_outfit_019"
- $.collections[23].items[]: "GS_outfit_033"
- $.collections[23].items[]: "HS_outfit_025"
- $.collections[23].items[]: "MK_outfit_017"
- $.collections[23].items[]: "S25_outfit_019"
- $.collections[23].items[]: "S31_outfit_013"
- $.collections[23].items[]: "US_outfit_025"
+ $.collections[23].items[]: "AV_outfit_010_01"
+ $.collections[23].items[]: "DF_outfit_005_01"
+ $.collections[23].items[]: "DO_outfit_013"
+ $.collections[23].items[]: "FM_outfit_01_06"
+ $.collections[23].items[]: "GK_outfit_02_04"
+ $.collections[23].items[]: "KS_outfit_008_01"
+ $.collections[23].items[]: "S28_outfit_007"
+ $.collections[23].items[]: "TR_outfit_01_04"
+ $.collections[23].items[]: "TW_outfit_007_01"
- $.collections[23].sortOrder: "-173"
+ $.collections[23].sortOrder: "-174"
- $.collections[23].updatedDate: "2024-09-19T19:13:53Z"
+ $.collections[23].updatedDate: "2024-09-19T16:10:17Z"
- $.collections[24].collectionId: "MidnightGrove"
+ $.collections[24].collectionId: "TricksAndTreats"
- $.collections[24].collectionTitle.de: "Der Mitternachtshain"
+ $.collections[24].collectionTitle.de: "Süßes und Saures"
- $.collections[24].collectionTitle.en: "The Midnight Grove"
+ $.collections[24].collectionTitle.en: "Tricks and Treats"
- $.collections[24].collectionTitle.es: "Arboleda de medianoche"
+ $.collections[24].collectionTitle.es: "Trucos y tratos"
- $.collections[24].collectionTitle["es-MX"]: "El bosque nocturno"
+ $.collections[24].collectionTitle["es-MX"]: "Dulces y travesuras"
- $.collections[24].collectionTitle.fr: "Le Bosquet de minuit"
+ $.collections[24].collectionTitle.fr: "Farces et friandises"
- $.collections[24].collectionTitle.it: "Bosco notturno"
+ $.collections[24].collectionTitle.it: "Dolcetti e scherzetti"
- $.collections[24].collectionTitle.ja: "真夜中の森"
+ $.collections[24].collectionTitle.ja: "トリックとトリート"
- $.collections[24].collectionTitle.ko: "자정의 숲"
… 5844 more change(s) — see the commit diff for everything
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.UdonCharm.title: "DLC_UdonCharm_SHORT_NAME"
+ $.dlcList.UdonCharm.title: "@#DLC_UdonCharm_SHORT_NAME"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[9].contentVersion: "47089302c3b0d6f4eba3d604000caf9d34bbf25a"
+ $.entries[9].contentVersion: "75859283a178ec1f1dd276d1d92b8f18a07f1071"
- $.entries[85].contentVersion: "b8621a14152d02d7b5ed6309183eca619b8e3011"
+ $.entries[85].contentVersion: "16bbf4e98cdc89df6c3d939f221467506aa63278"
- $.entries[87].contentVersion: "65cf8c39ebe92e679e5d23b24b9540f23a5bd971"
+ $.entries[87].contentVersion: "4d1c7fa0ac34de99103b50b7566e6d45e6739b7d"
- $.entries[180].contentVersion: "56fcce89ef3d1547b1e4accfc3214c8ca7414556"
+ $.entries[180].contentVersion: "420e33fa820dd54c142867c93e64d157e6b6154e"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Udon_W4].entries[0].weight: 14
+ $.featuredCard[id=Udon_W4].entries[0].weight: 15
- $.featuredCard[id=Udon_W4].entries[1].entryId: "Tome_8_Bundle"
+ $.featuredCard[id=Udon_W4].entries[1].entryId: "10.1.2_Autumn_Fashion"
- $.featuredCard[id=Udon_W4].entries[1].weight: 13
+ $.featuredCard[id=Udon_W4].entries[1].weight: 14
- $.featuredCard[id=Udon_W4].entries[2].entryId: "10.1.0_GameplayExpo"
+ $.featuredCard[id=Udon_W4].entries[2].entryId: "Tome_8_Bundle"
- $.featuredCard[id=Udon_W4].entries[2].type: "Collection"
+ $.featuredCard[id=Udon_W4].entries[2].type: "SpecialPack"
- $.featuredCard[id=Udon_W4].entries[2].weight: 12
+ $.featuredCard[id=Udon_W4].entries[2].weight: 13
- $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_Alien_Collection"
+ $.featuredCard[id=Udon_W4].entries[3].entryId: "10.1.0_GameplayExpo"
- $.featuredCard[id=Udon_W4].entries[3].weight: 11
+ $.featuredCard[id=Udon_W4].entries[3].weight: 12
- $.featuredCard[id=Udon_W4_1].entries[0].weight: 15
+ $.featuredCard[id=Udon_W4_1].entries[0].weight: 16
- $.featuredCard[id=Udon_W4_1].entries[1].entryId: "10.1.2_AutumnFashion"
+ $.featuredCard[id=Udon_W4_1].entries[1].entryId: "10.1.2_Autumn_Fashion"
- $.featuredCard[id=Udon_W4_1].entries[1].type: "Collection"
+ $.featuredCard[id=Udon_W4_1].entries[1].type: "SpecialPack"
- $.featuredCard[id=Udon_W4_1].entries[1].weight: 14
+ $.featuredCard[id=Udon_W4_1].entries[1].weight: 15
- $.featuredCard[id=Udon_W4_1].entries[2].entryId: "10.1.0_GameplayExpo"
+ $.featuredCard[id=Udon_W4_1].entries[2].entryId: "10.1.2_AutumnFashion"
- $.featuredCard[id=Udon_W4_1].entries[2].weight: 12
+ $.featuredCard[id=Udon_W4_1].entries[2].weight: 14
- $.featuredCard[id=Udon_W4_1].entries[3].entryId: "10.1.0_Alien_Collection"
+ $.featuredCard[id=Udon_W4_1].entries[3].entryId: "10.1.0_GameplayExpo"
- $.featuredCard[id=Udon_W4_1].entries[3].weight: 11
+ $.featuredCard[id=Udon_W4_1].entries[3].weight: 12
```

