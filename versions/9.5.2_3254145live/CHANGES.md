# live · 9.5.2_3254145live

| | |
|---|---|
| Build date | 2026-04-16 14:33 UTC |
| CDN version | `9.5.2_3254145live-1776349996` |
| Key | `9.5.2_live` |
| Compared with | [9.6.0_3253378live](../9.6.0_3253378live/CHANGES.md) (2026-04-15 18:31 UTC) |

## Summary

**3** added · **28** modified · **5** removed · 180 unchanged

## New or updated images

<a href="images/T_UI_CollectionBanner_Songkran.png"><img src="images/T_UI_CollectionBanner_Songkran.png" alt="T_UI_CollectionBanner_Songkran.png" width="240"></a>
<a href="images/T_UI_SpecialPack_MiNABundle.png"><img src="images/T_UI_SpecialPack_MiNABundle.png" alt="T_UI_SpecialPack_MiNABundle.png" width="240"></a>
<a href="images/T_UI_SpecialPack_Songkran.png"><img src="images/T_UI_SpecialPack_Songkran.png" alt="T_UI_SpecialPack_Songkran.png" width="240"></a>

## Removed files

- `images/T_UI_CollectionBanner_Aliens_Hudson.png`
- `images/T_UI_CollectionBanner_AoT_2.png`
- `images/T_UI_SpecialPack_Aliens_Hudson.png`
- `images/T_UI_SpecialPack_AoT_2.png`
- `images/T_UI_SpecialPack_Rift5.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.consent
- $.BHVRDynamicContent.isFailureBlocking: false
- $.analytics.minCountValuesForRules[]: "KL:90"
+ $.analytics.minCountValuesForRules[]: "KL:86"
- $.analyticsRules.KL[]: "BhvrDynamicContentDownloadedAnalytics"
- $.analyticsRules.KL[]: "BhvrDynamicContentErrorAnalytics"
- $.analyticsRules.KL[]: "BhvrDynamicContentInstalledAnalytics"
- $.analyticsRules.KL[]: "GameEventCountAnalytics"
- $.krakenRequestAnalyticsLevel: "HttpError"
+ $.krakenRequestAnalyticsLevel: "NetworkError"
```

### [`archiveQuests/Tome19.json`](archiveQuests/Tome19.json)

[Full line-by-line diff](diffs/archiveQuests/Tome19.json.diff)

```diff
- $.Tome19.level[3].nodes.node_T19_L4_08.objectives.Sacrifice.questEvent[0].parameters: "instigator:me"
```

### [`bonusPointEventsContent.json`](bonusPointEventsContent.json)

[Full line-by-line diff](diffs/bonusPointEventsContent.json.diff)

```diff
- $.bonusPointEvents[0].endTime: "2026-06-16T14:59:00"
+ $.bonusPointEvents[0].endTime: "2025-11-04T15:59:00"
- $.bonusPointEvents[0].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[0].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[0].multiplier: 2.0
+ $.bonusPointEvents[0].multiplier: 1.5
- $.bonusPointEvents[0].startTime: "2026-06-09T15:00:00"
+ $.bonusPointEvents[0].startTime: "2025-10-28T15:00:00"
- $.bonusPointEvents[1].endTime: "2025-11-04T15:59:00"
+ $.bonusPointEvents[1].endTime: "2025-06-17T14:59:00"
- $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[1].multiplier: 1.5
+ $.bonusPointEvents[1].multiplier: 2.0
- $.bonusPointEvents[1].startTime: "2025-10-28T15:00:00"
+ $.bonusPointEvents[1].startTime: "2025-06-03T15:00:00"
- $.bonusPointEvents[2].endTime: "2025-06-17T14:59:00"
+ $.bonusPointEvents[2].endTime: "2025-03-31T14:59:00"
- $.bonusPointEvents[2].startTime: "2025-06-03T15:00:00"
+ $.bonusPointEvents[2].startTime: "2025-03-18T15:00:00"
- $.bonusPointEvents[3].endTime: "2025-03-31T14:59:00"
+ $.bonusPointEvents[3].endTime: "2025-02-10T15:59:00"
- $.bonusPointEvents[3].startTime: "2025-03-18T15:00:00"
+ $.bonusPointEvents[3].startTime: "2025-02-04T16:00:00"
- $.bonusPointEvents[4].endTime: "2025-02-10T15:59:00"
+ $.bonusPointEvents[4].endTime: "2025-01-28T15:59:00"
- $.bonusPointEvents[4].startTime: "2025-02-04T16:00:00"
+ $.bonusPointEvents[4].startTime: "2025-01-21T16:00:00"
- $.bonusPointEvents[5].endTime: "2025-01-28T15:59:00"
+ $.bonusPointEvents[5].endTime: "2025-01-07T15:59:00"
- $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[5].multiplier: 2.0
+ $.bonusPointEvents[5].multiplier: 3.0
- $.bonusPointEvents[5].startTime: "2025-01-21T16:00:00"
+ $.bonusPointEvents[5].startTime: "2024-12-26T16:00:00"
- $.bonusPointEvents[6].endTime: "2025-01-07T15:59:00"
+ $.bonusPointEvents[6].endTime: "2024-12-26T15:59:00"
- $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[6].multiplier: 3.0
+ $.bonusPointEvents[6].multiplier: 2.0
- $.bonusPointEvents[6].startTime: "2024-12-26T16:00:00"
+ $.bonusPointEvents[6].startTime: "2024-12-19T16:00:00"
- $.bonusPointEvents[7].endTime: "2024-12-26T15:59:00"
+ $.bonusPointEvents[7].endTime: "2024-11-28T16:00:00"
- $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[7].multiplier: 2.0
+ $.bonusPointEvents[7].multiplier: 3.0
- $.bonusPointEvents[7].startTime: "2024-12-19T16:00:00"
+ $.bonusPointEvents[7].startTime: "2024-11-22T20:00:00"
- $.bonusPointEvents[8].endTime: "2024-11-28T16:00:00"
+ $.bonusPointEvents[8].endTime: "2024-10-01T15:00:00"
- $.bonusPointEvents[8].startTime: "2024-11-22T20:00:00"
+ $.bonusPointEvents[8].startTime: "2024-09-24T15:00:00"
- $.bonusPointEvents[9].endTime: "2024-10-01T15:00:00"
+ $.bonusPointEvents[9].endTime: "2024-09-12T15:00:00"
- $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[9].multiplier: 3.0
+ $.bonusPointEvents[9].multiplier: 2.0
- $.bonusPointEvents[9].startTime: "2024-09-24T15:00:00"
+ $.bonusPointEvents[9].startTime: "2024-09-05T15:00:00"
- $.bonusPointEvents[10].endTime: "2024-09-12T15:00:00"
+ $.bonusPointEvents[10].endTime: "2024-06-13T15:00:00"
- $.bonusPointEvents[10].startTime: "2024-09-05T15:00:00"
+ $.bonusPointEvents[10].startTime: "2024-06-03T15:00:00"
- $.bonusPointEvents[11].endTime: "2024-06-13T15:00:00"
+ $.bonusPointEvents[11].endTime: "2024-05-21T15:00:00"
- $.bonusPointEvents[11].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[11].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[11].multiplier: 2.0
+ $.bonusPointEvents[11].multiplier: 3.0
- $.bonusPointEvents[11].startTime: "2024-06-03T15:00:00"
+ $.bonusPointEvents[11].startTime: "2024-05-14T16:00:00"
- $.bonusPointEvents[12].endTime: "2024-05-21T15:00:00"
+ $.bonusPointEvents[12].endTime: "2024-02-20T16:00:00"
- $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[12].multiplier: 3.0
+ $.bonusPointEvents[12].multiplier: 1.5
- $.bonusPointEvents[12].startTime: "2024-05-14T16:00:00"
+ $.bonusPointEvents[12].startTime: "2024-02-14T16:00:00"
- $.bonusPointEvents[13].endTime: "2024-02-20T16:00:00"
+ $.bonusPointEvents[13].endTime: "2023-09-19T15:00:00"
- $.bonusPointEvents[13].startTime: "2024-02-14T16:00:00"
+ $.bonusPointEvents[13].startTime: "2023-09-12T15:00:00"
- $.bonusPointEvents[14].endTime: "2023-09-19T15:00:00"
+ $.bonusPointEvents[14].endTime: "2023-07-13T15:00:00"
- $.bonusPointEvents[14].startTime: "2023-09-12T15:00:00"
+ $.bonusPointEvents[14].startTime: "2023-07-07T15:00:00"
- $.bonusPointEvents[15].endTime: "2023-07-13T15:00:00"
+ $.bonusPointEvents[15].endTime: "2023-05-30T15:00:00"
- $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[15].multiplier: 1.5
+ $.bonusPointEvents[15].multiplier: 2.0
- $.bonusPointEvents[15].startTime: "2023-07-07T15:00:00"
+ $.bonusPointEvents[15].startTime: "2023-05-23T15:00:00"
- $.bonusPointEvents[16].endTime: "2023-05-30T15:00:00"
+ $.bonusPointEvents[16].endTime: "2022-11-29T16:00:00"
- $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[16].startTime: "2023-05-23T15:00:00"
+ $.bonusPointEvents[16].startTime: "2022-11-22T16:00:00"
- $.bonusPointEvents[17].endTime: "2022-11-29T16:00:00"
+ $.bonusPointEvents[17].endTime: "2022-06-27T15:00:00"
- $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[17].startTime: "2022-11-22T16:00:00"
+ $.bonusPointEvents[17].startTime: "2022-06-23T15:00:00"
- $.bonusPointEvents[18].endTime: "2022-06-27T15:00:00"
+ $.bonusPointEvents[18].endTime: "2022-05-30T15:00:00"
- $.bonusPointEvents[18].startTime: "2022-06-23T15:00:00"
+ $.bonusPointEvents[18].startTime: "2022-05-23T15:00:00"
- $.bonusPointEvents[19].endTime: "2022-05-30T15:00:00"
+ $.bonusPointEvents[19].endTime: "2022-03-07T16:00:00"
- $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[19].multiplier: 2.0
+ $.bonusPointEvents[19].multiplier: 1.5
- $.bonusPointEvents[19].startTime: "2022-05-23T15:00:00"
+ $.bonusPointEvents[19].startTime: "2022-02-28T16:00:00"
- $.bonusPointEvents[20].endTime: "2022-03-07T16:00:00"
+ $.bonusPointEvents[20].endTime: "2022-01-21T16:00:00"
- $.bonusPointEvents[20].startTime: "2022-02-28T16:00:00"
+ $.bonusPointEvents[20].startTime: "2022-01-14T16:00:00"
- $.bonusPointEvents[21].endTime: "2022-01-21T16:00:00"
+ $.bonusPointEvents[21].endTime: "2021-11-29T16:00:00"
- $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[21].multiplier: 1.5
+ $.bonusPointEvents[21].multiplier: 2.0
- $.bonusPointEvents[21].startTime: "2022-01-14T16:00:00"
+ $.bonusPointEvents[21].startTime: "2021-11-25T16:00:00"
- $.bonusPointEvents[22].endTime: "2021-11-29T16:00:00"
+ $.bonusPointEvents[22].endTime: "2021-08-03T15:00:00"
- $.bonusPointEvents[22].startTime: "2021-11-25T16:00:00"
+ $.bonusPointEvents[22].startTime: "2021-07-29T15:00:00"
- $.bonusPointEvents[23].endTime: "2021-08-03T15:00:00"
+ $.bonusPointEvents[23].endTime: "2021-01-22T16:00:00"
- $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[23].multiplier: 2.0
+ $.bonusPointEvents[23].multiplier: 1.5
- $.bonusPointEvents[23].startTime: "2021-07-29T15:00:00"
+ $.bonusPointEvents[23].startTime: "2021-01-15T16:00:00"
- $.bonusPointEvents[24].endTime: "2021-01-22T16:00:00"
+ $.bonusPointEvents[24].endTime: "2020-11-02T16:29:59"
- $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[24].multiplier: 1.5
+ $.bonusPointEvents[24].multiplier: 2.0
- $.bonusPointEvents[24].startTime: "2021-01-15T16:00:00"
+ $.bonusPointEvents[24].startTime: "2020-10-29T15:00:00"
- $.bonusPointEvents[25].endTime: "2020-11-02T16:29:59"
+ $.bonusPointEvents[25].endTime: "2020-04-15T15:00:00"
- $.bonusPointEvents[25].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[25].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[25].multiplier: 2.0
+ $.bonusPointEvents[25].multiplier: 1.5
- $.bonusPointEvents[25].startTime: "2020-10-29T15:00:00"
+ $.bonusPointEvents[25].startTime: "2020-03-25T15:00:00"
- $.bonusPointEvents[26].endTime: "2020-04-15T15:00:00"
+ $.bonusPointEvents[26].endTime: "2020-01-06T16:00:00"
- $.bonusPointEvents[26].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[26].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[26].multiplier: 1.5
+ $.bonusPointEvents[26].multiplier: 2.0
- $.bonusPointEvents[26].startTime: "2020-03-25T15:00:00"
+ $.bonusPointEvents[26].startTime: "2020-01-02T16:00:00"
- $.bonusPointEvents[27].endTime: "2020-01-06T16:00:00"
+ $.bonusPointEvents[27].endTime: "2019-11-04T15:00:00"
- $.bonusPointEvents[27].startTime: "2020-01-02T16:00:00"
+ $.bonusPointEvents[27].startTime: "2019-10-31T15:00:00"
- $.bonusPointEvents[28].endTime: "2019-11-04T15:00:00"
+ $.bonusPointEvents[28].endTime: "2019-09-30T15:00:00"
- $.bonusPointEvents[28].startTime: "2019-10-31T15:00:00"
+ $.bonusPointEvents[28].startTime: "2019-09-26T15:00:00"
- $.bonusPointEvents[29].endTime: "2019-09-30T15:00:00"
+ $.bonusPointEvents[29].endTime: "2019-06-20T18:00:00"
- $.bonusPointEvents[29].startTime: "2019-09-26T15:00:00"
+ $.bonusPointEvents[29].startTime: "2019-06-14T18:00:00"
- $.bonusPointEvents[30].endTime: "2019-06-20T18:00:00"
+ $.bonusPointEvents[30].endTime: "2019-05-06T18:00:00"
- $.bonusPointEvents[30].startTime: "2019-06-14T18:00:00"
+ $.bonusPointEvents[30].startTime: "2019-05-02T18:00:00"
- $.bonusPointEvents[31].endTime: "2019-05-06T18:00:00"
+ $.bonusPointEvents[31].endTime: "2019-01-03T19:00:00"
- $.bonusPointEvents[31].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[31].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
- $.bonusPointEvents[31].startTime: "2019-05-02T18:00:00"
+ $.bonusPointEvents[31].startTime: "2018-12-27T19:00:00"
- $.bonusPointEvents[32].endTime: "2019-01-03T19:00:00"
+ $.bonusPointEvents[32].endTime: "2018-11-12T19:00:00"
- $.bonusPointEvents[32].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
+ $.bonusPointEvents[32].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[32].multiplier: 2.0
+ $.bonusPointEvents[32].multiplier: 1.5
… 31 more change(s) — see the commit diff for everything
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=CHALLENGE_REWARD_TIER_Rift_05]
- $[id=CHALLENGE_BATTLE_PASS_Rift_05]
- $[id=BE_Body030]
- $[id=BE_Mask030]
- $[id=BE_W030]
- $[id=DF_Body01POC]
- $[id=DF_Head01_07]
- $[id=DF_Legs01_07]
- $[id=DF_Torso01_07]
- $[id=DK_Head032]
- $[id=DK_Head032_01]
- $[id=DK_Head032_02]
- $[id=DK_Legs032]
- $[id=DK_Legs032_01]
- $[id=DK_Legs032_02]
- $[id=DK_Torso032]
- $[id=DK_Torso032_01]
- $[id=DK_Torso032_02]
- $[id=FM_Legs043]
- $[id=FM_Torso043]
- $[id=HS_Legs032]
- $[id=HS_Torso032]
- $[id=JP_Head034]
- $[id=JP_Legs034]
- $[id=JP_Torso034]
- $[id=K21_Body023]
- $[id=K21_Body023_01]
- $[id=K21_Body023_02]
- $[id=K21_Head023]
- $[id=K21_Head023_01]
- $[id=K21_Head023_02]
- $[id=K21_W023]
- $[id=K21_W023_01]
- $[id=K21_W023_02]
- $[id=K22_Body015_01]
- $[id=K22_Head015_01]
- $[id=K22_W015_01]
- $[id=K30_Body013_01]
- $[id=K30_Head013_01]
- $[id=K30_W008_02]
- $[id=K31_Body019]
- $[id=K31_Head019]
- $[id=K31_W019]
- $[id=K41_Body009]
- $[id=K41_Head009]
- $[id=K41_W009]
- $[id=KS_Head012_03]
- $[id=KS_Legs010_01]
- $[id=KS_Torso015_01]
- $[id=MS_Head027]
- $[id=MS_Legs027]
- $[id=MS_Torso027]
- $[id=MT_Head036]
- $[id=MT_Head036_01]
- $[id=MT_Head036_02]
- $[id=MT_Legs036]
- $[id=MT_Legs036_01]
- $[id=MT_Legs036_02]
- $[id=MT_Torso036]
- $[id=MT_Torso036_01]
- $[id=MT_Torso036_02]
- $[id=NK_Head029_01]
- $[id=NK_Legs008_01]
- $[id=NK_Torso023_01]
- $[id=RAM_001]
- $[id=RAM_002]
- $[id=RAM_003]
- $[id=RAM_004]
- $[id=RAM_005]
- $[id=RAM_006]
- $[id=RAM_007]
- $[id=RAM_008]
- $[id=RAM_009]
- $[id=RAM_010]
- $[id=RAM_011]
- $[id=RAM_016]
- $[id=RAM_017]
- $[id=RAM_018]
- $[id=RAM_019]
- $[id=RAM_020]
- $[id=RAM_021]
- $[id=RAM_022]
- $[id=RAM_BDG_01]
- $[id=RAM_BDG_02]
- $[id=RAM_BDG_03]
- $[id=RAM_BDG_06]
- $[id=RAM_BDG_07]
- $[id=RAM_BDG_10]
- $[id=RAM_BDG_11]
- $[id=RAM_BDG_12]
- $[id=RAM_BDG_13]
- $[id=RAM_BDG_15]
- $[id=RAM_BDG_16]
- $[id=RAM_BDG_17]
- $[id=RAM_BDG_18]
- $[id=RAM_BDG_19]
- $[id=RAM_BDG_20]
- $[id=RAM_BDG_21]
- $[id=RAM_BDG_22]
- $[id=RAM_BDG_23]
- $[id=RAM_BDG_24]
- $[id=RAM_BDG_25]
- $[id=RAM_BDG_26]
- $[id=RAM_BDG_31]
- $[id=RAM_BNR_01]
- $[id=RAM_BNR_02]
- $[id=RAM_BNR_05]
- $[id=RAM_BNR_06]
- $[id=RAM_BNR_07]
- $[id=RAM_BNR_08]
- $[id=RAM_BNR_09]
- $[id=RAM_BNR_10]
- $[id=RAM_BNR_11]
- $[id=RAM_BNR_12]
- $[id=RAM_BNR_13]
- $[id=RAM_BNR_14]
- $[id=RAM_BNR_15]
- $[id=RAM_BNR_16]
- $[id=RAM_BNR_17]
- $[id=RAM_BNR_25]
- $[id=RAM_BNR_26]
- $[id=S23_Head031_01]
- $[id=S23_Legs028_01]
- $[id=S23_Torso021_01]
- $[id=S24_Legs028]
- $[id=S24_Torso028]
- $[id=S25_Head033]
- $[id=S25_Legs033]
- $[id=S25_Torso033]
- $[id=S28_Legs034]
- $[id=S28_Torso034]
- $[id=S31_Legs025]
- $[id=S31_Torso025]
- $[id=S34_Head026]
- $[id=S34_Head026_01]
- $[id=S34_Head026_02]
- $[id=S34_Legs026]
- $[id=S34_Legs026_01]
- $[id=S34_Legs026_02]
- $[id=S34_Torso026]
- $[id=S34_Torso026_01]
- $[id=S34_Torso026_02]
- $[id=S35_Head025]
- $[id=S35_Legs025]
- $[id=S35_Torso025]
- $[id=S36_Legs025]
- $[id=S36_Torso025]
- $[id=S37_Head026]
- $[id=S37_Legs026]
- $[id=S37_Torso026]
- $[id=S39_Head013]
- $[id=S39_Legs013]
- $[id=S39_Torso013]
- $[id=S52_Head007]
- $[id=S52_Legs007]
- $[id=S52_Torso007]
- $[id=SS_Head031]
- $[id=SS_Legs031]
- $[id=SS_Torso031]
- $[id=TN_Body027]
- $[id=TN_Body027_01]
- $[id=TN_Body027_02]
- $[id=TN_Head027]
- $[id=TN_Head027_01]
- $[id=TN_Head027_02]
- $[id=TN_W027]
- $[id=TN_W027_01]
- $[id=TN_W027_02]
- $[id=TR_Body01_05]
- $[id=TR_Body031]
- $[id=TR_Body031_01]
- $[id=TR_Body031_02]
- $[id=TR_Mask01_05]
- $[id=TR_Mask031]
- $[id=TR_Mask031_01]
- $[id=TR_Mask031_02]
- $[id=TR_W01_05]
- $[id=TR_W031]
- $[id=TR_W031_01]
- $[id=TR_W031_02]
- $[id=TW_Body024]
- $[id=TW_Head024]
- $[id=TW_W024]
- $[id=US_Head032]
- $[id=US_Head032_01]
- $[id=US_Head032_02]
- $[id=US_Legs032]
- $[id=US_Legs032_01]
- $[id=US_Legs032_02]
- $[id=US_Torso032]
- $[id=US_Torso032_01]
- $[id=US_Torso032_02]
- $[id=BE_outfit_030]
- $[id=DF_outfit_01_07]
- $[id=DK_outfit_032]
- $[id=DK_outfit_032_01]
- $[id=DK_outfit_032_02]
- $[id=FM_outfit_043]
- $[id=HS_outfit_032]
- $[id=JP_outfit_034]
… 592 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[586]
- $.locText[587]
- $.locText[588]
- $.locText[589]
- $.locText[590]
- $.locText[591]
- $.locText[592]
- $.locText[593]
```

### [`challengeRewardTrackers.json`](challengeRewardTrackers.json)

[Full line-by-line diff](diffs/challengeRewardTrackers.json.diff)

```diff
- $.Rift_05
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.CalamariRamen
- $.Milestone_05_Set
- $.Rift_05_QuestSet
- $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests1].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests1].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests2].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests2].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests3].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests3].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests4].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[0].challenges[id=BloodMoon_Quiche-Overarching-O_CompleteModeQuests4].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[0].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[0].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_CompleteModeTrial].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_CompleteModeTrial].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_DamageBloodGenerator].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_DamageBloodGenerator].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_DamageSurvivorWithBloodCan].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_DamageSurvivorWithBloodCan].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_FillBloodGenerator].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_FillBloodGenerator].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_FillBloodCan].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].challenges[id=BloodMoon_Quiche-Milestone-ME_FillBloodCan].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[1].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[1].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-D_ChaseOrBeChased].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-D_ChaseOrBeChased].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-D_DownOrHeal].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-D_DownOrHeal].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-B_HookDiffOneTrial].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-B_HookDiffOneTrial].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-B_BeChasedSingleTrial].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[2].challenges[id=BloodMoon_Quiche-Quest_List_1-B_BeChasedSingleTrial].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.challengeList[2].startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.challengeList[2].startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.startDate: "2026-03-26T17:00:00"
+ $.BloodMoon_Quiche.startDate: "2026-03-26T15:00:00"
- $.BloodMoon_Quiche.startDateInMs: 1774544400
+ $.BloodMoon_Quiche.startDateInMs: 1774537200
- $.Rift_04_QuestSet.challengeList[1].challenges[id=Rift_04_QuestSet-Kickstart-B_PlayAsSurvivorOrAnySurvivor].objectives.FinishedPlayingSurvivor
+ $.Rift_04_QuestSet.challengeList[1].challenges[id=Rift_04_QuestSet-Kickstart-B_PlayAsSurvivorOrAnySurvivor].objectives.FinishedPlayingKiller
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[25].limitedAvailabilityEndDate: "2026-04-28T15:00:00Z"
- $.collections[25].visibleAfterEndDate: false
- $.collections[58].additionalImages[0]
- $.collections[58].collectionId: "Alien_Ramen"
+ $.collections[58].collectionId: "DaringAdventure"
- $.collections[58].collectionTitle.de: "Alien"
+ $.collections[58].collectionTitle.de: "Waghalsiges Abenteuer"
- $.collections[58].collectionTitle.en: "Alien"
+ $.collections[58].collectionTitle.en: "Daring Adventure"
- $.collections[58].collectionTitle.es: "Alien"
+ $.collections[58].collectionTitle.es: "Aventura intrépida"
- $.collections[58].collectionTitle["es-MX"]: "Alien"
+ $.collections[58].collectionTitle["es-MX"]: "Aventura osada"
- $.collections[58].collectionTitle.fr: "Alien"
+ $.collections[58].collectionTitle.fr: "Aventure audacieuse"
- $.collections[58].collectionTitle.it: "Alien"
+ $.collections[58].collectionTitle.it: "Avventura audace"
- $.collections[58].collectionTitle.ja: "エイリアン"
+ $.collections[58].collectionTitle.ja: "果敢なる冒険"
- $.collections[58].collectionTitle.ko: "에이리언"
+ $.collections[58].collectionTitle.ko: "대담한 모험"
- $.collections[58].collectionTitle.pl: "Obcy"
+ $.collections[58].collectionTitle.pl: "Odważna przygoda"
- $.collections[58].collectionTitle["pt-BR"]: "Alien"
+ $.collections[58].collectionTitle["pt-BR"]: "Aventura Ousada"
- $.collections[58].collectionTitle.ru: "Чужой"
+ $.collections[58].collectionTitle.ru: "Отчаянное приключение"
- $.collections[58].collectionTitle.th: "เอเลี่ยน"
+ $.collections[58].collectionTitle.th: "การผจญภัยสุดท้าทาย"
- $.collections[58].collectionTitle.tr: "Alien"
+ $.collections[58].collectionTitle.tr: "Cesaret İsteyen Macera"
- $.collections[58].collectionTitle["zh-Hans"]: "异形"
+ $.collections[58].collectionTitle["zh-Hans"]: "大冒险系列"
- $.collections[58].collectionTitle["zh-Hant"]: "《異形》"
+ $.collections[58].collectionTitle["zh-Hant"]: "勇敢冒險"
- $.collections[58].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_Aliens_Hudson.T_UI_CollectionBanner_Aliens_Hudson"
+ $.collections[58].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_DaringAdventure.T_UI_CollectionBanner_DaringAdventure"
- $.collections[58].inclusionVersion: "9.6.0"
+ $.collections[58].inclusionVersion: "7.7.0 PTB"
- $.collections[58].items[]: "K33_outfit_006"
- $.collections[58].items[]: "K33_outfit_007"
- $.collections[58].items[]: "K33_outfit_008"
- $.collections[58].items[]: "K33_outfit_010"
- $.collections[58].items[]: "K33_outfit_011"
- $.collections[58].items[]: "K33_outfit_012"
- $.collections[58].items[]: "K33_outfit_02"
- $.collections[58].items[]: "S37_outfit_026"
- $.collections[58].items[]: "S39_outfit_006"
- $.collections[58].items[]: "S39_outfit_007"
- $.collections[58].items[]: "S39_outfit_009"
- $.collections[58].items[]: "S39_outfit_010"
- $.collections[58].items[]: "S39_outfit_011"
- $.collections[58].items[]: "S39_outfit_013"
+ $.collections[58].items[]: "UK_outfit_013"
+ $.collections[58].items[]: "US_outfit_017"
- $.collections[58].sortOrder: "-220"
+ $.collections[58].sortOrder: "-23"
- $.collections[58].updatedDate: "2026-03-10T17:12:37.542Z"
+ $.collections[58].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[59].additionalImages[0]
- $.collections[59].collectionId: "AttackOnTitan_Ramen"
+ $.collections[59].collectionId: "GreekLegends"
- $.collections[59].collectionTitle.de: "Attack On Titan"
+ $.collections[59].collectionTitle.de: "Griechische Legenden"
- $.collections[59].collectionTitle.en: "Attack on Titan"
+ $.collections[59].collectionTitle.en: "Greek Legends"
- $.collections[59].collectionTitle.es: "Ataque a los Titanes"
+ $.collections[59].collectionTitle.es: "Leyendas griegas"
- $.collections[59].collectionTitle["es-MX"]: "Attack on Titan"
+ $.collections[59].collectionTitle["es-MX"]: "Leyendas griegas"
- $.collections[59].collectionTitle.fr: "L'Attaque des Titans"
+ $.collections[59].collectionTitle.fr: "Légendes grecques"
- $.collections[59].collectionTitle.it: "Attack on Titan"
+ $.collections[59].collectionTitle.it: "Leggende greche"
- $.collections[59].collectionTitle.ja: "進撃の巨人"
+ $.collections[59].collectionTitle.ja: "ギリシャの伝説"
- $.collections[59].collectionTitle.ko: "진격의 거인"
+ $.collections[59].collectionTitle.ko: "그리스 전설"
- $.collections[59].collectionTitle.pl: "Attack on Titan"
+ $.collections[59].collectionTitle.pl: "Greckie legendy"
- $.collections[59].collectionTitle["pt-BR"]: "Ataque dos Titãs"
+ $.collections[59].collectionTitle["pt-BR"]: "Lendas Gregas"
- $.collections[59].collectionTitle.ru: "Атака титанов"
+ $.collections[59].collectionTitle.ru: "Легенды Греции"
- $.collections[59].collectionTitle.th: "ผ่าพิภพไททัน"
+ $.collections[59].collectionTitle.th: "ตำนานกรีก"
- $.collections[59].collectionTitle.tr: "Attack on Titan"
+ $.collections[59].collectionTitle.tr: "Yunan Efsaneleri"
- $.collections[59].collectionTitle["zh-Hans"]: "《进击的巨人》"
+ $.collections[59].collectionTitle["zh-Hans"]: "希腊传说"
- $.collections[59].collectionTitle["zh-Hant"]: "進擊的巨人"
+ $.collections[59].collectionTitle["zh-Hant"]: "希臘傳奇"
- $.collections[59].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_AoT_2.T_UI_CollectionBanner_AoT_2"
+ $.collections[59].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GreekLegends.T_UI_CollectionBanner_GreekLegends"
- $.collections[59].inclusionVersion: "9.6.0"
+ $.collections[59].inclusionVersion: "7.7.0 PTB"
- $.collections[59].items[]: "AV_outfit_017"
- $.collections[59].items[]: "DF_outfit_020"
- $.collections[59].items[]: "FM_outfit_043"
- $.collections[59].items[]: "GS_outfit_019"
- $.collections[59].items[]: "HK_outfit_016"
- $.collections[59].items[]: "HS_outfit_032"
- $.collections[59].items[]: "JP_outfit_018"
- $.collections[59].items[]: "JP_outfit_034"
- $.collections[59].items[]: "MT_outfit_019"
- $.collections[59].items[]: "S23_outfit_018"
- $.collections[59].items[]: "S24_outfit_028"
- $.collections[59].items[]: "S28_outfit_034"
- $.collections[59].items[]: "S31_outfit_025"
- $.collections[59].items[]: "S35_outfit_025"
- $.collections[59].items[]: "S36_outfit_025"
- $.collections[59].items[]: "SS_outfit_031"
- $.collections[59].items[]: "SwedenKiller_outfit_012"
- $.collections[59].items[]: "SwedenSurvivor_outfit_017"
- $.collections[59].items[]: "TR_outfit_031"
- $.collections[59].items[]: "TR_outfit_031_01"
- $.collections[59].items[]: "TR_outfit_031_02"
- $.collections[59].items[]: "US_outfit_016"
+ $.collections[59].items[]: "AV_outfit_014"
+ $.collections[59].items[]: "DK_outfit_012"
+ $.collections[59].items[]: "FM_outfit_012"
+ $.collections[59].items[]: "GK_outfit_011"
+ $.collections[59].items[]: "GS_outfit_016"
+ $.collections[59].items[]: "HK_outfit_011"
+ $.collections[59].items[]: "HS_outfit_010"
+ $.collections[59].items[]: "K21_outfit_008"
+ $.collections[59].items[]: "K26_outfit_009"
+ $.collections[59].items[]: "K28_outfit_010"
+ $.collections[59].items[]: "KS_outfit_012"
+ $.collections[59].items[]: "MK_outfit_013"
+ $.collections[59].items[]: "MS_outfit_013"
+ $.collections[59].items[]: "NK_outfit_022"
+ $.collections[59].items[]: "S24_outfit_009"
+ $.collections[59].items[]: "S28_outfit_014"
+ $.collections[59].items[]: "S35_outfit_009"
+ $.collections[59].items[]: "S36_outfit_009"
+ $.collections[59].items[]: "SwedenKiller_outfit_009"
+ $.collections[59].items[]: "SwedenSurvivor_outfit_011"
+ $.collections[59].items[]: "TN_outfit_013"
+ $.collections[59].items[]: "US_outfit_009"
- $.collections[59].sortOrder: "-221"
+ $.collections[59].sortOrder: "-25"
- $.collections[59].updatedDate: "2026-03-10T17:14:55.676Z"
+ $.collections[59].updatedDate: "2024-03-18T16:00:01Z"
- $.collections[60].limitedAvailabilityStartDate: "2026-05-05T15:00:00Z"
- $.collections[60].visibleBeforeStartDate: false
- $.collections[60].additionalImages[0]
- $.collections[60].collectionId: "Chrysalis_Ramen"
+ $.collections[60].collectionId: "MeanStreets"
- $.collections[60].collectionTitle.de: "Kokonsammlung"
+ $.collections[60].collectionTitle.de: "Gefährliche Straßen"
- $.collections[60].collectionTitle.en: "Chrysalis Collection"
+ $.collections[60].collectionTitle.en: "Mean Streets"
- $.collections[60].collectionTitle.es: "Colección de Crisálida"
+ $.collections[60].collectionTitle.es: "Calles peligrosas"
- $.collections[60].collectionTitle["es-MX"]: "Colección Crisálida"
+ $.collections[60].collectionTitle["es-MX"]: "Calles peligrosas"
- $.collections[60].collectionTitle.fr: "Collection Chrysalide"
+ $.collections[60].collectionTitle.fr: "Rues dangereuses"
- $.collections[60].collectionTitle.it: "Collezione Crisalide"
+ $.collections[60].collectionTitle.it: "Bassifondi"
- $.collections[60].collectionTitle.ja: "蛹コレクション"
+ $.collections[60].collectionTitle.ja: "意地悪なストリート"
- $.collections[60].collectionTitle.ko: "번데기 컬렉션"
+ $.collections[60].collectionTitle.ko: "비열한 거리"
- $.collections[60].collectionTitle.pl: "Kolekcja „Poczwarka”"
+ $.collections[60].collectionTitle.pl: "Podła dzielnica"
- $.collections[60].collectionTitle["pt-BR"]: "Coleção Crisálida"
+ $.collections[60].collectionTitle["pt-BR"]: "Ruas Cruéis"
- $.collections[60].collectionTitle.ru: "Коллекция «Кокон»"
+ $.collections[60].collectionTitle.ru: "Трущобы"
- $.collections[60].collectionTitle.th: "ชุดสะสมดักแด้"
+ $.collections[60].collectionTitle.th: "ถนนซอมซ่อ"
- $.collections[60].collectionTitle.tr: "Koza Koleksiyonu"
+ $.collections[60].collectionTitle.tr: "Amansız Sokaklar"
- $.collections[60].collectionTitle["zh-Hans"]: "茧蛹收藏"
+ $.collections[60].collectionTitle["zh-Hans"]: "穷街陋巷"
- $.collections[60].collectionTitle["zh-Hant"]: "繭蛹收藏"
+ $.collections[60].collectionTitle["zh-Hant"]: "窮街陋巷"
- $.collections[60].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_Chrysalis_2.T_UI_CollectionBanner_Chrysalis_2"
+ $.collections[60].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_MeanStreets.T_UI_CollectionBanner_MeanStreets"
- $.collections[60].inclusionVersion: "9.6.0"
+ $.collections[60].inclusionVersion: "7.7.0 PTB"
- $.collections[60].items[]: "BE_outfit_030"
- $.collections[60].items[]: "DO_outfit_014"
- $.collections[60].items[]: "GS_Head030"
- $.collections[60].items[]: "K20_outfit_009"
- $.collections[60].items[]: "K30_outfit_013"
- $.collections[60].items[]: "K33_outfit_011"
- $.collections[60].items[]: "KS_outfit_015"
- $.collections[60].items[]: "NK_outfit_021"
- $.collections[60].items[]: "S25_outfit_033"
- $.collections[60].items[]: "S35_outfit_021"
- $.collections[60].items[]: "S36_outfit_023"
- $.collections[60].items[]: "S41_outfit_008"
- $.collections[60].items[]: "SwedenKiller_outfit_022"
- $.collections[60].items[]: "UK_outfit_010"
+ $.collections[60].items[]: "AV_outfit_010"
+ $.collections[60].items[]: "Claudette_outfit_009_01"
+ $.collections[60].items[]: "DK_outfit_011"
… 1957 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[1].MapsWeight.Brl_Temple_Calamari: "500"
- $.schedule[1].MapsWeight.Ind_Foundry_Calamari: "500"
+ $.schedule[5]
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
+ $.dlcList.ChineseEventOct2017.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.ChineseEventOct2017.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.ChineseEventOct2017.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.DeathGarden.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.DeathGarden.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.DeathGarden.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.DonutCust.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillFreeWeek.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillFreeWeek.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillFreeWeek.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillGeneral.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillGeneral.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.EpicBrillGeneral.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.GStar2017.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.GStar2017.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.GStar2017.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.HeritagePack1.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.HeritagePack1.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.Kabuki.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.Kabuki.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.Kabuki.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.Quiche.platforms
+ $.dlcList.StoreItem.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.StoreItem.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.StoreItem.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.bloodletting.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.bloodletting.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.bloodletting.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.development.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.development.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.development.platforms.xsx: "9ZZZZZZZZZZZ"
+ $.dlcList.steamOnly.platforms.grdk: "9ZZZZZZZZZZZ"
+ $.dlcList.steamOnly.platforms.xbox: "9ZZZZZZZZZZZ"
+ $.dlcList.steamOnly.platforms.xsx: "9ZZZZZZZZZZZ"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "cd78791691749d15bd36957f6370133a990f85a4"
+ $.entries[0].contentVersion: "cf7cf00b919d33db2cac5803060754bacc45871e"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_AoT_2.T_UI_SpecialPack_AoT_2"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_MiNABundle.T_UI_SpecialPack_MiNABundle"
- $.entries[0].uri: "images/T_UI_SpecialPack_AoT_2.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_MiNABundle.png"
- $.entries[1].contentVersion: "c98f80124bd6f0e7c53d9ea1fa76f2684f1fb782"
+ $.entries[1].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_Rift5.T_UI_SpecialPack_Rift5"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[1].uri: "images/T_UI_SpecialPack_Rift5.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[2].contentVersion: "14139f9b234fdd66cb273cc5fd16228bd75b3258"
+ $.entries[2].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_Aliens_Hudson.T_UI_CollectionBanner_Aliens_Hudson"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[2].uri: "images/T_UI_CollectionBanner_Aliens_Hudson.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[3].contentVersion: "fef3ab3957518899c95abb8a021b8f85e4cb34bf"
+ $.entries[3].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_Aliens_Hudson.T_UI_SpecialPack_Aliens_Hudson"
+ $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[3].uri: "images/T_UI_SpecialPack_Aliens_Hudson.png"
+ $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[4].contentVersion: "53f65dbd74c78bb0f527d27b019825a215ae0a5b"
+ $.entries[4].contentVersion: "019bd9f78117c22e825d54799ad5a34fbca2abfa"
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_AoT_2.T_UI_CollectionBanner_AoT_2"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_Songkran.T_UI_CollectionBanner_Songkran"
- $.entries[4].uri: "images/T_UI_CollectionBanner_AoT_2.png"
+ $.entries[4].uri: "images/T_UI_CollectionBanner_Songkran.png"
- $.entries[5].contentVersion: "cd78791691749d15bd36957f6370133a990f85a4"
+ $.entries[5].contentVersion: "ef596b89f090b384fc3ce9a9ea2157313250f9be"
- $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_AoT_2.T_UI_SpecialPack_AoT_2"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Songkran.T_UI_SpecialPack_Songkran"
- $.entries[5].uri: "images/T_UI_SpecialPack_AoT_2.png"
+ $.entries[5].uri: "images/T_UI_SpecialPack_Songkran.png"
- $.entries[6].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[6].contentVersion: "16e0c3c71627606efbf39ab95733c748fd426028"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[7].contentVersion: "00ccec5c57d21b3084d71e55376d5df80b2b4e44"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[8].contentVersion: "4660259350d68d784ff362796b810d90249c934e"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "14139f9b234fdd66cb273cc5fd16228bd75b3258"
+ $.entries[9].contentVersion: "4660259350d68d784ff362796b810d90249c934e"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_Aliens_Hudson.T_UI_CollectionBanner_Aliens_Hudson"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_CollectionBanner_Aliens_Hudson.png"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "fef3ab3957518899c95abb8a021b8f85e4cb34bf"
+ $.entries[10].contentVersion: "563ba8863857d87bfce206cca6f3d2bac203f56f"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_Aliens_Hudson.T_UI_SpecialPack_Aliens_Hudson"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_SpecialPack_Aliens_Hudson.png"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "53f65dbd74c78bb0f527d27b019825a215ae0a5b"
+ $.entries[11].contentVersion: "3115f5e7d61a970a71e9a41100a55f046eb9bd48"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Ramen/T_UI_CollectionBanner_AoT_2.T_UI_CollectionBanner_AoT_2"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_CollectionBanner_AoT_2.png"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "cd78791691749d15bd36957f6370133a990f85a4"
+ $.entries[12].contentVersion: "e2dcf644f8525a2ae1a9233bf85b0df55370c5bc"
- $.entries[12].downloadStrategy: "preferPackaged"
+ $.entries[12].downloadStrategy: "preferRemote"
- $.entries[12].enableChecksum: false
+ $.entries[12].enableChecksum: true
- $.entries[12].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Ramen/T_UI_SpecialPack_AoT_2.T_UI_SpecialPack_AoT_2"
+ $.entries[12].packagedPath: ""
- $.entries[12].schema: "s3verbin://"
+ $.entries[12].schema: "s3ver://"
- $.entries[12].uri: "images/T_UI_SpecialPack_AoT_2.png"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "24ce5266e6e528945160dcb7d48beb625dfcbf6b"
+ $.entries[13].contentVersion: "cddf4d17ad3a41bfc299db5d6a90fbced3b21e58"
- $.entries[13].uri: "catalog.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "9bc7504e7a5bcc4398add60d02e147e250a6dd5d"
+ $.entries[14].contentVersion: "7d287907649ba3489aeb1dcf64693d3b7616ebce"
- $.entries[14].uri: "bonusPointEventsContent.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "57b2f10b394a5daf365b9b02d33199497ca5a84d"
+ $.entries[15].contentVersion: "87c0d35b78cefcb1e3662e2e2c3f75318d3a3548"
- $.entries[15].uri: "freetoplay/NA/event.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "57b2f10b394a5daf365b9b02d33199497ca5a84d"
+ $.entries[16].contentVersion: "bb3f06a2880e3ff04e3b6238b498422861c71297"
- $.entries[16].uri: "freetoplay/EU/event.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "3953720ee154b487c3f492621098e7f4a6a4a5e9"
+ $.entries[17].contentVersion: "4579ad21e48a50b6a3df083acae1bda30b51b927"
- $.entries[17].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "965b39e991ac1f0aab369f8be266e55490a7a925"
+ $.entries[18].contentVersion: "a5fd0fb1270f3c2acdde21598d487e6982e142f8"
- $.entries[18].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "8d15a6cc85ac05877bc37f90a5ccebea3750379e"
+ $.entries[19].contentVersion: "3c418e56e731fa6c0bce50fe214afdcbebed4d97"
- $.entries[19].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "e72b49f1600e1e1c2141811a0383e8558b4c29af"
+ $.entries[20].contentVersion: "ce17656b4f57f9bb4f55a647888e9c131cbffd86"
- $.entries[20].uri: "archiveQuests/CalamariV1.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "e61223c7b774ec09a8ec2af894eeb9fa8b43d2bd"
+ $.entries[21].contentVersion: "31c2ba9e1fc6549a9d87fd8e886cf58a3c6d620b"
- $.entries[21].uri: "archiveQuests/CalamariV2.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "6cfe47ec654820643f994811c5e018baf1b073c8"
+ $.entries[22].contentVersion: "0920c356f45356ae9a1f8194d39076438f3595e3"
- $.entries[22].uri: "archiveQuests/CalamariV3.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "18ba000dd125ee35ad8a1ccb4bdd41f29b57ac17"
+ $.entries[23].contentVersion: "9298ad2daaa92b1ad66dfc69c159ca51919ab7e9"
- $.entries[23].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "84455a29d341abc102fcf68c0c9d1397b11c8346"
+ $.entries[24].contentVersion: "e9e019462c7bdc7cac1ec0ff6843f2f3d0d3852b"
- $.entries[24].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "909c1f2584bcc773d4f7043b7de6824f9d6a0cd6"
+ $.entries[25].contentVersion: "bae9534b4da6340edc518860172b367beb402155"
- $.entries[25].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "9b8e124de452ee838bf37963ec62f4085839cc41"
+ $.entries[26].contentVersion: "1a3c1265f105674a7f30254832f60258fc420487"
- $.entries[26].uri: "archiveQuests/FireflyV1.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "4c20d7caf91bc607087db7bac0c4eab7c9953277"
+ $.entries[27].contentVersion: "c85645524e7d9462e910271ec5d6c54871a80085"
- $.entries[27].uri: "archiveQuests/Halloween2021.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "c16b0896331824bff516844b11cae24aaf0a9123"
+ $.entries[28].contentVersion: "c22d11818ccd3e092fa80428aa70dc5f5e531931"
- $.entries[28].uri: "archiveQuests/Halloween2022.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "3af021a9c7fe2b734209e8d98f0fb0325b923f72"
+ $.entries[29].contentVersion: "8516f40e7e71b533193b4bcf03f6bf4675a1f614"
- $.entries[29].uri: "archiveQuests/Halloween2023.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "4ab23d5d546f7a8fd1cdcc83370c2cac64af070e"
+ $.entries[30].contentVersion: "da3a16840f040f646d2581527f85728bc77c71a6"
- $.entries[30].uri: "archiveQuests/Halloween2024.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "e331c3e442fedfde5fd54d7681349943e4cfc773"
+ $.entries[31].contentVersion: "c785a3236927daa079873486ebcc9be943275e0d"
- $.entries[31].uri: "archiveQuests/Spring2024.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "896c9bbe16c2360eda0f602817c87915ea53702d"
+ $.entries[32].contentVersion: "31896fd041142a0281c074a1a620bc082bdb7fcc"
- $.entries[32].uri: "archiveQuests/Spring2025.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
… 765 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.Legion.gameTypes
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=Ramen_W1]
- $.featuredCard[id=Ramen_W2]
- $.featuredCard[id=Ramen_W3]
- $.featuredCard[id=Lasagna_W7].activeTo: "2025-09-25T15:00:00"
+ $.featuredCard[id=Lasagna_W7].activeTo: "2025-09-23T15:00:00"
- $.featuredCard[id=Lasagna_W7].activeToInMs: 1758812400
+ $.featuredCard[id=Lasagna_W7].activeToInMs: 1758639600
- $.featuredCard[id=Lasagna_W7].entries[0].entryId: "ModernBaroque"
+ $.featuredCard[id=Lasagna_W7].entries[0].entryId: "Tome_6_Bundle"
- $.featuredCard[id=Lasagna_W7].entries[0].type: "Collection"
+ $.featuredCard[id=Lasagna_W7].entries[0].type: "SpecialPack"
- $.featuredCard[id=Lasagna_W7].entries[0].weight: 14
+ $.featuredCard[id=Lasagna_W7].entries[0].weight: 15
- $.featuredCard[id=Lasagna_W7].entries[1].entryId: "PartyGoneWrong"
+ $.featuredCard[id=Lasagna_W7].entries[1].entryId: "ModernBaroque"
- $.featuredCard[id=Lasagna_W7].entries[1].weight: 13
+ $.featuredCard[id=Lasagna_W7].entries[1].weight: 14
- $.featuredCard[id=Lasagna_W7].entries[2].entryId: "Counterculture"
+ $.featuredCard[id=Lasagna_W7].entries[2].entryId: "PartyGoneWrong"
- $.featuredCard[id=Lasagna_W7].entries[2].weight: 12
+ $.featuredCard[id=Lasagna_W7].entries[2].weight: 13
- $.featuredCard[id=Lasagna_W7].entries[3].entryId: "Rift_2_Bundle"
+ $.featuredCard[id=Lasagna_W7].entries[3].entryId: "Counterculture"
- $.featuredCard[id=Lasagna_W7].entries[3].type: "SpecialPack"
+ $.featuredCard[id=Lasagna_W7].entries[3].type: "Collection"
- $.featuredCard[id=Lasagna_W7].entries[3].weight: 9
+ $.featuredCard[id=Lasagna_W7].entries[3].weight: 12
+ $.featuredCard[id=Lasagna_W7].entries[4]
- $.featuredCustomizationRecommendations[id=RamenW1]
- $.featuredCustomizationRecommendations[id=RamenW2]
- $.featuredCustomizationRecommendations[id=RamenW3]
- $.specialsRecommendations[id=RoadToAnniversary2026_W1]
- $.specialsRecommendations[id=RoadToAnniversary2026_W2]
- $.specialsRecommendations[id=RoadToAnniversary2026_W3]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[65].startTime: "2026-03-26T17:00:00"
+ $.specialEvents[65].startTime: "2026-03-26T15:00:00"
- $.specialEvents[66].startTime: "2026-03-26T17:00:00"
+ $.specialEvents[66].startTime: "2026-03-26T15:00:00"
+ $.specialEvents[67].eventName
+ $.specialEvents[67].eventType: "MapShowcase"
- $.specialEvents[67].eventId: "CalamariV8"
+ $.specialEvents[67].eventId: "MapShowcaseQuiche"
- $.specialEvents[67].mainEndTime: "2026-05-19T15:00:00"
+ $.specialEvents[67].mainEndTime: "2026-03-24T15:00:00"
- $.specialEvents[67].postEndTime: "2026-05-19T15:00:00"
+ $.specialEvents[67].postEndTime: "2026-03-24T15:00:00"
- $.specialEvents[67].startTime: "2026-04-28T15:00:00"
+ $.specialEvents[67].startTime: "2026-03-17T15:00:00"
- $.specialEvents[67].useCommonData: false
+ $.specialEvents[67].useCommonData: true
- $.specialEvents[68]
- $.specialEventsData[13].eventId: "CalamariV8"
+ $.specialEventsData[13].eventId: "ChocolateBoxEclair"
+ $.specialEventsData[13].lteData.incentiveBonus: 0.0
- $.specialEventsData[13].lteData.affectsMMR: false
+ $.specialEventsData[13].lteData.affectsMMR: true
- $.specialEventsData[13].lteData.gameModeQueue: "Calamari"
+ $.specialEventsData[13].lteData.gameModeQueue: "ChocolateBox"
- $.specialEventsData[13].lteData.gameType: "Calamari"
+ $.specialEventsData[13].lteData.gameType: "ChocolateBox"
- $.specialEventsData[14].eventId: "ChocolateBoxEclair"
+ $.specialEventsData[14].eventId: "ChocolateBoxGelato"
- $.specialEventsData[15].eventId: "ChocolateBoxGelato"
+ $.specialEventsData[15].eventId: "ChocolateBoxHotdog"
- $.specialEventsData[16].eventId: "ChocolateBoxHotdog"
+ $.specialEventsData[16].eventId: "ChocolateBoxIcecream"
- $.specialEventsData[17].eventId: "ChocolateBoxIcecream"
+ $.specialEventsData[17].eventId: "ChocolateBoxJerky"
- $.specialEventsData[18].eventId: "ChocolateBoxJerky"
+ $.specialEventsData[18].eventId: "ChocolateBoxKetchup"
- $.specialEventsData[19].eventId: "ChocolateBoxKetchup"
+ $.specialEventsData[19].eventId: "ChocolateBoxOmelet"
- $.specialEventsData[19].lteData.incentiveBonus: 0.0
- $.specialEventsData[20].eventId: "ChocolateBoxOmelet"
+ $.specialEventsData[20].eventId: "ChocolateBoxV1"
+ $.specialEventsData[20].lteData.incentiveBonus: 0.0
- $.specialEventsData[21].eventId: "ChocolateBoxV1"
+ $.specialEventsData[21].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[21].lteData.affectsMMR: true
+ $.specialEventsData[21].lteData.affectsMMR: false
- $.specialEventsData[21].lteData.gameModeQueue: "ChocolateBox"
+ $.specialEventsData[21].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[21].lteData.gameType: "ChocolateBox"
+ $.specialEventsData[21].lteData.gameType: "DreadByDaylight"
- $.specialEventsData[22].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[22].eventId: "FireflyV1"
- $.specialEventsData[22].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[22].lteData.gameModeQueue: "Firefly"
- $.specialEventsData[22].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[22].lteData.gameType: "Firefly"
- $.specialEventsData[23].lteData
- $.specialEventsData[23].eventId: "FireflyV1"
+ $.specialEventsData[23].eventId: "Halloween2022"
+ $.specialEventsData[23].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[24].eventId: "Halloween2022"
+ $.specialEventsData[24].eventId: "Halloween2023"
+ $.specialEventsData[24].milestoneRewards[0]
+ $.specialEventsData[24].milestoneRewards[1]
+ $.specialEventsData[24].milestoneRewards[2]
- $.specialEventsData[24].ownerRewards[id=Halloween2022Reward]
+ $.specialEventsData[25].lteData
- $.specialEventsData[25].eventId: "Halloween2023"
+ $.specialEventsData[25].eventId: "Halloween2024"
+ $.specialEventsData[25].eventPeriods[id=Halloween2024]
- $.specialEventsData[25].milestoneRewards[0].rewards[id=XR_037]
+ $.specialEventsData[25].milestoneRewards[0].rewards[id=FU_012]
- $.specialEventsData[25].milestoneRewards[1].rewards[id=MT_Head027]
+ $.specialEventsData[25].milestoneRewards[1].rewards[id=FU_BDG_18]
- $.specialEventsData[25].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[25].milestoneRewards[2].pointsCost: 20
- $.specialEventsData[25].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[25].milestoneRewards[2].rewards[id=FU_BNR_12]
- $.specialEventsData[26].eventId: "Halloween2024"
+ $.specialEventsData[26].eventId: "Halloween2025"
- $.specialEventsData[26].eventPeriods[id=Halloween2024]
- $.specialEventsData[26].lteData.incentiveBonus: 50.0
- $.specialEventsData[26].lteData.gameModeQueue: "Halloween2024"
+ $.specialEventsData[26].lteData.gameModeQueue: "Halloween2025"
- $.specialEventsData[26].milestoneRewards[0]
- $.specialEventsData[26].milestoneRewards[1]
- $.specialEventsData[26].milestoneRewards[2]
- $.specialEventsData[27].lteData
- $.specialEventsData[27].eventId: "Halloween2025"
+ $.specialEventsData[27].eventId: "Lunar2022"
+ $.specialEventsData[27].miscRewards[id=killerStaticReward]
+ $.specialEventsData[27].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[27].scoreEventRewards[0]
+ $.specialEventsData[27].scoreEventRewards[1]
+ $.specialEventsData[27].scoreEventRewards[2]
+ $.specialEventsData[27].scoreEventRewards[3]
+ $.specialEventsData[27].scoreEventRewards[4]
+ $.specialEventsData[27].scoreEventRewards[5]
+ $.specialEventsData[27].scoreEventRewards[6]
+ $.specialEventsData[27].scoreEventRewards[7]
- $.specialEventsData[28].eventId: "Lunar2022"
+ $.specialEventsData[28].eventId: "Lunar2023"
- $.specialEventsData[28].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
+ $.specialEventsData[28].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
- $.specialEventsData[28].ownerRewards[id=Lunar2022Reward]
+ $.specialEventsData[28].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[28].scoreEventRewards[2].weight: 20
+ $.specialEventsData[28].scoreEventRewards[2].weight: 15
- $.specialEventsData[28].scoreEventRewards[3].weight: 20
+ $.specialEventsData[28].scoreEventRewards[3].weight: 25
- $.specialEventsData[28].scoreEventRewards[5].weight: 15
+ $.specialEventsData[28].scoreEventRewards[5].weight: 20
- $.specialEventsData[28].scoreEventRewards[6].weight: 8
+ $.specialEventsData[28].scoreEventRewards[6].weight: 10
- $.specialEventsData[28].scoreEventRewards[7].weight: 2
+ $.specialEventsData[28].scoreEventRewards[7].weight: 5
+ $.specialEventsData[29].lteData
- $.specialEventsData[29].eventId: "Lunar2023"
+ $.specialEventsData[29].eventId: "MapShowcaseKetchup"
- $.specialEventsData[29].miscRewards[id=killerStaticReward]
- $.specialEventsData[29].ownerRewards[id=Lunar2023Reward]
- $.specialEventsData[29].scoreEventRewards[0]
- $.specialEventsData[29].scoreEventRewards[1]
- $.specialEventsData[29].scoreEventRewards[2]
- $.specialEventsData[29].scoreEventRewards[3]
- $.specialEventsData[29].scoreEventRewards[4]
- $.specialEventsData[29].scoreEventRewards[5]
- $.specialEventsData[29].scoreEventRewards[6]
- $.specialEventsData[29].scoreEventRewards[7]
- $.specialEventsData[30].eventId: "MapShowcaseKetchup"
+ $.specialEventsData[30].eventId: "MapShowcaseQuiche"
- $.specialEventsData[31].lteData
- $.specialEventsData[31].eventId: "MapShowcaseQuiche"
+ $.specialEventsData[31].eventId: "Spring2024"
+ $.specialEventsData[31].eventTrackerObjectives[id=main]
+ $.specialEventsData[32].lteData
- $.specialEventsData[32].eventId: "Spring2024"
+ $.specialEventsData[32].eventId: "Spring2025"
- $.specialEventsData[32].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
- $.specialEventsData[32].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
+ $.specialEventsData[32].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
+ $.specialEventsData[32].eventTrackerObjectives[id=main].questEventConditions
+ $.specialEventsData[32].eventTrackerObjectives[id=main].questEvents
- $.specialEventsData[32].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
+ $.specialEventsData[32].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[4]
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[5]
+ $.specialEventsData[32].milestoneRewards[0]
+ $.specialEventsData[32].milestoneRewards[1]
+ $.specialEventsData[32].milestoneRewards[2]
- $.specialEventsData[33].eventId: "Spring2025"
+ $.specialEventsData[33].eventId: "Spring2026"
+ $.specialEventsData[33].eventPeriods[id=Spring2025]
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.5
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.75
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].neededProgression: 5000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.25
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].neededProgression: 15000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 3.0
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].neededProgression: 25000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].additiveMultiplier: 3.75
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].additiveMultiplier: 4.0
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].neededProgression: 35000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].neededProgression: 40000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[5].neededProgression: 50000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[5].neededProgression: 55000000
- $.specialEventsData[33].lteData.gameModeQueue: "Spring2025"
+ $.specialEventsData[33].lteData.gameModeQueue: "Spring2026"
- $.specialEventsData[33].milestoneRewards[0]
- $.specialEventsData[33].milestoneRewards[1]
- $.specialEventsData[33].milestoneRewards[2]
- $.specialEventsData[34].lteData
- $.specialEventsData[34].eventId: "Spring2026"
+ $.specialEventsData[34].eventId: "Winter2023"
- $.specialEventsData[34].eventPeriods[id=Spring2025]
- $.specialEventsData[34].eventTrackerObjectives[id=main]
+ $.specialEventsData[34].milestoneRewards[0]
+ $.specialEventsData[34].milestoneRewards[1]
+ $.specialEventsData[34].milestoneRewards[2]
… 30 more change(s) — see the commit diff for everything
```

