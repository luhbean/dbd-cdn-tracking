# live · 8.7.2_2498539live

| | |
|---|---|
| Build date | 2025-06-10 14:52 UTC |
| CDN version | `8.7.2_2498539live-1749567129` |
| Key | `8.7.2_live` |
| Compared with | [8.7.2_2495438live](../8.7.2_2495438live/CHANGES.md) (2025-06-06 20:23 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 199 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=FM_Head024].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Head024].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=FM_Head024].purchasable: false
+ $[id=FM_Head024].purchasable: true
- $[id=FM_Legs024].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Legs024].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=FM_Legs024].purchasable: false
+ $[id=FM_Legs024].purchasable: true
- $[id=FM_Torso024].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Torso024].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=FM_Torso024].purchasable: false
+ $[id=FM_Torso024].purchasable: true
- $[id=K31_Body013].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K31_Body013].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=K31_Body013].purchasable: false
+ $[id=K31_Body013].purchasable: true
- $[id=K31_Head013].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K31_Head013].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=K31_Head013].purchasable: false
+ $[id=K31_Head013].purchasable: true
- $[id=K31_W013].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K31_W013].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=K31_W013].purchasable: false
+ $[id=K31_W013].purchasable: true
- $[id=FM_outfit_024].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_outfit_024].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=FM_outfit_024].purchasable: false
+ $[id=FM_outfit_024].purchasable: true
- $[id=K31_outfit_013].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K31_outfit_013].metaData.releaseDate: "2025-06-10T15:00:00"
- $[id=K31_outfit_013].purchasable: false
+ $[id=K31_outfit_013].purchasable: true
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[1].additionalImages[0]
- $.collections[1].collectionId: "Gold&Silk"
+ $.collections[1].collectionId: "TokyoGhoul"
- $.collections[1].collectionTitle.de: "Gold und Seide"
+ $.collections[1].collectionTitle.de: "Tokyo Ghoul"
- $.collections[1].collectionTitle.en: "Gold & Silk"
+ $.collections[1].collectionTitle.en: "Tokyo Ghoul"
- $.collections[1].collectionTitle.es: "Oro y seda"
+ $.collections[1].collectionTitle.es: "Tokyo Ghoul"
- $.collections[1].collectionTitle["es-MX"]: "Oro y seda"
+ $.collections[1].collectionTitle["es-MX"]: "Tokyo Ghoul"
- $.collections[1].collectionTitle.fr: "Or et soie"
+ $.collections[1].collectionTitle.fr: "Tokyo Ghoul"
- $.collections[1].collectionTitle.it: "Oro e seta"
+ $.collections[1].collectionTitle.it: "Tokyo Ghoul"
- $.collections[1].collectionTitle.ja: "黄金と絹"
+ $.collections[1].collectionTitle.ja: "東京喰種"
- $.collections[1].collectionTitle.ko: "황금 & 실크"
+ $.collections[1].collectionTitle.ko: "도쿄 구울"
- $.collections[1].collectionTitle.pl: "Wieczorna elegancja"
+ $.collections[1].collectionTitle.pl: "Tokyo Ghoul"
- $.collections[1].collectionTitle["pt-BR"]: "Ouro e Seda"
+ $.collections[1].collectionTitle["pt-BR"]: "Tokyo Ghoul"
- $.collections[1].collectionTitle.ru: "Золото и шелк"
+ $.collections[1].collectionTitle.ru: "Токийский гуль"
- $.collections[1].collectionTitle.th: "ทองกับผ้าไหม"
+ $.collections[1].collectionTitle.th: "Tokyo Ghoul"
- $.collections[1].collectionTitle.tr: "Altın ve İpek"
+ $.collections[1].collectionTitle.tr: "Tokyo Gûl"
- $.collections[1].collectionTitle["zh-Hans"]: "金丝华服"
+ $.collections[1].collectionTitle["zh-Hans"]: "《Tokyo Ghoul》"
- $.collections[1].collectionTitle["zh-Hant"]: "黃金&絲綢"
+ $.collections[1].collectionTitle["zh-Hant"]: "《東京喰種》"
- $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GoldAndSilk.T_UI_CollectionBanner_GoldAndSilk"
+ $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
- $.collections[1].inclusionVersion: "8.5.0"
+ $.collections[1].inclusionVersion: "8.6.0"
- $.collections[1].items[]: "Claudette_outfit_010_01"
- $.collections[1].items[]: "CM_outfit_010_01"
- $.collections[1].items[]: "Kate_outfit_009_01"
- $.collections[1].items[]: "Jeff_outfit_008"
- $.collections[1].items[]: "S23_outfit_012"
- $.collections[1].items[]: "S24_outfit_011"
- $.collections[1].items[]: "Killer07_outfit_008_01"
- $.collections[1].items[]: "Witch_outfit_006_01"
- $.collections[1].items[]: "MT_outfit_013"
- $.collections[1].items[]: "JP_outfit_024"
- $.collections[1].items[]: "TR_outfit_023"
- $.collections[1].items[]: "K23_outfit_022"
- $.collections[1].items[]: "US_Outfit_024"
+ $.collections[1].items[]: "K39_outfit_02"
+ $.collections[1].items[]: "K39_outfit_008"
+ $.collections[1].items[]: "SS_outfit_029"
+ $.collections[1].items[]: "NK_outfit_035"
+ $.collections[1].items[]: "S36_outfit_021"
+ $.collections[1].items[]: "K35_Head013"
+ $.collections[1].items[]: "S29_Head023"
+ $.collections[1].items[]: "JP_Head028"
+ $.collections[1].items[]: "DK_Head028"
- $.collections[1].sortOrder: "-101"
+ $.collections[1].sortOrder: "-103"
- $.collections[1].updatedDate: "2025-03-11T13:55:53.737Z"
+ $.collections[1].updatedDate: "2025-01-13T17:01:53.962Z"
+ $.collections[2].limitedAvailabilityEndDate: "2025-04-10T15:00:00Z"
+ $.collections[2].limitedAvailabilityStartDate: "2025-04-07T15:00:00Z"
+ $.collections[2].visibleAfterEndDate: false
+ $.collections[2].visibleBeforeStartDate: false
- $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TokyoGhoul.T_UI_SpecialPack_TokyoGhoul"
+ $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
- $.collections[2].collectionId: "TokyoGhoul"
+ $.collections[2].collectionId: "Bloodmoon"
- $.collections[2].collectionTitle.de: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.de: "Blutmond"
- $.collections[2].collectionTitle.en: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.en: "Blood Moon"
- $.collections[2].collectionTitle.es: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.es: "Luna de sangre"
- $.collections[2].collectionTitle["es-MX"]: "Tokyo Ghoul"
+ $.collections[2].collectionTitle["es-MX"]: "Luna de sangre"
- $.collections[2].collectionTitle.fr: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.fr: "Lune de sang"
- $.collections[2].collectionTitle.it: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.it: "Luna sanguinosa"
- $.collections[2].collectionTitle.ja: "東京喰種"
+ $.collections[2].collectionTitle.ja: "ブラッドムーン"
- $.collections[2].collectionTitle.ko: "도쿄 구울"
+ $.collections[2].collectionTitle.ko: "핏빛 달"
- $.collections[2].collectionTitle.pl: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.pl: "Krwawy księżyc"
- $.collections[2].collectionTitle["pt-BR"]: "Tokyo Ghoul"
+ $.collections[2].collectionTitle["pt-BR"]: "Lua de Sangue"
- $.collections[2].collectionTitle.ru: "Токийский гуль"
+ $.collections[2].collectionTitle.ru: "Кровавая луна"
- $.collections[2].collectionTitle.th: "Tokyo Ghoul"
+ $.collections[2].collectionTitle.th: "จันทราโลหิต"
- $.collections[2].collectionTitle.tr: "Tokyo Gûl"
+ $.collections[2].collectionTitle.tr: "Kanlı Ay"
- $.collections[2].collectionTitle["zh-Hans"]: "《Tokyo Ghoul》"
+ $.collections[2].collectionTitle["zh-Hans"]: "血月"
- $.collections[2].collectionTitle["zh-Hant"]: "《東京喰種》"
+ $.collections[2].collectionTitle["zh-Hant"]: "血月"
- $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
+ $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
- $.collections[2].items[]: "K39_outfit_02"
- $.collections[2].items[]: "K39_outfit_008"
- $.collections[2].items[]: "SS_outfit_029"
- $.collections[2].items[]: "NK_outfit_035"
- $.collections[2].items[]: "S36_outfit_021"
- $.collections[2].items[]: "K35_Head013"
- $.collections[2].items[]: "S29_Head023"
- $.collections[2].items[]: "JP_Head028"
- $.collections[2].items[]: "DK_Head028"
+ $.collections[2].items[]: "AV_outfit_022"
+ $.collections[2].items[]: "DO_outfit_020"
+ $.collections[2].items[]: "K31_outfit_012"
+ $.collections[2].items[]: "S24_outfit_021"
+ $.collections[2].items[]: "S28_outfit_023"
+ $.collections[2].items[]: "SwedenKiller_outfit_021"
+ $.collections[2].items[]: "K26_outfit_019"
+ $.collections[2].items[]: "K30_outfit_012"
+ $.collections[2].items[]: "K38_outfit_007"
+ $.collections[2].items[]: "CM_outfit_030"
+ $.collections[2].items[]: "S45_outfit_011"
- $.collections[2].sortOrder: "-103"
+ $.collections[2].sortOrder: "-104"
- $.collections[2].updatedDate: "2025-01-13T17:01:53.962Z"
+ $.collections[2].updatedDate: "2025-01-08T21:01:45.055Z"
- $.collections[3].limitedAvailabilityEndDate: "2025-04-10T15:00:00Z"
- $.collections[3].limitedAvailabilityStartDate: "2025-04-07T15:00:00Z"
- $.collections[3].visibleAfterEndDate: false
- $.collections[3].visibleBeforeStartDate: false
- $.collections[3].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
+ $.collections[3].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
- $.collections[3].collectionId: "Bloodmoon"
+ $.collections[3].collectionId: "Techwear"
- $.collections[3].collectionTitle.de: "Blutmond"
+ $.collections[3].collectionTitle.de: "Techbekleidung"
- $.collections[3].collectionTitle.en: "Blood Moon"
+ $.collections[3].collectionTitle.en: "Techwear"
- $.collections[3].collectionTitle.es: "Luna de sangre"
+ $.collections[3].collectionTitle.es: "Colección de Equipo técnico"
- $.collections[3].collectionTitle["es-MX"]: "Luna de sangre"
+ $.collections[3].collectionTitle["es-MX"]: "Colección Indumentaria tecnológica"
- $.collections[3].collectionTitle.fr: "Lune de sang"
+ $.collections[3].collectionTitle.fr: "Technovêtements"
- $.collections[3].collectionTitle.it: "Luna sanguinosa"
+ $.collections[3].collectionTitle.it: "Collezione Techwear"
- $.collections[3].collectionTitle.ja: "ブラッドムーン"
+ $.collections[3].collectionTitle.ja: "テックウェア"
- $.collections[3].collectionTitle.ko: "핏빛 달"
+ $.collections[3].collectionTitle.ko: "테크웨어 컬렉션"
- $.collections[3].collectionTitle.pl: "Krwawy księżyc"
+ $.collections[3].collectionTitle.pl: "Kolekcja odzieży technicznej"
- $.collections[3].collectionTitle["pt-BR"]: "Lua de Sangue"
+ $.collections[3].collectionTitle["pt-BR"]: "Coleção da Roupa Tecnológica"
- $.collections[3].collectionTitle.ru: "Кровавая луна"
+ $.collections[3].collectionTitle.ru: "Коллекция «Техно»"
- $.collections[3].collectionTitle.th: "จันทราโลหิต"
+ $.collections[3].collectionTitle.th: "อุปกรณ์เทคโนโลยี"
- $.collections[3].collectionTitle.tr: "Kanlı Ay"
+ $.collections[3].collectionTitle.tr: "Teknolojik Kıyafet Koleksiyonu"
- $.collections[3].collectionTitle["zh-Hans"]: "血月"
+ $.collections[3].collectionTitle["zh-Hans"]: "机能服装系列"
- $.collections[3].collectionTitle["zh-Hant"]: "血月"
+ $.collections[3].collectionTitle["zh-Hant"]: "機能服飾收藏"
- $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
+ $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
- $.collections[3].inclusionVersion: "8.6.0"
+ $.collections[3].inclusionVersion: "7.7.0"
- $.collections[3].items[]: "AV_outfit_022"
- $.collections[3].items[]: "DO_outfit_020"
- $.collections[3].items[]: "K31_outfit_012"
- $.collections[3].items[]: "S24_outfit_021"
- $.collections[3].items[]: "S28_outfit_023"
- $.collections[3].items[]: "SwedenKiller_outfit_021"
- $.collections[3].items[]: "K26_outfit_019"
- $.collections[3].items[]: "K30_outfit_012"
- $.collections[3].items[]: "K38_outfit_007"
- $.collections[3].items[]: "CM_outfit_030"
- $.collections[3].items[]: "S45_outfit_011"
+ $.collections[3].items[]: "MT_outfit_023"
+ $.collections[3].items[]: "S25_outfit_015"
+ $.collections[3].items[]: "S28_outfit_018"
+ $.collections[3].items[]: "S34_outfit_011"
+ $.collections[3].items[]: "KK_outfit_025"
+ $.collections[3].items[]: "K23_outfit_021"
+ $.collections[3].items[]: "US_Outfit_023"
+ $.collections[3].items[]: "DK_outfit_022"
+ $.collections[3].items[]: "GS_outfit_029"
+ $.collections[3].items[]: "NK_outfit_029"
+ $.collections[3].items[]: "S29_outfit_017"
+ $.collections[3].items[]: "FM_outfit_038"
+ $.collections[3].items[]: "S23_outfit_031"
+ $.collections[3].items[]: "AV_outfit_026"
+ $.collections[3].items[]: "K31_outfit_017"
+ $.collections[3].items[]: "DO_outfit_026"
- $.collections[3].sortOrder: "-104"
+ $.collections[3].sortOrder: "-105"
- $.collections[3].updatedDate: "2025-01-08T21:01:45.055Z"
+ $.collections[3].updatedDate: "2025-04-21T13:25:07.469Z"
… 547 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[7].contentVersion: "e35f42d03543d5f0d1852576502a9886619143e6"
+ $.entries[7].contentVersion: "e376296307df3527601d63b947c7977048a60dfe"
- $.entries[175].contentVersion: "d725a5b5a91592249e694b96470d19e90ff9bf9b"
+ $.entries[175].contentVersion: "b29f81bda9c4d2bc2b02f936ae66552fd5ba2c1e"
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

