# live · 9.3.0_2880935live

| | |
|---|---|
| Build date | 2025-11-24 17:26 UTC |
| CDN version | `9.3.0_2880935live-1764005162` |
| Key | `9.3.0_live` |
| Compared with | [9.3.0_2879176live](../9.3.0_2879176live/CHANGES.md) (2025-11-21 17:45 UTC) |

## Summary

**0** added · **8** modified · **0** removed · 197 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.analyticsRules.DD
- $.analyticsRules.BL[]: "AtlantaControlsSettingsAnalytics"
- $.analyticsRules.BL[]: "af_complete_registrationAnalytics"
- $.analyticsRules.BL[]: "af_killer_tutorial_completionAnalytics"
- $.analyticsRules.BL[]: "af_loginAnalytics"
- $.analyticsRules.BL[]: "af_survivor_tutorial_completionAnalytics"
+ $.analyticsRules.BL[]: "CheatExecutedAnalytics"
+ $.analyticsRules.BL[]: "CrowdChoiceOnGameRoundStartedAnalytics"
+ $.analyticsRules.BL[]: "CrowdChoiceSummaryResultAnalytics"
+ $.analyticsRules.BL[]: "CrowdChoiceVoteResultAnalytics"
+ $.analyticsRules.BL[]: "CrowdPlayLobbyEventsAnalytics"
+ $.analyticsRules.BL[]: "CrowdPlayLobbyResultsAnalytics"
+ $.analyticsRules.BL[]: "DailyCalendarRewardAnalytics"
+ $.analyticsRules.BL[]: "FrameTravelTimeAnalytics"
+ $.analyticsRules.BL[]: "GPUAnalytics"
+ $.analyticsRules.BL[]: "Gameplay_PigKillerAnalytics"
+ $.analyticsRules.BL[]: "Gameplay_PigSurvivorAnalytics"
+ $.analyticsRules.BL[]: "LegionKillerAnalytics"
+ $.analyticsRules.BL[]: "LegionSurvivorAnalytics"
+ $.analyticsRules.BL[]: "MatchmakingIncentiveAnalytics"
+ $.analyticsRules.BL[]: "StatsSystemUE4Analytics"
+ $.analyticsRules.BL[]: "TexturegroupChartingAnalytics"
+ $.analyticsRules.BL[]: "apps_flyer_acquisition"
+ $.analyticsRules.BL[]: "at_environment"
+ $.analyticsRules.BL[]: "at_performance"
+ $.analyticsRules.BL[]: "at_performancecharting"
+ $.analyticsRules.BL[]: "at_texturegroupcharting"
+ $.analyticsRules.BL[]: "challenge_system"
- $.analyticsRules.KA[]: "AtlantaCampaignEventAnalytics"
- $.analyticsRules.KA[]: "CrowdChoiceOnGameRoundStartedAnalytics"
- $.analyticsRules.KA[]: "CrowdChoiceSummaryResultAnalytics"
- $.analyticsRules.KA[]: "CrowdChoiceVoteResultAnalytics"
- $.analyticsRules.KA[]: "CrowdPlayLobbyEventsAnalytics"
- $.analyticsRules.KA[]: "CrowdPlayLobbyResultsAnalytics"
- $.analyticsRules.KA[]: "Gameplay_PigKillerAnalytics"
- $.analyticsRules.KA[]: "Gameplay_PigSurvivorAnalytics"
- $.analyticsRules.KA[]: "LegionKillerAnalytics"
- $.analyticsRules.KA[]: "LegionSurvivorAnalytics"
- $.analyticsRules.KA[]: "StadiaLivestreamAnalytics"
- $.analyticsRules.KA[]: "StadiaStreamAnalytics"
- $.analyticsRules.KAL[]: "AtlantaActivablePerkAnalytics"
- $.analyticsRules.KAL[]: "CheatExecutedAnalytics"
- $.analyticsRules.KAL[]: "CheatValidatedAnalytics"
- $.analyticsRules.KAL[]: "GPUAnalytics"
- $.analyticsRules.KAL[]: "GameInitAnalytics"
- $.analyticsRules.KL[]: "FrameTravelTimeAnalytics"
- $.analyticsRules.KL[]: "TexturegroupChartingAnalytics"
+ $.analyticsRules.KL[]: "CheatValidatedAnalytics"
+ $.analyticsRules.KL[]: "GameInitAnalytics"
+ $.cinematic.enablePostIISCinematic: true
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.enableLogForQuestEventIds
- $.analyticsRulesDedicatedServer.KAL[]: "CheatExecutedAnalytics"
- $.analyticsRulesDedicatedServer.KAL[]: "CheatValidatedAnalytics"
- $.analyticsRulesDedicatedServer.KAL[]: "GPUAnalytics"
+ $.analyticsRulesDedicatedServer.KL[]: "CheatExecutedAnalytics"
+ $.analyticsRulesDedicatedServer.KL[]: "CheatValidatedAnalytics"
+ $.analyticsRulesDedicatedServer.KL[]: "GPUAnalytics"
- $.mapHistoryWeights.1: 0.25
+ $.mapHistoryWeights.1: 0.0001
- $.mapHistoryWeights.2: 0.5
+ $.mapHistoryWeights.2: 0.0001
- $.mapHistoryWeights.3: 0.75
+ $.mapHistoryWeights.3: 0.0001
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=StarrySweaterBundle2025_0]
+ $[id=StarrySweaterBundle2025]
- $[id=BoneChillBundle2025].metaData.sortOrder: 800
+ $[id=BoneChillBundle2025].metaData.sortOrder: 3005
- $[id=DeckTheTrials2025].metaData.sortOrder: 800
+ $[id=DeckTheTrials2025].metaData.sortOrder: 3006
- $[id=DeckTheTrials2025].metaData.startDate: "2024-12-10T16:00:00"
+ $[id=DeckTheTrials2025].metaData.startDate: "2025-12-11T16:00:00"
- $[id=IcyWeaponBundle2025].metaData.sortOrder: 800
+ $[id=IcyWeaponBundle2025].metaData.sortOrder: 3004
+ $[id=UglySweaterBundle2025].metaData.endDate: "2026-01-06T16:00:00"
+ $[id=UglySweaterBundle2025].metaData.startDate: "2025-12-01T16:00:00"
- $[id=UglySweaterBundle2025].metaData.sortOrder: 800
+ $[id=UglySweaterBundle2025].metaData.sortOrder: 3000
- $[id=WinterTalesBundle2025].metaData.sortOrder: 800
+ $[id=WinterTalesBundle2025].metaData.sortOrder: 3007
- $[id=WinterTalesBundle2025].metaData.startDate: "2024-12-19T16:00:00"
+ $[id=WinterTalesBundle2025].metaData.startDate: "2025-12-19T16:00:00"
- $[id=From_The_Rift_Bundle_250930].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_250930].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251007].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251007].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251014].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251014].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251021].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251021].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251028].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251028].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251104].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251104].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251111].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251111].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251118].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251118].metaData.imageComposition.maxItemCount: 2
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Head008_01].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Head008_01].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Torso010_01].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Torso010_01].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Legs014_01].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Legs014_01].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Head013].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Head013].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Torso013].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Torso013].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Legs013].gameSpecificData.hasPriorityForPackImageComposition: false
+ $[id=From_The_Rift_Bundle_251125].consumptionReward[id=NK_Legs013].gameSpecificData.hasPriorityForPackImageComposition: true
- $[id=From_The_Rift_Bundle_251125].metaData.imageComposition.maxItemCount: 1
+ $[id=From_The_Rift_Bundle_251125].metaData.imageComposition.maxItemCount: 2
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[38].additionalImages[0]
- $.collections[38].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_UglySweaters2025.T_UI_CollectionBanner_UglySweaters2025"
+ $.collections[38].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Gelato/T_UI_CollectionBanner_UglySweaters.T_UI_CollectionBanner_UglySweaters"
+ $.collections[39].additionalImages[0]
- $.collections[39].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_HolidayHorror_GhostFace.T_UI_CollectionBanner_HolidayHorror_GhostFace"
+ $.collections[39].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Gelato/T_UI_CollectionBanner_HolidayHorror.T_UI_CollectionBanner_HolidayHorror"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
+ $.schedule[6]
+ $.schedule[7]
+ $.schedule[8]
+ $.schedule[9]
+ $.schedule[10]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[4].contentVersion: "0482fc197a35cc13cbfcbd73b273aff951a3e86d"
+ $.entries[4].contentVersion: "2403e6a96d01b6a837a9ca6dbd4fcc72423ae404"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_HolidayHorror_GhostFace.T_UI_CollectionBanner_HolidayHorror_GhostFace"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_HolidayHorror_GhostFace.T_UI_SpecialPack_HolidayHorror_GhostFace"
- $.entries[4].uri: "images/T_UI_CollectionBanner_HolidayHorror_GhostFace.png"
+ $.entries[4].uri: "images/T_UI_SpecialPack_HolidayHorror_GhostFace.png"
- $.entries[8].contentVersion: "dd38a8e21b4cbbf625698ee7e1b9f8f672c13a6a"
+ $.entries[8].contentVersion: "faf1dcbc557a2c576691ca028a80046270faf2cd"
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Omelet/T_UI_CollectionBanner_UglySweaters2025.T_UI_CollectionBanner_UglySweaters2025"
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Omelet/T_UI_SpecialPack_UglySweaters2025.T_UI_SpecialPack_UglySweaters2025"
- $.entries[8].uri: "images/T_UI_CollectionBanner_UglySweaters2025.png"
+ $.entries[8].uri: "images/T_UI_SpecialPack_UglySweaters2025.png"
- $.entries[9].contentVersion: "ee402e0725e468f334d76df2e7ea72b09bc8f7a4"
+ $.entries[9].contentVersion: "9fb0095074c967325b52bb129061d3424c9d154d"
- $.entries[85].contentVersion: "df414aa9a16f5a805e292145de9825aa170603ae"
+ $.entries[85].contentVersion: "90c6605613899b4b1d98149abdc4f8f1bee57d26"
- $.entries[169].contentVersion: "74c9206214c243e1b8d971d992474c188ec56603"
+ $.entries[169].contentVersion: "c3adc09d514a3da39ab4b14443a57e4240b11f8a"
- $.entries[177].contentVersion: "ff58fb35fa7b5b5f8f39581a68558f6ac4240ea3"
+ $.entries[177].contentVersion: "7205d4fb288b603cccdb19dd6aa3259542b7cdec"
- $.entries[180].contentVersion: "8162bed858cbf63c315c02fdca4ef16285e574af"
+ $.entries[180].contentVersion: "9c718bcca9bb214d42540a4a7519c0adc5f1cbf4"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=Omelet_W2]
+ $.featuredCard[id=Omelet_W3]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[61].eventName.de: "Visuelles Update für Autohaven"
+ $.specialEvents[61].eventName.de: "Sprithimmel"
- $.specialEvents[61].eventName.en: "Autohaven Visual Update"
+ $.specialEvents[61].eventName.en: "Gas Heaven"
- $.specialEvents[61].eventName.es: "Mejora visual de Autohaven"
+ $.specialEvents[61].eventName.es: "Gasolinera"
- $.specialEvents[61].eventName["es-MX"]: "Actualización visual de Autohaven"
+ $.specialEvents[61].eventName["es-MX"]: "Gasolinera"
- $.specialEvents[61].eventName.fr: "Mise à jour visuelle de Autohaven"
+ $.specialEvents[61].eventName.fr: "Gas Heaven"
- $.specialEvents[61].eventName.it: "Aggiornamento grafico Autohaven"
+ $.specialEvents[61].eventName.it: "Gas Heaven"
- $.specialEvents[61].eventName.ja: "オートヘイヴンのビジュアル更新"
+ $.specialEvents[61].eventName.ja: "ガス・ヘヴン"
- $.specialEvents[61].eventName.ko: "오토헤이븐 시각 효과 업데이트"
+ $.specialEvents[61].eventName.ko: "가스 헤븐"
- $.specialEvents[61].eventName.pl: "Aktualizacja wizualna Autohaven"
+ $.specialEvents[61].eventName.pl: "Stacja Paliw"
- $.specialEvents[61].eventName["pt-BR"]: "Atualização Visual de Autohaven"
+ $.specialEvents[61].eventName["pt-BR"]: "Paraíso do Combustível"
- $.specialEvents[61].eventName.ru: "Визуальное обновление Автохевена"
+ $.specialEvents[61].eventName.ru: "Гэс Хевен"
- $.specialEvents[61].eventName.th: "ปรับปรุงภาพของออโต้ฮาเว่น"
+ $.specialEvents[61].eventName.th: "ร้านแก๊สเฮเว่น"
- $.specialEvents[61].eventName.tr: "Otomobil Mezarlığı Görsel Güncellemesi"
+ $.specialEvents[61].eventName.tr: "Benzin İstasyonu"
- $.specialEvents[61].eventName["zh-Hans"]: "奥托海文视觉更新"
+ $.specialEvents[61].eventName["zh-Hans"]: "汽油天堂"
- $.specialEvents[61].eventName["zh-Hant"]: "汽油天堂視覺更新"
+ $.specialEvents[61].eventName["zh-Hant"]: "廢棄加油站"
- $.specialEvents[61].mainEndTime: "2025-11-05T15:59:00"
+ $.specialEvents[61].mainEndTime: "2025-11-26T15:59:00"
- $.specialEvents[61].postEndTime: "2025-11-05T15:59:00"
+ $.specialEvents[61].postEndTime: "2025-11-26T15:59:00"
- $.specialEvents[61].startTime: "2025-11-01T16:00:00"
+ $.specialEvents[61].startTime: "2025-11-25T16:00:00"
- $.specialEvents[62].eventName.de: "Visuelles Update für Autohaven"
+ $.specialEvents[62].eventName.de: "Azarovs Ruhestätte"
- $.specialEvents[62].eventName.en: "Autohaven Visual Update"
+ $.specialEvents[62].eventName.en: "Azarov's Resting Place"
- $.specialEvents[62].eventName.es: "Mejora visual de Autohaven"
+ $.specialEvents[62].eventName.es: "Lugar de descanso de Azarov"
- $.specialEvents[62].eventName["es-MX"]: "Actualización visual de Autohaven"
+ $.specialEvents[62].eventName["es-MX"]: "Lugar de descanso de Azarov"
- $.specialEvents[62].eventName.fr: "Mise à jour visuelle de Autohaven"
+ $.specialEvents[62].eventName.fr: "Dernière demeure d'Azarov"
- $.specialEvents[62].eventName.it: "Aggiornamento grafico Autohaven"
+ $.specialEvents[62].eventName.it: "Sepolcro di Azarov"
- $.specialEvents[62].eventName.ja: "オートヘイヴンのビジュアル更新"
+ $.specialEvents[62].eventName.ja: "アザロフの休憩所"
- $.specialEvents[62].eventName.ko: "오토헤이븐 시각 효과 업데이트"
+ $.specialEvents[62].eventName.ko: "아자로프의 휴게실"
- $.specialEvents[62].eventName.pl: "Aktualizacja wizualna Autohaven"
+ $.specialEvents[62].eventName.pl: "Miejsce Spoczynku Azarowa"
- $.specialEvents[62].eventName["pt-BR"]: "Atualização Visual de Autohaven"
+ $.specialEvents[62].eventName["pt-BR"]: "Sepultura de Azarov"
- $.specialEvents[62].eventName.ru: "Визуальное обновление Автохевена"
+ $.specialEvents[62].eventName.ru: "Место Упокоения Азарова"
- $.specialEvents[62].eventName.th: "ปรับปรุงภาพของออโต้ฮาเว่น"
+ $.specialEvents[62].eventName.th: "ที่พำนักของอาซารอฟ"
- $.specialEvents[62].eventName.tr: "Otomobil Mezarlığı Görsel Güncellemesi"
+ $.specialEvents[62].eventName.tr: "Azarov'un Yazıhanesi"
- $.specialEvents[62].eventName["zh-Hans"]: "奥托海文视觉更新"
+ $.specialEvents[62].eventName["zh-Hans"]: "阿扎罗夫长眠处"
- $.specialEvents[62].eventName["zh-Hant"]: "汽油天堂視覺更新"
+ $.specialEvents[62].eventName["zh-Hant"]: "阿扎羅夫長眠處"
- $.specialEvents[62].mainEndTime: "2025-11-06T15:59:00"
+ $.specialEvents[62].mainEndTime: "2025-11-27T15:59:00"
- $.specialEvents[62].postEndTime: "2025-11-06T15:59:00"
+ $.specialEvents[62].postEndTime: "2025-11-27T15:59:00"
- $.specialEvents[62].startTime: "2025-11-05T16:00:00"
+ $.specialEvents[62].startTime: "2025-11-26T16:00:00"
- $.specialEvents[63].eventName.de: "Visuelles Update für Autohaven"
+ $.specialEvents[63].eventName.de: "Werkstatt"
- $.specialEvents[63].eventName.en: "Autohaven Visual Update"
+ $.specialEvents[63].eventName.en: "Wretched Shop"
- $.specialEvents[63].eventName.es: "Mejora visual de Autohaven"
+ $.specialEvents[63].eventName.es: "Taller ruinoso"
- $.specialEvents[63].eventName["es-MX"]: "Actualización visual de Autohaven"
+ $.specialEvents[63].eventName["es-MX"]: "Taller ruinoso"
- $.specialEvents[63].eventName.fr: "Mise à jour visuelle de Autohaven"
+ $.specialEvents[63].eventName.fr: "Atelier misérable"
- $.specialEvents[63].eventName.it: "Aggiornamento grafico Autohaven"
+ $.specialEvents[63].eventName.it: "Negozio squallido"
- $.specialEvents[63].eventName.ja: "オートヘイヴンのビジュアル更新"
+ $.specialEvents[63].eventName.ja: "レッチド・ショップ"
- $.specialEvents[63].eventName.ko: "오토헤이븐 시각 효과 업데이트"
+ $.specialEvents[63].eventName.ko: "정비소"
- $.specialEvents[63].eventName.pl: "Aktualizacja wizualna Autohaven"
+ $.specialEvents[63].eventName.pl: "Sklep Nędzy"
- $.specialEvents[63].eventName["pt-BR"]: "Atualização Visual de Autohaven"
+ $.specialEvents[63].eventName["pt-BR"]: "Loja Desgraçada"
- $.specialEvents[63].eventName.ru: "Визуальное обновление Автохевена"
+ $.specialEvents[63].eventName.ru: "Магазин Барахольщика"
- $.specialEvents[63].eventName.th: "ปรับปรุงภาพของออโต้ฮาเว่น"
+ $.specialEvents[63].eventName.th: "ร้านค้าชั้นต่ำ"
- $.specialEvents[63].eventName.tr: "Otomobil Mezarlığı Görsel Güncellemesi"
+ $.specialEvents[63].eventName.tr: "Sefil Atölye"
- $.specialEvents[63].eventName["zh-Hans"]: "奥托海文视觉更新"
+ $.specialEvents[63].eventName["zh-Hans"]: "悲惨商店"
- $.specialEvents[63].eventName["zh-Hant"]: "汽油天堂視覺更新"
+ $.specialEvents[63].eventName["zh-Hant"]: "悲慘商店"
- $.specialEvents[63].mainEndTime: "2025-11-07T15:59:00"
+ $.specialEvents[63].mainEndTime: "2025-11-28T15:59:00"
- $.specialEvents[63].postEndTime: "2025-11-07T15:59:00"
+ $.specialEvents[63].postEndTime: "2025-11-28T15:59:00"
- $.specialEvents[63].startTime: "2025-11-06T16:00:00"
+ $.specialEvents[63].startTime: "2025-11-27T16:00:00"
- $.specialEvents[64].eventName.de: "Visuelles Update für Autohaven"
+ $.specialEvents[64].eventName.de: "Bluthütte"
- $.specialEvents[64].eventName.en: "Autohaven Visual Update"
+ $.specialEvents[64].eventName.en: "Blood Lodge"
- $.specialEvents[64].eventName.es: "Mejora visual de Autohaven"
+ $.specialEvents[64].eventName.es: "Cabaña de sangre"
- $.specialEvents[64].eventName["es-MX"]: "Actualización visual de Autohaven"
+ $.specialEvents[64].eventName["es-MX"]: "Cabaña de sangre"
- $.specialEvents[64].eventName.fr: "Mise à jour visuelle de Autohaven"
+ $.specialEvents[64].eventName.fr: "Cabane du sang"
- $.specialEvents[64].eventName.it: "Aggiornamento grafico Autohaven"
+ $.specialEvents[64].eventName.it: "Rifugio insanguinato"
- $.specialEvents[64].eventName.ja: "オートヘイヴンのビジュアル更新"
+ $.specialEvents[64].eventName.ja: "ブラッド・ロッジ"
- $.specialEvents[64].eventName.ko: "오토헤이븐 시각 효과 업데이트"
+ $.specialEvents[64].eventName.ko: "피의 오두막"
- $.specialEvents[64].eventName.pl: "Aktualizacja wizualna Autohaven"
+ $.specialEvents[64].eventName.pl: "Krwawa Stróżówka"
- $.specialEvents[64].eventName["pt-BR"]: "Atualização Visual de Autohaven"
+ $.specialEvents[64].eventName["pt-BR"]: "Abrigo Sangrento"
- $.specialEvents[64].eventName.ru: "Визуальное обновление Автохевена"
+ $.specialEvents[64].eventName.ru: "Кровавая Лачуга"
- $.specialEvents[64].eventName.th: "ปรับปรุงภาพของออโต้ฮาเว่น"
+ $.specialEvents[64].eventName.th: "กระท่อมโลหิต"
- $.specialEvents[64].eventName.tr: "Otomobil Mezarlığı Görsel Güncellemesi"
+ $.specialEvents[64].eventName.tr: "Kan Kulübesi"
- $.specialEvents[64].eventName["zh-Hans"]: "奥托海文视觉更新"
+ $.specialEvents[64].eventName["zh-Hans"]: "鲜血之屋"
- $.specialEvents[64].eventName["zh-Hant"]: "汽油天堂視覺更新"
+ $.specialEvents[64].eventName["zh-Hant"]: "血屋"
- $.specialEvents[64].mainEndTime: "2025-11-08T15:59:00"
+ $.specialEvents[64].mainEndTime: "2025-11-29T15:59:00"
- $.specialEvents[64].postEndTime: "2025-11-08T15:59:00"
+ $.specialEvents[64].postEndTime: "2025-11-29T15:59:00"
- $.specialEvents[64].startTime: "2025-11-07T16:00:00"
+ $.specialEvents[64].startTime: "2025-11-28T16:00:00"
- $.specialEvents[65].eventName.de: "Visuelles Update für Autohaven"
+ $.specialEvents[65].eventName.de: "Schrottplatz"
- $.specialEvents[65].eventName.en: "Autohaven Visual Update"
+ $.specialEvents[65].eventName.en: "Wreckers' Yard"
- $.specialEvents[65].eventName.es: "Mejora visual de Autohaven"
+ $.specialEvents[65].eventName.es: "Desguace"
- $.specialEvents[65].eventName["es-MX"]: "Actualización visual de Autohaven"
+ $.specialEvents[65].eventName["es-MX"]: "Desguace"
- $.specialEvents[65].eventName.fr: "Mise à jour visuelle de Autohaven"
+ $.specialEvents[65].eventName.fr: "Terrain de la casse"
- $.specialEvents[65].eventName.it: "Aggiornamento grafico Autohaven"
+ $.specialEvents[65].eventName.it: "Deposito Demolizioni"
- $.specialEvents[65].eventName.ja: "オートヘイヴンのビジュアル更新"
+ $.specialEvents[65].eventName.ja: "レッカーズ・ヤード"
- $.specialEvents[65].eventName.ko: "오토헤이븐 시각 효과 업데이트"
+ $.specialEvents[65].eventName.ko: "폐차장"
- $.specialEvents[65].eventName.pl: "Aktualizacja wizualna Autohaven"
+ $.specialEvents[65].eventName.pl: "Podwórze Złomowiska"
- $.specialEvents[65].eventName["pt-BR"]: "Atualização Visual de Autohaven"
+ $.specialEvents[65].eventName["pt-BR"]: "Quintal do Ferro-Velho"
- $.specialEvents[65].eventName.ru: "Визуальное обновление Автохевена"
+ $.specialEvents[65].eventName.ru: "Зона Свалки"
- $.specialEvents[65].eventName.th: "ปรับปรุงภาพของออโต้ฮาเว่น"
+ $.specialEvents[65].eventName.th: "ลานเก็บของเก่า"
- $.specialEvents[65].eventName.tr: "Otomobil Mezarlığı Görsel Güncellemesi"
+ $.specialEvents[65].eventName.tr: "Hurdacı Bahçesi"
- $.specialEvents[65].eventName["zh-Hans"]: "奥托海文视觉更新"
+ $.specialEvents[65].eventName["zh-Hans"]: "废车回收场"
- $.specialEvents[65].eventName["zh-Hant"]: "汽油天堂視覺更新"
+ $.specialEvents[65].eventName["zh-Hant"]: "廢舊車庫后院"
- $.specialEvents[65].mainEndTime: "2025-11-09T15:59:00"
+ $.specialEvents[65].mainEndTime: "2025-11-30T15:59:00"
- $.specialEvents[65].postEndTime: "2025-11-09T15:59:00"
+ $.specialEvents[65].postEndTime: "2025-11-30T15:59:00"
- $.specialEvents[65].startTime: "2025-11-08T16:00:00"
+ $.specialEvents[65].startTime: "2025-11-29T16:00:00"
- $.specialEvents[66]
- $.specialEventsData[33].lteData
- $.specialEventsData[33].eventId: "MapShowcase_PTB6"
+ $.specialEventsData[33].eventId: "Spring2024"
+ $.specialEventsData[33].eventTrackerObjectives[id=main]
+ $.specialEventsData[34].lteData
- $.specialEventsData[34].eventId: "Spring2024"
+ $.specialEventsData[34].eventId: "Spring2025"
- $.specialEventsData[34].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
- $.specialEventsData[34].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
+ $.specialEventsData[34].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
+ $.specialEventsData[34].eventTrackerObjectives[id=main].questEventConditions
+ $.specialEventsData[34].eventTrackerObjectives[id=main].questEvents
- $.specialEventsData[34].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
+ $.specialEventsData[34].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
- $.specialEventsData[34].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
+ $.specialEventsData[34].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
- $.specialEventsData[34].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
+ $.specialEventsData[34].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
- $.specialEventsData[34].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
… 58 more change(s) — see the commit diff for everything
```

## Could not download

- `images/T_UI_CollectionBanner_TWD_Rick.png (HTTP 404)`
- `images/T_UI_SpecialPack_HolidayHorror_GhostFace.png (HTTP 404)`
- `images/T_UI_SpecialPack_StrangerThings_Collection.png (HTTP 404)`
- `images/T_UI_SpecialPack_TWD_Rick.png (HTTP 404)`
- `images/T_UI_SpecialPack_UglySweaters2025.png (HTTP 404)`
- `images/T_UI_Specialpack_Bonechill2024.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_GenQuest1.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_cosmetic.png (HTTP 404)`
- `images/T_UI_Tutorial_ImageBG_gift.png (HTTP 404)`

