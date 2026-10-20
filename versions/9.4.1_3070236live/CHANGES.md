# live · 9.4.1_3070236live

| | |
|---|---|
| Build date | 2026-02-02 18:31 UTC |
| CDN version | `9.4.1_3070236live-1770057100` |
| Key | `9.4.1_live` |
| Compared with | [9.4.0_3066215live](../9.4.0_3066215live/CHANGES.md) (2026-01-30 13:46 UTC) |

## Summary

**1** added · **11** modified · **6** removed · 197 unchanged

## New or updated images

<a href="images/T_UI_SpecialPack_ModernTales.png"><img src="images/T_UI_SpecialPack_ModernTales.png" alt="T_UI_SpecialPack_ModernTales.png" width="240"></a>

## Removed files

- `images/T_UI_ChapterBundle_StrangerThings_Chapter2.png`
- `images/T_UI_CollectionBanner_StrangerThings_Chapter2.png`
- `images/T_UI_SpecialPack_Rift4.png`
- `images/T_UI_SpecialPack_StrangerThings_Chapter2.png`
- `images/T_UI_icon_Event_FogCarnival.png`
- `images/T_UI_icon_Event_LunarYear.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.DSProviderOnShutdownNotificationDelay: 15.0
+ $.DSProviderOnShutdownNotificationDelay: 90.0
- $.enableAlwaysSendCrashWithUI: false
+ $.enableAlwaysSendCrashWithUI: true
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
+ $.TOME23.vignettes[id=TOME23_02].entries[9]
+ $.TOME23.vignettes[id=TOME23_03].entries[0]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=From_The_Rift_Bundle_260120]
- $[id=From_The_Rift_Bundle_260127]
- $[id=Recurring_Charm_Bundle_260120]
- $[id=Recurring_Charm_Bundle_260127]
- $[id=Recurring_Dev_Bundle_260120]
- $[id=Recurring_Dev_Bundle_260127]
- $[id=Recurring_Killer_Bundle_260120]
- $[id=Recurring_Killer_Bundle_260127]
- $[id=Recurring_Survivor_Bundle_260120]
- $[id=Recurring_Survivor_Bundle_260127]
- $[id=Recurring_Survivor_Bundle_2_260127]
+ $[id=POU_BDG_25]
+ $[id=POU_BNR_17]
+ $[id=SilentHill_Omelet_Bundle]
- $[id=S22_outfit_02].metaData.temporaryDiscounts
- $[id=S22_outfit_02_01].metaData.temporaryDiscounts
- $[id=TorturedSoulsBundle].metaData.sortOrder: 600
+ $[id=TorturedSoulsBundle].metaData.sortOrder: 1100
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[0].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[1].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[2].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.challengeList[3].endDate: "2026-01-27T16:00:00"
- $.ChocolateBoxOmeletSet.endDate: "2026-01-27T14:00:00"
+ $.ChocolateBoxOmeletSet.endDate: "2026-01-27T16:00:00"
- $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChaseInTrial_Community.maxProgressionPerPlayer: 12000000
+ $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChaseInTrial_Community.maxProgressionPerPlayer: 950000000
- $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChaseInTrial_Community.neededProgression[]: 12000000
+ $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChaseInTrial_Community.neededProgression[]: 950000000
- $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChasedByKillerInTrial_Community.maxProgressionPerPlayer: 12000000
+ $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChasedByKillerInTrial_Community.maxProgressionPerPlayer: 750000000
- $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChasedByKillerInTrial_Community.neededProgression[]: 12000000
+ $.FogCarnival.challengeList[0].challenges[id=FogCarnival-FogCarnival_CommunityQuests-C_ChaseSingleTrialOrBeChasedSingleTrial].objectives.ChasedByKillerInTrial_Community.neededProgression[]: 750000000
- $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests1].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests1].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests2].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].challenges[id=LNYPoutine-Overarching-O_CompleteQuests2].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[0].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[0].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_ChaseOrBeChased].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_ChaseOrBeChased].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_CarryOrEscapeChase].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-D_CarryOrEscapeChase].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_BreakGen].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_BreakGen].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_Repair].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].challenges[id=LNYPoutine-LNYPoutine_QuestList_1-B_Repair].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.challengeList[1].startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.challengeList[1].startDate: "2026-02-15T16:00:00"
- $.LNYPoutine.endDate: "2026-02-24T16:00:00"
+ $.LNYPoutine.endDate: "2026-03-01T16:00:00"
- $.LNYPoutine.startDate: "2026-02-12T16:00:00"
+ $.LNYPoutine.startDate: "2026-02-15T16:00:00"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[46].additionalImages[0]
- $.collections[46].collectionId: "CthulhuNoir"
+ $.collections[46].collectionId: "ModernTales"
- $.collections[46].collectionTitle.de: "Schaurige Albträume"
+ $.collections[46].collectionTitle.de: "Moderne Geschichten"
- $.collections[46].collectionTitle.en: "Eldritch Nightmares"
+ $.collections[46].collectionTitle.en: "Modern Tales"
- $.collections[46].collectionTitle.es: "Pesadillas abominables"
+ $.collections[46].collectionTitle.es: "Historias modernas"
- $.collections[46].collectionTitle["es-MX"]: "Pesadillas sobrenaturales"
+ $.collections[46].collectionTitle["es-MX"]: "Cuentos modernos"
- $.collections[46].collectionTitle.fr: "Cauchemars surnaturels"
+ $.collections[46].collectionTitle.fr: "Contes modernes"
- $.collections[46].collectionTitle.it: "Incubi occulti"
+ $.collections[46].collectionTitle.it: "Racconti moderni"
- $.collections[46].collectionTitle.ja: "得体の知れない悪夢"
+ $.collections[46].collectionTitle.ja: "現代物語"
- $.collections[46].collectionTitle.ko: "엘드리치 악몽"
+ $.collections[46].collectionTitle.ko: "현대 동화"
- $.collections[46].collectionTitle.pl: "Straszne koszmary"
+ $.collections[46].collectionTitle.pl: "Współczesne opowieści"
- $.collections[46].collectionTitle["pt-BR"]: "Pesadelos Sobrenaturais"
+ $.collections[46].collectionTitle["pt-BR"]: "Contos Modernos"
- $.collections[46].collectionTitle.ru: "Зловещие кошмары"
+ $.collections[46].collectionTitle.ru: "Современные сказки"
- $.collections[46].collectionTitle.th: "ฝันร้ายวิปริต"
+ $.collections[46].collectionTitle.th: "นิทานยุคใหม่"
- $.collections[46].collectionTitle.tr: "Yaratık Kâbusları"
+ $.collections[46].collectionTitle.tr: "Modern Hikâyeler"
- $.collections[46].collectionTitle["zh-Hans"]: "诡异噩梦"
+ $.collections[46].collectionTitle["zh-Hans"]: "现代故事"
- $.collections[46].collectionTitle["zh-Hant"]: "詭異的惡夢"
+ $.collections[46].collectionTitle["zh-Hant"]: "摩登故事"
- $.collections[46].heroImage.path: "/Game/UI/UMGAssets/Icons/Help/iconHelp_loadingMissing.iconHelp_loadingMissing"
+ $.collections[46].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ModernTales.T_UI_CollectionBanner_ModernTales"
- $.collections[46].inclusionVersion: "9.4.0"
+ $.collections[46].inclusionVersion: "7.7.0 PTB"
- $.collections[46].items[]: "S45_outfit_014"
- $.collections[46].items[]: "TN_outfit_026"
+ $.collections[46].items[]: "BE_outfit_014"
+ $.collections[46].items[]: "DF_outfit_035"
+ $.collections[46].items[]: "FM_outfit_018"
+ $.collections[46].items[]: "GS_outfit_039"
+ $.collections[46].items[]: "MK_outfit_020"
+ $.collections[46].items[]: "MT_outfit_017"
+ $.collections[46].items[]: "S29_outfit_024"
+ $.collections[46].items[]: "S31_outfit_017"
+ $.collections[46].items[]: "TR_outfit_026"
- $.collections[46].limitedAvailabilityStartDate: "2026-02-10T16:00:00Z"
+ $.collections[46].limitedAvailabilityStartDate: "2024-10-23T15:00:00Z"
- $.collections[46].updatedDate: "2025-10-02T17:11:46.936Z"
+ $.collections[46].updatedDate: "2026-02-02T15:37:26.708Z"
+ $.collections[47].limitedAvailabilityStartDate: "2026-02-10T16:00:00Z"
+ $.collections[47].visibleBeforeStartDate: false
- $.collections[47].collectionId: "GrimMatsuri"
+ $.collections[47].collectionId: "CthulhuNoir"
- $.collections[47].collectionTitle.de: "Düsteres Matsuri-Fest"
+ $.collections[47].collectionTitle.de: "Schaurige Albträume"
- $.collections[47].collectionTitle.en: "Grim Matsuri"
+ $.collections[47].collectionTitle.en: "Eldritch Nightmares"
- $.collections[47].collectionTitle.es: "Matsuri tenebrosa"
+ $.collections[47].collectionTitle.es: "Pesadillas abominables"
- $.collections[47].collectionTitle["es-MX"]: "Matsuri tenebrosa"
+ $.collections[47].collectionTitle["es-MX"]: "Pesadillas sobrenaturales"
- $.collections[47].collectionTitle.fr: "Matsuri sinistre"
+ $.collections[47].collectionTitle.fr: "Cauchemars surnaturels"
- $.collections[47].collectionTitle.it: "Matsuri funebre"
+ $.collections[47].collectionTitle.it: "Incubi occulti"
- $.collections[47].collectionTitle.ja: "おぞましい祭り"
+ $.collections[47].collectionTitle.ja: "得体の知れない悪夢"
- $.collections[47].collectionTitle.ko: "음산한 축제"
+ $.collections[47].collectionTitle.ko: "엘드리치 악몽"
- $.collections[47].collectionTitle.pl: "Ponury Festiwal"
+ $.collections[47].collectionTitle.pl: "Straszne koszmary"
- $.collections[47].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
+ $.collections[47].collectionTitle["pt-BR"]: "Pesadelos Sobrenaturais"
- $.collections[47].collectionTitle.ru: "Мрачный Мацури"
+ $.collections[47].collectionTitle.ru: "Зловещие кошмары"
- $.collections[47].collectionTitle.th: "เทศกาลสยอง"
+ $.collections[47].collectionTitle.th: "ฝันร้ายวิปริต"
- $.collections[47].collectionTitle.tr: "Kasvetli Festival"
+ $.collections[47].collectionTitle.tr: "Yaratık Kâbusları"
- $.collections[47].collectionTitle["zh-Hans"]: "冷血祭"
+ $.collections[47].collectionTitle["zh-Hans"]: "诡异噩梦"
- $.collections[47].collectionTitle["zh-Hant"]: "冷血祭"
+ $.collections[47].collectionTitle["zh-Hant"]: "詭異的惡夢"
- $.collections[47].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
+ $.collections[47].heroImage.path: "/Game/UI/UMGAssets/Icons/Help/iconHelp_loadingMissing.iconHelp_loadingMissing"
- $.collections[47].inclusionVersion: "7.7.0 PTB"
+ $.collections[47].inclusionVersion: "9.4.0"
- $.collections[47].items[]: "Bear_outfit_003"
- $.collections[47].items[]: "Claudette_outfit_018"
- $.collections[47].items[]: "GS_outfit_011"
- $.collections[47].items[]: "Jake_outfit_017"
- $.collections[47].items[]: "Meg_outfit_023"
- $.collections[47].items[]: "Nea_outfit_010"
- $.collections[47].items[]: "SwedenSurvivor_outfit_009"
- $.collections[47].items[]: "TN_outfit_010"
+ $.collections[47].items[]: "S45_outfit_014"
+ $.collections[47].items[]: "TN_outfit_026"
- $.collections[47].sortOrder: "-2"
+ $.collections[47].sortOrder: "-197"
- $.collections[47].updatedDate: "2024-03-06T20:44:22Z"
+ $.collections[47].updatedDate: "2025-10-02T17:11:46.936Z"
- $.collections[48].collectionId: "AliceInWonderland"
+ $.collections[48].collectionId: "GrimMatsuri"
- $.collections[48].collectionTitle.de: "Alice im Wunderland"
+ $.collections[48].collectionTitle.de: "Düsteres Matsuri-Fest"
- $.collections[48].collectionTitle.en: "Alice in Wonderland"
+ $.collections[48].collectionTitle.en: "Grim Matsuri"
- $.collections[48].collectionTitle.es: "Alicia en el País de las Maravillas"
+ $.collections[48].collectionTitle.es: "Matsuri tenebrosa"
- $.collections[48].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
+ $.collections[48].collectionTitle["es-MX"]: "Matsuri tenebrosa"
- $.collections[48].collectionTitle.fr: "Alice au pays des merveilles"
+ $.collections[48].collectionTitle.fr: "Matsuri sinistre"
- $.collections[48].collectionTitle.it: "Alice nel paese delle meraviglie"
+ $.collections[48].collectionTitle.it: "Matsuri funebre"
- $.collections[48].collectionTitle.ja: "不思議の国のアリス"
+ $.collections[48].collectionTitle.ja: "おぞましい祭り"
- $.collections[48].collectionTitle.ko: "이상한 나라의 앨리스"
+ $.collections[48].collectionTitle.ko: "음산한 축제"
- $.collections[48].collectionTitle.pl: "Alicja w Krainie Czarów"
+ $.collections[48].collectionTitle.pl: "Ponury Festiwal"
- $.collections[48].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
+ $.collections[48].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
- $.collections[48].collectionTitle.ru: "Алиса в Стране чудес"
+ $.collections[48].collectionTitle.ru: "Мрачный Мацури"
- $.collections[48].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
+ $.collections[48].collectionTitle.th: "เทศกาลสยอง"
- $.collections[48].collectionTitle.tr: "Alice Harikalar Diyarında"
+ $.collections[48].collectionTitle.tr: "Kasvetli Festival"
- $.collections[48].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
+ $.collections[48].collectionTitle["zh-Hans"]: "冷血祭"
- $.collections[48].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
+ $.collections[48].collectionTitle["zh-Hant"]: "冷血祭"
- $.collections[48].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
+ $.collections[48].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
- $.collections[48].items[]: "AV_outfit_018"
- $.collections[48].items[]: "BE_outfit_020"
- $.collections[48].items[]: "GS_outfit_023"
- $.collections[48].items[]: "K26_outfit_011"
- $.collections[48].items[]: "NK_outfit_023"
+ $.collections[48].items[]: "Bear_outfit_003"
+ $.collections[48].items[]: "Claudette_outfit_018"
+ $.collections[48].items[]: "GS_outfit_011"
+ $.collections[48].items[]: "Jake_outfit_017"
+ $.collections[48].items[]: "Meg_outfit_023"
+ $.collections[48].items[]: "Nea_outfit_010"
+ $.collections[48].items[]: "SwedenSurvivor_outfit_009"
+ $.collections[48].items[]: "TN_outfit_010"
- $.collections[48].sortOrder: "-20"
+ $.collections[48].sortOrder: "-2"
- $.collections[48].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[48].updatedDate: "2024-03-06T20:44:22Z"
- $.collections[49].collectionId: "Wasteland"
+ $.collections[49].collectionId: "AliceInWonderland"
- $.collections[49].collectionTitle.de: "Ödland"
+ $.collections[49].collectionTitle.de: "Alice im Wunderland"
- $.collections[49].collectionTitle.en: "Wasteland"
+ $.collections[49].collectionTitle.en: "Alice in Wonderland"
- $.collections[49].collectionTitle.es: "Páramo"
+ $.collections[49].collectionTitle.es: "Alicia en el País de las Maravillas"
- $.collections[49].collectionTitle["es-MX"]: "Páramo"
+ $.collections[49].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
- $.collections[49].collectionTitle.fr: "Terre dévastée"
+ $.collections[49].collectionTitle.fr: "Alice au pays des merveilles"
- $.collections[49].collectionTitle.it: "Landa desolata"
+ $.collections[49].collectionTitle.it: "Alice nel paese delle meraviglie"
- $.collections[49].collectionTitle.ja: "荒れ地"
+ $.collections[49].collectionTitle.ja: "不思議の国のアリス"
- $.collections[49].collectionTitle.ko: "황무지"
+ $.collections[49].collectionTitle.ko: "이상한 나라의 앨리스"
- $.collections[49].collectionTitle.pl: "Pustkowie"
+ $.collections[49].collectionTitle.pl: "Alicja w Krainie Czarów"
- $.collections[49].collectionTitle["pt-BR"]: "Desolação"
+ $.collections[49].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
- $.collections[49].collectionTitle.ru: "Пустошь"
+ $.collections[49].collectionTitle.ru: "Алиса в Стране чудес"
- $.collections[49].collectionTitle.th: "แดนรกร้าง"
+ $.collections[49].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
- $.collections[49].collectionTitle.tr: "Çorak"
+ $.collections[49].collectionTitle.tr: "Alice Harikalar Diyarında"
- $.collections[49].collectionTitle["zh-Hans"]: "荒芜之地"
+ $.collections[49].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
- $.collections[49].collectionTitle["zh-Hant"]: "荒地"
+ $.collections[49].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
- $.collections[49].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Wasteland.T_UI_CollectionBanner_Wasteland"
+ $.collections[49].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
- $.collections[49].items[]: "K30_outfit_008"
- $.collections[49].items[]: "S23_outfit_021"
- $.collections[49].items[]: "S31_outfit_009"
+ $.collections[49].items[]: "AV_outfit_018"
+ $.collections[49].items[]: "BE_outfit_020"
+ $.collections[49].items[]: "GS_outfit_023"
+ $.collections[49].items[]: "K26_outfit_011"
+ $.collections[49].items[]: "NK_outfit_023"
- $.collections[49].sortOrder: "-21"
+ $.collections[49].sortOrder: "-20"
- $.collections[50].collectionId: "Brazil"
… 1639 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[6]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "22f4426df683b6384ac0d61b71e28e3880e1c7ec"
+ $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_Rift4.T_UI_SpecialPack_Rift4"
+ $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[0].uri: "images/T_UI_SpecialPack_Rift4.png"
+ $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[3].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
- $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[3].uri: "images/T_UI_SpecialPack_ModernTales.png"
- $.entries[4].contentVersion: "ecea0cbb601208988fb7e266e6339430fbd26066"
+ $.entries[4].contentVersion: "b5c31d3f55eee34a9540adb78fdf8c2fd45d83e7"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_FogCarnival.T_UI_icon_Event_FogCarnival"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_icon_Event_FogCarnival.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "ba5908d103a3c970227c15e80f8c1cedd3ed9bec"
+ $.entries[5].contentVersion: "5d124c36de256559501744cadda80d8524b1753d"
- $.entries[5].enableChecksum: false
+ $.entries[5].enableChecksum: true
- $.entries[5].packagedPath: "/DBDUICore/Assets/Common/Event/T_UI_icon_Event_LunarYear.T_UI_icon_Event_LunarYear"
+ $.entries[5].packagedPath: ""
- $.entries[5].schema: "s3verbin://"
+ $.entries[5].schema: "s3ver://"
- $.entries[5].uri: "images/T_UI_icon_Event_LunarYear.png"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "36c04d7010039e4bbed2a8374fce6f33020d71f9"
+ $.entries[6].contentVersion: "9a3480f6b6a4ac884b60d841509796280849c249"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_StrangerThings_Chapter2.T_UI_ChapterBundle_StrangerThings_Chapter2"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_ChapterBundle_StrangerThings_Chapter2.png"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "f8b2414afc2858c35fed794667b3ba6f27a3e7a0"
+ $.entries[7].contentVersion: "9a3480f6b6a4ac884b60d841509796280849c249"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_StrangerThings_Chapter2.T_UI_CollectionBanner_StrangerThings_Chapter2"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_CollectionBanner_StrangerThings_Chapter2.png"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "12010aea83ad4e1ee56c50df0da8cd85a85498a2"
+ $.entries[8].contentVersion: "bc006d92d29a5e6328e91285b11aa54a0e0c411f"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/Poutine/T_UI_SpecialPack_StrangerThings_Chapter2.T_UI_SpecialPack_StrangerThings_Chapter2"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_SpecialPack_StrangerThings_Chapter2.png"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "d583fe7c38336b067d7db87629f7c532a0bd9b5f"
+ $.entries[9].contentVersion: "ab5e8b9e9ca68f4f8059f1b14449269d0ffeadb8"
- $.entries[9].uri: "catalog.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "0688a6020b52e6bd9500b266ac4b4b6baa60860d"
+ $.entries[10].contentVersion: "7a0b19c453ff0736b3dbf7ba57fa907f66134ece"
- $.entries[10].uri: "bonusPointEventsContent.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[11].contentVersion: "d27cd9bc810294e4fa260a00a26d9262c3df3b2f"
- $.entries[11].uri: "freetoplay/NA/event.json"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[12].contentVersion: "fe44212cf941925219bc4dc5d3a882350924d26a"
- $.entries[12].uri: "freetoplay/EU/event.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "dd527570e43d5227bc28afe72fb1f78e53ac6822"
+ $.entries[13].contentVersion: "19ca4e16bcba6dd47a5cee03b8333bcf8b343ad2"
- $.entries[13].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "52fc655e6b41b211e455230a518f9846c8b5286a"
+ $.entries[14].contentVersion: "76f1017394843b2d22851a5a6f9985c962a416d8"
- $.entries[14].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "946926ad6e5fc8348d1f1132ac7b59cc676cff14"
+ $.entries[15].contentVersion: "2fadd29ada397df69c995d89af3cb33c813b37a1"
- $.entries[15].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "44a5c8ea54340fdfc9b01597243b454a8622e029"
+ $.entries[16].contentVersion: "ccdb1cf13b148d29fc66281c13aaf1543013b320"
- $.entries[16].uri: "archiveQuests/CalamariV1.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "671675edb2bebab5f35c2e4b6b8e5fa78882ee92"
+ $.entries[17].contentVersion: "7c6a8bf71078b820849b4630b11b29fb5f8791b8"
- $.entries[17].uri: "archiveQuests/CalamariV2.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "c36008b30af60617d7038322e37ad3f3cd2754e5"
+ $.entries[18].contentVersion: "e7f9a9518d965a55b41ffca9e1cb2b3e107f4fbf"
- $.entries[18].uri: "archiveQuests/CalamariV3.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "680a0cf92894220d6b78184aef473d2da4c76013"
+ $.entries[19].contentVersion: "46204ae471ea73fd72d29cea51d914f10df01e9a"
- $.entries[19].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "eae70968d8423a3a0f61227e8b7da194f8856be1"
+ $.entries[20].contentVersion: "2257b9f00eb53b5dbf54eda8bb4b5805dc94bb1b"
- $.entries[20].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "5210f96a51547ac1be938e0651440a5c5569ef3a"
+ $.entries[21].contentVersion: "20013d8c29cdcc7f2abf90fe9db21811871df20e"
- $.entries[21].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "3de6169053b9db24bf1f8464a61002e16a417945"
+ $.entries[22].contentVersion: "67d4205d65da1a7ddcb442abe12b9ab56dc1f011"
- $.entries[22].uri: "archiveQuests/FireflyV1.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "69fe782985a5376bac4f588fac10e1f567cbeca4"
+ $.entries[23].contentVersion: "02f1ba95f160a443d3d2134179f481519054eb01"
- $.entries[23].uri: "archiveQuests/Halloween2021.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "3b38b442968cdb458f8afd787c8e688df454f3ff"
+ $.entries[24].contentVersion: "95528a855f0f57c424f8649b32daf3cba921b1a7"
- $.entries[24].uri: "archiveQuests/Halloween2022.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "0349ede198538537ff43da647cb4a6f17d238593"
+ $.entries[25].contentVersion: "1a53f6ac66d7a90847f8fc602da6113b4e4011b3"
- $.entries[25].uri: "archiveQuests/Halloween2023.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "1e181ef15456cd2d7365430e6a10805da93a4e04"
+ $.entries[26].contentVersion: "3c508b1e5c472402c742a24f45598eb04ee53bbc"
- $.entries[26].uri: "archiveQuests/Halloween2024.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "a362e2dc91965ba6c44c49cdaebac40ca88214b4"
+ $.entries[27].contentVersion: "71d36cc34c08f37d6025d47867419be11ab8457a"
- $.entries[27].uri: "archiveQuests/Spring2024.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "30b252650a511f485554eb5e67b17aea7dbfef26"
+ $.entries[28].contentVersion: "113c61c02c94df30863c1d1e950667592e7fd3f9"
- $.entries[28].uri: "archiveQuests/Spring2025.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "adab2d09b46d816bc7e799c9c630c7a5ebfa08ba"
+ $.entries[29].contentVersion: "1889ae6bcaa7d2e64f13dc16d26998a04ef57180"
- $.entries[29].uri: "archiveQuests/Summer2023.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "b37423fb4e1b4e8acf9b8fe07224f0c038e96cff"
+ $.entries[30].contentVersion: "46a11887e67b717e5c69d541d3146492f42e6fb0"
- $.entries[30].uri: "archiveQuests/Tome01.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
- $.entries[31].contentVersion: "60d7af5b70c58eac3b28cc14dbc25328d2b847b0"
+ $.entries[31].contentVersion: "9c2b9cd73b5699250400e4266f6aee81df7f7974"
- $.entries[31].uri: "archiveQuests/Tome02.json"
+ $.entries[31].uri: "archiveQuests/Tome07.json"
- $.entries[32].contentVersion: "3fb24f03ef3244a27f7aa961c96c2b55edd1ec3f"
+ $.entries[32].contentVersion: "28579a3d46d6c5787869b036b5c8938f46959560"
- $.entries[32].uri: "archiveQuests/Tome03.json"
+ $.entries[32].uri: "archiveQuests/Tome08.json"
- $.entries[33].contentVersion: "640a22d59c6f914dc04d116de6272409a953b004"
+ $.entries[33].contentVersion: "3bb463544d259a291ef2473fd6c09b9a2a36b408"
- $.entries[33].uri: "archiveQuests/Tome04.json"
+ $.entries[33].uri: "archiveQuests/Tome09.json"
- $.entries[34].contentVersion: "11f1b9c5ed4aa0bc45ea73ae6ca39a350fd6eacd"
+ $.entries[34].contentVersion: "66cfa45818464e4c6f93d6ed662e0766dee24580"
- $.entries[34].uri: "archiveQuests/Tome05.json"
+ $.entries[34].uri: "archiveQuests/Tome10.json"
- $.entries[35].contentVersion: "5b2531dd0791c4dcac0e21db1cb57dbb78cc4f2b"
+ $.entries[35].contentVersion: "94b3c3f29541c06754b383226687586469a20163"
- $.entries[35].uri: "archiveQuests/Tome06.json"
+ $.entries[35].uri: "archiveQuests/Tome11.json"
- $.entries[36].contentVersion: "843f5036329ee37e87906e3091ca04e164663d7d"
+ $.entries[36].contentVersion: "446484c6629dc0a50536ed4eacbee5e204f0f018"
- $.entries[36].uri: "archiveQuests/Tome07.json"
+ $.entries[36].uri: "archiveQuests/Tome12.json"
- $.entries[37].contentVersion: "b5a1060f76982c8fb38f1e9fd12a0e6480e90293"
+ $.entries[37].contentVersion: "8302f3decedff72bca3bcd48f193b6f79b24debc"
- $.entries[37].uri: "archiveQuests/Tome08.json"
+ $.entries[37].uri: "archiveQuests/Tome13.json"
… 723 more change(s) — see the commit diff for everything
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2025-11-03T16:00:00"
+ $.event.end: "2026-02-02T18:00:00"
- $.event.start: "2025-10-30T15:00:00"
+ $.event.start: "2026-01-29T18:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2025-11-03T16:00:00"
+ $.event.end: "2026-02-02T18:00:00"
- $.event.start: "2025-10-30T15:00:00"
+ $.event.start: "2026-01-29T18:00:00"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Omelet_W6]
- $.featuredCard[id=Omelet_W5].activeTo: "2026-01-27T16:00:00"
+ $.featuredCard[id=Omelet_W5].activeTo: "2026-01-23T16:00:00"
- $.featuredCard[id=PoutineW2].entries[1].entryId: "Rift_4_Bundle"
+ $.featuredCard[id=PoutineW2].entries[1].entryId: "ModernTales"
- $.featuredCard[id=PoutineW2].entries[1].type: "SpecialPack"
+ $.featuredCard[id=PoutineW2].entries[1].type: "Collection"
- $.featuredCard[id=PoutineW2].entries[2].entryId: "StrangerThings"
+ $.featuredCard[id=PoutineW2].entries[2].entryId: "Rift_4_Bundle"
- $.featuredCard[id=PoutineW2].entries[2].type: "Collection"
+ $.featuredCard[id=PoutineW2].entries[2].type: "SpecialPack"
- $.featuredCard[id=PoutineW2].entries[3].entryId: "TorturedSouls"
+ $.featuredCard[id=PoutineW2].entries[3].entryId: "StrangerThings"
- $.featuredCustomizationRecommendations[id=Poutine_W2].recommendations[id=MK_outfit_020].weight: 351
+ $.featuredCustomizationRecommendations[id=Poutine_W2].recommendations[id=MK_outfit_020].weight: 352
- $.featuredCustomizationRecommendations[id=Poutine_W3].recommendations[id=MK_outfit_020].weight: 351
+ $.featuredCustomizationRecommendations[id=Poutine_W3].recommendations[id=MK_outfit_020].weight: 352
+ $.specialsRecommendations[id=SilentHillSale]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[61].mainEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].mainEndTime: "2026-01-27T16:00:00"
- $.specialEvents[61].postEndTime: "2026-01-27T14:00:00"
+ $.specialEvents[61].postEndTime: "2026-01-27T16:00:00"
- $.specialEvents[64].mainEndTime: "2026-02-24T16:00:00"
+ $.specialEvents[64].mainEndTime: "2026-03-01T16:00:00"
- $.specialEvents[64].postEndTime: "2026-02-24T16:00:00"
+ $.specialEvents[64].postEndTime: "2026-03-01T16:00:00"
- $.specialEvents[64].startTime: "2026-02-12T16:00:00"
+ $.specialEvents[64].startTime: "2026-02-15T16:00:00"
```

