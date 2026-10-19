# live · 8.7.0_2443247live

| | |
|---|---|
| Build date | 2025-05-12 11:45 UTC |
| CDN version | `8.7.0_2443247live-1747050348` |
| Key | `8.7.0_live` |
| Compared with | [8.6.2_2430333live](../8.6.2_2430333live/CHANGES.md) (2025-05-02 14:46 UTC) |

## Summary

**18** added · **90** modified · **1** removed · 94 unchanged

## Added files

- [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)
- [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)
- [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)
- [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)
- [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)
- [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)
- [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)
- [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)
- [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)
- [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)
- [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)
- [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)
- [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)
- [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)
- [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)
- [`challengeRewardTrackers.json`](challengeRewardTrackers.json)
- [`challengeSets.json`](challengeSets.json)
- [`gameplayTunables.json`](gameplayTunables.json)

## Removed files

- `coreRituals.json`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.enableChallengeSystem: false
+ $.enableBattlePass: true
+ $.enableDeniedStateTransition: true
- $.analyticsRules.KA[]: "EmblemProgressionAnalytics"
+ $.analyticsRules.KAL[]: "BootStepAnalytics"
+ $.analyticsRules.KAL[]: "CrossfriendsAnalytics"
+ $.analyticsRules.KAL[]: "GameInitAnalytics"
+ $.analyticsRules.KAL[]: "LamentConfigurationPlayerPossessionAnalytics"
+ $.analyticsRules.KAL[]: "NewKillerTutorialAnalytics"
+ $.analyticsRules.KAL[]: "NewRiftPopupAnalytics"
+ $.analyticsRules.KAL[]: "NewSurvivorTutorialAnalytics"
+ $.analyticsRules.KAL[]: "PrestigeLevelUpAnalytics"
+ $.analyticsRules.KAL[]: "QuestNotificationAnalytics"
+ $.analyticsRules.KAL[]: "QuestTrackingAnalytics"
- $.analyticsRules.KL[]: "GameInitAnalytics"
+ $.analyticsRules.KL[]: "PlayerCardAnimationSettingAnalytics"
+ $.analyticsRules.KL[]: "SingleEndpointLatencyAnalytics"
+ $.analyticsRulesHVS.GameInitAnalytics: "HVSStrict"
+ $.dynamicContent.DynamicContentKillswitchPlatforms[]: "switch"
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.analyticsRulesDedicatedServer.KAL[]: "DedicatedServerInvalidLoadoutAnalytics"
+ $.analyticsRulesDedicatedServer.KAL[]: "DedicatedServerPlayerEquipDisabledItemAnalytics"
+ $.analyticsRulesDedicatedServer.KAL[]: "Gameplay_ChaseAnalytics"
```

### [`archiveRewardData/content.json`](archiveRewardData/content.json)

[Full line-by-line diff](diffs/archiveRewardData/content.json.diff)

```diff
- $.Tome22.starsEarnedPerLevel: 2
+ $.Tome22.starsEarnedPerLevel: 1
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
- $.RarityCost.UltraRare: 5000
+ $.RarityCost.Ascended: 5000
+ $.RarityCost.Visceral: 5000
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=S46]
+ $[id=CHALLENGE_REWARD_TIER_Rift_01]
+ $[id=CHALLENGE_BATTLE_PASS_Rift_01]
+ $[id=AV_Head019_01]
+ $[id=AV_Legs010_02]
+ $[id=AV_Torso019_01]
+ $[id=CM_Head08_01]
+ $[id=CM_Legs08_01]
+ $[id=CM_Torso08_01]
+ $[id=DF_Head036]
+ $[id=FM_Head040]
+ $[id=FM_Head040_01]
+ $[id=FM_Head040_02]
+ $[id=FM_Head040_03]
+ $[id=FM_Legs040]
+ $[id=FM_Legs040_01]
+ $[id=FM_Legs040_02]
+ $[id=FM_Legs040_03]
+ $[id=FM_Torso040]
+ $[id=FM_Torso040_01]
+ $[id=FM_Torso040_02]
+ $[id=FM_Torso040_03]
+ $[id=HS_Head030]
+ $[id=HS_Head030_01]
+ $[id=HS_Head030_02]
+ $[id=HS_Head030_03]
+ $[id=HS_Legs030]
+ $[id=HS_Legs030_01]
+ $[id=HS_Legs030_02]
+ $[id=HS_Legs030_03]
+ $[id=HS_Torso030]
+ $[id=HS_Torso030_01]
+ $[id=HS_Torso030_02]
+ $[id=HS_Torso030_03]
+ $[id=JE_001]
+ $[id=JE_002]
+ $[id=JE_003]
+ $[id=JE_004]
+ $[id=JE_005]
+ $[id=JE_006]
+ $[id=JE_007]
+ $[id=JE_008]
+ $[id=JE_009]
+ $[id=JE_010]
+ $[id=JE_012]
+ $[id=JE_BDG_03]
+ $[id=JE_BDG_04]
+ $[id=JE_BDG_05]
+ $[id=JE_BDG_06]
+ $[id=JE_BDG_07]
+ $[id=JE_BDG_08]
+ $[id=JE_BDG_09]
+ $[id=JE_BDG_10]
+ $[id=JE_BDG_11]
+ $[id=JE_BDG_12]
+ $[id=JE_BDG_16]
+ $[id=JE_BNR_03]
+ $[id=JE_BNR_04]
+ $[id=JE_BNR_05]
+ $[id=JE_BNR_06]
+ $[id=JE_BNR_07]
+ $[id=JE_BNR_08]
+ $[id=JE_BNR_09]
+ $[id=JE_BNR_10]
+ $[id=JE_BNR_11]
+ $[id=JE_BNR_12]
+ $[id=JP_Head030]
+ $[id=JP_Legs030]
+ $[id=JP_Torso030]
+ $[id=K28_Body019]
+ $[id=K28_Body019_01]
+ $[id=K28_Body019_02]
+ $[id=K28_Body019_03]
+ $[id=K28_Head019]
+ $[id=K28_Head019_01]
+ $[id=K28_Head019_02]
+ $[id=K28_Head019_03]
+ $[id=K28_W019]
+ $[id=K28_W019_01]
+ $[id=K28_W019_02]
+ $[id=K28_W019_03]
+ $[id=K31_Body013_01]
+ $[id=K31_Head013_01]
+ $[id=K31_W013_01]
+ $[id=K32_Body013]
+ $[id=K32_Head013]
+ $[id=K32_W013]
+ $[id=KK_Body038]
+ $[id=KK_Mask038]
+ $[id=KK_W038]
+ $[id=OK_Body016]
+ $[id=OK_Mask016]
+ $[id=OK_W016]
+ $[id=S25_Head030]
+ $[id=S25_Legs030]
+ $[id=S25_Torso030]
+ $[id=S31_Head022]
+ $[id=S31_Head022_01]
+ $[id=S31_Head022_02]
+ $[id=S31_Head022_03]
+ $[id=S31_Legs022]
+ $[id=S31_Legs022_01]
+ $[id=S31_Legs022_02]
+ $[id=S31_Legs022_03]
+ $[id=S31_Torso022]
+ $[id=S31_Torso022_01]
+ $[id=S31_Torso022_02]
+ $[id=S31_Torso022_03]
+ $[id=S37_Head021]
+ $[id=S37_Legs021]
+ $[id=S37_Torso021]
+ $[id=S46_Head006]
+ $[id=S46_Head006_01]
+ $[id=S46_Head007]
+ $[id=S46_Head007_01]
+ $[id=S46_Head007_02]
+ $[id=S46_Head007_03]
+ $[id=S46_Head01]
+ $[id=S46_Head01_01]
+ $[id=S46_Head01_02]
+ $[id=S46_Head01_03]
+ $[id=S46_Head01_P01]
+ $[id=S46_Head02]
+ $[id=S46_Head02_01]
+ $[id=S46_Legs006]
+ $[id=S46_Legs006_01]
+ $[id=S46_Legs007]
+ $[id=S46_Legs007_01]
+ $[id=S46_Legs007_02]
+ $[id=S46_Legs007_03]
+ $[id=S46_Legs01]
+ $[id=S46_Legs01_01]
+ $[id=S46_Legs01_02]
+ $[id=S46_Legs01_03]
+ $[id=S46_Legs01_CV01]
+ $[id=S46_Legs01_CV02]
+ $[id=S46_Legs01_CV03]
+ $[id=S46_Legs01_CV04]
+ $[id=S46_Legs01_P01]
+ $[id=S46_Legs02]
+ $[id=S46_Legs02_01]
+ $[id=S46_PCharm001]
+ $[id=S46_PCharm002]
+ $[id=S46_PCharm003]
+ $[id=S46_Torso006]
+ $[id=S46_Torso006_01]
+ $[id=S46_Torso007]
+ $[id=S46_Torso007_01]
+ $[id=S46_Torso007_02]
+ $[id=S46_Torso007_03]
+ $[id=S46_Torso008]
+ $[id=S46_Torso01]
+ $[id=S46_Torso01_01]
+ $[id=S46_Torso01_02]
+ $[id=S46_Torso01_03]
+ $[id=S46_Torso01_04]
+ $[id=S46_Torso01_CV01]
+ $[id=S46_Torso01_CV02]
+ $[id=S46_Torso01_CV03]
+ $[id=S46_Torso01_CV04]
+ $[id=S46_Torso01_P01]
+ $[id=S46_Torso02]
+ $[id=S46_Torso02_01]
+ $[id=TN_Body023]
+ $[id=TN_Body023_01]
+ $[id=TN_Body023_02]
+ $[id=TN_Body023_03]
+ $[id=TN_Head023]
+ $[id=TN_Head023_01]
+ $[id=TN_Head023_02]
+ $[id=TN_Head023_03]
+ $[id=TN_W023]
+ $[id=TN_W023_01]
+ $[id=TN_W023_02]
+ $[id=TN_W023_03]
+ $[id=TW_Body008_01]
+ $[id=TW_Head008_01]
+ $[id=TW_W008_01]
+ $[id=US_Head009_02]
+ $[id=US_Legs009_02]
+ $[id=US_Torso009_02]
+ $[id=AV_outfit_019_01]
+ $[id=CM_outfit_08_01]
+ $[id=FM_outfit_040]
+ $[id=FM_outfit_040_01]
+ $[id=FM_outfit_040_02]
+ $[id=FM_outfit_040_03]
+ $[id=HS_outfit_030]
+ $[id=HS_outfit_030_01]
+ $[id=HS_outfit_030_02]
+ $[id=HS_outfit_030_03]
+ $[id=JP_outfit_030]
+ $[id=K28_outfit_019]
+ $[id=K28_outfit_019_01]
+ $[id=K28_outfit_019_02]
+ $[id=K28_outfit_019_03]
+ $[id=K31_outfit_013_01]
+ $[id=K32_outfit_013]
+ $[id=KK_outfit_038]
+ $[id=OK_outfit_016]
… 1732 more change(s) — see the commit diff for everything
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[3].limitedAvailabilityEndDate: "2025-04-29T15:00:00Z"
+ $.collections[3].limitedAvailabilityEndDate: "2025-04-10T15:00:00Z"
+ $.collections[5].additionalImages[0]
- $.collections[5].collectionId: "Hanami"
+ $.collections[5].collectionId: "SteadyPulse"
- $.collections[5].collectionTitle.de: "Hanami "
+ $.collections[5].collectionTitle.de: "Steady Pulse"
- $.collections[5].collectionTitle.en: "Hanami "
+ $.collections[5].collectionTitle.en: "Steady Pulse"
- $.collections[5].collectionTitle.es: "Hanami "
+ $.collections[5].collectionTitle.es: "Steady Pulse"
- $.collections[5].collectionTitle["es-MX"]: "Hanami "
+ $.collections[5].collectionTitle["es-MX"]: "Steady Pulse"
- $.collections[5].collectionTitle.fr: "Hanami "
+ $.collections[5].collectionTitle.fr: "Steady Pulse"
- $.collections[5].collectionTitle.it: "Hanami "
+ $.collections[5].collectionTitle.it: "Steady Pulse"
- $.collections[5].collectionTitle.ja: "花見 "
+ $.collections[5].collectionTitle.ja: "Steady Pulse"
- $.collections[5].collectionTitle.ko: "벚꽃 축제 "
+ $.collections[5].collectionTitle.ko: "Steady Pulse"
- $.collections[5].collectionTitle.pl: "Hanami "
+ $.collections[5].collectionTitle.pl: "Steady Pulse"
- $.collections[5].collectionTitle["pt-BR"]: "Hanami "
+ $.collections[5].collectionTitle["pt-BR"]: "Steady Pulse"
- $.collections[5].collectionTitle.ru: "Ханами "
+ $.collections[5].collectionTitle.ru: "«Ровный пульс»"
- $.collections[5].collectionTitle.th: "ฮานามิ "
+ $.collections[5].collectionTitle.th: "Steady Pulse"
- $.collections[5].collectionTitle.tr: "Hanami "
+ $.collections[5].collectionTitle.tr: "Steady Pulse"
- $.collections[5].collectionTitle["zh-Hans"]: "花见 "
+ $.collections[5].collectionTitle["zh-Hans"]: "《Steady Pulse》"
- $.collections[5].collectionTitle["zh-Hant"]: "賞花 "
+ $.collections[5].collectionTitle["zh-Hant"]: "穩定脈搏"
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
+ $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
- $.collections[5].inclusionVersion: "7.7.0 PTB"
+ $.collections[5].inclusionVersion: "8.7.0"
- $.collections[5].items[]: "MS_outfit_016"
- $.collections[5].items[]: "SwedenSurvivor_outfit_015"
- $.collections[5].items[]: "HK_outfit_014"
+ $.collections[5].items[]: "S46_outfit_01_CV01"
+ $.collections[5].items[]: "S46_outfit_01_CV02"
+ $.collections[5].items[]: "S46_outfit_01_CV03"
+ $.collections[5].items[]: "S46_outfit_01_CV04"
+ $.collections[5].items[]: "S46_outfit_01_01"
+ $.collections[5].items[]: "S46_outfit_01_02"
+ $.collections[5].items[]: "S46_outfit_01_03"
+ $.collections[5].items[]: "S46_outfit_02"
+ $.collections[5].items[]: "S46_outfit_02_01"
+ $.collections[5].items[]: "S46_outfit_006"
+ $.collections[5].items[]: "S46_outfit_006_01"
- $.collections[5].sortOrder: "-13"
+ $.collections[5].sortOrder: "-108"
- $.collections[5].updatedDate: "2024-02-01T17:19:10Z"
+ $.collections[5].updatedDate: "2025-02-28T13:55:18.092Z"
+ $.collections[6].limitedAvailabilityStartDate: "2025-05-15T15:00:00Z"
+ $.collections[6].visibleBeforeStartDate: false
+ $.collections[6].additionalImages[0]
- $.collections[6].collectionId: "Rockabilly"
+ $.collections[6].collectionId: "GuardiansAndShadows"
- $.collections[6].collectionTitle.de: "Rockabilly"
+ $.collections[6].collectionTitle.de: "Wächter und Schatten"
- $.collections[6].collectionTitle.en: "Rockabilly"
+ $.collections[6].collectionTitle.en: "Guardians & Shadows"
- $.collections[6].collectionTitle.es: "Rockabilly"
+ $.collections[6].collectionTitle.es: "Guardianes y sombras"
- $.collections[6].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[6].collectionTitle["es-MX"]: "Guardianes y sombras"
- $.collections[6].collectionTitle.fr: "Rockabilly"
+ $.collections[6].collectionTitle.fr: "Gardiens et ombres"
- $.collections[6].collectionTitle.it: "Rockabilly"
+ $.collections[6].collectionTitle.it: "Guardiani e ombre"
- $.collections[6].collectionTitle.ja: "ロカビリー "
+ $.collections[6].collectionTitle.ja: "守護者と影"
- $.collections[6].collectionTitle.ko: "로커빌리"
+ $.collections[6].collectionTitle.ko: "수호자와 그림자"
- $.collections[6].collectionTitle.pl: "Rockabilly"
+ $.collections[6].collectionTitle.pl: "Strażnicy i cienie"
- $.collections[6].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[6].collectionTitle["pt-BR"]: "Guardiões e Sombras"
- $.collections[6].collectionTitle.ru: "Рокабилли"
+ $.collections[6].collectionTitle.ru: "Стражи и тени"
- $.collections[6].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[6].collectionTitle.th: "ผู้พิทักษ์กับเงา"
- $.collections[6].collectionTitle.tr: "Rockabilly"
+ $.collections[6].collectionTitle.tr: "Muhafızlar ve Gölgeler"
- $.collections[6].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[6].collectionTitle["zh-Hans"]: "守护者&暗影"
- $.collections[6].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[6].collectionTitle["zh-Hant"]: "守衛與暗影"
- $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GuardiansAndShadows.T_UI_CollectionBanner_GuardiansAndShadows"
- $.collections[6].inclusionVersion: "7.7.0 PTB"
+ $.collections[6].inclusionVersion: "8.7.0"
- $.collections[6].items[]: "AV_outfit_015"
- $.collections[6].items[]: "MS_outfit_014"
- $.collections[6].items[]: "GS_outfit_014"
- $.collections[6].items[]: "MT_outfit_015"
- $.collections[6].items[]: "NK_outfit_014"
- $.collections[6].items[]: "S23_outfit_016"
- $.collections[6].items[]: "S24_outfit_013"
+ $.collections[6].items[]: "KK_outfit_038"
+ $.collections[6].items[]: "OK_outfit_016"
+ $.collections[6].items[]: "S25_outfit_030"
+ $.collections[6].items[]: "S37_outfit_021"
+ $.collections[6].items[]: "HK_outfit_020"
+ $.collections[6].items[]: "SwedenSurvivor_outfit_025"
+ $.collections[6].items[]: "DK_outfit_023"
+ $.collections[6].items[]: "TW_outfit_021"
+ $.collections[6].items[]: "S24_outfit_022"
- $.collections[6].sortOrder: "-14"
+ $.collections[6].sortOrder: "-109"
- $.collections[6].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[6].updatedDate: "2025-02-28T13:49:52Z"
- $.collections[7].collectionId: "SpringEnsembles"
+ $.collections[7].collectionId: "Hanami"
- $.collections[7].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[7].collectionTitle.de: "Hanami "
- $.collections[7].collectionTitle.en: "Spring Ensembles"
+ $.collections[7].collectionTitle.en: "Hanami "
- $.collections[7].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[7].collectionTitle.es: "Hanami "
- $.collections[7].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[7].collectionTitle["es-MX"]: "Hanami "
- $.collections[7].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[7].collectionTitle.fr: "Hanami "
- $.collections[7].collectionTitle.it: "Completi primaverili"
+ $.collections[7].collectionTitle.it: "Hanami "
- $.collections[7].collectionTitle.ja: "春のアンサンブル"
+ $.collections[7].collectionTitle.ja: "花見 "
- $.collections[7].collectionTitle.ko: "봄의 조화"
+ $.collections[7].collectionTitle.ko: "벚꽃 축제 "
- $.collections[7].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[7].collectionTitle.pl: "Hanami "
- $.collections[7].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[7].collectionTitle["pt-BR"]: "Hanami "
- $.collections[7].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[7].collectionTitle.ru: "Ханами "
- $.collections[7].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[7].collectionTitle.th: "ฮานามิ "
- $.collections[7].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[7].collectionTitle.tr: "Hanami "
- $.collections[7].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[7].collectionTitle["zh-Hans"]: "花见 "
- $.collections[7].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[7].collectionTitle["zh-Hant"]: "賞花 "
- $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
- $.collections[7].items[]: "Ace_outfit_008_01"
- $.collections[7].items[]: "HillBilly_outfit_008_01"
- $.collections[7].items[]: "FM_outfit_011"
- $.collections[7].items[]: "FM_outfit_011_01"
- $.collections[7].items[]: "S28_outfit_011"
- $.collections[7].items[]: "US_outfit_015"
- $.collections[7].items[]: "K21_outfit_010"
- $.collections[7].items[]: "K26_outfit_007"
- $.collections[7].items[]: "GK_outfit_013"
- $.collections[7].items[]: "S29_outfit_008"
+ $.collections[7].items[]: "MS_outfit_016"
+ $.collections[7].items[]: "SwedenSurvivor_outfit_015"
+ $.collections[7].items[]: "HK_outfit_014"
- $.collections[7].sortOrder: "-15"
+ $.collections[7].sortOrder: "-13"
- $.collections[7].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[7].updatedDate: "2024-02-01T17:19:10Z"
- $.collections[8].collectionId: "PopSuperstar"
+ $.collections[8].collectionId: "Rockabilly"
- $.collections[8].collectionTitle.de: "Superpopstar"
+ $.collections[8].collectionTitle.de: "Rockabilly"
- $.collections[8].collectionTitle.en: "Pop Superstar"
+ $.collections[8].collectionTitle.en: "Rockabilly"
- $.collections[8].collectionTitle.es: "Superestrella del pop"
+ $.collections[8].collectionTitle.es: "Rockabilly"
- $.collections[8].collectionTitle["es-MX"]: "Superestrella del pop"
+ $.collections[8].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[8].collectionTitle.fr: "Superstar de la pop"
+ $.collections[8].collectionTitle.fr: "Rockabilly"
- $.collections[8].collectionTitle.it: "Superstar pop"
+ $.collections[8].collectionTitle.it: "Rockabilly"
- $.collections[8].collectionTitle.ja: "ポップスター"
+ $.collections[8].collectionTitle.ja: "ロカビリー "
- $.collections[8].collectionTitle.ko: "팝 슈퍼스타"
+ $.collections[8].collectionTitle.ko: "로커빌리"
- $.collections[8].collectionTitle.pl: "Supergwiazda popu"
+ $.collections[8].collectionTitle.pl: "Rockabilly"
- $.collections[8].collectionTitle["pt-BR"]: "Estrela Pop"
+ $.collections[8].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[8].collectionTitle.ru: "Поп-суперзвезда"
+ $.collections[8].collectionTitle.ru: "Рокабилли"
- $.collections[8].collectionTitle.th: "ซูเปอร์สตาร์ป็อป"
+ $.collections[8].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[8].collectionTitle.tr: "Popçu Süperstar"
+ $.collections[8].collectionTitle.tr: "Rockabilly"
- $.collections[8].collectionTitle["zh-Hans"]: "流行巨星"
+ $.collections[8].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[8].collectionTitle["zh-Hant"]: "流行巨星"
+ $.collections[8].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[8].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_PopSuperstar.T_UI_CollectionBanner_PopSuperstar"
… 4107 more change(s) — see the commit diff for everything
```

### [`consents/eula/v4/de.json`](consents/eula/v4/de.json)

[Full line-by-line diff](diffs/consents/eula/v4/de.json.diff)

```diff
- $[id=eula].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG \n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BE…
+ $[id=eula].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG \n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BE…
```

### [`consents/eula/v4/en.json`](consents/eula/v4/en.json)

[Full line-by-line diff](diffs/consents/eula/v4/en.json.diff)

```diff
- $[id=eula].versions[0].content.en: "END USER LICENCE AGREEMENT \n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE …
+ $[id=eula].versions[0].content.en: "END USER LICENCE AGREEMENT \n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE …
```

### [`consents/eula/v4/es-MX.json`](consents/eula/v4/es-MX.json)

[Full line-by-line diff](diffs/consents/eula/v4/es-MX.json.diff)

```diff
- $[id=eula].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
+ $[id=eula].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
```

### [`consents/eula/v4/es.json`](consents/eula/v4/es.json)

[Full line-by-line diff](diffs/consents/eula/v4/es.json.diff)

```diff
- $[id=eula].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
+ $[id=eula].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
```

### [`consents/eula/v4/fr.json`](consents/eula/v4/fr.json)

[Full line-by-line diff](diffs/consents/eula/v4/fr.json.diff)

```diff
- $[id=eula].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
+ $[id=eula].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
```

### [`consents/eula/v4/it.json`](consents/eula/v4/it.json)

[Full line-by-line diff](diffs/consents/eula/v4/it.json.diff)

```diff
- $[id=eula].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
+ $[id=eula].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
```

### [`consents/eula/v4/ja.json`](consents/eula/v4/ja.json)

[Full line-by-line diff](diffs/consents/eula/v4/ja.json.diff)

```diff
- $[id=eula].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
+ $[id=eula].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
```

### [`consents/eula/v4/ko.json`](consents/eula/v4/ko.json)

[Full line-by-line diff](diffs/consents/eula/v4/ko.json.diff)

```diff
- $[id=eula].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
+ $[id=eula].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
```

### [`consents/eula/v4/pl.json`](consents/eula/v4/pl.json)

[Full line-by-line diff](diffs/consents/eula/v4/pl.json.diff)

```diff
- $[id=eula].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
+ $[id=eula].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
```

### [`consents/eula/v4/pt-BR.json`](consents/eula/v4/pt-BR.json)

[Full line-by-line diff](diffs/consents/eula/v4/pt-BR.json.diff)

```diff
- $[id=eula].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
+ $[id=eula].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
```

### [`consents/eula/v4/ru.json`](consents/eula/v4/ru.json)

[Full line-by-line diff](diffs/consents/eula/v4/ru.json.diff)

```diff
- $[id=eula].versions[0].content.ru: "\nЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA»…
+ $[id=eula].versions[0].content.ru: "\nЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA»…
```

### [`consents/eula/v4/th.json`](consents/eula/v4/th.json)

[Full line-by-line diff](diffs/consents/eula/v4/th.json.diff)

```diff
- $[id=eula].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
+ $[id=eula].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
```

### [`consents/eula/v4/tr.json`](consents/eula/v4/tr.json)

[Full line-by-line diff](diffs/consents/eula/v4/tr.json.diff)

```diff
- $[id=eula].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
+ $[id=eula].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
```

### [`consents/eula/v4/zh-Hans.json`](consents/eula/v4/zh-Hans.json)

[Full line-by-line diff](diffs/consents/eula/v4/zh-Hans.json.diff)

```diff
- $[id=eula].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过https…
+ $[id=eula].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过<a hr…
```

### [`consents/eula/v4/zh-Hant.json`](consents/eula/v4/zh-Hant.json)

[Full line-by-line diff](diffs/consents/eula/v4/zh-Hant.json.diff)

```diff
- $[id=eula].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過https…
+ $[id=eula].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過<a hr…
```

### [`consents/eula_psn_eu/v5/de.json`](consents/eula_psn_eu/v5/de.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/de.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG\n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BEZ…
+ $[id=eula_psn_eu].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG\n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BEZ…
```

### [`consents/eula_psn_eu/v5/en.json`](consents/eula_psn_eu/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/en.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_eu].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`consents/eula_psn_eu/v5/es-MX.json`](consents/eula_psn_eu/v5/es-MX.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/es-MX.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
+ $[id=eula_psn_eu].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
```

### [`consents/eula_psn_eu/v5/es.json`](consents/eula_psn_eu/v5/es.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/es.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
+ $[id=eula_psn_eu].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
```

### [`consents/eula_psn_eu/v5/fr.json`](consents/eula_psn_eu/v5/fr.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/fr.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
+ $[id=eula_psn_eu].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
```

### [`consents/eula_psn_eu/v5/it.json`](consents/eula_psn_eu/v5/it.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/it.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
+ $[id=eula_psn_eu].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
```

### [`consents/eula_psn_eu/v5/ja.json`](consents/eula_psn_eu/v5/ja.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/ja.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
+ $[id=eula_psn_eu].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
```

### [`consents/eula_psn_eu/v5/ko.json`](consents/eula_psn_eu/v5/ko.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/ko.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
+ $[id=eula_psn_eu].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
```

### [`consents/eula_psn_eu/v5/pl.json`](consents/eula_psn_eu/v5/pl.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/pl.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
+ $[id=eula_psn_eu].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
```

### [`consents/eula_psn_eu/v5/pt-BR.json`](consents/eula_psn_eu/v5/pt-BR.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/pt-BR.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
+ $[id=eula_psn_eu].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
```

### [`consents/eula_psn_eu/v5/ru.json`](consents/eula_psn_eu/v5/ru.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/ru.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.ru: "ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA» И…
+ $[id=eula_psn_eu].versions[0].content.ru: "ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA» И…
```

### [`consents/eula_psn_eu/v5/th.json`](consents/eula_psn_eu/v5/th.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/th.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
+ $[id=eula_psn_eu].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
```

### [`consents/eula_psn_eu/v5/tr.json`](consents/eula_psn_eu/v5/tr.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/tr.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
+ $[id=eula_psn_eu].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
```

### [`consents/eula_psn_eu/v5/zh-Hans.json`](consents/eula_psn_eu/v5/zh-Hans.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/zh-Hans.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过https…
+ $[id=eula_psn_eu].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过<a hr…
```

### [`consents/eula_psn_eu/v5/zh-Hant.json`](consents/eula_psn_eu/v5/zh-Hant.json)

[Full line-by-line diff](diffs/consents/eula_psn_eu/v5/zh-Hant.json.diff)

```diff
- $[id=eula_psn_eu].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過https…
+ $[id=eula_psn_eu].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過<a hr…
```

### [`consents/eula_psn_na/v5/de.json`](consents/eula_psn_na/v5/de.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/de.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG\n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BEZ…
+ $[id=eula_psn_na].versions[0].content.de: "ENDBENUTZER-LIZENZVERTRAG\n\nBITTE LESEN SIE DIESEN ENDBENUTZER-LIZENZVERTRAG (ENGLISCH: END USER LICENCE AGREEMENT, IM FOLGENDEN ALS „EULA“ ODER „VERTRAG“ BEZ…
```

### [`consents/eula_psn_na/v5/en.json`](consents/eula_psn_na/v5/en.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/en.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
+ $[id=eula_psn_na].versions[0].content.en: "END USER LICENCE AGREEMENT\n\nPLEASE READ THIS END USER LICENCE AGREEMENT (“EULA” OR “AGREEMENT”) CAREFULLY. BY USING AND PARTICIPATING IN THE GAME YOU AGREE T…
```

### [`consents/eula_psn_na/v5/es-MX.json`](consents/eula_psn_na/v5/es-MX.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/es-MX.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
+ $[id=eula_psn_na].versions[0].content["es-MX"]: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL “CLUF” O EL “CONTRATO”). AL USAR EL JUEG…
```

### [`consents/eula_psn_na/v5/es.json`](consents/eula_psn_na/v5/es.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/es.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
+ $[id=eula_psn_na].versions[0].content.es: "CONTRATO DE LICENCIA DE USUARIO FINAL\n\nES IMPORTANTE LEER ATENTAMENTE ESTE CONTRATO DE LICENCIA DE USUARIO FINAL (EL «CLUF» O EL «CONTRATO»). AL USAR EL JUEG…
```

### [`consents/eula_psn_na/v5/fr.json`](consents/eula_psn_na/v5/fr.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/fr.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
+ $[id=eula_psn_na].versions[0].content.fr: "CONTRAT DE LICENCE D’UTILISATEUR FINAL\n\nVEUILLEZ LIRE ATTENTIVEMENT LE PRÉSENT CONTRAT DE LICENCE D’UTILISATEUR FINAL (ci-après « CLUF » ou « CONTRAT »). VOT…
```

### [`consents/eula_psn_na/v5/it.json`](consents/eula_psn_na/v5/it.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/it.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
+ $[id=eula_psn_na].versions[0].content.it: "CONTRATTO DI LICENZA PER L’UTENTE FINALE\n\nLEGGERE ATTENTAMENTE IL PRESENTE CONTRATTO DI LICENZA PER L’UTENTE FINALE (“EULA” O “CONTRATTO”). L’UTILIZZO E LA P…
```

### [`consents/eula_psn_na/v5/ja.json`](consents/eula_psn_na/v5/ja.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/ja.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
+ $[id=eula_psn_na].versions[0].content.ja: "エンドユーザー使用許諾契約書\n\n本エンドユーザー使用許諾契約書 (「EULA」 あるいは 「契約」) を、よくお読みください。本ゲームを使用して参加することにより、署名された全契約書と同様にEULAが法的に強制可能であることに同意されたこととなります。EULAのすべての条件に合意されない場合、ゲームをインストール…
```

### [`consents/eula_psn_na/v5/ko.json`](consents/eula_psn_na/v5/ko.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/ko.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
+ $[id=eula_psn_na].versions[0].content.ko: "최종 사용자 사용권 계약\n\n본 최종 사용자 사용권 계약(이하 \"EULA\" 또는 \"계약\")을 주의 깊게 읽어주시기 바랍니다. 게임을 사용하거나 게임에 참여하는 것은 본 EULA가 귀하가 서명한 기타 서면 계약과 동일한 효력을 갖는 것에 동의하는 것이 됩니다. 만약 EULA의 …
```

### [`consents/eula_psn_na/v5/pl.json`](consents/eula_psn_na/v5/pl.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/pl.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
+ $[id=eula_psn_na].versions[0].content.pl: "PRZECZYTAJ TĘ UMOWĘ LICENCYJNĄ UŻYTKOWNIKA (zwaną dalej “EULA/umowa licencyjna użytkownika” ALBO “POROZUMIENIE“) BARDZO DOKŁADNIE. GRAJĄC W GRĘ I KORZYSTAJĄC Z…
```

### [`consents/eula_psn_na/v5/pt-BR.json`](consents/eula_psn_na/v5/pt-BR.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/pt-BR.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
+ $[id=eula_psn_na].versions[0].content["pt-BR"]: "CONTRATO DE LICENÇA DE USUÁRIO FINAL\n\nLEIA ATENTAMENTE ESTE CONTRATO DE LICENÇA DE USUÁRIO FINAL (“EULA” OU “CONTRATO”). AO USAR E PARTICIPAR DO JOGO VOCÊ CO…
```

### [`consents/eula_psn_na/v5/ru.json`](consents/eula_psn_na/v5/ru.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/ru.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.ru: "ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA» И…
+ $[id=eula_psn_na].versions[0].content.ru: "ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ\n\nВНИМАТЕЛЬНО ПРОЧИТАЙТЕ ДАННОЕ ЛИЦЕНЗИОННОЕ СОГЛАШЕНИЕ С КОНЕЧНЫМ ПОЛЬЗОВАТЕЛЕМ (ДАЛЕЕ — «СОГЛАШЕНИЕ EULA» И…
```

### [`consents/eula_psn_na/v5/th.json`](consents/eula_psn_na/v5/th.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/th.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
+ $[id=eula_psn_na].versions[0].content.th: "โปรดอ่านข้อตกลงอนุญาตให้ใช้สิทธิ์ของผู้ใช้ (\"ข้อตกลง\") นี้โดยละเอียด ในการใช้งานและมีส่วนร่วมในเกม คุณได้ยอมรับว่าข้อตกลงนี้มีผลบังคับใช้เสมือนสัญญาลายลักษณ์…
```

### [`consents/eula_psn_na/v5/tr.json`](consents/eula_psn_na/v5/tr.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/tr.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
+ $[id=eula_psn_na].versions[0].content.tr: "SON KULLANICI LİSANS SÖZLEŞMESİ\n\nLÜTFEN BU SON KULLANICI LİSANS SÖZLEŞMESİNİ (“EULA” VEYA “SÖZLEŞME“) DİKKATLİ BİR ŞEKLİNDE OKUYUN. OYUNU KULLANARAK VE OYUNA…
```

### [`consents/eula_psn_na/v5/zh-Hans.json`](consents/eula_psn_na/v5/zh-Hans.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/zh-Hans.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过https…
+ $[id=eula_psn_na].versions[0].content["zh-Hans"]: "终端用户许可协议\n\n请仔细阅读本终端用户许可协议(“EULA”或“协议”)。通过使用和参与游戏，您同意本EULA与您签署的任何书面合同都具有可执行性。如果您不同意本EULA的所有条款，请不要安装或使用游戏。您在使用和参与游戏时所产生的任何互联网连接费用均由您自行承担。\n\n本EULA、使用条款（可通过<a hr…
```

### [`consents/eula_psn_na/v5/zh-Hant.json`](consents/eula_psn_na/v5/zh-Hant.json)

[Full line-by-line diff](diffs/consents/eula_psn_na/v5/zh-Hant.json.diff)

```diff
- $[id=eula_psn_na].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過https…
+ $[id=eula_psn_na].versions[0].content["zh-Hant"]: "終端使用者授權協定\n\n請仔細閱讀此終端使用者授權協定（以下簡稱為「EULA」或「協議」）通過使用和參與遊戲，您同意本EULA與您簽署的任何書面合同都具有同等效力。如果您不同意本EULA的所有條款，請不要安裝或使用遊戲。在使用和參與遊戲時，您需要自行承擔網際網路連接費用。\n\n本EULA使用條款（可通過<a hr…
```

### [`consents/marketing/v2/de.json`](consents/marketing/v2/de.json)

[Full line-by-line diff](diffs/consents/marketing/v2/de.json.diff)

```diff
- $[id=marketing].versions[0].content.de: "MARKETING\nDer Publisher dieses Spiels, Behaviour Interactive Inc. („BHVR“), möchte mehr über die Wirksamkeit seiner Online-Marketingaktivitäten erfahren.  Aus…
+ $[id=marketing].versions[0].content.de: "MARKETING\nDer Publisher dieses Spiels, Behaviour Interactive Inc. („BHVR“), möchte mehr über die Wirksamkeit seiner Online-Marketingaktivitäten erfahren.  Aus…
```

### [`consents/marketing/v2/en.json`](consents/marketing/v2/en.json)

[Full line-by-line diff](diffs/consents/marketing/v2/en.json.diff)

```diff
- $[id=marketing].versions[0].content.en: "MARKETING\nBehaviour Interactive Inc. (“BHVR”) is interested to learn more about the effectiveness of its online marketing activities. As a result, BHVR is ask…
+ $[id=marketing].versions[0].content.en: "MARKETING\nBehaviour Interactive Inc. (“BHVR”) is interested to learn more about the effectiveness of its online marketing activities. As a result, BHVR is ask…
```

### [`consents/marketing/v2/es-MX.json`](consents/marketing/v2/es-MX.json)

[Full line-by-line diff](diffs/consents/marketing/v2/es-MX.json.diff)

```diff
- $[id=marketing].versions[0].content["es-MX"]: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\") está interesado en saber más sobre la eficacia de sus acciones publicitarias en línea.  Por ende y únicamente …
+ $[id=marketing].versions[0].content["es-MX"]: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\") está interesado en saber más sobre la eficacia de sus acciones publicitarias en línea.  Por ende y únicamente …
```

### [`consents/marketing/v2/es.json`](consents/marketing/v2/es.json)

[Full line-by-line diff](diffs/consents/marketing/v2/es.json.diff)

```diff
- $[id=marketing].versions[0].content.es: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\", en adelante) quiere saber más sobre el funcionamiento de sus actividades comerciales en línea. Por ello, BHVR …
+ $[id=marketing].versions[0].content.es: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\", en adelante) quiere saber más sobre el funcionamiento de sus actividades comerciales en línea. Por ello, BHVR …
```

### [`consents/marketing/v2/fr.json`](consents/marketing/v2/fr.json)

[Full line-by-line diff](diffs/consents/marketing/v2/fr.json.diff)

```diff
- $[id=marketing].versions[0].content.fr: "MARKETING\nL'éditeur de ce jeu, Behaviour Interactif Inc. (« BHVR »), souhaite en savoir plus sur l'efficacité de ses activités de marketing en ligne. Par cons…
+ $[id=marketing].versions[0].content.fr: "MARKETING\nL'éditeur de ce jeu, Behaviour Interactif Inc. (« BHVR »), souhaite en savoir plus sur l'efficacité de ses activités de marketing en ligne. Par cons…
```

### [`consents/marketing/v2/it.json`](consents/marketing/v2/it.json)

[Full line-by-line diff](diffs/consents/marketing/v2/it.json.diff)

```diff
- $[id=marketing].versions[0].content.it: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\") desidera saperne di più sull'efficacia delle sue attività di marketing online.  Pertanto, BHVR chiede il conse…
+ $[id=marketing].versions[0].content.it: "MARKETING\nBehaviour Interactive Inc. (\"BHVR\") desidera saperne di più sull'efficacia delle sue attività di marketing online.  Pertanto, BHVR chiede il conse…
```

### [`consents/marketing/v2/ja.json`](consents/marketing/v2/ja.json)

[Full line-by-line diff](diffs/consents/marketing/v2/ja.json.diff)

```diff
- $[id=marketing].versions[0].content.ja: "マーケティング\n本ゲームのパブリッシャーであるBehaviour Interactive Inc.（以下「BHVR」）は、オンラインマーケティング活動の効果について詳しく知りたいと考えています。そのため、お客様が他の目的について別に同意する場合を除き、BHVRはこの特定の目的のためだけに個人データの一部を分析するこ…
+ $[id=marketing].versions[0].content.ja: "マーケティング\n本ゲームのパブリッシャーであるBehaviour Interactive Inc.（以下「BHVR」）は、オンラインマーケティング活動の効果について詳しく知りたいと考えています。そのため、お客様が他の目的について別に同意する場合を除き、BHVRはこの特定の目的のためだけに個人データの一部を分析するこ…
```

### [`consents/marketing/v2/ko.json`](consents/marketing/v2/ko.json)

[Full line-by-line diff](diffs/consents/marketing/v2/ko.json.diff)

```diff
- $[id=marketing].versions[0].content.ko: "마케팅\nBehavior Interactive Inc.(이하 “BHVR”)는 온라인 마케팅 활동의 효과에 대해 자세히 알고자 합니다.  따라서 BHVR은 사용자가 기타 목적으로 별도의 동의를 하지 않는 한, 이러한 특정 목적으로 사용자의 개인 데이터 일부를 분석하는 데에 대한 사용자의…
+ $[id=marketing].versions[0].content.ko: "마케팅\nBehavior Interactive Inc.(이하 “BHVR”)는 온라인 마케팅 활동의 효과에 대해 자세히 알고자 합니다.  따라서 BHVR은 사용자가 기타 목적으로 별도의 동의를 하지 않는 한, 이러한 특정 목적으로 사용자의 개인 데이터 일부를 분석하는 데에 대한 사용자의…
```

### [`consents/marketing/v2/pl.json`](consents/marketing/v2/pl.json)

[Full line-by-line diff](diffs/consents/marketing/v2/pl.json.diff)

```diff
- $[id=marketing].versions[0].content.pl: "MARKETING\nBehaviour Interactive Inc. („BHVR”)chce dowiedzieć się więcej na temat skuteczności swoich działań marketingowych online. W związku z tym prosi o zg…
+ $[id=marketing].versions[0].content.pl: "MARKETING\nBehaviour Interactive Inc. („BHVR”)chce dowiedzieć się więcej na temat skuteczności swoich działań marketingowych online. W związku z tym prosi o zg…
```

### [`consents/marketing/v2/pt-BR.json`](consents/marketing/v2/pt-BR.json)

[Full line-by-line diff](diffs/consents/marketing/v2/pt-BR.json.diff)

```diff
- $[id=marketing].versions[0].content["pt-BR"]: "MARKETING\nA Behaviour Interactive Inc. (“BHVR”) quer saber mais sobre a eficiência de suas atividades de marketing online.  Portanto, a BHVR está pedindo a su…
+ $[id=marketing].versions[0].content["pt-BR"]: "MARKETING\nA Behaviour Interactive Inc. (“BHVR”) quer saber mais sobre a eficiência de suas atividades de marketing online.  Portanto, a BHVR está pedindo a su…
```

### [`consents/marketing/v2/ru.json`](consents/marketing/v2/ru.json)

[Full line-by-line diff](diffs/consents/marketing/v2/ru.json.diff)

```diff
- $[id=marketing].versions[0].content.ru: "МАРКЕТИНГ\nКомпания Behaviour Interactive Inc. (далее – «BHVR») хочет оценить эффективность своих маркетинговых онлайн-мероприятий. Поэтому BHVR просит разреше…
+ $[id=marketing].versions[0].content.ru: "МАРКЕТИНГ\nКомпания Behaviour Interactive Inc. (далее – «BHVR») хочет оценить эффективность своих маркетинговых онлайн-мероприятий. Поэтому BHVR просит разреше…
```

### [`consents/marketing/v2/th.json`](consents/marketing/v2/th.json)

[Full line-by-line diff](diffs/consents/marketing/v2/th.json.diff)

```diff
- $[id=marketing].versions[0].content.th: "การตลาด\nBehaviour Interactive Inc. (“BHVR”) สนใจจะทราบข้อมูลเพิ่มเติมเรื่องประสิทธิภาพของกิจกรรมการตลาดออนไลน์  ผลก็คือ ทาง BHVR จึงได้ขอความยินยอมจากคุณ เพื่…
+ $[id=marketing].versions[0].content.th: "การตลาด\nBehaviour Interactive Inc. (“BHVR”) สนใจจะทราบข้อมูลเพิ่มเติมเรื่องประสิทธิภาพของกิจกรรมการตลาดออนไลน์  ผลก็คือ ทาง BHVR จึงได้ขอความยินยอมจากคุณ เพื่…
```

### [`consents/marketing/v2/tr.json`](consents/marketing/v2/tr.json)

[Full line-by-line diff](diffs/consents/marketing/v2/tr.json.diff)

```diff
- $[id=marketing].versions[0].content.tr: "PAZARLAMA\nBehaviour Interactive Inc. (\"BHVR\"), pazarlama faaliyetlerinin verimliliği hakkında daha fazla bilgi almayı amaçlamaktadır. Bu sebeple başka amaçl…
+ $[id=marketing].versions[0].content.tr: "PAZARLAMA\nBehaviour Interactive Inc. (\"BHVR\"), pazarlama faaliyetlerinin verimliliği hakkında daha fazla bilgi almayı amaçlamaktadır. Bu sebeple başka amaçl…
```

### [`consents/marketing/v2/zh-Hans.json`](consents/marketing/v2/zh-Hans.json)

[Full line-by-line diff](diffs/consents/marketing/v2/zh-Hans.json.diff)

```diff
- $[id=marketing].versions[0].content["zh-Hans"]: "市场信息数据\nBehaviour Interactive Inc. （以下简称“bhvr”）为更好了解线上营销策略的效果，想征求您的同意，允许bhvr分析您的部分个人数据。如果您同意，bhvr将会根据隐私政策(https://www.bhvr.com/privacy-policy-zh-hans/)和收集、处理和第…
+ $[id=marketing].versions[0].content["zh-Hans"]: "市场信息数据\nBehaviour Interactive Inc. （以下简称“bhvr”）为更好了解线上营销策略的效果，想征求您的同意，允许bhvr分析您的部分个人数据。如果您同意，bhvr将会根据隐私政策(<a href=\"event:https://www.bhvr.com/privacy-policy-z…
```

### [`consents/marketing/v2/zh-Hant.json`](consents/marketing/v2/zh-Hant.json)

[Full line-by-line diff](diffs/consents/marketing/v2/zh-Hant.json.diff)

```diff
- $[id=marketing].versions[0].content["zh-Hant"]: "行銷\nBehaviour Interactive Inc.（以下簡稱「BHVR」）想要深入了解線上行銷活動的效果。因此，BHVR需要你同意我們分析你的部分個人資料，但僅會用於線上行銷的用途，除非你另行同意用於其他目的。。如果你接受，BHVR將依照隱私權政策（https://www.bhvr.com/privacy-…
+ $[id=marketing].versions[0].content["zh-Hant"]: "行銷\nBehaviour Interactive Inc.（以下簡稱「BHVR」）想要深入了解線上行銷活動的效果。因此，BHVR需要你同意我們分析你的部分個人資料，但僅會用於線上行銷的用途，除非你另行同意用於其他目的。。如果你接受，BHVR將依照隱私權政策（<a href=\"event:https://www.b…
```

### [`consents/privacy/v3/de.json`](consents/privacy/v3/de.json)

[Full line-by-line diff](diffs/consents/privacy/v3/de.json.diff)

```diff
- $[id=privacy].versions[0].content.de: "Datenschutzrichtlinie\n\nBEHAVIOUR INTERACTIVE INC.\nLetzter Stand: 1. April 2023\n\nWillkommen bei der Datenschutzrichtlinie von Behaviour Interactive („Richt…
+ $[id=privacy].versions[0].content.de: "Datenschutzrichtlinie\n\nBEHAVIOUR INTERACTIVE INC.\nLetzter Stand: 1. April 2023\n\nWillkommen bei der Datenschutzrichtlinie von Behaviour Interactive („Richt…
```

### [`consents/privacy/v3/en.json`](consents/privacy/v3/en.json)

[Full line-by-line diff](diffs/consents/privacy/v3/en.json.diff)

```diff
- $[id=privacy].versions[0].content.en: "Privacy Policy\n\nBEHAVIOUR INTERACTIVE INC.\nLast updated: April 1, 2023\n\nWelcome to the Behaviour Interactive privacy policy (“Policy”).  This Policy was d…
+ $[id=privacy].versions[0].content.en: "Privacy Policy\n\nBEHAVIOUR INTERACTIVE INC.\nLast updated: April 1, 2023\n\nWelcome to the Behaviour Interactive privacy policy (“Policy”).  This Policy was d…
```

### [`consents/privacy/v3/es-MX.json`](consents/privacy/v3/es-MX.json)

[Full line-by-line diff](diffs/consents/privacy/v3/es-MX.json.diff)

```diff
- $[id=privacy].versions[0].content["es-MX"]: "Política de privacidad\n\nBEHAVIOUR INTERACTIVE INC.\nFecha de última actualización: 1 de abril de 2023\n\nBienvenido a la política de privacidad de Behaviour …
+ $[id=privacy].versions[0].content["es-MX"]: "Política de privacidad\n\nBEHAVIOUR INTERACTIVE INC.\nFecha de última actualización: 1 de abril de 2023\n\nBienvenido a la política de privacidad de Behaviour …
```

### [`consents/privacy/v3/es.json`](consents/privacy/v3/es.json)

[Full line-by-line diff](diffs/consents/privacy/v3/es.json.diff)

```diff
- $[id=privacy].versions[0].content.es: "Política de privacidad\n\nBEHAVIOUR INTERACTIVE INC.\nFecha de la última actualización: 1 de abril de 2023\n\nBienvenido a la Política de privacidad de Behavio…
+ $[id=privacy].versions[0].content.es: "Política de privacidad\n\nBEHAVIOUR INTERACTIVE INC.\nFecha de la última actualización: 1 de abril de 2023\n\nBienvenido a la Política de privacidad de Behavio…
```

### [`consents/privacy/v3/fr.json`](consents/privacy/v3/fr.json)

[Full line-by-line diff](diffs/consents/privacy/v3/fr.json.diff)

```diff
- $[id=privacy].versions[0].content.fr: "Politique de confidentialité\n\nBEHAVIOUR INTERACTIVE NC.\nDernière mise à jour : 1er avril 2023\n\nBienvenue sur la politique de confidentialité de Behaviour …
+ $[id=privacy].versions[0].content.fr: "Politique de confidentialité\n\nBEHAVIOUR INTERACTIVE NC.\nDernière mise à jour : 1er avril 2023\n\nBienvenue sur la politique de confidentialité de Behaviour …
```

### [`consents/privacy/v3/it.json`](consents/privacy/v3/it.json)

[Full line-by-line diff](diffs/consents/privacy/v3/it.json.diff)

```diff
- $[id=privacy].versions[0].content.it: "Informativa sulla privacy\n\nBEHAVIOUR INTERACTIVE INC.\nData dell'ultimo aggiornamento: 1° aprile 2023\n\nIl presente documento contiene l'Informativa sulla p…
+ $[id=privacy].versions[0].content.it: "Informativa sulla privacy\n\nBEHAVIOUR INTERACTIVE INC.\nData dell'ultimo aggiornamento: 1° aprile 2023\n\nIl presente documento contiene l'Informativa sulla p…
```

### [`consents/privacy/v3/ja.json`](consents/privacy/v3/ja.json)

[Full line-by-line diff](diffs/consents/privacy/v3/ja.json.diff)

```diff
- $[id=privacy].versions[0].content.ja: "プライバシーポリシー\n\nBEHAVIOUR INTERACTIVE INC.\n最終更新日：2023年4月1日\n\nBehaviour Interactiveのプライバシーポリシー（以下「ポリシー」といいます）へようこそ。本ポリシーは、当社がお客様のプライバシーを尊重し、プライバシーを保護することを約束するため…
+ $[id=privacy].versions[0].content.ja: "プライバシーポリシー\n\nBEHAVIOUR INTERACTIVE INC.\n最終更新日：2023年4月1日\n\nBehaviour Interactiveのプライバシーポリシー（以下「ポリシー」といいます）へようこそ。本ポリシーは、当社がお客様のプライバシーを尊重し、プライバシーを保護することを約束するため…
```

### [`consents/privacy/v3/ko.json`](consents/privacy/v3/ko.json)

[Full line-by-line diff](diffs/consents/privacy/v3/ko.json.diff)

```diff
- $[id=privacy].versions[0].content.ko: "개인정보처리방침\n\nBEHAVIOUR INTERACTIVE INC.\n최근 개정시행일자: 2023년 4월 1일\n\nBehaviour Interactive 개인정보처리방침(“방침”)에 오신 것을 환영합니다.  본 방침은 당사가 귀하의 프라이버시를 존중하고 귀하의 프라이버시를 보호하기…
+ $[id=privacy].versions[0].content.ko: "개인정보처리방침\n\nBEHAVIOUR INTERACTIVE INC.\n최근 개정시행일자: 2023년 4월 1일\n\nBehaviour Interactive 개인정보처리방침(“방침”)에 오신 것을 환영합니다.  본 방침은 당사가 귀하의 프라이버시를 존중하고 귀하의 프라이버시를 보호하기…
```

### [`consents/privacy/v3/pl.json`](consents/privacy/v3/pl.json)

[Full line-by-line diff](diffs/consents/privacy/v3/pl.json.diff)

```diff
- $[id=privacy].versions[0].content.pl: "Polityka prywatności\n\nBEHAVIOUR INTERACTIVE INC.\nData ostatniej aktualizacji: 1 kwietnia 2023 r.\n\nWitamy w Polityce prywatności Behaviour Interactive (dal…
+ $[id=privacy].versions[0].content.pl: "Polityka prywatności\n\nBEHAVIOUR INTERACTIVE INC.\nData ostatniej aktualizacji: 1 kwietnia 2023 r.\n\nWitamy w Polityce prywatności Behaviour Interactive (dal…
```

### [`consents/privacy/v3/pt-BR.json`](consents/privacy/v3/pt-BR.json)

[Full line-by-line diff](diffs/consents/privacy/v3/pt-BR.json.diff)

```diff
- $[id=privacy].versions[0].content["pt-BR"]: "Política de Privacidade\n\nBEHAVIOUR INTERACTIVE INC.\nÚltima atualização: 1º de abril de 2023\n\nBoas-vindas à política de privacidade de Behaviour Interactiv…
+ $[id=privacy].versions[0].content["pt-BR"]: "Política de Privacidade\n\nBEHAVIOUR INTERACTIVE INC.\nÚltima atualização: 1º de abril de 2023\n\nBoas-vindas à política de privacidade de Behaviour Interactiv…
```

### [`consents/privacy/v3/ru.json`](consents/privacy/v3/ru.json)

[Full line-by-line diff](diffs/consents/privacy/v3/ru.json.diff)

```diff
- $[id=privacy].versions[0].content.ru: "Политика конфиденциальности\n\nBEHAVIOUR INTERACTIVE INC.\nДата последнего обновления: 1 апреля 2023 г.\n\nБлагодарим вас за то, что решили ознакомиться с поли…
+ $[id=privacy].versions[0].content.ru: "Политика конфиденциальности\n\nBEHAVIOUR INTERACTIVE INC.\nДата последнего обновления: 1 апреля 2023 г.\n\nБлагодарим вас за то, что решили ознакомиться с поли…
```

### [`consents/privacy/v3/th.json`](consents/privacy/v3/th.json)

[Full line-by-line diff](diffs/consents/privacy/v3/th.json.diff)

```diff
- $[id=privacy].versions[0].content.th: "นโยบายความเป็นส่วนตัว\n\nBEHAVIOUR INTERACTIVE INC.\nปรับปรุงล่าสุด: 1 เมษายน 2023\n\nยินดีต้อนรับสู่นโยบายความเป็นส่วนตัวของ Behaviour Interactive (“นโยบาย”) …
+ $[id=privacy].versions[0].content.th: "นโยบายความเป็นส่วนตัว\n\nBEHAVIOUR INTERACTIVE INC.\nปรับปรุงล่าสุด: 1 เมษายน 2023\n\nยินดีต้อนรับสู่นโยบายความเป็นส่วนตัวของ Behaviour Interactive (“นโยบาย”) …
```

### [`consents/privacy/v3/tr.json`](consents/privacy/v3/tr.json)

[Full line-by-line diff](diffs/consents/privacy/v3/tr.json.diff)

```diff
- $[id=privacy].versions[0].content.tr: "Gizlilik Politikası\n\nBEHAVIOUR INTERACTIVE INC.\nSon güncelleme: 1 Nisan 2023\n\nBehaviour Interactive gizlilik politikasına (\"Politika\") hoş geldiniz.  Bu…
+ $[id=privacy].versions[0].content.tr: "Gizlilik Politikası\n\nBEHAVIOUR INTERACTIVE INC.\nSon güncelleme: 1 Nisan 2023\n\nBehaviour Interactive gizlilik politikasına (\"Politika\") hoş geldiniz.  Bu…
```

### [`consents/privacy/v3/zh-Hans.json`](consents/privacy/v3/zh-Hans.json)

[Full line-by-line diff](diffs/consents/privacy/v3/zh-Hans.json.diff)

```diff
- $[id=privacy].versions[0].content["zh-Hans"]: "隐私政策\n\nBEHAVIOUR INTERACTIVE INC.\n上次更新：2023 年 4 月 1 日\n\n欢迎阅读 Behaviour Interactive 隐私政策（“政策”）。我们尊重并承诺保护您的隐私，因此制定了本政策。 \n\n本政策的摘要请见下文。如果摘要与本政策不一致，以本政策为准。\n\n…
+ $[id=privacy].versions[0].content["zh-Hans"]: "隐私政策\n\nBEHAVIOUR INTERACTIVE INC.\n上次更新：2023 年 4 月 1 日\n\n欢迎阅读 Behaviour Interactive 隐私政策（“政策”）。我们尊重并承诺保护您的隐私，因此制定了本政策。 \n\n本政策的摘要请见下文。如果摘要与本政策不一致，以本政策为准。\n\n…
```

### [`consents/privacy/v3/zh-Hant.json`](consents/privacy/v3/zh-Hant.json)

[Full line-by-line diff](diffs/consents/privacy/v3/zh-Hant.json.diff)

```diff
- $[id=privacy].versions[0].content["zh-Hant"]: "隱私權政策\n\nBEHAVIOUR INTERACTIVE INC.\n最後更新：2023年4月1日\n\n歡迎閱讀Behaviour Interactive隱私權政策（統稱「政策」）。我們尊重並致力保護您的隱私，因而制定了本政策。 \n\n本政策摘要描述如下。如果摘要與本政策存在不一致，以本政策為準。\n\n政策…
+ $[id=privacy].versions[0].content["zh-Hant"]: "隱私權政策\n\nBEHAVIOUR INTERACTIVE INC.\n最後更新：2023年4月1日\n\n歡迎閱讀Behaviour Interactive隱私權政策（統稱「政策」）。我們尊重並致力保護您的隱私，因而制定了本政策。 \n\n本政策摘要描述如下。如果摘要與本政策存在不一致，以本政策為準。\n\n政策…
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
+ $.schedule[1].MapsWeight.Frm_Silo_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_Forest_Calamari: "500"
+ $.schedule[1].MapsWeight.Jnk_Garage_Calamari: "500"
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
+ $.Campaigns.TCOFS_Flash_Sale
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
+ $.dlcList.Jerky
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "260a0617beb48350aebadd55978418630fc12a9c"
+ $.entries[0].contentVersion: "8ad130275f30ece9aaac35aac1c7745e650fc913"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Rift1.T_UI_SpecialPack_Rift1"
- $.entries[0].uri: "images/T_UI_CollectionBanner_Techwear_2.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Rift1.png"
- $.entries[1].contentVersion: "73375dcf0e664697725a8d6fa73b8f8053a98033"
+ $.entries[1].contentVersion: "4582bf53d8714b99c19b3695989c265087a3ed0a"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SteadyPulse.T_UI_ChapterBundle_SteadyPulse"
- $.entries[1].uri: "images/T_UI_SpecialPack_Techwear.png"
+ $.entries[1].uri: "images/T_UI_ChapterBundle_SteadyPulse.png"
- $.entries[2].contentVersion: "13d64d0013547d3391ace5877b1307231062e2cf"
+ $.entries[2].contentVersion: "e09d8bc5bd3cb3dc3d76494253f09082027952f0"
- $.entries[2].enableChecksum: true
+ $.entries[2].enableChecksum: false
- $.entries[2].packagedPath: ""
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GuardiansAndShadows.T_UI_CollectionBanner_GuardiansAndShadows"
- $.entries[2].schema: "s3ver://"
+ $.entries[2].schema: "s3verbin://"
- $.entries[2].uri: "catalog.json"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_GuardiansAndShadows.png"
- $.entries[3].contentVersion: "808ede4e12ff2d4ece6f2e067535a46322de9ccb"
+ $.entries[3].contentVersion: "d3fc405a5ce47c53930d289dba1fabe0e4469e54"
- $.entries[3].enableChecksum: true
+ $.entries[3].enableChecksum: false
- $.entries[3].packagedPath: ""
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_GuardiansAndShadows.T_UI_SpecialPack_GuardiansAndShadows"
- $.entries[3].schema: "s3ver://"
+ $.entries[3].schema: "s3verbin://"
- $.entries[3].uri: "bonusPointEventsContent.json"
+ $.entries[3].uri: "images/T_UI_SpecialPack_GuardiansAndShadows.png"
- $.entries[4].contentVersion: "f06f7b4ad5e3efe599a7a923e6d484d6a9f99a75"
+ $.entries[4].contentVersion: "25d2963fb1278a11161c7fb25bc8b8737e898156"
- $.entries[4].downloadStrategy: "preferRemote"
+ $.entries[4].downloadStrategy: "preferPackaged"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "freetoplay/NA/event.json"
+ $.entries[4].uri: "images/T_UI_CollectionBanner_SteadyPulse.png"
- $.entries[5].contentVersion: "f06f7b4ad5e3efe599a7a923e6d484d6a9f99a75"
+ $.entries[5].contentVersion: "08cefbaf2f71670cf0bee76f2a745be07c503885"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_SteadyPulse.T_UI_SpecialPack_SteadyPulse"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "freetoplay/EU/event.json"
+ $.entries[5].uri: "images/T_UI_SpecialPack_SteadyPulse.png"
- $.entries[6].contentVersion: "a6078019755c78cff394ca2c39ab04a6a375e99f"
+ $.entries[6].contentVersion: "d08991cdb35d340bc58e5338b62a1afc2e20d1ad"
- $.entries[6].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "43784920126224bbbe326d768831b57e4a7e1bc9"
+ $.entries[7].contentVersion: "bdd20af71340598d2e8f67153ea568359edb623d"
- $.entries[7].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "82c4514754b7f6e0739d210139ceaede3984e79c"
+ $.entries[8].contentVersion: "caba6c6e542a9569e6234e7ae754924a601d48a9"
- $.entries[8].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "6665cc5d8b6a8c1b7f88490d3c99397f6c2cf3a8"
+ $.entries[9].contentVersion: "caba6c6e542a9569e6234e7ae754924a601d48a9"
- $.entries[9].uri: "archiveQuests/CalamariV1.json"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "462bac629c399f32268d77d40534d049c54e873a"
+ $.entries[10].contentVersion: "9ae228329908067eed2301c9e6bf1f8248bf3a05"
- $.entries[10].uri: "archiveQuests/CalamariV2.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "aa34d51c2f0178a667bd402b5c845810289391c7"
+ $.entries[11].contentVersion: "56786b3e45f632a799ad25eb85db0549f55a325b"
- $.entries[11].uri: "archiveQuests/CalamariV3.json"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "23afeef4be969d96dc56225e3b9fcc28928fffbc"
+ $.entries[12].contentVersion: "ac641e8ce7d53687f5b6789e6bc2c82bee86a66b"
- $.entries[12].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "adedaf00e25f4fc3386d7c94abaab0990cda27b4"
+ $.entries[13].contentVersion: "be20d92149f6f2186b15001615aa121b0f20b5d5"
- $.entries[13].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "67dfef8a2054da2ec9b2e2ac89bc99b3aa606398"
+ $.entries[14].contentVersion: "3c1465e0ccb4b4eabc57e7583b42692b92571397"
- $.entries[14].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "bb073f0a03e97999ba59b1f9ddee9878414bbfd5"
+ $.entries[15].contentVersion: "a513d516bb39dc5fffaad350781967d8fbddf8ce"
- $.entries[15].uri: "archiveQuests/FireflyV1.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "f3f0e07f1f20d589ac89296f260a0eed8d49d185"
+ $.entries[16].contentVersion: "427f5edc5ffb3eb2c286f826d88ae32a826618ab"
- $.entries[16].uri: "archiveQuests/Halloween2021.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "2c035c5a92570b8ff142ac2d501fb375e4e28eed"
+ $.entries[17].contentVersion: "7b613d7a13f232c7db8823b9318e24e228ff02a3"
- $.entries[17].uri: "archiveQuests/Halloween2022.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "8308c191b9dd6b1b7fea34dc1c6be05cef7cdf13"
+ $.entries[18].contentVersion: "059daf1fd92433656af77b6f320794cbb3e36341"
- $.entries[18].uri: "archiveQuests/Halloween2023.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "d280a807b23e2e9842643adbd574303459e1222d"
+ $.entries[19].contentVersion: "4212b8c2697a36061ff7a2f743d2a172257694fb"
- $.entries[19].uri: "archiveQuests/Halloween2024.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "6032b70c40b4aee0dbd1b3b1e58035cab0c5d2b3"
+ $.entries[20].contentVersion: "d4ebce49806c509edc15011cdae2537f62029ce1"
- $.entries[20].uri: "archiveQuests/Spring2024.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "aa766e97d6cff1b711974f7b44d33abd7929a91e"
+ $.entries[21].contentVersion: "3262bb89fba258a22a180ec4ec948ea00a058269"
- $.entries[21].uri: "archiveQuests/Spring2025.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "f3bb83ad36b7d831616a80b3f6c67390b2071fda"
+ $.entries[22].contentVersion: "2de63c1500f51009eae8e77a959a103f24647e7f"
- $.entries[22].uri: "archiveQuests/Summer2023.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "736197229f73584973ce0eb060c6d2739beb7a3e"
+ $.entries[23].contentVersion: "7d8366c503dd387f8f117f729e16cbe82cb5948c"
- $.entries[23].uri: "archiveQuests/Tome01.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "98e8ccf1289ed156fed049019c7a3607ccd44548"
+ $.entries[24].contentVersion: "03b656862cddd49ae87a4b3c3d8a86a87f95d913"
- $.entries[24].uri: "archiveQuests/Tome02.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "08dde1e72d8e97692bf94663c5065985bfa1872d"
+ $.entries[25].contentVersion: "c284deb8eacfed02432412acda362887ddff587d"
- $.entries[25].uri: "archiveQuests/Tome03.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "8c582dbb5062abbdd04dc73d6ec7b103706058b8"
+ $.entries[26].contentVersion: "41f0ead4266cfc2ae217de9182dccac76cebd3ea"
- $.entries[26].uri: "archiveQuests/Tome04.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "8b6e558850b3eb4fdfec552bce0c59b99fd6e890"
+ $.entries[27].contentVersion: "00958b1157ec510ba7e32afbb04001527785815c"
- $.entries[27].uri: "archiveQuests/Tome05.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "e923f0d1790bb74d6ec7c3ad075630a6bcaf4af3"
+ $.entries[28].contentVersion: "57bd4a3bfbe45f76e0296e79694ebae61392fdcf"
- $.entries[28].uri: "archiveQuests/Tome06.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "c79c8bb5de80f8e28145ff325de25cf96d6f5d9f"
+ $.entries[29].contentVersion: "4c3a97f61f9df7397c856d04df475cf72991ea3c"
- $.entries[29].uri: "archiveQuests/Tome07.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "9d8dd948c425e6fbc6b463df59329297263b3317"
+ $.entries[30].contentVersion: "866545597733a06061192bae9e9f2a8b593fc721"
- $.entries[30].uri: "archiveQuests/Tome08.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "332cc293b4e4575673d71baac4821adfd9464223"
+ $.entries[31].contentVersion: "84ceb62e57d4680f793e2d75e21f3013ae81b8e5"
- $.entries[31].uri: "archiveQuests/Tome09.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "e043e3b6ccba5ecc9f956694cbf636802dfde026"
+ $.entries[32].contentVersion: "e25a6ce8ca28cb8333c581a6dc3b036e1e8678c2"
- $.entries[32].uri: "archiveQuests/Tome10.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
- $.entries[33].contentVersion: "d9dc7af9f11d66ead44c156c6d9ede3e9dc238e1"
+ $.entries[33].contentVersion: "e8674d9102b51be7b1ed60eded313e5f80dc1144"
- $.entries[33].uri: "archiveQuests/Tome11.json"
+ $.entries[33].uri: "archiveQuests/Tome07.json"
- $.entries[34].contentVersion: "3874a62ca18ec788700af1e8ca3d52eb9ccfeb9c"
+ $.entries[34].contentVersion: "6a9939ff8e84325cff7df8f217396a382b903b78"
- $.entries[34].uri: "archiveQuests/Tome12.json"
+ $.entries[34].uri: "archiveQuests/Tome08.json"
- $.entries[35].contentVersion: "e786ed7b9bfdeb1a3284d651f30b1d78bb85b320"
+ $.entries[35].contentVersion: "43d11a74236b9c735dfebec28cd70ec7b6e19cd6"
- $.entries[35].uri: "archiveQuests/Tome13.json"
+ $.entries[35].uri: "archiveQuests/Tome09.json"
- $.entries[36].contentVersion: "cf3845b031651abe89509fc5f13240293e9c5570"
+ $.entries[36].contentVersion: "dde7a3f694ca07edc0b9406710c65df5f4bdf6cc"
- $.entries[36].uri: "archiveQuests/Tome14.json"
+ $.entries[36].uri: "archiveQuests/Tome10.json"
- $.entries[37].contentVersion: "7f48a26b05e959112a5d289f7b0faa7b2e00749c"
+ $.entries[37].contentVersion: "0ea80e880120f283909f000e56612997186ab4f6"
- $.entries[37].uri: "archiveQuests/Tome15.json"
+ $.entries[37].uri: "archiveQuests/Tome11.json"
- $.entries[38].contentVersion: "dc54b21473c81281312d717e3d1a54d186976ad9"
+ $.entries[38].contentVersion: "298a5cccda5587053da5f187ec9ea6bfd8e3ae36"
- $.entries[38].uri: "archiveQuests/Tome16.json"
+ $.entries[38].uri: "archiveQuests/Tome12.json"
- $.entries[39].contentVersion: "503e640005e5fd302441636e3895b5bb6b8fa422"
+ $.entries[39].contentVersion: "612d87357812492994b8ea85d1b038160f8c678e"
- $.entries[39].uri: "archiveQuests/Tome17.json"
+ $.entries[39].uri: "archiveQuests/Tome13.json"
- $.entries[40].contentVersion: "26e6f2868726c52a3c7167c3a96b0e5b18bf4362"
+ $.entries[40].contentVersion: "cb8a6386bfc1d652eea41d6b45607dd98273a13b"
- $.entries[40].uri: "archiveQuests/Tome18.json"
+ $.entries[40].uri: "archiveQuests/Tome14.json"
- $.entries[41].contentVersion: "e1c001a56045abbf858eaa1bd3d028df638c70b0"
+ $.entries[41].contentVersion: "76af9bc9875558ddc1e10e226c26cc325b0eb134"
- $.entries[41].uri: "archiveQuests/Tome19.json"
+ $.entries[41].uri: "archiveQuests/Tome15.json"
… 737 more change(s) — see the commit diff for everything
```

### [`featureLocks.json`](featureLocks.json)

[Full line-by-line diff](diffs/featureLocks.json.diff)

```diff
- $.featureLocks[2].id: "DAILYRITUALS"
+ $.featureLocks[2].id: "CUSTOMGAME"
+ $.featureLocks[3].role: "killer"
- $.featureLocks[3].condition[0].left: "matchCount:total"
+ $.featureLocks[3].condition[0].left: "matchCount:killer"
- $.featureLocks[3].condition[0].right: "5"
+ $.featureLocks[3].condition[0].right: "1"
- $.featureLocks[3].id: "CUSTOMGAME"
+ $.featureLocks[3].id: "BLOODWEB"
- $.featureLocks[4].condition[0].left: "matchCount:killer"
+ $.featureLocks[4].condition[0].left: "matchCount:survivor"
- $.featureLocks[4].role: "killer"
+ $.featureLocks[4].role: "survivor"
- $.featureLocks[5].condition[0].left: "matchCount:survivor"
+ $.featureLocks[5].condition[0].left: "matchCount:killer"
- $.featureLocks[5].condition[0].right: "1"
+ $.featureLocks[5].condition[0].right: "3"
- $.featureLocks[5].id: "BLOODWEB"
+ $.featureLocks[5].id: "OFFERINGS"
- $.featureLocks[5].role: "survivor"
+ $.featureLocks[5].role: "killer"
- $.featureLocks[6].condition[0].left: "matchCount:killer"
+ $.featureLocks[6].condition[0].left: "matchCount:survivor"
- $.featureLocks[6].condition[0].right: "3"
+ $.featureLocks[6].condition[0].right: "4"
- $.featureLocks[6].role: "killer"
+ $.featureLocks[6].role: "survivor"
- $.featureLocks[7].condition[0].right: "4"
+ $.featureLocks[7].condition[0].right: "1"
- $.featureLocks[7].id: "OFFERINGS"
+ $.featureLocks[7].id: "ITEMS"
- $.featureLocks[8].condition[0].left: "matchCount:survivor"
+ $.featureLocks[8].condition[0].left: "matchCount:killer"
- $.featureLocks[8].id: "ITEMS"
+ $.featureLocks[8].id: "ADDONS"
- $.featureLocks[8].role: "survivor"
+ $.featureLocks[8].role: "killer"
- $.featureLocks[9].condition[0].left: "matchCount:killer"
+ $.featureLocks[9].condition[0].left: "matchCount:survivor"
- $.featureLocks[9].condition[0].right: "1"
+ $.featureLocks[9].condition[0].right: "2"
- $.featureLocks[9].role: "killer"
+ $.featureLocks[9].role: "survivor"
- $.featureLocks[10].role: "survivor"
- $.featureLocks[10].condition[0].left: "matchCount:survivor"
+ $.featureLocks[10].condition[0].left: "matchCount:total"
- $.featureLocks[10].condition[0].right: "2"
+ $.featureLocks[10].condition[0].right: "6"
- $.featureLocks[10].id: "ADDONS"
+ $.featureLocks[10].id: "LTE"
- $.featureLocks[11]
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
+ $.disabledItems.K24
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
+ $.rewards.S46
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=IcecreamW3]
- $.featuredCard[id=IcecreamW4]
+ $.featuredCard[id=Jerky_W1]
+ $.featuredCard[id=Jerky_W2]
+ $.featuredCard[id=Jerky_W3]
+ $.featuredCard[id=Jerky_W4]
- $.featuredCard[id=IcecreamW1].entries[1].entryId: "RiftPass22_Bundle"
+ $.featuredCard[id=IcecreamW1].entries[1].entryId: "DBD-Store-Promo_2"
- $.featuredCard[id=IcecreamW1].entries[1].type: "SpecialPack"
+ $.featuredCard[id=IcecreamW1].entries[1].type: "CrossPromotion"
- $.featuredCard[id=IcecreamW1].entries[1].weight: 1
+ $.featuredCard[id=IcecreamW1].entries[1].weight: 2
- $.featuredCard[id=IcecreamW1].entries[2].entryId: "DBD-Store-Promo_2"
+ $.featuredCard[id=IcecreamW1].entries[2].entryId: "LicensorBundle_Domrebel"
- $.featuredCard[id=IcecreamW1].entries[2].type: "CrossPromotion"
+ $.featuredCard[id=IcecreamW1].entries[2].type: "SpecialPack"
- $.featuredCard[id=IcecreamW1].entries[2].weight: 2
+ $.featuredCard[id=IcecreamW1].entries[2].weight: 4
- $.featuredCard[id=IcecreamW1].entries[3]
- $.featuredCard[id=IcecreamW2].entries[0].entryId: "Bloodmoon"
+ $.featuredCard[id=IcecreamW2].entries[0].entryId: "TokyoGhoul"
- $.featuredCard[id=IcecreamW2].entries[1].entryId: "TokyoGhoul"
+ $.featuredCard[id=IcecreamW2].entries[1].entryId: "DBD-Store-Promo_2"
- $.featuredCard[id=IcecreamW2].entries[1].type: "Collection"
+ $.featuredCard[id=IcecreamW2].entries[1].type: "CrossPromotion"
- $.featuredCard[id=IcecreamW2].entries[1].weight: 0
+ $.featuredCard[id=IcecreamW2].entries[1].weight: 2
- $.featuredCard[id=IcecreamW2].entries[2]
- $.featuredCard[id=IcecreamW2].entries[3]
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Icecream"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Jerky"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_SteadyPulse.T_UI_ChapterBundle_SteadyPulse"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Gelato"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Icecream"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Eclair"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Gelato"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Donut"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Eclair"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "Churros"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "Donut"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "ApplePie"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "Churros"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "Zodiac"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "ApplePie"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "Yerkes"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "Zodiac"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Wormhole"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Yerkes"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Venus"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Wormhole"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].associatedDlcId: "Umbra"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].associatedDlcId: "Venus"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_EndTransmission.T_UI_ChapterBundle_EndTransmission"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[11]
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "268435494"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].characterIndex: "45"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Jerky/S46_OrelaRose_Portrait.S46_OrelaRose_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].characterIndex: "268435494"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "44"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].characterIndex: "268435493"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "268435492"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].characterIndex: "44"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "43"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].characterIndex: "268435492"
- $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[id=Featured_Characters].characters[5]
- $.featuredCustomizationRecommendations[id=HotdogW1]
- $.featuredCustomizationRecommendations[id=HotdogW2]
- $.featuredCustomizationRecommendations[id=HotdogW3]
- $.featuredCustomizationRecommendations[id=HotdogW4]
- $.featuredCustomizationRecommendations[id=HotdogW5]
- $.featuredCustomizationRecommendations[id=HotdogW6]
- $.featuredCustomizationRecommendations[id=HotdogW7]
- $.featuredCustomizationRecommendations[id=HotdogSale]
- $.featuredCustomizationRecommendations[id=HotdogW8]
- $.featuredCustomizationRecommendations[id=HotdogW9]
- $.featuredCustomizationRecommendations[id=IceCreamW1]
- $.featuredCustomizationRecommendations[id=HotdogW10]
- $.featuredCustomizationRecommendations[id=IceCreamW2]
- $.featuredCustomizationRecommendations[id=IceCreamW3]
- $.featuredCustomizationRecommendations[id=IceCreamW4]
+ $.featuredCustomizationRecommendations[id=JerkyW1]
+ $.featuredCustomizationRecommendations[id=IceCream_W1]
+ $.featuredCustomizationRecommendations[id=JerkyW2]
+ $.specialsRecommendations[id=2V8_Sale]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[45].mainEndTime: "2025-04-29T15:00:00"
+ $.specialEvents[45].mainEndTime: "2025-04-08T15:00:00"
- $.specialEvents[45].postEndTime: "2025-04-29T15:00:00"
+ $.specialEvents[45].postEndTime: "2025-04-08T15:00:00"
- $.specialEvents[46].mainEndTime: "2025-04-29T15:00:00"
+ $.specialEvents[46].mainEndTime: "2025-04-08T15:00:00"
- $.specialEvents[46].postEndTime: "2025-04-29T15:00:00"
+ $.specialEvents[46].postEndTime: "2025-04-08T15:00:00"
- $.specialEvents[47].startTime: "2025-04-29T15:01:00"
+ $.specialEvents[47].startTime: "2025-04-29T17:00:00"
```

## Could not download

- `images/T_UI_ChapterBundle_SteadyPulse.png (HTTP 404)`
- `images/T_UI_CollectionBanner_GuardiansAndShadows.png (HTTP 404)`
- `images/T_UI_CollectionBanner_SteadyPulse.png (HTTP 404)`
- `images/T_UI_SpecialPack_GuardiansAndShadows.png (HTTP 404)`
- `images/T_UI_SpecialPack_Rift1.png (HTTP 404)`
- `images/T_UI_SpecialPack_SteadyPulse.png (HTTP 404)`
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

