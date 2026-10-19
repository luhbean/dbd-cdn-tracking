# live · 8.6.0_2377854live

| | |
|---|---|
| Build date | 2025-04-08 14:07 UTC |
| CDN version | `8.6.0_2377854live-1744121265` |
| Key | `8.6.0_live` |
| Compared with | [8.5.2_2369089live](../8.5.2_2369089live/CHANGES.md) (2025-04-01 15:07 UTC) |

## Summary

**1** added · **18** modified · **6** removed · 166 unchanged

## Added files

- [`archiveQuests/Spring2025.json`](archiveQuests/Spring2025.json)

## Removed files

- `contentMetadata.json`
- `images/T_UI_SpecialPack_Tome1.png`
- `images/T_UI_SpecialPack_Tome2.png`
- `images/T_UI_SpecialPack_Tome3.png`
- `images/T_UI_SpecialPack_Tome4.png`
- `images/T_UI_SpecialPack_Wasteland.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.dedicatedServer.latencyPingsComputationMethod: "Minimum"
+ $.dedicatedServer.endpointsUDP[14]
- $.dedicatedServer.suspiciousEnabledBuilds[]: "DBD_Churros_DS_Lin_Test_409_1759908"
+ $.dedicatedServer.suspiciousEnabledBuilds[]: "DBD_Live_DS_Lin_Test_472_1566101"
+ $.match.disableSurrender: false
- $.seenPopupsConfig.MarketingInvitationPopup
- $.socialCrossprogressionPlatforms.grdk: false
+ $.socialCrossprogressionPlatforms.grdk: true
- $.socialCrossprogressionPlatforms.ps4: false
+ $.socialCrossprogressionPlatforms.ps4: true
- $.socialCrossprogressionPlatforms.ps5: false
+ $.socialCrossprogressionPlatforms.ps5: true
- $.socialCrossprogressionPlatforms.switch: false
+ $.socialCrossprogressionPlatforms.switch: true
- $.socialCrossprogressionPlatforms.xbox: false
+ $.socialCrossprogressionPlatforms.xbox: true
- $.socialCrossprogressionPlatforms.xsx: false
+ $.socialCrossprogressionPlatforms.xsx: true
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.analyticsRulesDedicatedServer.KL[]: "MatchStartAnalytics"
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
+ $.Spring2025
```

### [`archiveQuests/Tome02.json`](archiveQuests/Tome02.json)

[Full line-by-line diff](diffs/archiveQuests/Tome02.json.diff)

```diff
+ $.Tome02.level[0].nodes.node_L1_19.objectives.DoctorInflictMadness1DifferentInTrial.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome02.level[2].nodes.node_L3_15.objectives.DoctorInflictMadness3InTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[2].nodes.node_L3_15.objectives.DoctorInflictMadness3InTrial.questEvent[0].parameters: "target:any"
```

### [`archiveQuests/Tome03.json`](archiveQuests/Tome03.json)

[Full line-by-line diff](diffs/archiveQuests/Tome03.json.diff)

```diff
- $.Tome03.level[1].nodes.node_T3L2_01.coordinates.y: 23.076923076923077
+ $.Tome03.level[1].nodes.node_T3L2_01.coordinates.y: 23.07692308
- $.Tome03.level[1].nodes.node_T3L2_02.coordinates.y: 46.15384615384615
+ $.Tome03.level[1].nodes.node_T3L2_02.coordinates.y: 46.15384615
- $.Tome03.level[1].nodes.node_T3L2_04.coordinates.x: 73.33333333333333
+ $.Tome03.level[1].nodes.node_T3L2_04.coordinates.x: 73.33333333
- $.Tome03.level[1].nodes.node_T3L2_04.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_04.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_05.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_05.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_06.coordinates.x: 13.333333333333334
+ $.Tome03.level[1].nodes.node_T3L2_06.coordinates.x: 13.33333333
- $.Tome03.level[1].nodes.node_T3L2_06.coordinates.y: 92.3076923076923
+ $.Tome03.level[1].nodes.node_T3L2_06.coordinates.y: 92.30769231
- $.Tome03.level[1].nodes.node_T3L2_07.coordinates.x: 33.333333333333336
+ $.Tome03.level[1].nodes.node_T3L2_07.coordinates.x: 33.33333333
- $.Tome03.level[1].nodes.node_T3L2_07.coordinates.y: 92.3076923076923
+ $.Tome03.level[1].nodes.node_T3L2_07.coordinates.y: 92.30769231
- $.Tome03.level[1].nodes.node_T3L2_08.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_08.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_10.coordinates.x: 86.66666666666667
+ $.Tome03.level[1].nodes.node_T3L2_10.coordinates.x: 86.66666667
- $.Tome03.level[1].nodes.node_T3L2_10.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_10.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_11.coordinates.x: 13.333333333333334
+ $.Tome03.level[1].nodes.node_T3L2_11.coordinates.x: 13.33333333
- $.Tome03.level[1].nodes.node_T3L2_12.coordinates.x: 86.66666666666667
+ $.Tome03.level[1].nodes.node_T3L2_12.coordinates.x: 86.66666667
- $.Tome03.level[1].nodes.node_T3L2_12.coordinates.y: 23.076923076923077
+ $.Tome03.level[1].nodes.node_T3L2_12.coordinates.y: 23.07692308
- $.Tome03.level[1].nodes.node_T3L2_13.coordinates.x: 46.666666666666664
+ $.Tome03.level[1].nodes.node_T3L2_13.coordinates.x: 46.66666667
- $.Tome03.level[1].nodes.node_T3L2_13.coordinates.y: 23.076923076923077
+ $.Tome03.level[1].nodes.node_T3L2_13.coordinates.y: 23.07692308
- $.Tome03.level[1].nodes.node_T3L2_14.coordinates.x: 66.66666666666667
+ $.Tome03.level[1].nodes.node_T3L2_14.coordinates.x: 66.66666667
- $.Tome03.level[1].nodes.node_T3L2_14.coordinates.y: 23.076923076923077
+ $.Tome03.level[1].nodes.node_T3L2_14.coordinates.y: 23.07692308
- $.Tome03.level[1].nodes.node_T3L2_17.coordinates.x: 66.66666666666667
+ $.Tome03.level[1].nodes.node_T3L2_17.coordinates.x: 66.66666667
- $.Tome03.level[1].nodes.node_T3L2_17.coordinates.y: 46.15384615384615
+ $.Tome03.level[1].nodes.node_T3L2_17.coordinates.y: 46.15384615
- $.Tome03.level[1].nodes.node_T3L2_19.coordinates.x: 6.666666666666667
+ $.Tome03.level[1].nodes.node_T3L2_19.coordinates.x: 6.666666667
- $.Tome03.level[1].nodes.node_T3L2_19.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_19.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_20.coordinates.y: 69.23076923076923
+ $.Tome03.level[1].nodes.node_T3L2_20.coordinates.y: 69.23076923
- $.Tome03.level[1].nodes.node_T3L2_21.coordinates.x: 46.666666666666664
+ $.Tome03.level[1].nodes.node_T3L2_21.coordinates.x: 46.66666667
- $.Tome03.level[1].nodes.node_T3L2_21.coordinates.y: 92.3076923076923
+ $.Tome03.level[1].nodes.node_T3L2_21.coordinates.y: 92.30769231
- $.Tome03.level[1].nodes.node_T3L2_22.coordinates.x: 73.33333333333333
+ $.Tome03.level[1].nodes.node_T3L2_22.coordinates.x: 73.33333333
- $.Tome03.level[1].nodes.node_T3L2_22.coordinates.y: 92.3076923076923
+ $.Tome03.level[1].nodes.node_T3L2_22.coordinates.y: 92.30769231
- $.Tome03.level[1].nodes.node_T3L2_23.coordinates.x: 6.666666666666667
+ $.Tome03.level[1].nodes.node_T3L2_23.coordinates.x: 6.666666667
- $.Tome03.level[1].nodes.node_T3L2_23.coordinates.y: 46.15384615384615
+ $.Tome03.level[1].nodes.node_T3L2_23.coordinates.y: 46.15384615
- $.Tome03.level[1].nodes.node_T3L2_25.coordinates.y: 46.15384615384615
+ $.Tome03.level[1].nodes.node_T3L2_25.coordinates.y: 46.15384615
- $.Tome03.level[1].nodes.node_T3L2_28.coordinates.x: 33.333333333333336
+ $.Tome03.level[1].nodes.node_T3L2_28.coordinates.x: 33.33333333
- $.Tome03.level[1].nodes.node_T3L2_28.coordinates.y: 23.076923076923077
+ $.Tome03.level[1].nodes.node_T3L2_28.coordinates.y: 23.07692308
- $.Tome03.level[1].nodes.node_T3L2_28.objectives.HuntressHatchetChargedHitInTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome03.level[1].nodes.node_T3L2_28.objectives.HuntressHatchetChargedHitInTrial.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome03.level[1].nodes.node_T3L2_End01.coordinates.y: 46.15384615384615
+ $.Tome03.level[1].nodes.node_T3L2_End01.coordinates.y: 46.15384615
- $.Tome03.level[1].nodes.node_T3L2_Start02.coordinates.y: 92.3076923076923
+ $.Tome03.level[1].nodes.node_T3L2_Start02.coordinates.y: 92.30769231
```

### [`archiveQuests/Tome15.json`](archiveQuests/Tome15.json)

[Full line-by-line diff](diffs/archiveQuests/Tome15.json.diff)

```diff
+ $.Tome15.level[2].nodes.node_T15_L3_05.objectives.DoctorInflictMadness3InTrial.questEvent[0].parameters: "instigator:me;target:any"
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
+ $.EventChestProbability[10]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=AV_Head00]
- $[id=AV_Head01_CV02]
- $[id=AV_Head01_CV03]
- $[id=AV_Head01_CV04]
- $[id=AV_Legs00]
- $[id=AV_Legs01_CV02]
- $[id=AV_Legs01_CV03]
- $[id=AV_Legs01_CV04]
- $[id=AV_Torso00]
- $[id=AV_Torso01_CV02]
- $[id=AV_Torso01_CV03]
- $[id=AV_Torso01_CV04]
- $[id=BE_W02_02]
- $[id=CM_Head00]
- $[id=CM_Head002_02]
- $[id=CM_Head01_CV05]
- $[id=CM_Head01_CV07]
- $[id=CM_Legs00]
- $[id=CM_Legs002_01]
- $[id=CM_Legs01_CV05]
- $[id=CM_Legs01_CV07]
- $[id=CM_Torso00]
- $[id=CM_Torso002_01]
- $[id=CM_Torso01_CV05]
- $[id=CM_Torso01_CV07]
- $[id=CM_Torso04_Mods]
- $[id=DF_Head00]
- $[id=DF_Head01_CV05]
- $[id=DF_Head01_CV06]
- $[id=DF_Head01_CV07]
- $[id=DF_Legs00]
- $[id=DF_Legs01_CV05]
- $[id=DF_Legs01_CV06]
- $[id=DF_Legs01_CV07]
- $[id=DF_Torso00]
- $[id=DF_Torso01_CV05]
- $[id=DF_Torso01_CV06]
- $[id=DF_Torso01_CV07]
- $[id=DF_Torso04_Mods]
- $[id=DK_Head00]
- $[id=DK_Legs00]
- $[id=DK_Legs01_CV06]
- $[id=DK_Torso00]
- $[id=DK_Torso01_CV06]
- $[id=FM_Head00]
- $[id=FM_Legs00]
- $[id=FM_Legs01_CV05]
- $[id=FM_Legs01_CV06]
- $[id=FM_Legs01_CV07]
- $[id=FM_Torso00]
- $[id=FM_Torso01_CV05]
- $[id=FM_Torso01_CV06]
- $[id=FM_Torso01_CV07]
- $[id=GS_Legs01_CV03]
- $[id=GS_Torso01_CV03]
- $[id=JP_Head00]
- $[id=JP_Head01_CV06]
- $[id=JP_Head01_CV07]
- $[id=JP_Head01_CV08]
- $[id=JP_Legs00]
- $[id=JP_Legs01_CV06]
- $[id=JP_Legs01_CV07]
- $[id=JP_Legs01_CV08]
- $[id=JP_Torso00]
- $[id=JP_Torso01_CV06]
- $[id=JP_Torso01_CV07]
- $[id=JP_Torso01_CV08]
- $[id=JP_Torso04_Mods]
- $[id=MT_Head00]
- $[id=MT_Head01_CV04]
- $[id=MT_Head01_CV05]
- $[id=MT_Head01_CV06]
- $[id=MT_Head01_CV07]
- $[id=MT_Legs00]
- $[id=MT_Legs01_CV04]
- $[id=MT_Legs01_CV05]
- $[id=MT_Legs01_CV06]
- $[id=MT_Legs01_CV07]
- $[id=MT_Torso00]
- $[id=MT_Torso01_CV04]
- $[id=MT_Torso01_CV05]
- $[id=MT_Torso01_CV06]
- $[id=MT_Torso01_CV07]
- $[id=MT_Torso04_Mods]
- $[id=NK_Legs02_CV06]
- $[id=NK_Torso01_Mods]
- $[id=NK_Torso02_CV06]
- $[id=TR_Mask08]
- $[id=TR_Mask08_01]
- $[id=TR_Mask08_02]
- $[id=TR_Mask08_03]
- $[id=TR_Mask08_04]
- $[id=TR_Mask08_05]
- $[id=TRW_P03]
- $[id=Ace_outfit_011]
- $[id=Ace_outfit_012]
- $[id=Ace_outfit_013]
- $[id=Claudette_outfit_005]
- $[id=Claudette_outfit_015]
- $[id=Claudette_outfit_017]
- $[id=Dwight_outfit_015]
- $[id=Dwight_outfit_016]
- $[id=Dwight_outfit_017]
- $[id=Jake_outfit_014]
- $[id=Jake_outfit_015]
- $[id=Jake_outfit_016]
- $[id=Meg_outfit_017]
- $[id=Meg_outfit_018]
- $[id=Meg_outfit_019]
- $[id=Meg_outfit_020]
+ $[id=K39]
+ $[id=AV_Torso021_02]
+ $[id=CM_Head030]
+ $[id=CM_Legs030]
+ $[id=CM_Torso027_02]
+ $[id=CM_Torso030]
+ $[id=DK_Head028]
+ $[id=GK_W024]
+ $[id=GS_Torso035]
+ $[id=HS_Torso022_02]
+ $[id=HS_Torso028]
+ $[id=IC_001]
+ $[id=IC_BDG_01]
+ $[id=IC_BDG_02]
+ $[id=IC_BDG_03]
+ $[id=IC_BDG_04]
+ $[id=IC_BDG_05]
+ $[id=IC_BDG_06]
+ $[id=IC_BDG_07]
+ $[id=IC_BDG_08]
+ $[id=IC_BDG_09]
+ $[id=IC_BDG_10]
+ $[id=IC_BDG_12]
+ $[id=IC_BDG_13]
+ $[id=IC_BDG_14]
+ $[id=IC_BDG_15]
+ $[id=IC_BNR_01]
+ $[id=IC_BNR_02]
+ $[id=IC_BNR_03]
+ $[id=IC_BNR_04]
+ $[id=IC_BNR_05]
+ $[id=IC_BNR_06]
+ $[id=IC_BNR_07]
+ $[id=IC_BNR_08]
+ $[id=IC_BNR_09]
+ $[id=IC_BNR_10]
+ $[id=IC_BNR_11]
+ $[id=JP_Head028]
+ $[id=K26_Body019]
+ $[id=K26_Head019]
+ $[id=K26_W019]
+ $[id=K30_Body012]
+ $[id=K30_W012]
+ $[id=K32_W012]
+ $[id=K35_Head013]
+ $[id=K38_Body007]
+ $[id=K38_Head007]
+ $[id=K38_W007]
+ $[id=K39_Body008]
+ $[id=K39_Body01]
+ $[id=K39_Body01_P01]
+ $[id=K39_Body02]
+ $[id=K39_Head008]
+ $[id=K39_Head01]
+ $[id=K39_Head01_P01]
+ $[id=K39_Head02]
+ $[id=K39_PCharm001]
+ $[id=K39_PCharm002]
+ $[id=K39_PCharm003]
+ $[id=K39_W008]
+ $[id=K39_W01_P01]
+ $[id=K39_W02]
+ $[id=K39_Weapon01]
+ $[id=NK_Head035]
+ $[id=NK_Legs035]
+ $[id=NK_Torso028_02]
+ $[id=NK_Torso035]
+ $[id=S29_Head023]
+ $[id=S31_Torso020]
+ $[id=S34_Head021]
+ $[id=S34_Legs021]
+ $[id=S34_Torso021]
+ $[id=S36_Head021]
+ $[id=S36_Legs021]
+ $[id=S36_Torso021]
+ $[id=S45_Head011]
+ $[id=S45_Legs011]
+ $[id=S45_Torso011]
+ $[id=SS_Head029]
+ $[id=SS_Legs029]
+ $[id=SS_Torso029]
+ $[id=TR_Body027]
+ $[id=TR_Mask027]
+ $[id=TR_W027]
+ $[id=WI_W018]
+ $[id=CM_outfit_030]
+ $[id=K26_outfit_019]
+ $[id=K30_outfit_012]
+ $[id=K38_outfit_007]
+ $[id=K39_outfit_008]
… 584 more change(s) — see the commit diff for everything
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[2].additionalImages[0]
- $.collections[2].collectionId: "Hanami"
+ $.collections[2].collectionId: "TokyoGhoul"
- $.collections[2].collectionTitle.de: "Hanami "
+ $.collections[2].collectionTitle.de: "Tokyo Ghoul"
- $.collections[2].collectionTitle.en: "Hanami "
+ $.collections[2].collectionTitle.en: "Tokyo Ghoul"
- $.collections[2].collectionTitle.es: "Hanami "
+ $.collections[2].collectionTitle.es: "Tokyo Ghoul"
- $.collections[2].collectionTitle["es-MX"]: "Hanami "
+ $.collections[2].collectionTitle["es-MX"]: "Tokyo Ghoul"
- $.collections[2].collectionTitle.fr: "Hanami "
+ $.collections[2].collectionTitle.fr: "Tokyo Ghoul"
- $.collections[2].collectionTitle.it: "Hanami "
+ $.collections[2].collectionTitle.it: "Tokyo Ghoul"
- $.collections[2].collectionTitle.ja: "花見 "
+ $.collections[2].collectionTitle.ja: "東京喰種"
- $.collections[2].collectionTitle.ko: "벚꽃 축제 "
+ $.collections[2].collectionTitle.ko: "도쿄 구울"
- $.collections[2].collectionTitle.pl: "Hanami "
+ $.collections[2].collectionTitle.pl: "Tokyo Ghoul"
- $.collections[2].collectionTitle["pt-BR"]: "Hanami "
+ $.collections[2].collectionTitle["pt-BR"]: "Tokyo Ghoul"
- $.collections[2].collectionTitle.ru: "Ханами "
+ $.collections[2].collectionTitle.ru: "Токийский гуль"
- $.collections[2].collectionTitle.th: "ฮานามิ "
+ $.collections[2].collectionTitle.th: "Tokyo Ghoul"
- $.collections[2].collectionTitle.tr: "Hanami "
+ $.collections[2].collectionTitle.tr: "Tokyo Gûl"
- $.collections[2].collectionTitle["zh-Hans"]: "花见 "
+ $.collections[2].collectionTitle["zh-Hans"]: "《Tokyo Ghoul》"
- $.collections[2].collectionTitle["zh-Hant"]: "賞花 "
+ $.collections[2].collectionTitle["zh-Hant"]: "《東京喰種》"
- $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
+ $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
- $.collections[2].inclusionVersion: "7.7.0 PTB"
+ $.collections[2].inclusionVersion: "8.6.0"
- $.collections[2].items[]: "MS_outfit_016"
- $.collections[2].items[]: "SwedenSurvivor_outfit_015"
- $.collections[2].items[]: "HK_outfit_014"
+ $.collections[2].items[]: "K39_outfit_02"
+ $.collections[2].items[]: "K39_outfit_008"
+ $.collections[2].items[]: "SS_outfit_029"
+ $.collections[2].items[]: "NK_outfit_035"
+ $.collections[2].items[]: "S36_outfit_021"
+ $.collections[2].items[]: "K35_Head013"
+ $.collections[2].items[]: "S29_Head023"
+ $.collections[2].items[]: "JP_Head028"
+ $.collections[2].items[]: "DK_Head028"
- $.collections[2].sortOrder: "-13"
+ $.collections[2].sortOrder: "-103"
- $.collections[2].updatedDate: "2024-02-01T17:19:10Z"
+ $.collections[2].updatedDate: "2025-01-13T17:01:53.962Z"
+ $.collections[3].limitedAvailabilityEndDate: "2025-04-29T15:00:00Z"
+ $.collections[3].limitedAvailabilityStartDate: "2025-04-07T15:00:00Z"
+ $.collections[3].visibleAfterEndDate: false
+ $.collections[3].visibleBeforeStartDate: false
+ $.collections[3].additionalImages[0]
- $.collections[3].collectionId: "Rockabilly"
+ $.collections[3].collectionId: "Bloodmoon"
- $.collections[3].collectionTitle.de: "Rockabilly"
+ $.collections[3].collectionTitle.de: "Blutmond"
- $.collections[3].collectionTitle.en: "Rockabilly"
+ $.collections[3].collectionTitle.en: "Blood Moon"
- $.collections[3].collectionTitle.es: "Rockabilly"
+ $.collections[3].collectionTitle.es: "Luna de sangre"
- $.collections[3].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[3].collectionTitle["es-MX"]: "Luna de sangre"
- $.collections[3].collectionTitle.fr: "Rockabilly"
+ $.collections[3].collectionTitle.fr: "Lune de sang"
- $.collections[3].collectionTitle.it: "Rockabilly"
+ $.collections[3].collectionTitle.it: "Luna sanguinosa"
- $.collections[3].collectionTitle.ja: "ロカビリー "
+ $.collections[3].collectionTitle.ja: "ブラッドムーン"
- $.collections[3].collectionTitle.ko: "로커빌리"
+ $.collections[3].collectionTitle.ko: "핏빛 달"
- $.collections[3].collectionTitle.pl: "Rockabilly"
+ $.collections[3].collectionTitle.pl: "Krwawy księżyc"
- $.collections[3].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[3].collectionTitle["pt-BR"]: "Lua de Sangue"
- $.collections[3].collectionTitle.ru: "Рокабилли"
+ $.collections[3].collectionTitle.ru: "Кровавая луна"
- $.collections[3].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[3].collectionTitle.th: "จันทราโลหิต"
- $.collections[3].collectionTitle.tr: "Rockabilly"
+ $.collections[3].collectionTitle.tr: "Kanlı Ay"
- $.collections[3].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[3].collectionTitle["zh-Hans"]: "血月"
- $.collections[3].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[3].collectionTitle["zh-Hant"]: "血月"
- $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
- $.collections[3].inclusionVersion: "7.7.0 PTB"
+ $.collections[3].inclusionVersion: "8.6.0"
- $.collections[3].items[]: "AV_outfit_015"
- $.collections[3].items[]: "MS_outfit_014"
- $.collections[3].items[]: "GS_outfit_014"
- $.collections[3].items[]: "MT_outfit_015"
- $.collections[3].items[]: "NK_outfit_014"
- $.collections[3].items[]: "S23_outfit_016"
- $.collections[3].items[]: "S24_outfit_013"
+ $.collections[3].items[]: "AV_outfit_022"
+ $.collections[3].items[]: "DO_outfit_020"
+ $.collections[3].items[]: "K31_outfit_012"
+ $.collections[3].items[]: "S24_outfit_021"
+ $.collections[3].items[]: "S28_outfit_023"
+ $.collections[3].items[]: "SwedenKiller_outfit_021"
+ $.collections[3].items[]: "K26_outfit_019"
+ $.collections[3].items[]: "K30_outfit_012"
+ $.collections[3].items[]: "K38_outfit_007"
+ $.collections[3].items[]: "CM_outfit_030"
+ $.collections[3].items[]: "S45_outfit_011"
- $.collections[3].sortOrder: "-14"
+ $.collections[3].sortOrder: "-104"
- $.collections[3].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[3].updatedDate: "2025-01-08T21:01:45.055Z"
- $.collections[4].collectionId: "SpringEnsembles"
+ $.collections[4].collectionId: "Hanami"
- $.collections[4].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[4].collectionTitle.de: "Hanami "
- $.collections[4].collectionTitle.en: "Spring Ensembles"
+ $.collections[4].collectionTitle.en: "Hanami "
- $.collections[4].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[4].collectionTitle.es: "Hanami "
- $.collections[4].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[4].collectionTitle["es-MX"]: "Hanami "
- $.collections[4].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[4].collectionTitle.fr: "Hanami "
- $.collections[4].collectionTitle.it: "Completi primaverili"
+ $.collections[4].collectionTitle.it: "Hanami "
- $.collections[4].collectionTitle.ja: "春のアンサンブル"
+ $.collections[4].collectionTitle.ja: "花見 "
- $.collections[4].collectionTitle.ko: "봄의 조화"
+ $.collections[4].collectionTitle.ko: "벚꽃 축제 "
- $.collections[4].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[4].collectionTitle.pl: "Hanami "
- $.collections[4].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[4].collectionTitle["pt-BR"]: "Hanami "
- $.collections[4].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[4].collectionTitle.ru: "Ханами "
- $.collections[4].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[4].collectionTitle.th: "ฮานามิ "
- $.collections[4].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[4].collectionTitle.tr: "Hanami "
- $.collections[4].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[4].collectionTitle["zh-Hans"]: "花见 "
- $.collections[4].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[4].collectionTitle["zh-Hant"]: "賞花 "
- $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[4].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
- $.collections[4].items[]: "Ace_outfit_008_01"
- $.collections[4].items[]: "HillBilly_outfit_008_01"
- $.collections[4].items[]: "FM_outfit_011"
- $.collections[4].items[]: "FM_outfit_011_01"
- $.collections[4].items[]: "S28_outfit_011"
- $.collections[4].items[]: "US_outfit_015"
- $.collections[4].items[]: "K21_outfit_010"
- $.collections[4].items[]: "K26_outfit_007"
- $.collections[4].items[]: "GK_outfit_013"
- $.collections[4].items[]: "S29_outfit_008"
+ $.collections[4].items[]: "MS_outfit_016"
+ $.collections[4].items[]: "SwedenSurvivor_outfit_015"
+ $.collections[4].items[]: "HK_outfit_014"
- $.collections[4].sortOrder: "-15"
+ $.collections[4].sortOrder: "-13"
- $.collections[4].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[4].updatedDate: "2024-02-01T17:19:10Z"
- $.collections[5].collectionId: "Leatherface"
+ $.collections[5].collectionId: "Rockabilly"
- $.collections[5].collectionTitle.de: "Leatherface"
+ $.collections[5].collectionTitle.de: "Rockabilly"
- $.collections[5].collectionTitle.en: "Leatherface"
+ $.collections[5].collectionTitle.en: "Rockabilly"
- $.collections[5].collectionTitle.es: "Cara de cuero"
+ $.collections[5].collectionTitle.es: "Rockabilly"
- $.collections[5].collectionTitle["es-MX"]: "Cara de cuero"
+ $.collections[5].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[5].collectionTitle.fr: "Leatherface"
+ $.collections[5].collectionTitle.fr: "Rockabilly"
- $.collections[5].collectionTitle.it: "Faccia di cuoio"
+ $.collections[5].collectionTitle.it: "Rockabilly"
- $.collections[5].collectionTitle.ja: "レザーフェイス"
+ $.collections[5].collectionTitle.ja: "ロカビリー "
- $.collections[5].collectionTitle.ko: "가죽 가면"
+ $.collections[5].collectionTitle.ko: "로커빌리"
- $.collections[5].collectionTitle.pl: "Leatherface"
+ $.collections[5].collectionTitle.pl: "Rockabilly"
- $.collections[5].collectionTitle["pt-BR"]: "Leatherface"
+ $.collections[5].collectionTitle["pt-BR"]: "Rockabilly"
- $.collections[5].collectionTitle.ru: "Кожаное Лицо"
+ $.collections[5].collectionTitle.ru: "Рокабилли"
- $.collections[5].collectionTitle.th: "หน้ากากหนัง"
+ $.collections[5].collectionTitle.th: "ร็อกอะบิลลี่"
- $.collections[5].collectionTitle.tr: "Deri Surat"
+ $.collections[5].collectionTitle.tr: "Rockabilly"
- $.collections[5].collectionTitle["zh-Hans"]: "人皮脸"
+ $.collections[5].collectionTitle["zh-Hans"]: "山区摇滚"
- $.collections[5].collectionTitle["zh-Hant"]: "皮臉"
+ $.collections[5].collectionTitle["zh-Hant"]: "鄉村搖滾"
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Leatherface.T_UI_CollectionBanner_Leatherface"
… 4171 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
+ $.schedule[0].GameModes[]: "SeasonalEvent_FuelGenerator"
+ $.schedule[0].MapsWeight.Ion_Shack: "750"
- $.schedule[0].MapsWeight.Eng_Street_01: "200"
+ $.schedule[0].MapsWeight.Eng_Street_01: "750"
- $.schedule[0].MapsWeight.Eng_Street_02: "200"
+ $.schedule[0].MapsWeight.Eng_Street_02: "1"
- $.schedule[0].MapsWeight.Eng_Street_03: "200"
+ $.schedule[0].MapsWeight.Eng_Street_03: "1"
- $.schedule[0].MapsWeight.Eng_Street_04: "200"
+ $.schedule[0].MapsWeight.Eng_Street_04: "1"
- $.schedule[0].MapsWeight.Eng_Street_05: "200"
+ $.schedule[0].MapsWeight.Eng_Street_05: "1"
- $.schedule[0].MapsWeight.Hti_Manor: "500"
+ $.schedule[0].MapsWeight.Hti_Manor: "750"
- $.schedule[0].MapsWeight.Hti_Manor02: "500"
+ $.schedule[0].MapsWeight.Hti_Manor02: "1"
- $.schedule[0].MapsWeight.Hti_Shrine: "500"
+ $.schedule[0].MapsWeight.Hti_Shrine: "750"
- $.schedule[0].MapsWeight.Hti_Shrine02: "500"
+ $.schedule[0].MapsWeight.Hti_Shrine02: "1"
- $.schedule[0].MapsWeight.Ind_CoalTower: "200"
+ $.schedule[0].MapsWeight.Ind_CoalTower: "500"
- $.schedule[0].MapsWeight.Ind_CoalTower02: "200"
+ $.schedule[0].MapsWeight.Ind_CoalTower02: "1"
- $.schedule[0].MapsWeight.Ind_Forest: "200"
+ $.schedule[0].MapsWeight.Ind_Forest: "500"
- $.schedule[0].MapsWeight.Ind_Forest02: "200"
+ $.schedule[0].MapsWeight.Ind_Forest02: "1"
- $.schedule[0].MapsWeight.Ind_Foundry: "200"
+ $.schedule[0].MapsWeight.Ind_Foundry: "500"
- $.schedule[0].MapsWeight.Ind_Foundry02: "200"
+ $.schedule[0].MapsWeight.Ind_Foundry02: "1"
- $.schedule[0].MapsWeight.Ind_Mine: "200"
+ $.schedule[0].MapsWeight.Ind_Mine: "500"
- $.schedule[0].MapsWeight.Ind_Mine02: "200"
+ $.schedule[0].MapsWeight.Ind_Mine02: "1"
- $.schedule[0].MapsWeight.Ind_Storehouse: "200"
+ $.schedule[0].MapsWeight.Ind_Storehouse: "500"
- $.schedule[0].MapsWeight.Ind_Storehouse02: "200"
+ $.schedule[0].MapsWeight.Ind_Storehouse02: "1"
- $.schedule[0].MapsWeight.Ion_level_01: "1000"
+ $.schedule[0].MapsWeight.Ion_level_01: "750"
- $.schedule[0].MapsWeight.Kny_Cottage02: "750"
+ $.schedule[0].MapsWeight.Kny_Cottage02: "1"
- $.schedule[0].MapsWeight.Kny_Cottage03: "750"
+ $.schedule[0].MapsWeight.Kny_Cottage03: "1"
- $.schedule[3].EndDate: "2024-12-12T15:59:00"
- $.schedule[3].StartDate: "2024-11-25T15:00:00"
+ $.schedule[3].GameModes
- $.schedule[3].Description: "Killswitch"
+ $.schedule[3].Description: "RemovedFromRotation"
- $.schedule[3].MapsWeight.Glo_Level_01: "0"
+ $.schedule[3].MapsWeight.Eng_Street_02: "0"
+ $.schedule[3].MapsWeight.Eng_Street_03: "0"
+ $.schedule[3].MapsWeight.Eng_Street_04: "0"
+ $.schedule[3].MapsWeight.Eng_Street_05: "0"
+ $.schedule[3].MapsWeight.Hti_Manor02: "0"
+ $.schedule[3].MapsWeight.Hti_Shrine02: "0"
+ $.schedule[3].MapsWeight.Ind_CoalTower02: "0"
+ $.schedule[3].MapsWeight.Ind_Forest02: "0"
+ $.schedule[3].MapsWeight.Ind_Foundry02: "0"
+ $.schedule[3].MapsWeight.Ind_Mine02: "0"
+ $.schedule[3].MapsWeight.Ind_Storehouse02: "0"
+ $.schedule[3].MapsWeight.Kny_Cottage02: "0"
+ $.schedule[3].MapsWeight.Kny_Cottage03: "0"
- $.schedule[4].EndDate: "2024-12-15T15:59:00"
- $.schedule[4].StartDate: "2024-12-12T16:00:00"
+ $.schedule[4].GameModes
- $.schedule[4].Description: "Map_Boost"
+ $.schedule[4].Description: "EventMapAdjust"
- $.schedule[4].MapsWeight.Glo_Level_01: "7000"
+ $.schedule[4].MapsWeight.Eng_Street_01: "100"
+ $.schedule[4].MapsWeight.Qat_Lab: "100"
+ $.schedule[4].MapsWeight.Qtm_Level_02: "100"
+ $.schedule[4].MapsWeight.Wal_Level_01: "100"
- $.schedule[4].Priority: "5"
+ $.schedule[4].Priority: "6"
- $.schedule[5]
```

### [`coreRituals.json`](coreRituals.json)

[Full line-by-line diff](diffs/coreRituals.json.diff)

```diff
+ $.data[id=DR_ghoul]
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
+ $.dlcList.Icecream
+ $.dlcList.IcecreamCust
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "7e9bb9cbc6129d7b93eb1a2becffbb05525639be"
+ $.entries[0].contentVersion: "67c01e47c54f78385210ab74a876a00e89d5ccca"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Wasteland.T_UI_SpecialPack_Wasteland"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_BloodmoonBundle.T_UI_SpecialPack_BloodmoonBundle"
- $.entries[0].uri: "images/T_UI_SpecialPack_Wasteland.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_BloodmoonBundle.png"
- $.entries[1].contentVersion: "b818bdf525cccfbb0fcc820f0cc48abbb58b9bb4"
+ $.entries[1].contentVersion: "0c2d2a6e13151bce7029fad8596bae18619b82a6"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Tome1.T_UI_SpecialPack_Tome1"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
- $.entries[1].uri: "images/T_UI_SpecialPack_Tome1.png"
+ $.entries[1].uri: "images/T_UI_ChapterBundle_TokyoGhoul.png"
- $.entries[2].contentVersion: "83d9bba5f3cf318378d4b4247c7f34313f37071f"
+ $.entries[2].contentVersion: "007f0cc71fe1edaa7bbe1aaeeb6ebeedd0c03d1d"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Tome2.T_UI_SpecialPack_Tome2"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
- $.entries[2].uri: "images/T_UI_SpecialPack_Tome2.png"
+ $.entries[2].uri: "images/T_UI_CollectionBanner_Bloodmoon.png"
- $.entries[3].contentVersion: "828948a9e4b2816b2cec7390af40dbb7a8507ffe"
+ $.entries[3].contentVersion: "9e9b93b257e0ae4072d0401de636ed5ae63fe442"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Tome3.T_UI_SpecialPack_Tome3"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
- $.entries[3].uri: "images/T_UI_SpecialPack_Tome3.png"
+ $.entries[3].uri: "images/T_UI_SpecialPack_Bloodmoon.png"
- $.entries[4].contentVersion: "81bd8b50d5c6189c369286cc3c1eea1245ed8e12"
+ $.entries[4].contentVersion: "89f46233ea81e5cc1a4a25b6f20bd13045764eef"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Tome4.T_UI_SpecialPack_Tome4"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_TokyoGhoul.T_UI_CollectionBanner_TokyoGhoul"
- $.entries[4].uri: "images/T_UI_SpecialPack_Tome4.png"
+ $.entries[4].uri: "images/T_UI_CollectionBanner_TokyoGhoul.png"
- $.entries[5].contentVersion: "0af46be5fa8d2787dd8fb885cc30c0b73ea5fa33"
+ $.entries[5].contentVersion: "daf805a25a74cfe7a2374be5a59731ccd60e438a"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_TokyoGhoul.T_UI_SpecialPack_TokyoGhoul"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "catalog.json"
+ $.entries[5].uri: "images/T_UI_SpecialPack_TokyoGhoul.png"
- $.entries[6].contentVersion: "eaa89a42558391113270baa6df715723ca7c9ade"
+ $.entries[6].contentVersion: "d3e2512bfcf0e3d8b491dd487265e48b3d730bc5"
- $.entries[6].uri: "bonusPointEventsContent.json"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "685c9bb83a6a6a3846260c1b15d9f2fe746bac5a"
+ $.entries[7].contentVersion: "a0bbc287f15f1b50d64837c0c98ed812464906b6"
- $.entries[7].uri: "freetoplay/NA/event.json"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "685c9bb83a6a6a3846260c1b15d9f2fe746bac5a"
+ $.entries[8].contentVersion: "4873d14f6f330f38be396d21613299418ccb0b71"
- $.entries[8].uri: "freetoplay/EU/event.json"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "2f126916a6227f1aead8a3c07837e8505c23cb35"
+ $.entries[9].contentVersion: "4873d14f6f330f38be396d21613299418ccb0b71"
- $.entries[9].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "843e0e096d87beb4ae134a394329edc40b6fb85c"
+ $.entries[10].contentVersion: "791c6b71c67f42ce93e4b4ff0bf2397ad18ceb05"
- $.entries[10].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "02fde988454a53598a5fba88b7d5d0a3c14412ee"
+ $.entries[11].contentVersion: "d8db1c1da229091c17f16a82910e7e76c4ae803f"
- $.entries[11].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "b0f1d3d14955b37e1585bfce4eee9d001c96701a"
+ $.entries[12].contentVersion: "b376ad86c41d8202341d30d95c8fbe63dc1ac982"
- $.entries[12].uri: "archiveQuests/CalamariV1.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "10c758fca24d15cdabb2583cb222c0f739f06c2b"
+ $.entries[13].contentVersion: "26fe3e0169fc5c6ab6b5e463483ff61d1cb27227"
- $.entries[13].uri: "archiveQuests/CalamariV2.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "06d82540614245278764b434c8769714f1881a02"
+ $.entries[14].contentVersion: "2f19daab11ed799c750fed86d7dfcb887e93c3d9"
- $.entries[14].uri: "archiveQuests/CalamariV3.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "12c0d0049e3555a50602e62e8b79d7c747f0fe10"
+ $.entries[15].contentVersion: "d6f1d89ce587f0c7f2918e63de04c6ce1474c32e"
- $.entries[15].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "554c400b072b7af341c932d63dcc3676ca7d5904"
+ $.entries[16].contentVersion: "7b607dd80bbcc6a87099295b2741ea1293a7768b"
- $.entries[16].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "ee809b423de85bf0de794d16a46524ab919eab95"
+ $.entries[17].contentVersion: "4fa83b6f550365836c7a6edb5a79ccd8cb082fab"
- $.entries[17].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "9b982adc29354f7c3d6a8f5610816be53b1f4591"
+ $.entries[18].contentVersion: "c280ae447337d4333f388e87750f365f2632ee84"
- $.entries[18].uri: "archiveQuests/FireflyV1.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "71c3c0bc176f575b2282ec61cc770697a5fd45c8"
+ $.entries[19].contentVersion: "55200da04b65f7b9ecb7525938d105f2cab2d935"
- $.entries[19].uri: "archiveQuests/Halloween2021.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "78d3c3e6bf401e8b6977e932c51f6bd276616637"
+ $.entries[20].contentVersion: "49ec8afadecd4ed7fdee6dba91b6951d163882c4"
- $.entries[20].uri: "archiveQuests/Halloween2022.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "217f2b68ac007386165f4a7591070eeaa2691b55"
+ $.entries[21].contentVersion: "35871765acefeff16a1fc95498f3ddb2bc90c532"
- $.entries[21].uri: "archiveQuests/Halloween2023.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "65ac6df4ecfe1a0fea5c1d3820d7988b425ce5eb"
+ $.entries[22].contentVersion: "daab419c5d789787aaf77dc3f11d13692c485c6c"
- $.entries[22].uri: "archiveQuests/Halloween2024.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "82da1434713a68c8f7b1638c6d973b90530254a9"
+ $.entries[23].contentVersion: "9c8448334a649ffa54667052ccc72d695e743cdd"
- $.entries[23].uri: "archiveQuests/Spring2024.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "fd1fbdfbef6a9bc56cea52e66c09c30e08e2979a"
+ $.entries[24].contentVersion: "16a59c13e5c879661aa4a336b129199cab2c204b"
- $.entries[24].uri: "archiveQuests/Summer2023.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "5d1af2da2453bb0c4ecb52dd46cd4270f55b61f8"
+ $.entries[25].contentVersion: "832316ecd88680614aaf47a373e9da4d9aa3e558"
- $.entries[25].uri: "archiveQuests/Tome01.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "e85278b489f41472396e4f62f99d75bf8c4a80e1"
+ $.entries[26].contentVersion: "dcaba203e7ddabecb4da92f0c2a1a81de35c49aa"
- $.entries[26].uri: "archiveQuests/Tome02.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "7b7cfed0f02e837f03e1e5cad1f48e72de27a9a9"
+ $.entries[27].contentVersion: "dd9aa52937372f4f4401be1d0814b8fe7679c3fe"
- $.entries[27].uri: "archiveQuests/Tome03.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "0b257668e06021b88bd848c8b07f50c1b3ffbe38"
+ $.entries[28].contentVersion: "5c0bd80b51972b1af1e0d5da2fe4f4e2d600297f"
- $.entries[28].uri: "archiveQuests/Tome04.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "b028aa9c97b5c855fc73b572471de7070d30d855"
+ $.entries[29].contentVersion: "dc1b77fc6a0a6e0504ba92ea27a3a259ddee0830"
- $.entries[29].uri: "archiveQuests/Tome05.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "dc13bce183fa917d48250db09ea3a6df6d57a150"
+ $.entries[30].contentVersion: "c0024e5c3f7a3479d33967f4e44bd3fb84161075"
- $.entries[30].uri: "archiveQuests/Tome06.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "5aaf57063068e3e1e9a4bb41a442139b2f09f6b5"
+ $.entries[31].contentVersion: "c3e16183ca5814d3b0c3fa05dbcb71042f81d21d"
- $.entries[31].uri: "archiveQuests/Tome07.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "54be4d724477f17931de43801491773bcda8761f"
+ $.entries[32].contentVersion: "0cea91cd25e1ad75034d68fbb5f5c047f411d862"
- $.entries[32].uri: "archiveQuests/Tome08.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
- $.entries[33].contentVersion: "8e044d252e18e47fdcadb32a8790681fe48a1d26"
+ $.entries[33].contentVersion: "6688f7cbe4660093165afa649707f60bd20ffab2"
- $.entries[33].uri: "archiveQuests/Tome09.json"
+ $.entries[33].uri: "archiveQuests/Tome07.json"
- $.entries[34].contentVersion: "2ff257196c01ef717e53e03fc648e0821c6e4448"
+ $.entries[34].contentVersion: "868af8e33f4629fa7777f8e3080bfbf7e7b237e7"
- $.entries[34].uri: "archiveQuests/Tome10.json"
+ $.entries[34].uri: "archiveQuests/Tome08.json"
- $.entries[35].contentVersion: "8a5263c88e00f4f0ec7970af11313aac72ca43fd"
+ $.entries[35].contentVersion: "7cd3a855704d97c8ab7dae129e1f67ee9fcd4f33"
- $.entries[35].uri: "archiveQuests/Tome11.json"
+ $.entries[35].uri: "archiveQuests/Tome09.json"
- $.entries[36].contentVersion: "575f6f902df950958687a0ebebb19fae33dcde7b"
+ $.entries[36].contentVersion: "27bef41484f04264427aa9d6c77a0e5d244c6f22"
- $.entries[36].uri: "archiveQuests/Tome12.json"
+ $.entries[36].uri: "archiveQuests/Tome10.json"
- $.entries[37].contentVersion: "802c9ab79cd4b2d9486a2cfbd49dea1821bb8f08"
+ $.entries[37].contentVersion: "336b687b2f42cc51f3f220be41eebba6dc3d3bd2"
- $.entries[37].uri: "archiveQuests/Tome13.json"
+ $.entries[37].uri: "archiveQuests/Tome11.json"
- $.entries[38].contentVersion: "3eee4f5d63a8116a927b99052c24b63f04f6308c"
+ $.entries[38].contentVersion: "2ecfc84d5f8744b23298a8fd6c4ffe6b49df6947"
- $.entries[38].uri: "archiveQuests/Tome14.json"
+ $.entries[38].uri: "archiveQuests/Tome12.json"
- $.entries[39].contentVersion: "d4ebdc99326a33e30c88f8b7775ae2c10dd37ed1"
+ $.entries[39].contentVersion: "bb81b8c2eac397dd08bd8009060d9d086e481f0b"
- $.entries[39].uri: "archiveQuests/Tome15.json"
+ $.entries[39].uri: "archiveQuests/Tome13.json"
- $.entries[40].contentVersion: "74baa184d3bcdc2605f49c39f4797384cc208628"
+ $.entries[40].contentVersion: "d3d916386c2c8daf5c0ed79c409a70c1cbe5c73c"
- $.entries[40].uri: "archiveQuests/Tome16.json"
+ $.entries[40].uri: "archiveQuests/Tome14.json"
- $.entries[41].contentVersion: "9c07bf04d88bbffcbe8ed1bce67a24b63cfd4d59"
+ $.entries[41].contentVersion: "ca39c956ec19311511e43c2806237bab0c65e94e"
- $.entries[41].uri: "archiveQuests/Tome17.json"
+ $.entries[41].uri: "archiveQuests/Tome15.json"
- $.entries[42].contentVersion: "f8950159d5f481712a0e918acf3d7d7046f76f55"
+ $.entries[42].contentVersion: "09f8eb4e898bb9b00f9c29e600fa6ef673318d85"
- $.entries[42].uri: "archiveQuests/Tome18.json"
+ $.entries[42].uri: "archiveQuests/Tome16.json"
- $.entries[43].contentVersion: "5ae037d1d743b2579b5a932875056c8a6196c4a4"
+ $.entries[43].contentVersion: "27893fc910d32acedbf7d7ab7c707aa7b94777af"
- $.entries[43].uri: "archiveQuests/Tome19.json"
+ $.entries[43].uri: "archiveQuests/Tome17.json"
- $.entries[44].contentVersion: "ddf003223eecef8bc6890d0752d707df7e33724e"
+ $.entries[44].contentVersion: "8b76086bcda239769e3620b7575ddc487915c891"
- $.entries[44].uri: "archiveQuests/Tome20.json"
+ $.entries[44].uri: "archiveQuests/Tome18.json"
- $.entries[45].contentVersion: "873540d53f1d4b98f6c902a445b9a9600412210b"
+ $.entries[45].contentVersion: "ec95350d4fae0187aba6b128332cc3ddfa05af69"
… 655 more change(s) — see the commit diff for everything
```

### [`freetoplay/EU/event.json`](freetoplay/EU/event.json)

[Full line-by-line diff](diffs/freetoplay/EU/event.json.diff)

```diff
- $.event.end: "2024-11-25T16:00:00"
+ $.event.end: "2025-04-07T15:00:00"
- $.event.start: "2024-11-21T16:00:00"
+ $.event.start: "2025-04-03T15:00:00"
```

### [`freetoplay/NA/event.json`](freetoplay/NA/event.json)

[Full line-by-line diff](diffs/freetoplay/NA/event.json.diff)

```diff
- $.event.end: "2024-11-25T16:00:00"
+ $.event.end: "2025-04-07T15:00:00"
- $.event.start: "2024-11-21T16:00:00"
+ $.event.start: "2025-04-03T15:00:00"
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
+ $.legacyPrestige
+ $.rewards.K39
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=IcecreamW1]
+ $.featuredCard[id=IcecreamW2]
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Gelato"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].associatedDlcId: "Icecream"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[0].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TokyoGhoul.T_UI_ChapterBundle_TokyoGhoul"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Eclair"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].associatedDlcId: "Gelato"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[1].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DoomedCourse.T_UI_ChapterBundle_DoomedCourse"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Donut"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].associatedDlcId: "Eclair"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[2].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Castlevania.T_UI_ChapterBundle_Castlevania"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Churros"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].associatedDlcId: "Donut"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[3].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_TombRaider.T_UI_ChapterBundle_TombRaider"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "ApplePie"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].associatedDlcId: "Churros"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[4].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_DungeonsAndDragons.T_UI_ChapterBundle_DungeonsAndDragons"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "Zodiac"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].associatedDlcId: "ApplePie"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[5].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllThingsWicked.T_UI_ChapterBundle_AllThingsWicked"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "Yerkes"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].associatedDlcId: "Zodiac"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[6].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AlanWake.T_UI_ChapterBundle_AlanWake"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "Wormhole"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].associatedDlcId: "Yerkes"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[7].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Chucky.T_UI_ChapterBundle_Chucky"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Venus"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].associatedDlcId: "Wormhole"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[8].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_Alien.T_UI_ChapterBundle_Alien"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Umbra"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].associatedDlcId: "Venus"
- $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_EndTransmission.T_UI_ChapterBundle_EndTransmission"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[9].image.path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_NicolasCage.T_UI_ChapterBundle_NicolasCage"
+ $.featuredChapterPackRecommendations[id=Test].chapterPacks[10]
- $.featuredCharacterRecommendations[0].activeFrom: "2025-03-04T16:00:00Z"
+ $.featuredCharacterRecommendations[0].activeFrom: "2025-04-04T16:00:00Z"
- $.featuredCharacterRecommendations[0].activeTo: "2025-04-04T16:00:00Z"
+ $.featuredCharacterRecommendations[0].activeTo: "2033-09-04T00:00:00Z"
- $.featuredCharacterRecommendations[0].characters[0].characterIndex: "268435480"
+ $.featuredCharacterRecommendations[0].characters[0].characterIndex: "268435494"
- $.featuredCharacterRecommendations[0].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gemini/K25_TheCenobite_Portrait.K25_TheCenobite_Portrait"
+ $.featuredCharacterRecommendations[0].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Icecream/K39_TheGhoul_Portrait.K39_TheGhoul_Portrait"
- $.featuredCharacterRecommendations[0].characters[5]
- $.featuredCharacterRecommendations[0].characters[6]
- $.featuredCharacterRecommendations[0].characters[7]
- $.featuredCharacterRecommendations[0].characters[8]
- $.featuredCharacterRecommendations[0].characters[9]
- $.featuredCharacterRecommendations[0].characters[10]
- $.featuredCharacterRecommendations[0].characters[11]
- $.featuredCharacterRecommendations[0].characters[12]
- $.featuredCharacterRecommendations[0].characters[13]
- $.featuredCharacterRecommendations[1]
- $.featuredCharacterRecommendations[2]
+ $.featuredCustomizationRecommendations[id=IceCreamW1]
+ $.featuredCustomizationRecommendations[id=IceCreamW2]
- $.featuredCustomizationRecommendations[id=HotdogSale].recommendations[id=K25_outfit_02].weight: 45
+ $.featuredCustomizationRecommendations[id=HotdogSale].recommendations[id=K25_outfit_02].weight: 0
- $.featuredCustomizationRecommendations[id=HotdogSale].recommendations[id=K25_outfit_006].weight: 44
+ $.featuredCustomizationRecommendations[id=HotdogSale].recommendations[id=K25_outfit_006].weight: 0
- $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=S28_outfit_021]
- $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=NK_outfit_027]
- $.featuredCustomizationRecommendations[id=HotdogW10].recommendations[id=BE_outfit_018]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[45]
+ $.specialEvents[46]
+ $.specialEventsData[20].lteData
- $.specialEventsData[20].eventId: "Winter2023"
+ $.specialEventsData[20].eventId: "Spring2025"
+ $.specialEventsData[20].eventTrackerObjectives[id=main]
- $.specialEventsData[20].milestoneRewards[0].rewards[id=YE_005]
+ $.specialEventsData[20].milestoneRewards[0].rewards[id=IC_001]
- $.specialEventsData[20].milestoneRewards[1].pointsCost: 6
+ $.specialEventsData[20].milestoneRewards[1].pointsCost: 8
- $.specialEventsData[20].milestoneRewards[1].rewards[id=YE_BDG_01]
+ $.specialEventsData[20].milestoneRewards[1].rewards[id=IC_BDG_03]
- $.specialEventsData[20].milestoneRewards[2].pointsCost: 9
+ $.specialEventsData[20].milestoneRewards[2].pointsCost: 15
- $.specialEventsData[20].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[20].milestoneRewards[2].rewards[id=IC_BNR_03]
- $.specialEventsData[20].milestoneRewards[3]
- $.specialEventsData[20].milestoneRewards[4]
- $.specialEventsData[21].lteData
- $.specialEventsData[21].eventId: "Winter2024"
+ $.specialEventsData[21].eventId: "Winter2023"
- $.specialEventsData[21].eventPeriods[id=Winter2024]
- $.specialEventsData[21].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[21].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[21].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[21].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[21].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[21].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[21].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[21].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[21].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[21].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[21].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[21].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[21].milestoneRewards[3]
+ $.specialEventsData[21].milestoneRewards[4]
+ $.specialEventsData[22]
```

## Could not download

- `images/T_UI_ChapterBundle_TokyoGhoul.png (HTTP 404)`
- `images/T_UI_CollectionBanner_Bloodmoon.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TokyoGhoul.png (HTTP 404)`
- `images/T_UI_SpecialPack_Bloodmoon.png (HTTP 404)`
- `images/T_UI_SpecialPack_BloodmoonBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TokyoGhoul.png (HTTP 404)`
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

