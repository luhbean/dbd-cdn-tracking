# live · 9.4.1_3072485live

| | |
|---|---|
| Build date | 2026-02-03 18:49 UTC |
| CDN version | `9.4.1_3072485live-1770144581` |
| Key | `9.4.1_live` |
| Compared with | [9.4.0_3072078live](../9.4.0_3072078live/CHANGES.md) (2026-02-03 15:35 UTC) |

## Summary

**0** added · **21** modified · **6** removed · 188 unchanged

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
+ $[id=SUS_017]
+ $[id=SilentHill_Omelet_Bundle]
- $[id=S22_outfit_02].metaData.temporaryDiscounts
- $[id=S22_outfit_02_01].metaData.temporaryDiscounts
- $[id=TorturedSoulsBundle].metaData.sortOrder: 600
+ $[id=TorturedSoulsBundle].metaData.sortOrder: 1100
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[46].text: "Spiele {0} Prüfung(en) als {1}."
+ $.locText[46].text: "Schließe {0} Prüfung(en) als {1} ab."
- $.locText[47].text: "Spiele als {1} in {0} Prüfung(en)."
+ $.locText[47].text: "Schließe {0} Prüfung(en) als {1} ab."
- $.locText[538].text: "Enthülle einen Killer für {0} Sekunden."
+ $.locText[538].text: "Enthülle die Aura des Killers für {0} Sekunden."
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[46].text: "Juega como {1} durante {0} partida(s)."
+ $.locText[46].text: "Como {1}, completa {0} partida(s)."
- $.locText[47].text: "En {0} partida(s), juega como {1}."
+ $.locText[47].text: "Como {1}, completa {0} partida(s)."
- $.locText[538].text: "Revela a un asesino durante {0} segundos."
+ $.locText[538].text: "Revela el aura del asesino durante {0} segundos."
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[46].text: "Juega como {1} durante {0} partida(s)."
+ $.locText[46].text: "Completa {0} partida(s) con {1}."
- $.locText[47].text: "Juega como {1} en {0} partida(s)."
+ $.locText[47].text: "Completa {0} partida(s) con {1}."
- $.locText[538].text: "Revela a un asesino durante {0} segundos."
+ $.locText[538].text: "Revela el aura del asesino durante {0} segundos."
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[46].text: "Gioca nei panni di {1} per {0} prova/e"
+ $.locText[46].text: "Completa {0} prova/e con {1}"
- $.locText[47].text: "Gioca nei panni di {1} in {0} prova/e."
+ $.locText[47].text: "Completa {0} prova/e con {1}"
- $.locText[538].text: "Rivela un killer per {0} secondi"
+ $.locText[538].text: "Rivela l'aura del killer per {0} secondi"
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[46].text: "희생제 {0}회 동안 {1}(으)로 플레이하기"
+ $.locText[46].text: "{1}(으)로 희생제 {0}회 완료하기"
- $.locText[47].text: "{0} 희생제에서 {1}(으)로 플레이하기."
+ $.locText[47].text: "{1}(으)로 희생제 {0}회 완료하기"
- $.locText[538].text: "{0}초 동안 살인마 드러내기"
+ $.locText[538].text: "{0}초 동안 살인마의 오라 드러내기."
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[46].text: "Graj jako {1} przez tyle prób: {0}"
+ $.locText[46].text: "Ukończ tyle prób jako {1}: {0}"
- $.locText[47].text: "Zagraj jako {1} w tylu próbach: {0}."
+ $.locText[47].text: "Ukończ tyle prób jako {1}: {0}"
- $.locText[538].text: "Ujawnij zabójcę na {0} s."
+ $.locText[538].text: "Odkryj aurę zabójcy na {0} s."
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[46].text: "Jogue como {1} por {0} partida(s)"
+ $.locText[46].text: "Complete {0} partida(s) como {1}"
- $.locText[47].text: "Jogue como {1} em {0} partida(s)."
+ $.locText[47].text: "Complete {0} partida(s) como {1}"
- $.locText[538].text: "Revele um Assassino por {0} s"
+ $.locText[538].text: "Revela a aura do Assassino por {0} s"
- $.locText[546].text: "Parque de Diversões da Névoa"
+ $.locText[546].text: "CarnaNévoa"
- $.locText[547].text: "Parque de Diversões da Névoa"
+ $.locText[547].text: "CarnaNévoa"
- $.locText[554].text: "Missões da Comunidade de Parque de Diversões da Névoa"
+ $.locText[554].text: "Missões do CarnaNévoa"
- $.locText[555].text: "Parque de Diversões da Névoa - Parte 1"
+ $.locText[555].text: "CarnaNévoa - Parte 1"
- $.locText[556].text: "Parque de Diversões da Névoa - Parte 2"
+ $.locText[556].text: "CarnaNévoa - Parte 2"
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[46].text: "Сыграйте как {1} {0} р."
+ $.locText[46].text: "Завершите матч {0} раз(а), играя за персонажа по имени {1}"
- $.locText[47].text: "Сыграйте за персонажа {1} {0} раз(а)."
+ $.locText[47].text: "Завершите матч {0} раз(а), играя за персонажа по имени {1}"
- $.locText[538].text: "Показать убийцу на {0} сек."
+ $.locText[538].text: "Показывает ауру убийцы в течение {0} сек."
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[46].text: "เล่นเป็น{1} {0} เกม"
+ $.locText[46].text: "จบ {0} เกมโดยเล่นเป็น{1}"
- $.locText[47].text: "เล่นเป็น{1}ใน {0} เกม"
+ $.locText[47].text: "จบ {0} เกมโดยเล่นเป็น{1}"
- $.locText[538].text: "เผยตัวฆาตกรนาน {0} วินาที"
+ $.locText[538].text: "เผยออร่าของฆาตกรนาน {0} วินาที"
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[46].text: "{0} Mücadele boyunca {1} olarak oyna"
+ $.locText[46].text: "{1} olarak {0} mücadele tamamla"
- $.locText[47].text: "{1} olarak {0} mücadele oyna"
+ $.locText[47].text: "{1} olarak {0} mücadele tamamla"
- $.locText[538].text: "{0} saniye boyunca bir Katil'i açığa çıkar"
+ $.locText[538].text: "Katil'in Haresini {0} saniye açığa çıkar"
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[46].text: "在{0}場遊戲中扮演{1}"
+ $.locText[46].text: "扮演{1}完成{0}場審判"
- $.locText[47].text: "扮演{1}進行{0}場遊戲。"
+ $.locText[47].text: "扮演{1}完成{0}場審判"
- $.locText[538].text: "顯示殺手{0}秒"
+ $.locText[538].text: "暴露殺手的氣場，持續{0}秒。"
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
- $.FogCarnival.titleLocalizationText["pt-BR"]: "Parque de Diversões da Névoa"
+ $.FogCarnival.titleLocalizationText["pt-BR"]: "CarnaNévoa"
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
+ $.entries[4].contentVersion: "9660e790cc7986b8420a210087fb79f3d4de30fc"
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
- $.entries[7].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
+ $.entries[7].contentVersion: "9a3480f6b6a4ac884b60d841509796280849c249"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_SpecialPack_ModernTales.png"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "f8b2414afc2858c35fed794667b3ba6f27a3e7a0"
+ $.entries[8].contentVersion: "bc006d92d29a5e6328e91285b11aa54a0e0c411f"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_StrangerThings_Chapter2.T_UI_CollectionBanner_StrangerThings_Chapter2"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_CollectionBanner_StrangerThings_Chapter2.png"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "12010aea83ad4e1ee56c50df0da8cd85a85498a2"
+ $.entries[9].contentVersion: "ab5e8b9e9ca68f4f8059f1b14449269d0ffeadb8"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/Poutine/T_UI_SpecialPack_StrangerThings_Chapter2.T_UI_SpecialPack_StrangerThings_Chapter2"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_SpecialPack_StrangerThings_Chapter2.png"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "d583fe7c38336b067d7db87629f7c532a0bd9b5f"
+ $.entries[10].contentVersion: "7a0b19c453ff0736b3dbf7ba57fa907f66134ece"
- $.entries[10].uri: "catalog.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "0688a6020b52e6bd9500b266ac4b4b6baa60860d"
+ $.entries[11].contentVersion: "d27cd9bc810294e4fa260a00a26d9262c3df3b2f"
- $.entries[11].uri: "bonusPointEventsContent.json"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[12].contentVersion: "fe44212cf941925219bc4dc5d3a882350924d26a"
- $.entries[12].uri: "freetoplay/NA/event.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "96087f3be3dde6dff67ed65bd856a3b504dc68de"
+ $.entries[13].contentVersion: "19ca4e16bcba6dd47a5cee03b8333bcf8b343ad2"
- $.entries[13].uri: "freetoplay/EU/event.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "dd527570e43d5227bc28afe72fb1f78e53ac6822"
+ $.entries[14].contentVersion: "76f1017394843b2d22851a5a6f9985c962a416d8"
- $.entries[14].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[15].contentVersion: "52fc655e6b41b211e455230a518f9846c8b5286a"
+ $.entries[15].contentVersion: "2fadd29ada397df69c995d89af3cb33c813b37a1"
- $.entries[15].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[16].contentVersion: "946926ad6e5fc8348d1f1132ac7b59cc676cff14"
+ $.entries[16].contentVersion: "ccdb1cf13b148d29fc66281c13aaf1543013b320"
- $.entries[16].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[17].contentVersion: "44a5c8ea54340fdfc9b01597243b454a8622e029"
+ $.entries[17].contentVersion: "7c6a8bf71078b820849b4630b11b29fb5f8791b8"
- $.entries[17].uri: "archiveQuests/CalamariV1.json"
+ $.entries[17].uri: "archiveQuests/FireflyV1.json"
- $.entries[18].contentVersion: "671675edb2bebab5f35c2e4b6b8e5fa78882ee92"
+ $.entries[18].contentVersion: "e7f9a9518d965a55b41ffca9e1cb2b3e107f4fbf"
- $.entries[18].uri: "archiveQuests/CalamariV2.json"
+ $.entries[18].uri: "archiveQuests/Halloween2021.json"
- $.entries[19].contentVersion: "c36008b30af60617d7038322e37ad3f3cd2754e5"
+ $.entries[19].contentVersion: "46204ae471ea73fd72d29cea51d914f10df01e9a"
- $.entries[19].uri: "archiveQuests/CalamariV3.json"
+ $.entries[19].uri: "archiveQuests/Halloween2022.json"
- $.entries[20].contentVersion: "680a0cf92894220d6b78184aef473d2da4c76013"
+ $.entries[20].contentVersion: "2257b9f00eb53b5dbf54eda8bb4b5805dc94bb1b"
- $.entries[20].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[20].uri: "archiveQuests/Halloween2023.json"
- $.entries[21].contentVersion: "eae70968d8423a3a0f61227e8b7da194f8856be1"
+ $.entries[21].contentVersion: "20013d8c29cdcc7f2abf90fe9db21811871df20e"
- $.entries[21].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[21].uri: "archiveQuests/Halloween2024.json"
- $.entries[22].contentVersion: "5210f96a51547ac1be938e0651440a5c5569ef3a"
+ $.entries[22].contentVersion: "67d4205d65da1a7ddcb442abe12b9ab56dc1f011"
- $.entries[22].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[22].uri: "archiveQuests/Spring2024.json"
- $.entries[23].contentVersion: "3de6169053b9db24bf1f8464a61002e16a417945"
+ $.entries[23].contentVersion: "02f1ba95f160a443d3d2134179f481519054eb01"
- $.entries[23].uri: "archiveQuests/FireflyV1.json"
+ $.entries[23].uri: "archiveQuests/Spring2025.json"
- $.entries[24].contentVersion: "69fe782985a5376bac4f588fac10e1f567cbeca4"
+ $.entries[24].contentVersion: "95528a855f0f57c424f8649b32daf3cba921b1a7"
- $.entries[24].uri: "archiveQuests/Halloween2021.json"
+ $.entries[24].uri: "archiveQuests/Summer2023.json"
- $.entries[25].contentVersion: "3b38b442968cdb458f8afd787c8e688df454f3ff"
+ $.entries[25].contentVersion: "1a53f6ac66d7a90847f8fc602da6113b4e4011b3"
- $.entries[25].uri: "archiveQuests/Halloween2022.json"
+ $.entries[25].uri: "archiveQuests/Tome01.json"
- $.entries[26].contentVersion: "0349ede198538537ff43da647cb4a6f17d238593"
+ $.entries[26].contentVersion: "3c508b1e5c472402c742a24f45598eb04ee53bbc"
- $.entries[26].uri: "archiveQuests/Halloween2023.json"
+ $.entries[26].uri: "archiveQuests/Tome02.json"
- $.entries[27].contentVersion: "1e181ef15456cd2d7365430e6a10805da93a4e04"
+ $.entries[27].contentVersion: "71d36cc34c08f37d6025d47867419be11ab8457a"
- $.entries[27].uri: "archiveQuests/Halloween2024.json"
+ $.entries[27].uri: "archiveQuests/Tome03.json"
- $.entries[28].contentVersion: "a362e2dc91965ba6c44c49cdaebac40ca88214b4"
+ $.entries[28].contentVersion: "113c61c02c94df30863c1d1e950667592e7fd3f9"
- $.entries[28].uri: "archiveQuests/Spring2024.json"
+ $.entries[28].uri: "archiveQuests/Tome04.json"
- $.entries[29].contentVersion: "30b252650a511f485554eb5e67b17aea7dbfef26"
+ $.entries[29].contentVersion: "1889ae6bcaa7d2e64f13dc16d26998a04ef57180"
- $.entries[29].uri: "archiveQuests/Spring2025.json"
+ $.entries[29].uri: "archiveQuests/Tome05.json"
- $.entries[30].contentVersion: "adab2d09b46d816bc7e799c9c630c7a5ebfa08ba"
+ $.entries[30].contentVersion: "46a11887e67b717e5c69d541d3146492f42e6fb0"
- $.entries[30].uri: "archiveQuests/Summer2023.json"
+ $.entries[30].uri: "archiveQuests/Tome06.json"
- $.entries[31].contentVersion: "b37423fb4e1b4e8acf9b8fe07224f0c038e96cff"
+ $.entries[31].contentVersion: "9c2b9cd73b5699250400e4266f6aee81df7f7974"
- $.entries[31].uri: "archiveQuests/Tome01.json"
+ $.entries[31].uri: "archiveQuests/Tome07.json"
- $.entries[32].contentVersion: "60d7af5b70c58eac3b28cc14dbc25328d2b847b0"
+ $.entries[32].contentVersion: "28579a3d46d6c5787869b036b5c8938f46959560"
- $.entries[32].uri: "archiveQuests/Tome02.json"
+ $.entries[32].uri: "archiveQuests/Tome08.json"
- $.entries[33].contentVersion: "3fb24f03ef3244a27f7aa961c96c2b55edd1ec3f"
+ $.entries[33].contentVersion: "3bb463544d259a291ef2473fd6c09b9a2a36b408"
- $.entries[33].uri: "archiveQuests/Tome03.json"
+ $.entries[33].uri: "archiveQuests/Tome09.json"
- $.entries[34].contentVersion: "640a22d59c6f914dc04d116de6272409a953b004"
+ $.entries[34].contentVersion: "66cfa45818464e4c6f93d6ed662e0766dee24580"
- $.entries[34].uri: "archiveQuests/Tome04.json"
+ $.entries[34].uri: "archiveQuests/Tome10.json"
- $.entries[35].contentVersion: "11f1b9c5ed4aa0bc45ea73ae6ca39a350fd6eacd"
+ $.entries[35].contentVersion: "94b3c3f29541c06754b383226687586469a20163"
- $.entries[35].uri: "archiveQuests/Tome05.json"
+ $.entries[35].uri: "archiveQuests/Tome11.json"
- $.entries[36].contentVersion: "5b2531dd0791c4dcac0e21db1cb57dbb78cc4f2b"
+ $.entries[36].contentVersion: "446484c6629dc0a50536ed4eacbee5e204f0f018"
… 736 more change(s) — see the commit diff for everything
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

