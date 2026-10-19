# live · 9.0.0_2520745live

| | |
|---|---|
| Build date | 2025-06-26 15:51 UTC |
| CDN version | `9.0.0_2520745live-1750953104` |
| Key | `9.0.0_live` |
| Compared with | [9.0.1_2520490live](../9.0.1_2520490live/CHANGES.md) (2025-06-26 14:16 UTC) |

## Summary

**0** added · **6** modified · **0** removed · 196 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S31_Head023]
- $[id=S31_Legs023]
- $[id=S31_Torso023]
- $[id=S35_Head022]
- $[id=S35_Legs022]
- $[id=S35_Torso022]
- $[id=S37_Head022]
- $[id=S37_Legs022]
- $[id=S37_Torso022]
- $[id=S45_Head012]
- $[id=S45_Legs012]
- $[id=S45_Torso012]
- $[id=S31_outfit_023]
- $[id=S35_outfit_022]
- $[id=S37_outfit_022]
- $[id=S45_outfit_012]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[16].text: "Tuez {0} survivant(s)"
+ $.locText[16].text: "Sacrifiez ou tuez {0} survivant(s)"
- $.locText[120].text: "Tuez {0} survivant(s) de vos mains"
+ $.locText[120].text: "Tuez {0} survivant(s)"
- $.locText[150].text: "Une fois que le dernier survivant est à terre, vous pouvez le tuer dans une épreuve sans l'accrocher."
+ $.locText[150].text: "Plus vous sacrifiez ou tuez de survivants, plus l'Entité vous récompense."
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[15].limitedAvailabilityStartDate: "2025-07-02T15:00:00Z"
- $.collections[15].visibleBeforeStartDate: false
- $.collections[15].additionalImages[0]
- $.collections[15].collectionId: "Casual"
+ $.collections[15].collectionId: "Rockabilly"
- $.collections[15].collectionTitle.de: "Leger"
+ $.collections[15].collectionTitle.de: "Rockabilly"
- $.collections[15].collectionTitle.en: "Casual"
+ $.collections[15].collectionTitle.en: "Rockabilly"
- $.collections[15].collectionTitle.es: "Casual"
+ $.collections[15].collectionTitle.es: "Rockabilly"
- $.collections[15].collectionTitle["es-MX"]: "Casual"
+ $.collections[15].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[15].collectionTitle.fr: "Décontracté"
+ $.collections[15].collectionTitle.fr: "Rockabilly"
- $.collections[15].collectionTitle.it: "Casual"
+ $.collections[15].collectionTitle.it: "Rockabilly"
- $.collections[15].collectionTitle.ja: "カジュアル"
+ $.collections[15].collectionTitle.ja: "ロカビリー "
- $.collections[15].collectionTitle.ko: "캐주얼"
+ $.collections[15].collectionTitle.ko: "로커빌리"
- $.collections[15].collectionTitle.pl: "Casual"
+ $.collections[15].collectionTitle.pl: "Rockabilly"
- $.collections[15].collectionTitle["pt-BR"]: "Casual"
+ $.collections[15].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[15].collectionTitle.ru: "Повседневная"
+ $.collections[15].collectionTitle.ru: "Рокабилли"
- $.collections[15].collectionTitle.th: "ลำลอง"
+ $.collections[15].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[15].collectionTitle.tr: "Günlük"
+ $.collections[15].collectionTitle.tr: "Rockabilly"
- $.collections[15].collectionTitle["zh-Hans"]: "休闲"
+ $.collections[15].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[15].collectionTitle["zh-Hant"]: "休閒"
+ $.collections[15].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_Casual.T_UI_CollectionBanner_Casual"
+ $.collections[15].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
- $.collections[15].inclusionVersion: "9.0.1"
+ $.collections[15].inclusionVersion: "7.7.0 PTB"
- $.collections[15].items[]: "S31_outfit_023"
- $.collections[15].items[]: "S45_outfit_012"
- $.collections[15].items[]: "S37_outfit_022"
- $.collections[15].items[]: "S35_outfit_022"
+ $.collections[15].items[]: "AV_outfit_015"
+ $.collections[15].items[]: "MS_outfit_014"
+ $.collections[15].items[]: "GS_outfit_014"
+ $.collections[15].items[]: "MT_outfit_015"
+ $.collections[15].items[]: "NK_outfit_014"
+ $.collections[15].items[]: "S23_outfit_016"
+ $.collections[15].items[]: "S24_outfit_013"
- $.collections[15].sortOrder: "-132"
+ $.collections[15].sortOrder: "-14"
- $.collections[15].updatedDate: "2025-05-23T13:05:39.676Z"
+ $.collections[15].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[16].collectionId: "Rockabilly"
+ $.collections[16].collectionId: "SpringEnsembles"
- $.collections[16].collectionTitle.de: "Rockabilly"
+ $.collections[16].collectionTitle.de: "Frühlings-Ensembles"
- $.collections[16].collectionTitle.en: "Rockabilly"
+ $.collections[16].collectionTitle.en: "Spring Ensembles"
- $.collections[16].collectionTitle.es: "Rockabilly"
+ $.collections[16].collectionTitle.es: "Conjuntos de primavera"
- $.collections[16].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[16].collectionTitle["es-MX"]: "Conjuntos de primavera"
- $.collections[16].collectionTitle.fr: "Rockabilly"
+ $.collections[16].collectionTitle.fr: "Ensembles printaniers"
- $.collections[16].collectionTitle.it: "Rockabilly"
+ $.collections[16].collectionTitle.it: "Completi primaverili"
- $.collections[16].collectionTitle.ja: "ロカビリー "
+ $.collections[16].collectionTitle.ja: "春のアンサンブル"
- $.collections[16].collectionTitle.ko: "로커빌리"
+ $.collections[16].collectionTitle.ko: "봄의 조화"
- $.collections[16].collectionTitle.pl: "Rockabilly"
+ $.collections[16].collectionTitle.pl: "Wiosenne stroje"
- $.collections[16].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[16].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
- $.collections[16].collectionTitle.ru: "Рокабилли"
+ $.collections[16].collectionTitle.ru: "Весенний ансамбль"
- $.collections[16].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[16].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
- $.collections[16].collectionTitle.tr: "Rockabilly"
+ $.collections[16].collectionTitle.tr: "Bahar Kreasyonu"
- $.collections[16].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[16].collectionTitle["zh-Hans"]: "春日套装"
- $.collections[16].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[16].collectionTitle["zh-Hant"]: "春天靈魂"
- $.collections[16].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[16].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
- $.collections[16].items[]: "AV_outfit_015"
- $.collections[16].items[]: "MS_outfit_014"
- $.collections[16].items[]: "GS_outfit_014"
- $.collections[16].items[]: "MT_outfit_015"
- $.collections[16].items[]: "NK_outfit_014"
- $.collections[16].items[]: "S23_outfit_016"
- $.collections[16].items[]: "S24_outfit_013"
+ $.collections[16].items[]: "Ace_outfit_008_01"
+ $.collections[16].items[]: "HillBilly_outfit_008_01"
+ $.collections[16].items[]: "FM_outfit_011"
+ $.collections[16].items[]: "FM_outfit_011_01"
+ $.collections[16].items[]: "S28_outfit_011"
+ $.collections[16].items[]: "US_outfit_015"
+ $.collections[16].items[]: "K21_outfit_010"
+ $.collections[16].items[]: "K26_outfit_007"
+ $.collections[16].items[]: "GK_outfit_013"
+ $.collections[16].items[]: "S29_outfit_008"
- $.collections[16].sortOrder: "-14"
+ $.collections[16].sortOrder: "-15"
- $.collections[16].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[16].updatedDate: "2024-02-20T17:45:49Z"
- $.collections[17].collectionId: "SpringEnsembles"
+ $.collections[17].collectionId: "Leatherface"
- $.collections[17].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[17].collectionTitle.de: "Leatherface"
- $.collections[17].collectionTitle.en: "Spring Ensembles"
+ $.collections[17].collectionTitle.en: "Leatherface"
- $.collections[17].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[17].collectionTitle.es: "Cara de cuero"
- $.collections[17].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[17].collectionTitle["es-MX"]: "Cara de cuero"
- $.collections[17].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[17].collectionTitle.fr: "Leatherface"
- $.collections[17].collectionTitle.it: "Completi primaverili"
+ $.collections[17].collectionTitle.it: "Faccia di cuoio"
- $.collections[17].collectionTitle.ja: "春のアンサンブル"
+ $.collections[17].collectionTitle.ja: "レザーフェイス"
- $.collections[17].collectionTitle.ko: "봄의 조화"
+ $.collections[17].collectionTitle.ko: "가죽 가면"
- $.collections[17].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[17].collectionTitle.pl: "Leatherface"
- $.collections[17].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[17].collectionTitle["pt-BR"]: "Leatherface"
- $.collections[17].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[17].collectionTitle.ru: "Кожаное Лицо"
- $.collections[17].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[17].collectionTitle.th: "หน้ากากหนัง"
- $.collections[17].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[17].collectionTitle.tr: "Deri Surat"
- $.collections[17].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[17].collectionTitle["zh-Hans"]: "人皮脸"
- $.collections[17].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[17].collectionTitle["zh-Hant"]: "皮臉"
- $.collections[17].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[17].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Leatherface.T_UI_CollectionBanner_Leatherface"
- $.collections[17].inclusionVersion: "7.7.0 PTB"
+ $.collections[17].inclusionVersion: "8.1.0"
- $.collections[17].items[]: "Ace_outfit_008_01"
- $.collections[17].items[]: "HillBilly_outfit_008_01"
- $.collections[17].items[]: "FM_outfit_011"
- $.collections[17].items[]: "FM_outfit_011_01"
- $.collections[17].items[]: "S28_outfit_011"
- $.collections[17].items[]: "US_outfit_015"
- $.collections[17].items[]: "K21_outfit_010"
- $.collections[17].items[]: "K26_outfit_007"
- $.collections[17].items[]: "GK_outfit_013"
- $.collections[17].items[]: "S29_outfit_008"
+ $.collections[17].items[]: "CA_outfit_006"
+ $.collections[17].items[]: "CA_outfit_007"
- $.collections[17].sortOrder: "-15"
+ $.collections[17].sortOrder: "-16"
- $.collections[17].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[17].updatedDate: "2024-06-25T12:13:35Z"
- $.collections[18].collectionId: "Leatherface"
+ $.collections[18].collectionId: "PopSuperstar"
- $.collections[18].collectionTitle.de: "Leatherface"
+ $.collections[18].collectionTitle.de: "Superpopstar"
- $.collections[18].collectionTitle.en: "Leatherface"
+ $.collections[18].collectionTitle.en: "Pop Superstar"
- $.collections[18].collectionTitle.es: "Cara de cuero"
+ $.collections[18].collectionTitle.es: "Superestrella del pop"
- $.collections[18].collectionTitle["es-MX"]: "Cara de cuero"
+ $.collections[18].collectionTitle["es-MX"]: "Superestrella del pop"
- $.collections[18].collectionTitle.fr: "Leatherface"
+ $.collections[18].collectionTitle.fr: "Superstar de la pop"
- $.collections[18].collectionTitle.it: "Faccia di cuoio"
+ $.collections[18].collectionTitle.it: "Superstar pop"
- $.collections[18].collectionTitle.ja: "レザーフェイス"
+ $.collections[18].collectionTitle.ja: "ポップスター"
- $.collections[18].collectionTitle.ko: "가죽 가면"
+ $.collections[18].collectionTitle.ko: "팝 슈퍼스타"
- $.collections[18].collectionTitle.pl: "Leatherface"
+ $.collections[18].collectionTitle.pl: "Supergwiazda popu"
- $.collections[18].collectionTitle["pt-BR"]: "Leatherface"
+ $.collections[18].collectionTitle["pt-BR"]: "Estrela Pop"
- $.collections[18].collectionTitle.ru: "Кожаное Лицо"
+ $.collections[18].collectionTitle.ru: "Поп-суперзвезда"
- $.collections[18].collectionTitle.th: "หน้ากากหนัง"
+ $.collections[18].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
- $.collections[18].collectionTitle.tr: "Deri Surat"
+ $.collections[18].collectionTitle.tr: "Popçu Süperstar"
- $.collections[18].collectionTitle["zh-Hans"]: "人皮脸"
+ $.collections[18].collectionTitle["zh-Hans"]: "流行巨星"
- $.collections[18].collectionTitle["zh-Hant"]: "皮臉"
+ $.collections[18].collectionTitle["zh-Hant"]: "流行巨星"
- $.collections[18].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Leatherface.T_UI_CollectionBanner_Leatherface"
+ $.collections[18].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
- $.collections[18].inclusionVersion: "8.1.0"
+ $.collections[18].inclusionVersion: "7.7.0 PTB"
- $.collections[18].items[]: "CA_outfit_006"
- $.collections[18].items[]: "CA_outfit_007"
+ $.collections[18].items[]: "FM_outfit_020"
… 3773 more change(s) — see the commit diff for everything
```

### [`consents/eula/v4/de.json`](consents/eula/v4/de.json)

[Full line-by-line diff](diffs/consents/eula/v4/de.json.diff)

```diff
- $[id=eula].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG \n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BE…
+ $[id=eula].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG\n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BEZ…
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "f04072b45c1b247424337afe9a23bde2256db465"
+ $.entries[0].contentVersion: "f15472ee9d269e11f8ab5991a6e5d5d5b3d685e8"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_Casual.T_UI_CollectionBanner_Casual"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TheWitcherBundle.T_UI_SpecialPack_TheWitcherBundle"
- $.entries[0].uri: "images/T_UI_CollectionBanner_Casual.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_TheWitcherBundle.png"
- $.entries[1].contentVersion: "8d3a062fe4575c5dac65c1ba9444acf44606748c"
+ $.entries[1].contentVersion: "50bce6cb7ae6795b14f8cc3e33991c49dfdc6826"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_Casual.T_UI_SpecialPack_Casual"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_FiveNightsAtFreddys.T_UI_ChapterBundle_FiveNightsAtFreddys"
- $.entries[1].uri: "images/T_UI_SpecialPack_Casual.png"
+ $.entries[1].uri: "images/T_UI_ChapterBundle_FiveNightsAtFreddys.png"
- $.entries[2].downloadStrategy: "preferPackaged"
+ $.entries[2].downloadStrategy: "preferRemote"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[4].contentVersion: "0ae191bf37ea7fa5aaa604ae16fae2e9bad9ccdf"
+ $.entries[4].contentVersion: "2e79221d369501f1b160482045957fbffc1e7a77"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ketchup/T_UI_CollectionBanner_FNAF.T_UI_CollectionBanner_FNAF"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "catalog.json"
+ $.entries[4].uri: "images/T_UI_CollectionBanner_FNAF.png"
- $.entries[5].contentVersion: "ea9ad0d09881b418176dd05a26d589ddf5fb7acc"
+ $.entries[5].contentVersion: "7de10c5e7961a12c8616a769b69d684ae8aa47ef"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ketchup/T_UI_SpecialPack_FNAF.T_UI_SpecialPack_FNAF"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "bonusPointEventsContent.json"
+ $.entries[5].uri: "images/T_UI_SpecialPack_FNAF.png"
- $.entries[6].contentVersion: "b9d9b0aa17c6fcac79c8afedbb0eed3331f7952d"
+ $.entries[6].contentVersion: "3b5d5ceea0a7a36fdb38d614421422f19cc2a4aa"
- $.entries[6].uri: "freetoplay/NA/event.json"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "b9d9b0aa17c6fcac79c8afedbb0eed3331f7952d"
+ $.entries[7].contentVersion: "ee119afb003a3abe4599e4b70a42a6563365b9b3"
- $.entries[7].uri: "freetoplay/EU/event.json"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "9658ef341c7af5d9c10460248df26902c561ee5e"
+ $.entries[8].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[8].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "c30342f0602d3a2f9fb882eb5a027fd018ff1463"
+ $.entries[9].contentVersion: "bbbc0d307d57d2edad6c97731f4dcd5385d4a64b"
- $.entries[9].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "7a7ccbd5590437ac9f69bb8de188edd0c814bc23"
+ $.entries[10].contentVersion: "3d79e5d3c0f38ac103d12f8a7216990f76887235"
- $.entries[10].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "c7cd05e4710525008288809f83aee4da738474c5"
+ $.entries[11].contentVersion: "5fc2e74b6547cad57aaa22fa61e18f24b1c6659d"
- $.entries[11].uri: "archiveQuests/CalamariV1.json"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "25aa245305f85d2173f46b283fe0fff3c803dfba"
+ $.entries[12].contentVersion: "baac2c534846886f85a06f6e53c1900d9e2147c8"
- $.entries[12].uri: "archiveQuests/CalamariV2.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "2da79b8d628610827c08bcbde9c45c49c1dfc1dd"
+ $.entries[13].contentVersion: "ea1176851d28dda829d7a3483fdd65ee2f96252d"
- $.entries[13].uri: "archiveQuests/CalamariV3.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "1827cac3f6780a1c43a7eb6fc9deda45d3549ae6"
+ $.entries[14].contentVersion: "a8701575be23d4eb00f57821e65b55126651c39c"
- $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "88091678a397895ba595b3f035745eaf869f1253"
+ $.entries[15].contentVersion: "fcc9d38ca8076c713715bdc3df7450093f99efa0"
- $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "052520c1f320c20f1965340b57ec032a6aa501ed"
+ $.entries[16].contentVersion: "0b3b85c9a115171243104b58cc30d455f193604b"
- $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "dfa2f29e511c617489c8b2a6c881b9b570f694ce"
+ $.entries[17].contentVersion: "7f656c9cc903be74c6ada4c5a7d76d54dff6f6a3"
- $.entries[17].uri: "archiveQuests/FireflyV1.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "1bd5ad50a0920364a7e69a6b408f946eeef3f11a"
+ $.entries[18].contentVersion: "78a5dae70495a089228cca71b5680813c39a760d"
- $.entries[18].uri: "archiveQuests/Halloween2021.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "a838b1aaadf1a840b7ebf71b92d88bb7e3b8b4b2"
+ $.entries[19].contentVersion: "f4bee6e3aac4fd6ff1018d424e5767e03b13d2e9"
- $.entries[19].uri: "archiveQuests/Halloween2022.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "e025f4d9bbbe37a3092956801e7322cf154aef75"
+ $.entries[20].contentVersion: "d0beaab94a8b37c6f7ac7f9cb889f7ab09421eae"
- $.entries[20].uri: "archiveQuests/Halloween2023.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "14f414f6465a4aea54a80e97f3d0b23e5dea9e43"
+ $.entries[21].contentVersion: "4ec20a78dde46c90f18875489757d6c3daf5bc3a"
- $.entries[21].uri: "archiveQuests/Halloween2024.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "ea3dda5e80e384ff4ebf056e1cfa8611e7694bb6"
+ $.entries[22].contentVersion: "f1d5d934cc04c244c0229983dd79b67fc4c55beb"
- $.entries[22].uri: "archiveQuests/Spring2024.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "f1efe767c98e13fec6917a45f73f54150f1643aa"
+ $.entries[23].contentVersion: "93bc73c450b3a5a6fd460fa190eb5bbfff78bce5"
- $.entries[23].uri: "archiveQuests/Spring2025.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "b2474dab85971920bf4c4fa41c2e5347f506e61a"
+ $.entries[24].contentVersion: "a5e96d81cf9d60a62929e46bccad53702e589a77"
- $.entries[24].uri: "archiveQuests/Summer2023.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "c4778cbd9e2241e077358c652ee80b31017f3121"
+ $.entries[25].contentVersion: "acd27f87e9da430c2425ef37d7fe8012e038e88e"
- $.entries[25].uri: "archiveQuests/Tome01.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "4f2965e280d3e107baf65ca2648c39ad09cd8c9c"
+ $.entries[26].contentVersion: "a243d259c3909a0d195ac55823368c39272c1d82"
- $.entries[26].uri: "archiveQuests/Tome02.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "90da129e628c31831926c0f10519c3af7c95ccdc"
+ $.entries[27].contentVersion: "4778974a5941f12c14a933f31bc0cb2a24fb972e"
- $.entries[27].uri: "archiveQuests/Tome03.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "71c15bcfe9965c0bfa8c21fd7ee43479292190c4"
+ $.entries[28].contentVersion: "4cbff6c453c8bd64e47f94c926b94abd92e8cace"
- $.entries[28].uri: "archiveQuests/Tome04.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "f5a7b0336c5d2a1a3b40bbe3deb908d6726e1594"
+ $.entries[29].contentVersion: "5036305610c36c2e019a43e26de48f2ec452c42a"
- $.entries[29].uri: "archiveQuests/Tome05.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "eab822d2c5919690560f32d1ca476985024daaf0"
+ $.entries[30].contentVersion: "5220ef03719ae476e386fcca63fd1ee11ed3b9c7"
- $.entries[30].uri: "archiveQuests/Tome06.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "824ea419de2837a94ae44053ab4c55b923a92630"
+ $.entries[31].contentVersion: "81e204ca4e3e7a08c4aba509a300d049e1bbf05e"
- $.entries[31].uri: "archiveQuests/Tome07.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "24732a7bd0db5334268be492c36da4ae47178df3"
+ $.entries[32].contentVersion: "aab27337a175139675c6593640404462e0fb026a"
- $.entries[32].uri: "archiveQuests/Tome08.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
- $.entries[33].contentVersion: "6a6bb2d702276dc5dd9014d8dd099fa6825cc1c6"
+ $.entries[33].contentVersion: "d565bb24eee4033846f9c7b44e3fa79c65f22184"
- $.entries[33].uri: "archiveQuests/Tome09.json"
+ $.entries[33].uri: "archiveQuests/Tome07.json"
- $.entries[34].contentVersion: "ab04d0157d81e8df5f1c1013c3666ddef2a9c116"
+ $.entries[34].contentVersion: "9a70cb6fdf8a2754a30d80b58f3a258a3a3dfbcd"
- $.entries[34].uri: "archiveQuests/Tome10.json"
+ $.entries[34].uri: "archiveQuests/Tome08.json"
- $.entries[35].contentVersion: "059ddf1f6298e3ee5ac313e35dba4b1d724cd424"
+ $.entries[35].contentVersion: "462b3ea0ac866fd453deaf359362b53887993fe8"
- $.entries[35].uri: "archiveQuests/Tome11.json"
+ $.entries[35].uri: "archiveQuests/Tome09.json"
- $.entries[36].contentVersion: "e46cee2f8510f353f762d83cec7fda63f65d8cce"
+ $.entries[36].contentVersion: "14f908e42c1515cdc605804fd964cb91748c4f09"
- $.entries[36].uri: "archiveQuests/Tome12.json"
+ $.entries[36].uri: "archiveQuests/Tome10.json"
- $.entries[37].contentVersion: "398b5f468bcd4a6ccbc52472323c2dc1a709beea"
+ $.entries[37].contentVersion: "2c75df4a6364501da8cc736ace271acad3806fa8"
- $.entries[37].uri: "archiveQuests/Tome13.json"
+ $.entries[37].uri: "archiveQuests/Tome11.json"
- $.entries[38].contentVersion: "83f316b57e6aa0d1d7cf28be6ee0f6a5f223d300"
+ $.entries[38].contentVersion: "7720fbc3ea7ebe343d23d5b08c0db0b310c77cf0"
- $.entries[38].uri: "archiveQuests/Tome14.json"
+ $.entries[38].uri: "archiveQuests/Tome12.json"
- $.entries[39].contentVersion: "dc80774fa66faff6d510f0d3f5f66ebfa65fc236"
+ $.entries[39].contentVersion: "c6855eb665035513aaae3418054ef2de203c002d"
- $.entries[39].uri: "archiveQuests/Tome15.json"
+ $.entries[39].uri: "archiveQuests/Tome13.json"
- $.entries[40].contentVersion: "ffaa6ea277261506e8e70e38c4a9949114809197"
+ $.entries[40].contentVersion: "d1d8a99c35dc35ad58872df934ffac0c75437bd0"
- $.entries[40].uri: "archiveQuests/Tome16.json"
+ $.entries[40].uri: "archiveQuests/Tome14.json"
- $.entries[41].contentVersion: "63d652eddb0cd5be63984f9a314a6961cb4c623d"
+ $.entries[41].contentVersion: "285100a3c684cad9445f9655dd0fb42c0e3bb42c"
- $.entries[41].uri: "archiveQuests/Tome17.json"
+ $.entries[41].uri: "archiveQuests/Tome15.json"
- $.entries[42].contentVersion: "9ca9e9406623690424ec626dcdb36eb572fb0513"
+ $.entries[42].contentVersion: "d74fa08fecca7edda0cb8c8a05da244b15a47b7a"
- $.entries[42].uri: "archiveQuests/Tome18.json"
+ $.entries[42].uri: "archiveQuests/Tome16.json"
- $.entries[43].contentVersion: "351dcea03e693be6c5eaca92afc0136e1531d7a1"
+ $.entries[43].contentVersion: "056013c7e688e685e0c10253d899f58345b823d3"
- $.entries[43].uri: "archiveQuests/Tome19.json"
+ $.entries[43].uri: "archiveQuests/Tome17.json"
- $.entries[44].contentVersion: "54f96b2e6b96fd12fa1f7eb39930e0d568424f98"
+ $.entries[44].contentVersion: "340f607da38694cf0ecfbc72cc0a2d7c8659e787"
- $.entries[44].uri: "archiveQuests/Tome20.json"
+ $.entries[44].uri: "archiveQuests/Tome18.json"
- $.entries[45].contentVersion: "5966e083e5bf2e9d597e0f2f38242fd163ddfd83"
+ $.entries[45].contentVersion: "630ce32e86268a45cd2bfafbc251e76d4d1eb1d7"
- $.entries[45].uri: "archiveQuests/Tome21.json"
+ $.entries[45].uri: "archiveQuests/Tome19.json"
… 726 more change(s) — see the commit diff for everything
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.specialsRecommendations[id=Anniversary]
```

## Could not download

- `images/T_UI_ChapterBundle_FiveNightsAtFreddys.png (HTTP 404)`
- `images/T_UI_CollectionBanner_FNAF.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TwistedMasquerade.png (HTTP 404)`
- `images/T_UI_SpecialPack_FNAF.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TwistedMasquerade.png (HTTP 404)`
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

