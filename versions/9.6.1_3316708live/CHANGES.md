# live · 9.6.1_3316708live

| | |
|---|---|
| Build date | 2026-05-04 15:06 UTC |
| CDN version | `9.6.1_3316708live-1777907193` |
| Key | `9.6.1_live` |
| Compared with | [9.6.1_3307649live](../9.6.1_3307649live/CHANGES.md) (2026-05-01 21:00 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 203 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=Chrysalis_collection_item]
+ $[id=From_The_Rift_Bundle_260505]
+ $[id=Recurring_Charm_Bundle_260505]
+ $[id=Recurring_Dev_Bundle_260505]
- $[id=DF_Head036].metaData.releaseDate: "2025-05-06T15:00:00"
+ $[id=DF_Head036].metaData.releaseDate: "2026-05-05T15:00:00"
- $[id=DF_Head036].metaData.releaseDateInMs: 1746543600000
+ $[id=DF_Head036].metaData.releaseDateInMs: 1777993200000
- $[id=DF_Head036].purchasable: false
+ $[id=DF_Head036].purchasable: true
+ $[id=Chrysalis_Ramen_collection_item].collectionItemIds[]: "DF_Head036"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[4].limitedAvailabilityStartDate: "2025-05-27T15:00:00Z"
+ $.collections[4].visibleBeforeStartDate: false
- $.collections[4].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_Chrysalis_1.T_UI_SpecialPack_Chrysalis_1"
+ $.collections[4].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_CatsAndDogs.T_UI_SpecialPack_CatsAndDogs"
- $.collections[4].collectionId: "Chrysalis"
+ $.collections[4].collectionId: "Cats&Dogs"
- $.collections[4].collectionTitle.de: "Kokonsammlung"
+ $.collections[4].collectionTitle.de: "Katzen und Hunde "
- $.collections[4].collectionTitle.en: "Chrysalis Collection"
+ $.collections[4].collectionTitle.en: "Cats & Dogs "
- $.collections[4].collectionTitle.es: "Colección de Crisálida"
+ $.collections[4].collectionTitle.es: "Como perros y gatos "
- $.collections[4].collectionTitle["es-MX"]: "Colección Crisálida"
+ $.collections[4].collectionTitle["es-MX"]: "Gatos y perros "
- $.collections[4].collectionTitle.fr: "Collection Chrysalide"
+ $.collections[4].collectionTitle.fr: "Chiens et chats"
- $.collections[4].collectionTitle.it: "Collezione Crisalide"
+ $.collections[4].collectionTitle.it: "Cani e gatti "
- $.collections[4].collectionTitle.ja: "蛹コレクション"
+ $.collections[4].collectionTitle.ja: "犬と猫 "
- $.collections[4].collectionTitle.ko: "번데기 컬렉션"
+ $.collections[4].collectionTitle.ko: "개와 고양이"
- $.collections[4].collectionTitle.pl: "Kolekcja „Poczwarka”"
+ $.collections[4].collectionTitle.pl: "Psy i koty "
- $.collections[4].collectionTitle["pt-BR"]: "Coleção Crisálida"
+ $.collections[4].collectionTitle["pt-BR"]: "Cães e Gatos "
- $.collections[4].collectionTitle.ru: "Коллекция «Кокон»"
+ $.collections[4].collectionTitle.ru: "Кошки и собаки "
- $.collections[4].collectionTitle.th: "ชุดสะสมดักแด้"
+ $.collections[4].collectionTitle.th: "แมวกับหมา "
- $.collections[4].collectionTitle.tr: "Koza Koleksiyonu"
+ $.collections[4].collectionTitle.tr: "Kediler ve Köpekler "
- $.collections[4].collectionTitle["zh-Hans"]: "茧蛹收藏"
+ $.collections[4].collectionTitle["zh-Hans"]: "猫猫&狗狗"
- $.collections[4].collectionTitle["zh-Hant"]: "繭蛹收藏"
+ $.collections[4].collectionTitle["zh-Hant"]: "貓與狗 "
- $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_Chrysalis_2.T_UI_CollectionBanner_Chrysalis_2"
+ $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_CatsAndDogs_2.T_UI_CollectionBanner_CatsAndDogs_2"
- $.collections[4].inclusionVersion: "7.7.0"
+ $.collections[4].inclusionVersion: "7.7.0 PTB"
- $.collections[4].items[]: "DO_outfit_014"
- $.collections[4].items[]: "GS_Head030"
- $.collections[4].items[]: "K20_outfit_009"
- $.collections[4].items[]: "K30_outfit_013"
- $.collections[4].items[]: "K33_outfit_011"
- $.collections[4].items[]: "KS_outfit_015"
- $.collections[4].items[]: "NK_outfit_021"
- $.collections[4].items[]: "S35_outfit_021"
- $.collections[4].items[]: "S36_outfit_023"
- $.collections[4].items[]: "S41_outfit_008"
- $.collections[4].items[]: "SwedenKiller_outfit_022"
- $.collections[4].items[]: "UK_outfit_010"
+ $.collections[4].items[]: "AV_Torso023"
+ $.collections[4].items[]: "CM_outfit_019"
+ $.collections[4].items[]: "DF_Torso017"
+ $.collections[4].items[]: "GS_Torso025"
+ $.collections[4].items[]: "JP_Torso020"
+ $.collections[4].items[]: "K35_outfit_007"
+ $.collections[4].items[]: "KK_Body021"
+ $.collections[4].items[]: "KS_Torso013"
+ $.collections[4].items[]: "MT_outfit_016"
+ $.collections[4].items[]: "NK_Torso019"
+ $.collections[4].items[]: "OK_Mask015"
+ $.collections[4].items[]: "S23_Torso020"
+ $.collections[4].items[]: "S25_Torso018"
+ $.collections[4].items[]: "S29_Torso014"
+ $.collections[4].items[]: "S31_Torso012"
+ $.collections[4].items[]: "S34_Torso013"
+ $.collections[4].items[]: "S35_Torso015"
+ $.collections[4].items[]: "S36_Torso016"
+ $.collections[4].items[]: "S37_Torso015"
+ $.collections[4].items[]: "S39_outfit_011"
- $.collections[4].sortOrder: "-112"
+ $.collections[4].sortOrder: "-113"
- $.collections[4].updatedDate: "2025-05-16T13:09:22.94Z"
+ $.collections[4].updatedDate: "2025-05-22T12:45:53.83Z"
- $.collections[5].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_CatsAndDogs.T_UI_SpecialPack_CatsAndDogs"
+ $.collections[5].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_TheWitcher.T_UI_SpecialPack_TheWitcher"
- $.collections[5].collectionId: "Cats&Dogs"
+ $.collections[5].collectionId: "TheWitcher"
- $.collections[5].collectionTitle.de: "Katzen und Hunde "
+ $.collections[5].collectionTitle.de: "The Witcher"
- $.collections[5].collectionTitle.en: "Cats & Dogs "
+ $.collections[5].collectionTitle.en: "The Witcher"
- $.collections[5].collectionTitle.es: "Como perros y gatos "
+ $.collections[5].collectionTitle.es: "The Witcher"
- $.collections[5].collectionTitle["es-MX"]: "Gatos y perros "
+ $.collections[5].collectionTitle["es-MX"]: "The Witcher"
- $.collections[5].collectionTitle.fr: "Chiens et chats"
+ $.collections[5].collectionTitle.fr: "The Witcher"
- $.collections[5].collectionTitle.it: "Cani e gatti "
+ $.collections[5].collectionTitle.it: "The Witcher"
- $.collections[5].collectionTitle.ja: "犬と猫 "
+ $.collections[5].collectionTitle.ja: "ウィッチャー"
- $.collections[5].collectionTitle.ko: "개와 고양이"
+ $.collections[5].collectionTitle.ko: "위쳐"
- $.collections[5].collectionTitle.pl: "Psy i koty "
+ $.collections[5].collectionTitle.pl: "Wiedźmin"
- $.collections[5].collectionTitle["pt-BR"]: "Cães e Gatos "
+ $.collections[5].collectionTitle["pt-BR"]: "The Witcher"
- $.collections[5].collectionTitle.ru: "Кошки и собаки "
+ $.collections[5].collectionTitle.ru: "Ведьмак"
- $.collections[5].collectionTitle.th: "แมวกับหมา "
+ $.collections[5].collectionTitle.th: "เดอะวิทเชอร์"
- $.collections[5].collectionTitle.tr: "Kediler ve Köpekler "
+ $.collections[5].collectionTitle.tr: "The Witcher"
- $.collections[5].collectionTitle["zh-Hans"]: "猫猫&狗狗"
+ $.collections[5].collectionTitle["zh-Hans"]: "《The Witcher》"
- $.collections[5].collectionTitle["zh-Hant"]: "貓與狗 "
+ $.collections[5].collectionTitle["zh-Hant"]: "《獵魔士》"
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_CatsAndDogs_2.T_UI_CollectionBanner_CatsAndDogs_2"
+ $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_TheWitcher.T_UI_CollectionBanner_TheWitcher"
- $.collections[5].inclusionVersion: "7.7.0 PTB"
+ $.collections[5].inclusionVersion: "8.7.2"
- $.collections[5].items[]: "AV_Torso023"
- $.collections[5].items[]: "CM_outfit_019"
- $.collections[5].items[]: "DF_Torso017"
- $.collections[5].items[]: "GS_Torso025"
- $.collections[5].items[]: "JP_Torso020"
- $.collections[5].items[]: "K35_outfit_007"
- $.collections[5].items[]: "KK_Body021"
- $.collections[5].items[]: "KS_Torso013"
- $.collections[5].items[]: "MT_outfit_016"
- $.collections[5].items[]: "NK_Torso019"
- $.collections[5].items[]: "OK_Mask015"
- $.collections[5].items[]: "S23_Torso020"
- $.collections[5].items[]: "S25_Torso018"
- $.collections[5].items[]: "S29_Torso014"
- $.collections[5].items[]: "S31_Torso012"
- $.collections[5].items[]: "S34_Torso013"
- $.collections[5].items[]: "S35_Torso015"
- $.collections[5].items[]: "S36_Torso016"
- $.collections[5].items[]: "S37_Torso015"
- $.collections[5].items[]: "S39_outfit_011"
+ $.collections[5].items[]: "GS_outfit_037"
+ $.collections[5].items[]: "K26_outfit_020"
+ $.collections[5].items[]: "K30_outfit_018"
+ $.collections[5].items[]: "S28_outfit_030"
+ $.collections[5].items[]: "S34_outfit_023"
+ $.collections[5].items[]: "S41_outfit_017"
- $.collections[5].limitedAvailabilityStartDate: "2025-05-27T15:00:00Z"
+ $.collections[5].limitedAvailabilityStartDate: "2025-06-03T15:00:00Z"
- $.collections[5].sortOrder: "-113"
+ $.collections[5].sortOrder: "-114"
- $.collections[5].updatedDate: "2025-05-22T12:45:53.83Z"
+ $.collections[5].updatedDate: "2025-02-28T13:44:00.782Z"
- $.collections[6].limitedAvailabilityStartDate: "2025-06-03T15:00:00Z"
- $.collections[6].visibleBeforeStartDate: false
- $.collections[6].additionalImages[0]
- $.collections[6].collectionId: "TheWitcher"
+ $.collections[6].collectionId: "Hanami"
- $.collections[6].collectionTitle.de: "The Witcher"
+ $.collections[6].collectionTitle.de: "Hanami "
- $.collections[6].collectionTitle.en: "The Witcher"
+ $.collections[6].collectionTitle.en: "Hanami "
- $.collections[6].collectionTitle.es: "The Witcher"
+ $.collections[6].collectionTitle.es: "Hanami "
- $.collections[6].collectionTitle["es-MX"]: "The Witcher"
+ $.collections[6].collectionTitle["es-MX"]: "Hanami "
- $.collections[6].collectionTitle.fr: "The Witcher"
+ $.collections[6].collectionTitle.fr: "Hanami "
- $.collections[6].collectionTitle.it: "The Witcher"
+ $.collections[6].collectionTitle.it: "Hanami "
- $.collections[6].collectionTitle.ja: "ウィッチャー"
+ $.collections[6].collectionTitle.ja: "花見 "
- $.collections[6].collectionTitle.ko: "위쳐"
+ $.collections[6].collectionTitle.ko: "벚꽃 축제 "
- $.collections[6].collectionTitle.pl: "Wiedźmin"
+ $.collections[6].collectionTitle.pl: "Hanami "
- $.collections[6].collectionTitle["pt-BR"]: "The Witcher"
+ $.collections[6].collectionTitle["pt-BR"]: "Hanami "
- $.collections[6].collectionTitle.ru: "Ведьмак"
+ $.collections[6].collectionTitle.ru: "Ханами "
- $.collections[6].collectionTitle.th: "เดอะวิทเชอร์"
+ $.collections[6].collectionTitle.th: "ฮานามิ "
- $.collections[6].collectionTitle.tr: "The Witcher"
+ $.collections[6].collectionTitle.tr: "Hanami "
- $.collections[6].collectionTitle["zh-Hans"]: "《The Witcher》"
+ $.collections[6].collectionTitle["zh-Hans"]: "花见 "
- $.collections[6].collectionTitle["zh-Hant"]: "《獵魔士》"
+ $.collections[6].collectionTitle["zh-Hant"]: "賞花 "
- $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_TheWitcher.T_UI_CollectionBanner_TheWitcher"
+ $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
- $.collections[6].inclusionVersion: "8.7.2"
+ $.collections[6].inclusionVersion: "7.7.0 PTB"
- $.collections[6].items[]: "GS_outfit_037"
- $.collections[6].items[]: "K26_outfit_020"
- $.collections[6].items[]: "K30_outfit_018"
- $.collections[6].items[]: "S28_outfit_030"
- $.collections[6].items[]: "S34_outfit_023"
- $.collections[6].items[]: "S41_outfit_017"
+ $.collections[6].items[]: "HK_outfit_014"
+ $.collections[6].items[]: "MS_outfit_016"
+ $.collections[6].items[]: "SwedenSurvivor_outfit_015"
- $.collections[6].sortOrder: "-114"
+ $.collections[6].sortOrder: "-13"
- $.collections[6].updatedDate: "2025-02-28T13:44:00.782Z"
+ $.collections[6].updatedDate: "2024-02-01T17:19:10Z"
+ $.collections[7].limitedAvailabilityEndDate: "2025-07-17T15:00:00Z"
+ $.collections[7].limitedAvailabilityStartDate: "2025-06-26T15:00:00Z"
… 5982 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[1].MapsWeight.Apl_Square_Calamari: "500"
+ $.schedule[1].MapsWeight.Apl_Square_Calamari: "200"
- $.schedule[1].MapsWeight.Asy_Asylum_Calamari: "300"
+ $.schedule[1].MapsWeight.Asy_Asylum_Calamari: "200"
- $.schedule[1].MapsWeight.Asy_Chapel_Calamari: "500"
+ $.schedule[1].MapsWeight.Asy_Chapel_Calamari: "200"
- $.schedule[1].MapsWeight.Brl_MaHouse_Calamari: "500"
+ $.schedule[1].MapsWeight.Brl_MaHouse_Calamari: "200"
- $.schedule[1].MapsWeight.Brl_Temple_Calamari: "500"
+ $.schedule[1].MapsWeight.Brl_Temple_Calamari: "200"
- $.schedule[1].MapsWeight.Ecl_Level03_Calamari: "500"
+ $.schedule[1].MapsWeight.Ecl_Level03_Calamari: "200"
- $.schedule[1].MapsWeight.Frm_Cornfield_Calamari: "500"
+ $.schedule[1].MapsWeight.Frm_Cornfield_Calamari: "200"
- $.schedule[1].MapsWeight.Frm_Farmhouse_Calamari: "100"
+ $.schedule[1].MapsWeight.Frm_Farmhouse_Calamari: "200"
- $.schedule[1].MapsWeight.Frm_Silo_Calamari: "500"
+ $.schedule[1].MapsWeight.Frm_Silo_Calamari: "200"
- $.schedule[1].MapsWeight.Frm_Slaughterhouse_Calamari: "300"
+ $.schedule[1].MapsWeight.Frm_Slaughterhouse_Calamari: "200"
- $.schedule[1].MapsWeight.Hos_Hospital_Calamari: "500"
+ $.schedule[1].MapsWeight.Hos_Hospital_Calamari: "200"
- $.schedule[1].MapsWeight.Hti_Manor_Calamari: "500"
+ $.schedule[1].MapsWeight.Hti_Manor_Calamari: "200"
- $.schedule[1].MapsWeight.Hti_Temple_Calamari: "300"
+ $.schedule[1].MapsWeight.Hti_Temple_Calamari: "200"
- $.schedule[1].MapsWeight.Ind_CoalTower_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_CoalTower_Calamari: "200"
- $.schedule[1].MapsWeight.Ind_Forest_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_Forest_Calamari: "200"
- $.schedule[1].MapsWeight.Ind_Foundry_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_Foundry_Calamari: "200"
- $.schedule[1].MapsWeight.Ind_Mine_Calamari: "300"
+ $.schedule[1].MapsWeight.Ind_Mine_Calamari: "200"
- $.schedule[1].MapsWeight.Ind_Storehouse_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_Storehouse_Calamari: "200"
- $.schedule[1].MapsWeight.Jnk_Garage_Calamari: "500"
+ $.schedule[1].MapsWeight.Jnk_Garage_Calamari: "200"
- $.schedule[1].MapsWeight.Jnk_GasStation_Calamari: "300"
+ $.schedule[1].MapsWeight.Jnk_GasStation_Calamari: "200"
- $.schedule[1].MapsWeight.Jnk_Office_Calamari: "300"
+ $.schedule[1].MapsWeight.Jnk_Office_Calamari: "200"
- $.schedule[1].MapsWeight.Jnk_Scrapyard_Calamari: "100"
+ $.schedule[1].MapsWeight.Jnk_Scrapyard_Calamari: "200"
- $.schedule[1].MapsWeight.Kny_Chalet_Calamari: "500"
+ $.schedule[1].MapsWeight.Kny_Chalet_Calamari: "200"
- $.schedule[1].MapsWeight.Qtm_ShatteredSqr_Calamari: "500"
+ $.schedule[1].MapsWeight.Qtm_ShatteredSqr_Calamari: "200"
- $.schedule[1].MapsWeight.Ukr_Saloon_Calamari: "500"
+ $.schedule[1].MapsWeight.Ukr_Saloon_Calamari: "200"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[3].contentVersion: "e641dba5acadb429ed92928c786754dd1daf3ceb"
+ $.entries[3].contentVersion: "a8a67547f41057e42364f2e254b78c22fe277bbf"
- $.entries[79].contentVersion: "f674fd5ca430dc1af592181a92518695f7c21de9"
+ $.entries[79].contentVersion: "a049989e8b854c831303acdb7dc428fe1307b18a"
- $.entries[171].contentVersion: "8ec2ce5a376727a115397d361a1dbf591da3eda4"
+ $.entries[171].contentVersion: "ecc08981444329bffab6cf22b57104fcf6d530c7"
- $.entries[174].contentVersion: "9c9ce9394b117e89b40fe8f2a69a04154a47af3e"
+ $.entries[174].contentVersion: "1d5d9d41608eabe394570ff5e4c55491efb7d01f"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=RamenW2].recommendations[id=DF_Head036]
- $.featuredCustomizationRecommendations[id=RamenW2].recommendations[id=S25_outfit_033].weight: 22
+ $.featuredCustomizationRecommendations[id=RamenW2].recommendations[id=S25_outfit_033].weight: 23
- $.featuredCustomizationRecommendations[id=RamenW2].recommendations[id=BE_outfit_030].weight: 21
+ $.featuredCustomizationRecommendations[id=RamenW2].recommendations[id=BE_outfit_030].weight: 22
+ $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=DF_Head036]
- $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=S52_outfit_007].weight: 24
+ $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=S52_outfit_007].weight: 25
- $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=K31_outfit_019].weight: 23
+ $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=K31_outfit_019].weight: 24
- $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=S25_outfit_033].weight: 22
+ $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=S25_outfit_033].weight: 23
- $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=BE_outfit_030].weight: 21
+ $.featuredCustomizationRecommendations[id=RamenW3].recommendations[id=BE_outfit_030].weight: 22
```

