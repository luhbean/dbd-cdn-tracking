# live · 8.5.1_2282865live

| | |
|---|---|
| Build date | 2025-02-11 16:07 UTC |
| CDN version | `8.5.1_2282865live-1739290073` |
| Key | `8.5.1_live` |
| Compared with | [8.4.2_2231971live](../8.4.2_2231971live/CHANGES.md) (2025-01-21 20:32 UTC) |

## Summary

**4** added · **14** modified · **5** removed · 167 unchanged

## Added files

- [`archiveQuests/CalamariV3.json`](archiveQuests/CalamariV3.json)
- [`archiveQuests/Tome22.json`](archiveQuests/Tome22.json)
- [`archiveRewardGrid/Tome22.json`](archiveRewardGrid/Tome22.json)
- [`dlcList.json`](dlcList.json)

## Removed files

- `images/T_UI_CollectionBanner_DungeonsAndDragons2.png`
- `images/T_UI_SpecialPack_BoneChill2023.png`
- `images/T_UI_SpecialPack_DungeonsAndDragons.png`
- `images/T_UI_SpecialPack_JunjiIto.png`
- `images/T_UI_SpecialPack_WinterTales.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.dlc
+ $.entitlementConfig
+ $.lobbyBot
+ $.analyticsRules.KL[]: "CustomizationAuditAnalytics"
+ $.dedicatedServer.endpointsHTTP[10]
+ $.dedicatedServer.endpointsHTTP[11]
+ $.dedicatedServer.endpointsHTTP[12]
+ $.dedicatedServer.endpointsHTTP[13]
+ $.dedicatedServer.endpointsUDP[10]
+ $.dedicatedServer.endpointsUDP[11]
+ $.dedicatedServer.endpointsUDP[12]
+ $.dedicatedServer.endpointsUDP[13]
+ $.dedicatedServer.endpointsUDP[14]
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
+ $.CalamariV3
+ $.Tome22
```

### [`archiveQuests/Tome02.json`](archiveQuests/Tome02.json)

[Full line-by-line diff](diffs/archiveQuests/Tome02.json.diff)

```diff
- $.Tome02.level[0].nodes.node_L1_10.objectives.Kill.questEvent[0].parameters: "target:other"
+ $.Tome02.level[0].nodes.node_L1_10.objectives.Kill.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome02.level[0].nodes.node_L1_11.objectives.Hook.questEvent[0].parameters: "target:other"
+ $.Tome02.level[0].nodes.node_L1_11.objectives.Hook.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome02.level[1].nodes.nodeEnd.coordinates.x: 93.33333333333333
+ $.Tome02.level[1].nodes.nodeEnd.coordinates.x: 93.33333333
- $.Tome02.level[1].nodes.nodeEnd.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.nodeEnd.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.nodeStart.coordinates.x: 8.88888888888889
+ $.Tome02.level[1].nodes.nodeStart.coordinates.x: 8.888888889
- $.Tome02.level[1].nodes.nodeStart.coordinates.y: 50.76923076923077
+ $.Tome02.level[1].nodes.nodeStart.coordinates.y: 50.76923077
- $.Tome02.level[1].nodes.node_L2_01.coordinates.x: 62.22222222222222
+ $.Tome02.level[1].nodes.node_L2_01.coordinates.x: 62.22222222
- $.Tome02.level[1].nodes.node_L2_01.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_01.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.node_L2_02.coordinates.x: 35.55555555555556
+ $.Tome02.level[1].nodes.node_L2_02.coordinates.x: 35.55555556
- $.Tome02.level[1].nodes.node_L2_02.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_02.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_03.coordinates.x: 62.22222222222222
+ $.Tome02.level[1].nodes.node_L2_03.coordinates.x: 62.22222222
- $.Tome02.level[1].nodes.node_L2_03.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_03.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_04.coordinates.x: 48.888888888888886
+ $.Tome02.level[1].nodes.node_L2_04.coordinates.x: 48.88888889
- $.Tome02.level[1].nodes.node_L2_04.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_04.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_05.coordinates.x: 62.22222222222222
+ $.Tome02.level[1].nodes.node_L2_05.coordinates.x: 62.22222222
- $.Tome02.level[1].nodes.node_L2_05.coordinates.y: 50.76923076923077
+ $.Tome02.level[1].nodes.node_L2_05.coordinates.y: 50.76923077
- $.Tome02.level[1].nodes.node_L2_06.coordinates.x: 75.55555555555556
+ $.Tome02.level[1].nodes.node_L2_06.coordinates.x: 75.55555556
- $.Tome02.level[1].nodes.node_L2_06.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_06.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_07.coordinates.x: 82.22222222222223
+ $.Tome02.level[1].nodes.node_L2_07.coordinates.x: 82.22222222
- $.Tome02.level[1].nodes.node_L2_07.coordinates.y: 50.76923076923077
+ $.Tome02.level[1].nodes.node_L2_07.coordinates.y: 50.76923077
- $.Tome02.level[1].nodes.node_L2_08.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_08.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_09.coordinates.x: 42.22222222222222
+ $.Tome02.level[1].nodes.node_L2_09.coordinates.x: 42.22222222
- $.Tome02.level[1].nodes.node_L2_09.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_09.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.node_L2_10.coordinates.x: 75.55555555555556
+ $.Tome02.level[1].nodes.node_L2_10.coordinates.x: 75.55555556
- $.Tome02.level[1].nodes.node_L2_10.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_10.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.node_L2_10.objectives.SacrificeEndgame.questEvent[0].parameters: "target:other"
+ $.Tome02.level[1].nodes.node_L2_10.objectives.SacrificeEndgame.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome02.level[1].nodes.node_L2_11.coordinates.x: 28.88888888888889
+ $.Tome02.level[1].nodes.node_L2_11.coordinates.x: 28.88888889
- $.Tome02.level[1].nodes.node_L2_11.coordinates.y: 50.76923076923077
+ $.Tome02.level[1].nodes.node_L2_11.coordinates.y: 50.76923077
- $.Tome02.level[1].nodes.node_L2_12.coordinates.x: 75.55555555555556
+ $.Tome02.level[1].nodes.node_L2_12.coordinates.x: 75.55555556
- $.Tome02.level[1].nodes.node_L2_12.coordinates.y: 4.615384615384615
+ $.Tome02.level[1].nodes.node_L2_12.coordinates.y: 4.615384615
- $.Tome02.level[1].nodes.node_L2_13.coordinates.x: 62.22222222222222
+ $.Tome02.level[1].nodes.node_L2_13.coordinates.x: 62.22222222
- $.Tome02.level[1].nodes.node_L2_13.coordinates.y: 4.615384615384615
+ $.Tome02.level[1].nodes.node_L2_13.coordinates.y: 4.615384615
- $.Tome02.level[1].nodes.node_L2_14.coordinates.x: 48.888888888888886
+ $.Tome02.level[1].nodes.node_L2_14.coordinates.x: 48.88888889
- $.Tome02.level[1].nodes.node_L2_14.coordinates.y: 50.76923076923077
+ $.Tome02.level[1].nodes.node_L2_14.coordinates.y: 50.76923077
- $.Tome02.level[1].nodes.node_L2_15.coordinates.x: 48.888888888888886
+ $.Tome02.level[1].nodes.node_L2_15.coordinates.x: 48.88888889
- $.Tome02.level[1].nodes.node_L2_15.coordinates.y: 4.615384615384615
+ $.Tome02.level[1].nodes.node_L2_15.coordinates.y: 4.615384615
- $.Tome02.level[1].nodes.node_L2_16.coordinates.y: 96.92307692307692
+ $.Tome02.level[1].nodes.node_L2_16.coordinates.y: 96.92307692
- $.Tome02.level[1].nodes.node_L2_17.coordinates.x: 15.555555555555555
+ $.Tome02.level[1].nodes.node_L2_17.coordinates.x: 15.55555556
- $.Tome02.level[1].nodes.node_L2_17.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_17.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.node_L2_17.objectives.DoctorInflictMadness1DifferentInTrial.questEvent[0].parameters: "target:other"
+ $.Tome02.level[1].nodes.node_L2_17.objectives.DoctorInflictMadness1DifferentInTrial.questEvent[0].parameters: "instigator:me;target:other"
- $.Tome02.level[1].nodes.node_L2_18.coordinates.x: 68.88888888888889
+ $.Tome02.level[1].nodes.node_L2_18.coordinates.x: 68.88888889
- $.Tome02.level[1].nodes.node_L2_18.coordinates.y: 96.92307692307692
+ $.Tome02.level[1].nodes.node_L2_18.coordinates.y: 96.92307692
- $.Tome02.level[1].nodes.node_L2_19.coordinates.x: 28.88888888888889
+ $.Tome02.level[1].nodes.node_L2_19.coordinates.x: 28.88888889
- $.Tome02.level[1].nodes.node_L2_19.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_19.coordinates.y: 73.84615385
- $.Tome02.level[1].nodes.node_L2_20.coordinates.x: 88.88888888888889
+ $.Tome02.level[1].nodes.node_L2_20.coordinates.x: 88.88888889
- $.Tome02.level[1].nodes.node_L2_20.coordinates.y: 27.692307692307693
+ $.Tome02.level[1].nodes.node_L2_20.coordinates.y: 27.69230769
- $.Tome02.level[1].nodes.node_L2_21.coordinates.x: 4.444444444444445
+ $.Tome02.level[1].nodes.node_L2_21.coordinates.x: 4.444444444
- $.Tome02.level[1].nodes.node_L2_21.coordinates.y: 73.84615384615384
+ $.Tome02.level[1].nodes.node_L2_21.coordinates.y: 73.84615385
+ $.Tome02.level[1].nodes.node_L2_21.objectives.HookInTrial.questEvent[0].parameters: "instigator:me"
- $.Tome02.level[1].nodes.node_L2_22.coordinates.x: 93.33333333333333
+ $.Tome02.level[1].nodes.node_L2_22.coordinates.x: 93.33333333
- $.Tome02.level[1].nodes.node_L2_22.coordinates.y: 96.92307692307692
+ $.Tome02.level[1].nodes.node_L2_22.coordinates.y: 96.92307692
+ $.Tome02.level[1].nodes.node_L2_22.objectives.GrabInTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[2].nodes.node_L3_09.objectives.SacrificeEndgame.questEvent[0].parameters: "instigator:me"
- $.Tome02.level[2].nodes.node_L3_10.objectives.Down.questEvent[0].parameters: "target:other"
+ $.Tome02.level[2].nodes.node_L3_10.objectives.Down.questEvent[0].parameters: "instigator:me;target:other"
+ $.Tome02.level[2].nodes.node_L3_15.objectives.DoctorInflictMadness3InTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[2].nodes.node_L3_17.objectives.SpiritHitPostPhaseInTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[2].nodes.node_L3_18.objectives.DownWithPerkInTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[2].nodes.node_L3_19.objectives.HookInTrial.questEvent[0].parameters: "instigator:me"
+ $.Tome02.level[3].nodes.node_L4_05.objectives.EarnBloodpoints.questEvent[0].parameters: "instigator:me"
- $.Tome02.level[3].nodes.node_L4_22.objectives.DownInTrial.questEvent[0].parameters: "target:other"
+ $.Tome02.level[3].nodes.node_L4_22.objectives.DownInTrial.questEvent[0].parameters: "instigator:me;target:other"
```

### [`archiveRewardData/content.json`](archiveRewardData/content.json)

[Full line-by-line diff](diffs/archiveRewardData/content.json.diff)

```diff
+ $.Tome22
- $.Tome21.endDate: "2025-01-28T16:00:00"
+ $.Tome21.endDate: "2025-01-28T15:00:00"
- $.Tome21.postEndDate: "2025-01-28T16:00:00"
+ $.Tome21.postEndDate: "2025-01-28T15:00:00"
```

### [`bonusPointEventsContent.json`](bonusPointEventsContent.json)

[Full line-by-line diff](diffs/bonusPointEventsContent.json.diff)

```diff
- $.bonusPointEvents[0].endTime: "2025-01-28T15:59:00"
+ $.bonusPointEvents[0].endTime: "2025-02-10T15:59:00"
- $.bonusPointEvents[0].startTime: "2025-01-21T16:00:00"
+ $.bonusPointEvents[0].startTime: "2025-02-04T16:00:00"
- $.bonusPointEvents[1].endTime: "2025-01-07T15:59:00"
+ $.bonusPointEvents[1].endTime: "2025-01-28T15:59:00"
- $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[1].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[1].multiplier: 3.0
+ $.bonusPointEvents[1].multiplier: 2.0
- $.bonusPointEvents[1].startTime: "2024-12-26T16:00:00"
+ $.bonusPointEvents[1].startTime: "2025-01-21T16:00:00"
- $.bonusPointEvents[2].endTime: "2024-12-26T15:59:00"
+ $.bonusPointEvents[2].endTime: "2025-01-07T15:59:00"
- $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[2].multiplier: 2.0
+ $.bonusPointEvents[2].multiplier: 3.0
- $.bonusPointEvents[2].startTime: "2024-12-19T16:00:00"
+ $.bonusPointEvents[2].startTime: "2024-12-26T16:00:00"
- $.bonusPointEvents[3].endTime: "2024-11-28T16:00:00"
+ $.bonusPointEvents[3].endTime: "2024-12-26T15:59:00"
- $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[3].multiplier: 3.0
+ $.bonusPointEvents[3].multiplier: 2.0
- $.bonusPointEvents[3].startTime: "2024-11-22T20:00:00"
+ $.bonusPointEvents[3].startTime: "2024-12-19T16:00:00"
- $.bonusPointEvents[4].endTime: "2024-10-01T15:00:00"
+ $.bonusPointEvents[4].endTime: "2024-11-28T16:00:00"
- $.bonusPointEvents[4].startTime: "2024-09-24T15:00:00"
+ $.bonusPointEvents[4].startTime: "2024-11-22T20:00:00"
- $.bonusPointEvents[5].endTime: "2024-09-12T15:00:00"
+ $.bonusPointEvents[5].endTime: "2024-10-01T15:00:00"
- $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[5].multiplier: 2.0
+ $.bonusPointEvents[5].multiplier: 3.0
- $.bonusPointEvents[5].startTime: "2024-09-05T15:00:00"
+ $.bonusPointEvents[5].startTime: "2024-09-24T15:00:00"
- $.bonusPointEvents[6].endTime: "2024-06-13T15:00:00"
+ $.bonusPointEvents[6].endTime: "2024-09-12T15:00:00"
- $.bonusPointEvents[6].startTime: "2024-06-03T15:00:00"
+ $.bonusPointEvents[6].startTime: "2024-09-05T15:00:00"
- $.bonusPointEvents[7].endTime: "2024-05-21T15:00:00"
+ $.bonusPointEvents[7].endTime: "2024-06-13T15:00:00"
- $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[7].multiplier: 3.0
+ $.bonusPointEvents[7].multiplier: 2.0
- $.bonusPointEvents[7].startTime: "2024-05-14T16:00:00"
+ $.bonusPointEvents[7].startTime: "2024-06-03T15:00:00"
- $.bonusPointEvents[8].endTime: "2024-02-20T16:00:00"
+ $.bonusPointEvents[8].endTime: "2024-05-21T15:00:00"
- $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[8].multiplier: 1.5
+ $.bonusPointEvents[8].multiplier: 3.0
- $.bonusPointEvents[8].startTime: "2024-02-14T16:00:00"
+ $.bonusPointEvents[8].startTime: "2024-05-14T16:00:00"
- $.bonusPointEvents[9].endTime: "2023-09-19T15:00:00"
+ $.bonusPointEvents[9].endTime: "2024-02-20T16:00:00"
- $.bonusPointEvents[9].startTime: "2023-09-12T15:00:00"
+ $.bonusPointEvents[9].startTime: "2024-02-14T16:00:00"
- $.bonusPointEvents[10].endTime: "2023-07-13T15:00:00"
+ $.bonusPointEvents[10].endTime: "2023-09-19T15:00:00"
- $.bonusPointEvents[10].startTime: "2023-07-07T15:00:00"
+ $.bonusPointEvents[10].startTime: "2023-09-12T15:00:00"
- $.bonusPointEvents[11].endTime: "2023-05-30T15:00:00"
+ $.bonusPointEvents[11].endTime: "2023-07-13T15:00:00"
- $.bonusPointEvents[11].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[11].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[11].multiplier: 2.0
+ $.bonusPointEvents[11].multiplier: 1.5
- $.bonusPointEvents[11].startTime: "2023-05-23T15:00:00"
+ $.bonusPointEvents[11].startTime: "2023-07-07T15:00:00"
- $.bonusPointEvents[12].endTime: "2022-11-29T16:00:00"
+ $.bonusPointEvents[12].endTime: "2023-05-30T15:00:00"
- $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[12].startTime: "2022-11-22T16:00:00"
+ $.bonusPointEvents[12].startTime: "2023-05-23T15:00:00"
- $.bonusPointEvents[13].endTime: "2022-06-27T15:00:00"
+ $.bonusPointEvents[13].endTime: "2022-11-29T16:00:00"
- $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[13].startTime: "2022-06-23T15:00:00"
+ $.bonusPointEvents[13].startTime: "2022-11-22T16:00:00"
- $.bonusPointEvents[14].endTime: "2022-05-30T15:00:00"
+ $.bonusPointEvents[14].endTime: "2022-06-27T15:00:00"
- $.bonusPointEvents[14].startTime: "2022-05-23T15:00:00"
+ $.bonusPointEvents[14].startTime: "2022-06-23T15:00:00"
- $.bonusPointEvents[15].endTime: "2022-03-07T16:00:00"
+ $.bonusPointEvents[15].endTime: "2022-05-30T15:00:00"
- $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[15].multiplier: 1.5
+ $.bonusPointEvents[15].multiplier: 2.0
- $.bonusPointEvents[15].startTime: "2022-02-28T16:00:00"
+ $.bonusPointEvents[15].startTime: "2022-05-23T15:00:00"
- $.bonusPointEvents[16].endTime: "2022-01-21T16:00:00"
+ $.bonusPointEvents[16].endTime: "2022-03-07T16:00:00"
- $.bonusPointEvents[16].startTime: "2022-01-14T16:00:00"
+ $.bonusPointEvents[16].startTime: "2022-02-28T16:00:00"
- $.bonusPointEvents[17].endTime: "2021-11-29T16:00:00"
+ $.bonusPointEvents[17].endTime: "2022-01-21T16:00:00"
- $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[17].multiplier: 2.0
+ $.bonusPointEvents[17].multiplier: 1.5
- $.bonusPointEvents[17].startTime: "2021-11-25T16:00:00"
+ $.bonusPointEvents[17].startTime: "2022-01-14T16:00:00"
- $.bonusPointEvents[18].endTime: "2021-08-03T15:00:00"
+ $.bonusPointEvents[18].endTime: "2021-11-29T16:00:00"
- $.bonusPointEvents[18].startTime: "2021-07-29T15:00:00"
+ $.bonusPointEvents[18].startTime: "2021-11-25T16:00:00"
- $.bonusPointEvents[19].endTime: "2021-01-22T16:00:00"
+ $.bonusPointEvents[19].endTime: "2021-08-03T15:00:00"
- $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[19].multiplier: 1.5
+ $.bonusPointEvents[19].multiplier: 2.0
- $.bonusPointEvents[19].startTime: "2021-01-15T16:00:00"
+ $.bonusPointEvents[19].startTime: "2021-07-29T15:00:00"
- $.bonusPointEvents[20].endTime: "2020-11-02T16:29:59"
+ $.bonusPointEvents[20].endTime: "2021-01-22T16:00:00"
- $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[20].multiplier: 2.0
+ $.bonusPointEvents[20].multiplier: 1.5
- $.bonusPointEvents[20].startTime: "2020-10-29T15:00:00"
+ $.bonusPointEvents[20].startTime: "2021-01-15T16:00:00"
- $.bonusPointEvents[21].endTime: "2020-04-15T15:00:00"
+ $.bonusPointEvents[21].endTime: "2020-11-02T16:29:59"
- $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[21].multiplier: 1.5
+ $.bonusPointEvents[21].multiplier: 2.0
- $.bonusPointEvents[21].startTime: "2020-03-25T15:00:00"
+ $.bonusPointEvents[21].startTime: "2020-10-29T15:00:00"
- $.bonusPointEvents[22].endTime: "2020-01-06T16:00:00"
+ $.bonusPointEvents[22].endTime: "2020-04-15T15:00:00"
- $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[22].multiplier: 2.0
+ $.bonusPointEvents[22].multiplier: 1.5
- $.bonusPointEvents[22].startTime: "2020-01-02T16:00:00"
+ $.bonusPointEvents[22].startTime: "2020-03-25T15:00:00"
- $.bonusPointEvents[23].endTime: "2019-11-04T15:00:00"
+ $.bonusPointEvents[23].endTime: "2020-01-06T16:00:00"
- $.bonusPointEvents[23].startTime: "2019-10-31T15:00:00"
+ $.bonusPointEvents[23].startTime: "2020-01-02T16:00:00"
- $.bonusPointEvents[24].endTime: "2019-09-30T15:00:00"
+ $.bonusPointEvents[24].endTime: "2019-11-04T15:00:00"
- $.bonusPointEvents[24].startTime: "2019-09-26T15:00:00"
+ $.bonusPointEvents[24].startTime: "2019-10-31T15:00:00"
- $.bonusPointEvents[25].endTime: "2019-06-20T18:00:00"
+ $.bonusPointEvents[25].endTime: "2019-09-30T15:00:00"
- $.bonusPointEvents[25].startTime: "2019-06-14T18:00:00"
+ $.bonusPointEvents[25].startTime: "2019-09-26T15:00:00"
- $.bonusPointEvents[26].endTime: "2019-05-06T18:00:00"
+ $.bonusPointEvents[26].endTime: "2019-06-20T18:00:00"
- $.bonusPointEvents[26].startTime: "2019-05-02T18:00:00"
+ $.bonusPointEvents[26].startTime: "2019-06-14T18:00:00"
- $.bonusPointEvents[27].endTime: "2019-01-03T19:00:00"
+ $.bonusPointEvents[27].endTime: "2019-05-06T18:00:00"
- $.bonusPointEvents[27].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
+ $.bonusPointEvents[27].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[27].startTime: "2018-12-27T19:00:00"
+ $.bonusPointEvents[27].startTime: "2019-05-02T18:00:00"
- $.bonusPointEvents[28].endTime: "2018-11-12T19:00:00"
+ $.bonusPointEvents[28].endTime: "2019-01-03T19:00:00"
- $.bonusPointEvents[28].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[28].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
- $.bonusPointEvents[28].multiplier: 1.5
+ $.bonusPointEvents[28].multiplier: 2.0
- $.bonusPointEvents[28].startTime: "2018-11-05T19:00:00"
+ $.bonusPointEvents[28].startTime: "2018-12-27T19:00:00"
- $.bonusPointEvents[29].endTime: "2018-09-27T00:00:00"
+ $.bonusPointEvents[29].endTime: "2018-11-12T19:00:00"
- $.bonusPointEvents[29].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[29].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[29].multiplier: 2.0
+ $.bonusPointEvents[29].multiplier: 1.5
- $.bonusPointEvents[29].startTime: "2018-09-21T00:00:00"
+ $.bonusPointEvents[29].startTime: "2018-11-05T19:00:00"
- $.bonusPointEvents[30].endTime: "2023-11-06T16:00:00"
+ $.bonusPointEvents[30].endTime: "2018-09-27T00:00:00"
- $.bonusPointEvents[30].startTime: "2023-10-30T15:00:00"
+ $.bonusPointEvents[30].startTime: "2018-09-21T00:00:00"
- $.bonusPointEvents[31].endTime: "2015-10-13T00:00:00"
+ $.bonusPointEvents[31].endTime: "2023-11-06T16:00:00"
- $.bonusPointEvents[31].startTime: "2015-10-11T00:00:00"
+ $.bonusPointEvents[31].startTime: "2023-10-30T15:00:00"
- $.bonusPointEvents[32].endTime: "2015-09-12T00:00:00"
+ $.bonusPointEvents[32].endTime: "2015-10-13T00:00:00"
- $.bonusPointEvents[32].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[32].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[32].startTime: "2015-09-11T00:00:00"
+ $.bonusPointEvents[32].startTime: "2015-10-11T00:00:00"
… 7 more change(s) — see the commit diff for everything
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=RiftCharacters21_Pack]
- $[id=RiftPass21_Pack]
- $[id=RiftPass21_Premium_Pack]
- $[id=Recurring_Charm_Bundle_250121]
- $[id=Recurring_Dev_Bundle_250121]
- $[id=From_The_Rift_Bundle_250121]
- $[id=Recurring_Killer_Bundle_250121]
- $[id=Recurring_Survivor_Bundle_250121]
+ $[id=ARCHIVE_REWARD_PASS_Tome22]
+ $[id=ARCHIVE_REWARD_TIER_Tome22]
+ $[id=BE_Body027]
+ $[id=BE_Body027_01]
+ $[id=BE_Mask027]
+ $[id=BE_Mask027_01]
+ $[id=BE_W027]
+ $[id=BE_W027_01]
+ $[id=DK_Head027]
+ $[id=DK_Head027_01]
+ $[id=DK_Legs027]
+ $[id=DK_Legs027_01]
+ $[id=DK_Torso027]
+ $[id=DK_Torso027_01]
+ $[id=HO_001]
+ $[id=HO_002]
+ $[id=HO_003]
+ $[id=HO_004]
+ $[id=HO_005]
+ $[id=HO_006]
+ $[id=HO_007]
+ $[id=HO_008]
+ $[id=HO_009]
+ $[id=HO_010]
+ $[id=HO_011]
+ $[id=HO_BDG_01]
+ $[id=HO_BDG_02]
+ $[id=HO_BDG_03]
+ $[id=HO_BDG_04]
+ $[id=HO_BDG_05]
+ $[id=HO_BDG_06]
+ $[id=HO_BDG_07]
+ $[id=HO_BDG_08]
+ $[id=HO_BDG_09]
+ $[id=HO_BDG_10]
+ $[id=HO_BDG_11]
+ $[id=HO_BDG_12]
+ $[id=HO_BDG_13]
+ $[id=HO_BDG_14]
+ $[id=HO_BDG_15]
+ $[id=HO_BDG_16]
+ $[id=HO_BNR_01]
+ $[id=HO_BNR_02]
+ $[id=HO_BNR_03]
+ $[id=HO_BNR_04]
+ $[id=HO_BNR_05]
+ $[id=HO_BNR_06]
+ $[id=HO_BNR_07]
+ $[id=HO_BNR_08]
+ $[id=HO_BNR_09]
+ $[id=HO_BNR_10]
+ $[id=HO_BNR_11]
+ $[id=HO_BNR_12]
+ $[id=JP_Head08_02]
+ $[id=JP_Legs08_02]
+ $[id=JP_Torso08_02]
+ $[id=K21_Body021]
+ $[id=K21_Body021_01]
+ $[id=K21_Head021]
+ $[id=K21_Head021_01]
+ $[id=K21_W021]
+ $[id=K21_W021_01]
+ $[id=K24_Body008]
+ $[id=K24_Head008]
+ $[id=K24_W008]
+ $[id=K29_Body008]
+ $[id=K29_Head008]
+ $[id=K29_W008]
+ $[id=K30_Body017]
+ $[id=K30_Body017_01]
+ $[id=K30_Head017]
+ $[id=K30_Head017_01]
+ $[id=K30_W017]
+ $[id=K30_W017_01]
+ $[id=K31_Body016]
+ $[id=K31_Head016]
+ $[id=K31_W016]
+ $[id=K35_Body011]
+ $[id=K35_Head011]
+ $[id=K35_W011]
+ $[id=KK_Body025_01]
+ $[id=KK_Mask025_01]
+ $[id=KK_W025_01]
+ $[id=KS_Head016_01]
+ $[id=KS_Legs016_01]
+ $[id=KS_Torso016_01]
+ $[id=MK_Body018]
+ $[id=MK_Body018_01]
+ $[id=MK_Mask018]
+ $[id=MK_Mask018_01]
+ $[id=MK_W018]
+ $[id=MK_W018_01]
+ $[id=MS_Head025]
+ $[id=MS_Head025_01]
+ $[id=MS_Legs025]
+ $[id=MS_Legs025_01]
+ $[id=MS_Torso025]
+ $[id=MS_Torso025_01]
+ $[id=NK_Head022_01]
+ $[id=NK_Legs016_01]
+ $[id=NK_Torso014_01]
+ $[id=S25_Head010_02]
+ $[id=S25_Legs015_01]
+ $[id=S25_Torso020_01]
+ $[id=S26_Head011]
+ $[id=S26_Legs011]
+ $[id=S26_Torso011]
+ $[id=S27_Head010]
+ $[id=S27_Legs010]
+ $[id=S27_Torso010]
+ $[id=S32_Head009]
+ $[id=S32_Legs009]
+ $[id=S32_Torso009]
+ $[id=S33_Head008]
+ $[id=S33_Legs008]
+ $[id=S33_Torso008]
+ $[id=S35_Head019]
+ $[id=S35_Head019_01]
+ $[id=S35_Legs019]
+ $[id=S35_Legs019_01]
+ $[id=S35_Torso019]
+ $[id=S35_Torso019_01]
+ $[id=S36_Head020]
+ $[id=S36_Head020_01]
+ $[id=S36_Legs020]
+ $[id=S36_Legs020_01]
+ $[id=S36_Torso020]
+ $[id=S36_Torso020_01]
+ $[id=S41_Head014]
+ $[id=S41_Legs014]
+ $[id=S41_Torso014]
+ $[id=TR_Body022_01]
+ $[id=TR_Mask009_01]
+ $[id=TR_W022_01]
+ $[id=WI_Body015_01]
+ $[id=WI_Hair015_01]
+ $[id=WI_W015_01]
+ $[id=AV_outfit_01]
+ $[id=AV_outfit_01_P01]
+ $[id=BE_outfit_01]
+ $[id=BE_outfit_01_P01]
+ $[id=BE_outfit_027]
+ $[id=BE_outfit_027_01]
+ $[id=BO_outfit_01]
+ $[id=BO_outfit_01_P01]
+ $[id=C_outfit_01]
+ $[id=C_outfit_01_P01]
+ $[id=CA_outfit_01]
+ $[id=CA_outfit_01_P01]
+ $[id=D_outfit_01]
+ $[id=D_outfit_01_P01]
+ $[id=DK_outfit_01]
+ $[id=DK_outfit_01_P01]
+ $[id=DK_outfit_027]
+ $[id=DK_outfit_027_01]
+ $[id=DO_outfit_01]
+ $[id=DO_outfit_01_P01]
+ $[id=FK_outfit_01]
+ $[id=FK_outfit_01_P01]
+ $[id=FM_outfit_01]
+ $[id=FM_outfit_01_P01]
+ $[id=FS_outfit_01]
+ $[id=FS_outfit_01_P01]
+ $[id=GK_outfit_01]
+ $[id=GK_outfit_01_P01]
+ $[id=GS_outfit_01]
+ $[id=GS_outfit_01_P01]
+ $[id=HA_outfit_01]
+ $[id=HA_outfit_01_P01]
+ $[id=Hillbilly_outfit_01]
+ $[id=Hillbilly_outfit_01_P01]
+ $[id=HK_outfit_01]
+ $[id=HK_outfit_01_P01]
+ $[id=HS_outfit_01]
+ $[id=HS_outfit_01_P01]
+ $[id=J_outfit_01]
+ $[id=J_outfit_01_P01]
+ $[id=JP_outfit_08_02]
+ $[id=K20_outfit_01]
+ $[id=K20_outfit_01_P01]
+ $[id=K21_outfit_01]
+ $[id=K21_outfit_01_P01]
+ $[id=K21_outfit_021]
+ $[id=K21_outfit_021_01]
+ $[id=K22_outfit_01]
+ $[id=K22_outfit_01_P01]
+ $[id=K23_outfit_01]
+ $[id=K23_outfit_01_P01]
+ $[id=K24_outfit_008]
+ $[id=K24_outfit_01]
+ $[id=K24_outfit_01_P01]
+ $[id=K25_outfit_01]
… 2996 more change(s) — see the commit diff for everything
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[5].collectionId: "ResidentEvilMega"
+ $.collections[5].collectionId: "HookedOnYou"
- $.collections[5].collectionTitle.de: "Resident Evil"
+ $.collections[5].collectionTitle.de: "Hooked on You"
- $.collections[5].collectionTitle.en: "Resident Evil"
+ $.collections[5].collectionTitle.en: "Hooked on You"
- $.collections[5].collectionTitle.es: "Resident Evil"
+ $.collections[5].collectionTitle.es: "Hooked on You"
- $.collections[5].collectionTitle["es-MX"]: "Resident Evil"
+ $.collections[5].collectionTitle["es-MX"]: "Hooked on You"
- $.collections[5].collectionTitle.fr: "Resident Evil"
+ $.collections[5].collectionTitle.fr: "Hooked on You"
- $.collections[5].collectionTitle.it: "Resident Evil"
+ $.collections[5].collectionTitle.it: "Hooked on You"
- $.collections[5].collectionTitle.ja: "バイオハザード"
+ $.collections[5].collectionTitle.ja: "Hooked on You"
- $.collections[5].collectionTitle.ko: "Biohazard"
+ $.collections[5].collectionTitle.ko: "Hooked on You"
- $.collections[5].collectionTitle.pl: "Resident Evil"
+ $.collections[5].collectionTitle.pl: "Hooked On You"
- $.collections[5].collectionTitle["pt-BR"]: "Resident Evil"
+ $.collections[5].collectionTitle["pt-BR"]: "Hooked on You"
- $.collections[5].collectionTitle.ru: "Resident Evil"
+ $.collections[5].collectionTitle.ru: "На твоем крючке"
- $.collections[5].collectionTitle.th: "Resident Evil"
+ $.collections[5].collectionTitle.th: "Hooked on You"
- $.collections[5].collectionTitle.tr: "Resident Evil"
+ $.collections[5].collectionTitle.tr: "Sana Tutuldum"
- $.collections[5].collectionTitle["zh-Hans"]: "生化危机"
+ $.collections[5].collectionTitle["zh-Hans"]: "心醉魂迷"
- $.collections[5].collectionTitle["zh-Hant"]: "《惡靈古堡》"
+ $.collections[5].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
- $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_RECollection.T_UI_CollectionBanner_RECollection"
+ $.collections[5].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
- $.collections[5].items[]: "S26_Outfit_006"
- $.collections[5].items[]: "S27_Outfit_006"
- $.collections[5].items[]: "S26_Outfit_02"
- $.collections[5].items[]: "S27_Outfit_02"
- $.collections[5].items[]: "K24_outfit_007"
- $.collections[5].items[]: "S32_outfit_006"
- $.collections[5].items[]: "S33_outfit_006"
- $.collections[5].items[]: "K29_outfit_006"
- $.collections[5].items[]: "K29_outfit_007"
- $.collections[5].items[]: "S26_Outfit_008"
- $.collections[5].items[]: "S26_Outfit_009"
- $.collections[5].items[]: "S27_Outfit_009"
- $.collections[5].items[]: "S27_Outfit_008"
- $.collections[5].items[]: "KK_outfit_023"
- $.collections[5].items[]: "S23_outfit_019"
- $.collections[5].items[]: "FM_outfit_021"
- $.collections[5].items[]: "K21_outfit_012"
- $.collections[5].items[]: "S32_outfit_008"
- $.collections[5].items[]: "S26_Outfit_010"
+ $.collections[5].items[]: "CM_outfit_021"
+ $.collections[5].items[]: "DF_outfit_023"
+ $.collections[5].items[]: "BE_outfit_017"
+ $.collections[5].items[]: "K23_outfit_014"
+ $.collections[5].items[]: "HK_outfit_017"
- $.collections[5].sortOrder: "-18"
+ $.collections[5].sortOrder: "-19"
- $.collections[5].updatedDate: "2024-01-31T19:34:50Z"
+ $.collections[5].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[6].collectionId: "HookedOnYou"
+ $.collections[6].collectionId: "GrimMatsuri"
- $.collections[6].collectionTitle.de: "Hooked on You"
+ $.collections[6].collectionTitle.de: "Düsteres Matsuri-Fest"
- $.collections[6].collectionTitle.en: "Hooked on You"
+ $.collections[6].collectionTitle.en: "Grim Matsuri"
- $.collections[6].collectionTitle.es: "Hooked on You"
+ $.collections[6].collectionTitle.es: "Matsuri tenebrosa"
- $.collections[6].collectionTitle["es-MX"]: "Hooked on You"
+ $.collections[6].collectionTitle["es-MX"]: "Matsuri tenebrosa"
- $.collections[6].collectionTitle.fr: "Hooked on You"
+ $.collections[6].collectionTitle.fr: "Matsuri sinistre"
- $.collections[6].collectionTitle.it: "Hooked on You"
+ $.collections[6].collectionTitle.it: "Matsuri funebre"
- $.collections[6].collectionTitle.ja: "Hooked on You"
+ $.collections[6].collectionTitle.ja: "おぞましい祭り"
- $.collections[6].collectionTitle.ko: "Hooked on You"
+ $.collections[6].collectionTitle.ko: "음산한 축제"
- $.collections[6].collectionTitle.pl: "Hooked On You"
+ $.collections[6].collectionTitle.pl: "Ponury Festiwal"
- $.collections[6].collectionTitle["pt-BR"]: "Hooked on You"
+ $.collections[6].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
- $.collections[6].collectionTitle.ru: "На твоем крючке"
+ $.collections[6].collectionTitle.ru: "Мрачный Мацури"
- $.collections[6].collectionTitle.th: "Hooked on You"
+ $.collections[6].collectionTitle.th: "เทศกาลสยอง"
- $.collections[6].collectionTitle.tr: "Sana Tutuldum"
+ $.collections[6].collectionTitle.tr: "Kasvetli Festival"
- $.collections[6].collectionTitle["zh-Hans"]: "心醉魂迷"
+ $.collections[6].collectionTitle["zh-Hans"]: "冷血祭"
- $.collections[6].collectionTitle["zh-Hant"]: "《鉤魂迷戀》"
+ $.collections[6].collectionTitle["zh-Hant"]: "冷血祭"
- $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_HookedOnYou.T_UI_CollectionBanner_HookedOnYou"
+ $.collections[6].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
- $.collections[6].items[]: "CM_outfit_021"
- $.collections[6].items[]: "DF_outfit_023"
- $.collections[6].items[]: "BE_outfit_017"
- $.collections[6].items[]: "K23_outfit_014"
- $.collections[6].items[]: "HK_outfit_017"
+ $.collections[6].items[]: "Nea_outfit_010"
+ $.collections[6].items[]: "GS_outfit_011"
+ $.collections[6].items[]: "SwedenSurvivor_outfit_009"
+ $.collections[6].items[]: "Meg_outfit_023"
+ $.collections[6].items[]: "Jake_outfit_017"
+ $.collections[6].items[]: "Bear_outfit_003"
+ $.collections[6].items[]: "Claudette_outfit_018"
+ $.collections[6].items[]: "TN_outfit_010"
- $.collections[6].sortOrder: "-19"
+ $.collections[6].sortOrder: "-2"
- $.collections[6].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[6].updatedDate: "2024-03-06T20:44:22Z"
- $.collections[7].collectionId: "GrimMatsuri"
+ $.collections[7].collectionId: "AliceInWonderland"
- $.collections[7].collectionTitle.de: "Düsteres Matsuri-Fest"
+ $.collections[7].collectionTitle.de: "Alice im Wunderland"
- $.collections[7].collectionTitle.en: "Grim Matsuri"
+ $.collections[7].collectionTitle.en: "Alice in Wonderland"
- $.collections[7].collectionTitle.es: "Matsuri tenebrosa"
+ $.collections[7].collectionTitle.es: "Alicia en el País de las Maravillas"
- $.collections[7].collectionTitle["es-MX"]: "Matsuri tenebrosa"
+ $.collections[7].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
- $.collections[7].collectionTitle.fr: "Matsuri sinistre"
+ $.collections[7].collectionTitle.fr: "Alice au pays des merveilles"
- $.collections[7].collectionTitle.it: "Matsuri funebre"
+ $.collections[7].collectionTitle.it: "Alice nel paese delle meraviglie"
- $.collections[7].collectionTitle.ja: "おぞましい祭り"
+ $.collections[7].collectionTitle.ja: "不思議の国のアリス"
- $.collections[7].collectionTitle.ko: "음산한 축제"
+ $.collections[7].collectionTitle.ko: "이상한 나라의 앨리스"
- $.collections[7].collectionTitle.pl: "Ponury Festiwal"
+ $.collections[7].collectionTitle.pl: "Alicja w Krainie Czarów"
- $.collections[7].collectionTitle["pt-BR"]: "Festival Japonês Sombrio"
+ $.collections[7].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
- $.collections[7].collectionTitle.ru: "Мрачный Мацури"
+ $.collections[7].collectionTitle.ru: "Алиса в Стране чудес"
- $.collections[7].collectionTitle.th: "เทศกาลสยอง"
+ $.collections[7].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
- $.collections[7].collectionTitle.tr: "Kasvetli Festival"
+ $.collections[7].collectionTitle.tr: "Alice Harikalar Diyarında"
- $.collections[7].collectionTitle["zh-Hans"]: "冷血祭"
+ $.collections[7].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
- $.collections[7].collectionTitle["zh-Hant"]: "冷血祭"
+ $.collections[7].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
- $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GrimMatsuri.T_UI_CollectionBanner_GrimMatsuri"
+ $.collections[7].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
- $.collections[7].items[]: "Nea_outfit_010"
- $.collections[7].items[]: "GS_outfit_011"
- $.collections[7].items[]: "SwedenSurvivor_outfit_009"
- $.collections[7].items[]: "Meg_outfit_023"
- $.collections[7].items[]: "Jake_outfit_017"
- $.collections[7].items[]: "Bear_outfit_003"
- $.collections[7].items[]: "Claudette_outfit_018"
- $.collections[7].items[]: "TN_outfit_010"
+ $.collections[7].items[]: "AV_outfit_018"
+ $.collections[7].items[]: "GS_outfit_023"
+ $.collections[7].items[]: "NK_outfit_023"
+ $.collections[7].items[]: "BE_outfit_020"
+ $.collections[7].items[]: "K26_outfit_011"
- $.collections[7].sortOrder: "-2"
+ $.collections[7].sortOrder: "-20"
- $.collections[7].updatedDate: "2024-03-06T20:44:22Z"
+ $.collections[7].updatedDate: "0001-01-01T00:00:00Z"
- $.collections[8].collectionId: "AliceInWonderland"
+ $.collections[8].collectionId: "Wasteland"
- $.collections[8].collectionTitle.de: "Alice im Wunderland"
+ $.collections[8].collectionTitle.de: "Ödland"
- $.collections[8].collectionTitle.en: "Alice in Wonderland"
+ $.collections[8].collectionTitle.en: "Wasteland"
- $.collections[8].collectionTitle.es: "Alicia en el País de las Maravillas"
+ $.collections[8].collectionTitle.es: "Páramo"
- $.collections[8].collectionTitle["es-MX"]: "Alicia en el País de las Maravillas"
+ $.collections[8].collectionTitle["es-MX"]: "Páramo"
- $.collections[8].collectionTitle.fr: "Alice au pays des merveilles"
+ $.collections[8].collectionTitle.fr: "Terre dévastée"
- $.collections[8].collectionTitle.it: "Alice nel paese delle meraviglie"
+ $.collections[8].collectionTitle.it: "Landa desolata"
- $.collections[8].collectionTitle.ja: "不思議の国のアリス"
+ $.collections[8].collectionTitle.ja: "荒れ地"
- $.collections[8].collectionTitle.ko: "이상한 나라의 앨리스"
+ $.collections[8].collectionTitle.ko: "황무지"
- $.collections[8].collectionTitle.pl: "Alicja w Krainie Czarów"
+ $.collections[8].collectionTitle.pl: "Pustkowie"
- $.collections[8].collectionTitle["pt-BR"]: "Alice no País das Maravilhas"
+ $.collections[8].collectionTitle["pt-BR"]: "Desolação"
- $.collections[8].collectionTitle.ru: "Алиса в Стране чудес"
+ $.collections[8].collectionTitle.ru: "Пустошь"
- $.collections[8].collectionTitle.th: "อลิซในแดนมหัศจรรย์"
+ $.collections[8].collectionTitle.th: "แดนรกร้าง"
- $.collections[8].collectionTitle.tr: "Alice Harikalar Diyarında"
+ $.collections[8].collectionTitle.tr: "Çorak"
- $.collections[8].collectionTitle["zh-Hans"]: "爱丽丝梦游仙境收藏"
+ $.collections[8].collectionTitle["zh-Hans"]: "荒芜之地"
- $.collections[8].collectionTitle["zh-Hant"]: "《愛麗絲夢遊仙境》"
+ $.collections[8].collectionTitle["zh-Hant"]: "荒地"
- $.collections[8].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_AliceInWonderland.T_UI_CollectionBanner_AliceInWonderland"
+ $.collections[8].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Wasteland.T_UI_CollectionBanner_Wasteland"
- $.collections[8].items[]: "AV_outfit_018"
- $.collections[8].items[]: "GS_outfit_023"
… 4020 more change(s) — see the commit diff for everything
```

### [`contentMetadata.json`](contentMetadata.json)

[Full line-by-line diff](diffs/contentMetadata.json.diff)

```diff
- $.deploymentDate: "2025-01-21 20:30:33Z"
+ $.deploymentDate: "2025-02-11 16:05:32Z"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
+ $.schedule[0].MapsWeight.Asy_Asylum_Calamari: "0"
+ $.schedule[0].MapsWeight.Asy_Chapel_Calamari: "0"
+ $.schedule[0].MapsWeight.Brl_MaHouse_Calamari: "0"
+ $.schedule[0].MapsWeight.Frm_Farmhouse_Calamari: "0"
+ $.schedule[0].MapsWeight.Frm_Slaughterhouse_Calamari: "0"
+ $.schedule[0].MapsWeight.Hti_Manor_Calamari: "0"
+ $.schedule[0].MapsWeight.Ind_Mine_Calamari: "0"
+ $.schedule[0].MapsWeight.Jnk_Office_Calamari: "0"
+ $.schedule[0].MapsWeight.Ukr_Saloon_Calamari: "0"
- $.schedule[1].Description: "Firefly Map List"
+ $.schedule[1].Description: "Calamari Map List"
- $.schedule[1].GameModes[]: "Firefly"
+ $.schedule[1].GameModes[]: "Calamari"
- $.schedule[1].MapsWeight.Apl_Level_01: "1200"
- $.schedule[1].MapsWeight.Hos_Treatment: "1200"
- $.schedule[1].MapsWeight.Hti_Manor: "600"
- $.schedule[1].MapsWeight.Hti_Manor02: "600"
- $.schedule[1].MapsWeight.Kny_Cottage: "400"
- $.schedule[1].MapsWeight.Kny_Cottage02: "400"
- $.schedule[1].MapsWeight.Kny_Cottage03: "400"
- $.schedule[1].MapsWeight.Qtm_Level_01: "1200"
- $.schedule[1].MapsWeight.Ukr_Saloon: "1200"
+ $.schedule[1].MapsWeight.Asy_Asylum_Calamari: "300"
+ $.schedule[1].MapsWeight.Asy_Chapel_Calamari: "500"
+ $.schedule[1].MapsWeight.Brl_MaHouse_Calamari: "500"
+ $.schedule[1].MapsWeight.Ecl_Level03_Calamari: "2500"
+ $.schedule[1].MapsWeight.Frm_Farmhouse_Calamari: "100"
+ $.schedule[1].MapsWeight.Frm_Slaughterhouse_Calamari: "300"
+ $.schedule[1].MapsWeight.Hti_Manor_Calamari: "500"
+ $.schedule[1].MapsWeight.Hti_Temple_Calamari: "300"
+ $.schedule[1].MapsWeight.Ind_CoalTower_Calamari: "500"
+ $.schedule[1].MapsWeight.Ind_Mine_Calamari: "300"
+ $.schedule[1].MapsWeight.Jnk_GasStation_Calamari: "300"
+ $.schedule[1].MapsWeight.Jnk_Office_Calamari: "300"
+ $.schedule[1].MapsWeight.Jnk_Scrapyard_Calamari: "100"
+ $.schedule[1].MapsWeight.Kny_Chalet_Calamari: "500"
+ $.schedule[1].MapsWeight.Ukr_Saloon_Calamari: "500"
- $.schedule[1].Priority: "4"
+ $.schedule[1].Priority: "3"
- $.schedule[2].EndDate: "2024-12-12T15:59:00"
- $.schedule[2].StartDate: "2024-11-25T15:00:00"
+ $.schedule[2].GameModes
- $.schedule[2].Description: "Killswitch"
+ $.schedule[2].Description: "Firefly Map List"
- $.schedule[2].MapsWeight.Glo_Level_01: "0"
+ $.schedule[2].MapsWeight.Apl_Level_01: "1200"
+ $.schedule[2].MapsWeight.Hos_Treatment: "1200"
+ $.schedule[2].MapsWeight.Hti_Manor: "600"
+ $.schedule[2].MapsWeight.Hti_Manor02: "600"
+ $.schedule[2].MapsWeight.Kny_Cottage: "400"
+ $.schedule[2].MapsWeight.Kny_Cottage02: "400"
+ $.schedule[2].MapsWeight.Kny_Cottage03: "400"
+ $.schedule[2].MapsWeight.Qtm_Level_01: "1200"
+ $.schedule[2].MapsWeight.Ukr_Saloon: "1200"
- $.schedule[2].Priority: "5"
+ $.schedule[2].Priority: "4"
- $.schedule[3].Description: "Map_Boost"
+ $.schedule[3].Description: "Killswitch"
- $.schedule[3].EndDate: "2024-12-15T15:59:00"
+ $.schedule[3].EndDate: "2024-12-12T15:59:00"
- $.schedule[3].MapsWeight.Glo_Level_01: "7000"
+ $.schedule[3].MapsWeight.Glo_Level_01: "0"
- $.schedule[3].StartDate: "2024-12-12T16:00:00"
+ $.schedule[3].StartDate: "2024-11-25T15:00:00"
- $.schedule[4].EndDate: "2024-12-18T15:59:00"
+ $.schedule[4].EndDate: "2024-12-15T15:59:00"
- $.schedule[4].MapsWeight.Glo_Level_01: "4500"
+ $.schedule[4].MapsWeight.Glo_Level_01: "7000"
- $.schedule[4].StartDate: "2024-12-15T16:00:00"
+ $.schedule[4].StartDate: "2024-12-12T16:00:00"
+ $.schedule[5]
```

### [`crossPromoCampaigns.json`](crossPromoCampaigns.json)

[Full line-by-line diff](diffs/crossPromoCampaigns.json.diff)

```diff
- $.Campaigns.DevVideoTest
- $.Campaigns["DBD-Store-Promo"].activeToDate: "2024-12-12T16:00:00"
+ $.Campaigns["DBD-Store-Promo"].activeToDate: "2024-12-10T16:00:00"
- $.Campaigns["DBD-Store-Promo_2"].activeFromDate: "2024-12-12T16:00:00"
+ $.Campaigns["DBD-Store-Promo_2"].activeFromDate: "2024-12-10T16:00:00"
- $.Campaigns["DBD-Store-Promo_2"].activeToDate: "2025-12-12T16:00:00"
+ $.Campaigns["DBD-Store-Promo_2"].activeToDate: "2025-12-10T16:00:00"
- $.Campaigns["DBD-Store-Promo_2"].daysBetweenViews: 90
+ $.Campaigns["DBD-Store-Promo_2"].daysBetweenViews: 7
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "1f493c84eb5a5078a749635b21c31af4ea4bbb0d"
+ $.entries[0].contentVersion: "7e9bb9cbc6129d7b93eb1a2becffbb05525639be"
- $.entries[0].downloadStrategy: "preferPackaged"
+ $.entries[0].downloadStrategy: "preferRemote"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_BoneChill2023.T_UI_SpecialPack_BoneChill2023"
+ $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Wasteland.T_UI_SpecialPack_Wasteland"
- $.entries[0].uri: "images/T_UI_SpecialPack_BoneChill2023.png"
+ $.entries[0].uri: "images/T_UI_SpecialPack_Wasteland.png"
- $.entries[1].contentVersion: "6f2c8cb6251d423059ef66da718e6f677847c357"
+ $.entries[1].contentVersion: "a376acfc87e5939f7f625755a9f1a39c886334bd"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_WinterTales.T_UI_SpecialPack_WinterTales"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ResidentEvil_V2.T_UI_CollectionBanner_ResidentEvil_V2"
- $.entries[1].uri: "images/T_UI_SpecialPack_WinterTales.png"
+ $.entries[1].uri: "images/T_UI_CollectionBanner_ResidentEvil_V2.png"
- $.entries[2].contentVersion: "8a9ee2baaa11cb2ddce356559e0b6f24a534a021"
+ $.entries[2].contentVersion: "53964bcb15e57ecf8ea8c3fb65b6991aa31f8b12"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_DungeonsAndDragons2.T_UI_CollectionBanner_DungeonsAndDragons2"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_ResidentEvil_V2.T_UI_SpecialPack_ResidentEvil_V2"
- $.entries[2].uri: "images/T_UI_CollectionBanner_DungeonsAndDragons2.png"
+ $.entries[2].uri: "images/T_UI_SpecialPack_ResidentEvil_V2.png"
- $.entries[3].contentVersion: "b9fe3b9bd713b76683dc6ded2000fc9d89935d9d"
+ $.entries[3].contentVersion: "046cd26cefdc52db4b6e33c63284a66b5f3f45df"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/News/T_UI_SpecialPack_DungeonsAndDragons.T_UI_SpecialPack_DungeonsAndDragons"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ArtistsFromTheFog_V2.T_UI_CollectionBanner_ArtistsFromTheFog_V2"
- $.entries[3].uri: "images/T_UI_SpecialPack_DungeonsAndDragons.png"
+ $.entries[3].uri: "images/T_UI_CollectionBanner_ArtistsFromTheFog_V2.png"
- $.entries[4].contentVersion: "c7ed55746881a2cef17d041322d576b95377cbe2"
+ $.entries[4].contentVersion: "67c93987330b11212afe4082b156c42ed073f6fe"
- $.entries[4].downloadStrategy: "preferPackaged"
+ $.entries[4].downloadStrategy: "preferRemote"
- $.entries[4].enableChecksum: false
+ $.entries[4].enableChecksum: true
- $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/News/T_UI_SpecialPack_JunjiIto.T_UI_SpecialPack_JunjiIto"
+ $.entries[4].packagedPath: ""
- $.entries[4].schema: "s3verbin://"
+ $.entries[4].schema: "s3ver://"
- $.entries[4].uri: "images/T_UI_SpecialPack_JunjiIto.png"
+ $.entries[4].uri: "catalog.json"
- $.entries[5].contentVersion: "042588b865ed241756a4e922fbfe977c8bfc79ea"
+ $.entries[5].contentVersion: "788b6e45e5f6f0f29d5237db487c0666397b6528"
- $.entries[5].uri: "catalog.json"
+ $.entries[5].uri: "bonusPointEventsContent.json"
- $.entries[6].contentVersion: "2f9e91f2c47952d26e2ba2f995b3280eb435d7ab"
+ $.entries[6].contentVersion: "6655edc636a0770868614915ae463e2342631a2a"
- $.entries[6].uri: "bonusPointEventsContent.json"
+ $.entries[6].uri: "freetoplay/NA/event.json"
- $.entries[7].contentVersion: "db52ce02f25fecc6117adcac8bad99f00f738154"
+ $.entries[7].contentVersion: "6655edc636a0770868614915ae463e2342631a2a"
- $.entries[7].uri: "freetoplay/NA/event.json"
+ $.entries[7].uri: "freetoplay/EU/event.json"
- $.entries[8].contentVersion: "db52ce02f25fecc6117adcac8bad99f00f738154"
+ $.entries[8].contentVersion: "543cd72e4e78a2b2222587d307e0db8cb593e032"
- $.entries[8].uri: "freetoplay/EU/event.json"
+ $.entries[8].uri: "archiveQuests/Anniversary2022.json"
- $.entries[9].contentVersion: "6831fa2ef5990473a8f720af1b27d8699535ad04"
+ $.entries[9].contentVersion: "8273e156250160bdcd648b2c30a93a8c51c9f22f"
- $.entries[9].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[9].uri: "archiveQuests/Anniversary2023.json"
- $.entries[10].contentVersion: "bab3b5054641170484a25d3e8063d2f3d9719b52"
+ $.entries[10].contentVersion: "bc3a487e7fd70ceb6c50b76d3ce3cec9260988dd"
- $.entries[10].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[10].uri: "archiveQuests/Anniversary2024.json"
- $.entries[11].contentVersion: "8959abce811033d8eef4d3de06c1765a5ef10a61"
+ $.entries[11].contentVersion: "a408fa0d35cd973148d69b66da450e6061df4e72"
- $.entries[11].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[11].uri: "archiveQuests/CalamariV1.json"
- $.entries[12].contentVersion: "1036d6bd20d59802d91eff0b2a3c09c620aab2e6"
+ $.entries[12].contentVersion: "71ad6e3e2c1d333a18f5e73e68b8ee4658dbd556"
- $.entries[12].uri: "archiveQuests/CalamariV1.json"
+ $.entries[12].uri: "archiveQuests/CalamariV2.json"
- $.entries[13].contentVersion: "fa8bc8bf93dd4db6918ee9651c6ee0b30b34668d"
+ $.entries[13].contentVersion: "963cf47cc485623f3a1a5965bf8b3299d610c3e2"
- $.entries[13].uri: "archiveQuests/CalamariV2.json"
+ $.entries[13].uri: "archiveQuests/CalamariV3.json"
- $.entries[14].contentVersion: "1a1b775c469a006bdef50fb8d905c4cdd4a538dc"
+ $.entries[14].contentVersion: "407b1d48b0b6d1ffb96f5a1dae5585e019b419cc"
- $.entries[15].contentVersion: "f76e575822ed0dde0080f548740162365524e9a2"
+ $.entries[15].contentVersion: "2262e42dcf42eb7387966da10979b40715e1cdf9"
- $.entries[16].contentVersion: "3c61ee1a8ba4b50db57bcd245fdf197fbd0cc5d7"
+ $.entries[16].contentVersion: "6b12ac012f05769e892c082f6518ebd32f610eab"
- $.entries[17].contentVersion: "0f142cb15e9474b33bbdef9bbe3791c09fe86bf2"
+ $.entries[17].contentVersion: "80a29841bca62c52e00331de3bc2bb4e20509060"
- $.entries[18].contentVersion: "bed1775fd90ef483475120f1009578a48b7ead69"
+ $.entries[18].contentVersion: "7c01b56b768aa030f6ecc2327dd34eb38a2a44a6"
- $.entries[19].contentVersion: "77e0780edaadecc3d194bb0cf373f0fedd31d4d6"
+ $.entries[19].contentVersion: "57e4ff1396924d2086371eadec19248faf05ac83"
- $.entries[20].contentVersion: "8e9f60956875d8c4860ac5035469dd135eea6c83"
+ $.entries[20].contentVersion: "5b218ca07d7df70ac32c6e16621c520a04587efe"
- $.entries[21].contentVersion: "19da0c22e06e16bc29aa25890b04364733337f01"
+ $.entries[21].contentVersion: "61d0e728f66fa0af60b6faba8a0c27dd7c5e65fb"
- $.entries[22].contentVersion: "17f08f51b0410d36cd069190b71ec25b92b921fe"
+ $.entries[22].contentVersion: "c225ca9dbc1a433a739e2f2ec350b6260e5b1a9f"
- $.entries[23].contentVersion: "2d8279de5ef2fc92bc01faba12e9c4c26c67c37d"
+ $.entries[23].contentVersion: "12e1fa2470d5a0812664c0c922fa61a667b09c6f"
- $.entries[24].contentVersion: "66619d76672da868e66e7b4f6ad61732c3747fa0"
+ $.entries[24].contentVersion: "4f81d96a4a7e8f5c6091bcd265c63303e5f64855"
- $.entries[25].contentVersion: "5d2b3cbd1134919a6996e3d568919104e8297ab1"
+ $.entries[25].contentVersion: "cd3746537274d6874f044b382efaa5fe8333c928"
- $.entries[26].contentVersion: "80315efc83d208d1d1ea48b711399d3c34215332"
+ $.entries[26].contentVersion: "9847d4aad35952d72c0d3932dfb6283829fc8cac"
- $.entries[27].contentVersion: "e5d8b9101fb28eddb7d49e4de67cdd79a86bb7be"
+ $.entries[27].contentVersion: "5d8c114b55ae6821c795376ea6cb488f7f21449d"
- $.entries[28].contentVersion: "faa06f1ba4861c92abd5dea35a86af55315822d3"
+ $.entries[28].contentVersion: "c657b5e7066a6175ee306b511e9360509594b777"
- $.entries[29].contentVersion: "31e3480e7f4aafc44e024068f6fca75c9e04f003"
+ $.entries[29].contentVersion: "6f1942f0d4adcf5e663b798ed66148af57df46f4"
- $.entries[30].contentVersion: "fef700028c935b5e478078dabaaed168079cf532"
+ $.entries[30].contentVersion: "bbfef48e50487debc04d01d0e3f29e7494e38b5c"
- $.entries[31].contentVersion: "3d13428cfe30ba250e21c92812f8eed4b9cbee47"
+ $.entries[31].contentVersion: "3f501474d90b4734b0e63230770844af65a19ae6"
- $.entries[32].contentVersion: "596b6eb38f8d527ac374424943380b67159cfba1"
+ $.entries[32].contentVersion: "f387646c722c10de1889a50eeec1f67cdc783ce4"
- $.entries[33].contentVersion: "4a3fe448ee2f326bdd90aee48829f5d9fa2796c9"
+ $.entries[33].contentVersion: "64077f50db4bdfb2cca60ff5bcf9f7cfac62ddf7"
- $.entries[34].contentVersion: "ad5b7a3b9783d16f724626eb7af5a75985cffdd7"
+ $.entries[34].contentVersion: "4e4a0b0407317fbc2d8bb6cf0796b00ab996c2c1"
- $.entries[35].contentVersion: "9febd2f61b4d903e5359cb4d758365e0d36120da"
+ $.entries[35].contentVersion: "d7221731d2d834cb3551c160e766ad4cf5f60ee0"
- $.entries[36].contentVersion: "fa027b027f64488aa1d1541bf82bd7fd8074772d"
+ $.entries[36].contentVersion: "33a105c6dbbba31758c19b359c65e68849976b87"
- $.entries[37].contentVersion: "c53237d9525db405a7ad215ce41160795a350543"
+ $.entries[37].contentVersion: "c14ac1c93887519dab614aad9edac4e1cde894f3"
- $.entries[38].contentVersion: "3bdcfb23be58e502c4638f579664e9aa3e57cc59"
+ $.entries[38].contentVersion: "d0c22309377e813e8d7ff1af7104e3a97a672e5d"
- $.entries[39].contentVersion: "52f3810875efe88dd8675c55061f7707a8bcafff"
+ $.entries[39].contentVersion: "2590e03b6eb88be1d515f90fcfc5774abb6ed0b9"
- $.entries[40].contentVersion: "47d3d4a02d0ac55cf31168ac3b48d186255f0379"
+ $.entries[40].contentVersion: "51c64855b61f141da69b5470f96a9a3462da314c"
- $.entries[41].contentVersion: "f381ddb1f5eddb221b37bb49f04c545c8b429a4c"
+ $.entries[41].contentVersion: "23651fb40b82a41c12d563d73bad259dcce5f3ba"
- $.entries[42].contentVersion: "19c56d3882b448498111af45c8b04e5f761302d4"
+ $.entries[42].contentVersion: "74a14f743cac5948af61efcc9ea98d1c3fb5d57b"
- $.entries[43].contentVersion: "467179e50722fb7687b90cdf3e70867e307c207e"
+ $.entries[43].contentVersion: "0cbaa769bce888fbc17a7dc0edafeea5f74564c8"
- $.entries[44].contentVersion: "346a5b2fab7eec38c4eb02924964dd6fe9d299db"
+ $.entries[44].contentVersion: "b52ee95864ffae5c721a6101919988a0ef321039"
- $.entries[45].contentVersion: "cb9410d57dbe7ae2d75020b3ea2e29a27125b353"
+ $.entries[45].contentVersion: "a6997e7cdd2185cf37ab2f9867bbf2374bc27f0b"
- $.entries[45].uri: "archiveQuests/Winter2022.json"
+ $.entries[45].uri: "archiveQuests/Tome22.json"
- $.entries[46].contentVersion: "1c6910d9e216db1ed67ef5853dae7012dfa2c791"
+ $.entries[46].contentVersion: "b692744cb64c6833f69a4c64a4db1c9e3f0f318b"
- $.entries[46].uri: "archiveQuests/Winter2023.json"
+ $.entries[46].uri: "archiveQuests/Winter2022.json"
- $.entries[47].contentVersion: "1c0caa9783b7c0675758da43ffa5d65754cf40b2"
+ $.entries[47].contentVersion: "f38ae7e4984c6fb43f3b1724f2d3c34a9859405d"
- $.entries[47].uri: "archiveQuests/Winter2024.json"
+ $.entries[47].uri: "archiveQuests/Winter2023.json"
- $.entries[48].contentVersion: "f470c83a5c754f2e7210066dd69c74d2af167b9b"
+ $.entries[48].contentVersion: "4bdccc334d366842d33a8b305242f1f2105b9bf8"
- $.entries[48].uri: "archiveRewardGrid/Tome01.json"
+ $.entries[48].uri: "archiveQuests/Winter2024.json"
- $.entries[49].contentVersion: "15ce2a6a6faae8dbc90d5aa661be3f8ebadb2056"
+ $.entries[49].contentVersion: "7b62df5047f5c2550a9dd59633fcb9bf5153e555"
- $.entries[49].uri: "archiveRewardGrid/Tome02.json"
+ $.entries[49].uri: "archiveRewardGrid/Tome01.json"
- $.entries[50].contentVersion: "99aac68b2cb1a70df4cbb66d4feba4b882a3337d"
+ $.entries[50].contentVersion: "a8ad812439317ca636261a4788a83a611f968362"
- $.entries[50].uri: "archiveRewardGrid/Tome03.json"
+ $.entries[50].uri: "archiveRewardGrid/Tome02.json"
- $.entries[51].contentVersion: "eeb510695dd7a3db92774ed432ef1fd79a652b0b"
+ $.entries[51].contentVersion: "524ce3c7b8e768a86d2ddffc8c9986d5f1832f36"
- $.entries[51].uri: "archiveRewardGrid/Tome04.json"
+ $.entries[51].uri: "archiveRewardGrid/Tome03.json"
- $.entries[52].contentVersion: "a59291bfa5c999304d4a1b4715a47ce8bc879275"
+ $.entries[52].contentVersion: "7fa0c4a4e9ac0ab63556144da9fdcc2907933ab3"
- $.entries[52].uri: "archiveRewardGrid/Tome05.json"
+ $.entries[52].uri: "archiveRewardGrid/Tome04.json"
- $.entries[53].contentVersion: "825c19df2cde69b0e0c185521ad362af8349cbd3"
+ $.entries[53].contentVersion: "80116f550c08e8b0caa1bdfdb7722cb49e2afbc3"
- $.entries[53].uri: "archiveRewardGrid/Tome06.json"
+ $.entries[53].uri: "archiveRewardGrid/Tome05.json"
- $.entries[54].contentVersion: "961f7791577b2ab9439352161c48bf390436cfb2"
+ $.entries[54].contentVersion: "4e1b681a9cf1883c5cd7261ce6fbaa2590e9a595"
- $.entries[54].uri: "archiveRewardGrid/Tome07.json"
+ $.entries[54].uri: "archiveRewardGrid/Tome06.json"
- $.entries[55].contentVersion: "53406c2a1a3e436e8765077a14868afc31a36c53"
+ $.entries[55].contentVersion: "54b12c7b686758d66f835419138a39be87c46ad4"
- $.entries[55].uri: "archiveRewardGrid/Tome08.json"
+ $.entries[55].uri: "archiveRewardGrid/Tome07.json"
- $.entries[56].contentVersion: "fd3cb31714d73777ddeae350ea0a6728a61a0372"
+ $.entries[56].contentVersion: "d72f3ca1c9c0a82be00ecef69d1182319812643a"
- $.entries[56].uri: "archiveRewardGrid/Tome09.json"
+ $.entries[56].uri: "archiveRewardGrid/Tome08.json"
- $.entries[57].contentVersion: "33d9dfa3476e508cc4d941df586ba4777a351ac1"
+ $.entries[57].contentVersion: "b1461a9956e3e5a7be7b60cfc035ef55bcb80e98"
- $.entries[57].uri: "archiveRewardGrid/Tome10.json"
+ $.entries[57].uri: "archiveRewardGrid/Tome09.json"
- $.entries[58].contentVersion: "9eb254f4cf7dcc5660ba5448849c41db66b32c28"
+ $.entries[58].contentVersion: "6bc1dc85aa5fc57c08d99e7b59b2282e2ca7755b"
- $.entries[58].uri: "archiveRewardGrid/Tome11.json"
+ $.entries[58].uri: "archiveRewardGrid/Tome10.json"
- $.entries[59].contentVersion: "6566a6dedbd93ce8dbf761d38c888ab30c5bc94a"
+ $.entries[59].contentVersion: "58e617c6f11d26f209ade0677feef6027a657a8f"
- $.entries[59].uri: "archiveRewardGrid/Tome12.json"
+ $.entries[59].uri: "archiveRewardGrid/Tome11.json"
- $.entries[60].contentVersion: "fe1de37a3761b64151e047c830b57e1e3a4aa01d"
+ $.entries[60].contentVersion: "32a74024a2f47217324f3291d3fb9d60e7b23ab0"
- $.entries[60].uri: "archiveRewardGrid/Tome13.json"
+ $.entries[60].uri: "archiveRewardGrid/Tome12.json"
… 595 more change(s) — see the commit diff for everything
```

### [`itemsKillswitch.json`](itemsKillswitch.json)

[Full line-by-line diff](diffs/itemsKillswitch.json.diff)

```diff
- $.disabledItems.K38
- $.disabledItems.S42_Torso009
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=GelatoW7]
+ $.featuredCard[id=HotdogW3]
- $.featuredCharacterRecommendations[id=Test]
+ $.featuredCharacterRecommendations[id=Featured_Characters]
- $.featuredCustomizationRecommendations[id=GelatoW5]
- $.featuredCustomizationRecommendations[id=GelatoW6_2]
- $.featuredCustomizationRecommendations[id=GelatoW6]
- $.featuredCustomizationRecommendations[id=GelatoW7]
- $.featuredCustomizationRecommendations[id=GelatoW8]
- $.featuredCustomizationRecommendations[id=GelatoW9]
+ $.featuredCustomizationRecommendations[id=HotdogW1]
+ $.featuredCustomizationRecommendations[id=HotdogW2]
+ $.featuredCustomizationRecommendations[id=HotdogW3]
- $.featuredCustomizationRecommendations[id=GelatoW4].activeTo: "2024-12-17T16:00:00"
+ $.featuredCustomizationRecommendations[id=GelatoW4].activeTo: "2025-01-07T16:00:00"
- $.specialsRecommendations[id=Winter_Part6]
- $.specialsRecommendations[id=Winter_Part7]
+ $.specialsRecommendations[id=ResidentEvil]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=AV_outfit_019]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=FM_outfit_017]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=KS_outfit_019]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=GS_outfit_026]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S23_outfit_014]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S24_outfit_018]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S25_outfit_011]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S28_outfit_010]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S29_outfit_006]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=Kate_outfit_011]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=AV_outfit_020]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=S37_outfit_011]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=K32_outfit_009]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=OK_outfit_010]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=K26_outfit_006]
- $.specialsRecommendations[id=Winter_Part3].recommendations[id=HK_outfit_013]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=AV_outfit_019]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=FM_outfit_017]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=KS_outfit_019]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=GS_outfit_026]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S23_outfit_014]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S24_outfit_018]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S25_outfit_011]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S28_outfit_010]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S29_outfit_006]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=Kate_outfit_011]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=AV_outfit_020]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=S37_outfit_011]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=K32_outfit_009]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=OK_outfit_010]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=K26_outfit_006]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=HK_outfit_013]
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=K28_outfit_008].weight: 4
+ $.specialsRecommendations[id=Winter_Part4].recommendations[id=K28_outfit_008].weight: 3
- $.specialsRecommendations[id=Winter_Part4].recommendations[id=DK_outfit_017].weight: 4
+ $.specialsRecommendations[id=Winter_Part4].recommendations[id=DK_outfit_017].weight: 3
- $.specialsRecommendations[id=Winter_Part5].activeTo: "2024-12-26T16:00:00"
+ $.specialsRecommendations[id=Winter_Part5].activeTo: "2025-01-07T16:00:00"
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S41_outfit_009]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S37_outfit_016]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=HS_outfit_023]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=CM_outfit_012]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=DK_outfit_014]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=DF_outfit_015]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=FM_outfit_019]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=MS_outfit_008]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=KS_outfit_017]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=GS_outfit_015]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=MT_outfit_024]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=NK_outfit_015]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S23_outfit_017]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S25_outfit_016]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S28_outfit_012]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=S31_outfit_006]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=SwedenSurvivor_outfit_010]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=TC_outfit_009]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=TC_outfit_009_01]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=K23_outfit_016]
- $.specialsRecommendations[id=Winter_Part5].recommendations[id=TR_outfit_010]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[43]
- $.specialEventsData[7].eventId: "ChocolateBoxEclair"
+ $.specialEventsData[7].eventId: "CalamariV3"
- $.specialEventsData[7].lteData.affectsMMR: true
+ $.specialEventsData[7].lteData.affectsMMR: false
- $.specialEventsData[7].lteData.gameModeQueue: "ChocolateBox"
+ $.specialEventsData[7].lteData.gameModeQueue: "Calamari"
- $.specialEventsData[7].lteData.gameType: "ChocolateBox"
+ $.specialEventsData[7].lteData.gameType: "Calamari"
- $.specialEventsData[8].eventId: "ChocolateBoxGelato"
+ $.specialEventsData[8].eventId: "ChocolateBoxEclair"
- $.specialEventsData[9].eventId: "ChocolateBoxV1"
+ $.specialEventsData[9].eventId: "ChocolateBoxGelato"
- $.specialEventsData[10].eventId: "DreadByDaylightZodiac"
+ $.specialEventsData[10].eventId: "ChocolateBoxV1"
- $.specialEventsData[10].lteData.affectsMMR: false
+ $.specialEventsData[10].lteData.affectsMMR: true
- $.specialEventsData[10].lteData.gameModeQueue: "DreadByDaylight"
+ $.specialEventsData[10].lteData.gameModeQueue: "ChocolateBox"
- $.specialEventsData[10].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[10].lteData.gameType: "ChocolateBox"
- $.specialEventsData[11].eventId: "FireflyV1"
+ $.specialEventsData[11].eventId: "DreadByDaylightZodiac"
- $.specialEventsData[11].lteData.gameModeQueue: "Firefly"
+ $.specialEventsData[11].lteData.gameModeQueue: "DreadByDaylight"
- $.specialEventsData[11].lteData.gameType: "Firefly"
+ $.specialEventsData[11].lteData.gameType: "DreadByDaylight"
+ $.specialEventsData[12].lteData
- $.specialEventsData[12].eventId: "Halloween2022"
+ $.specialEventsData[12].eventId: "FireflyV1"
- $.specialEventsData[12].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[13].eventId: "Halloween2023"
+ $.specialEventsData[13].eventId: "Halloween2022"
- $.specialEventsData[13].milestoneRewards[0]
- $.specialEventsData[13].milestoneRewards[1]
- $.specialEventsData[13].milestoneRewards[2]
+ $.specialEventsData[13].ownerRewards[id=Halloween2022Reward]
- $.specialEventsData[14].lteData
- $.specialEventsData[14].eventId: "Halloween2024"
+ $.specialEventsData[14].eventId: "Halloween2023"
- $.specialEventsData[14].eventPeriods[id=Halloween2024]
- $.specialEventsData[14].milestoneRewards[0].rewards[id=FU_012]
+ $.specialEventsData[14].milestoneRewards[0].rewards[id=XR_037]
- $.specialEventsData[14].milestoneRewards[1].rewards[id=FU_BDG_18]
+ $.specialEventsData[14].milestoneRewards[1].rewards[id=MT_Head027]
- $.specialEventsData[14].milestoneRewards[2].pointsCost: 20
+ $.specialEventsData[14].milestoneRewards[2].pointsCost: 21
- $.specialEventsData[14].milestoneRewards[2].rewards[id=FU_BNR_12]
+ $.specialEventsData[14].milestoneRewards[2].rewards[id=K30_Head011]
+ $.specialEventsData[15].lteData
- $.specialEventsData[15].eventId: "Lunar2022"
+ $.specialEventsData[15].eventId: "Halloween2024"
+ $.specialEventsData[15].eventPeriods[id=Halloween2024]
+ $.specialEventsData[15].milestoneRewards[0]
+ $.specialEventsData[15].milestoneRewards[1]
+ $.specialEventsData[15].milestoneRewards[2]
- $.specialEventsData[15].miscRewards[id=killerStaticReward]
- $.specialEventsData[15].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[15].scoreEventRewards[0]
- $.specialEventsData[15].scoreEventRewards[1]
- $.specialEventsData[15].scoreEventRewards[2]
- $.specialEventsData[15].scoreEventRewards[3]
- $.specialEventsData[15].scoreEventRewards[4]
- $.specialEventsData[15].scoreEventRewards[5]
- $.specialEventsData[15].scoreEventRewards[6]
- $.specialEventsData[15].scoreEventRewards[7]
- $.specialEventsData[16].eventId: "Lunar2023"
+ $.specialEventsData[16].eventId: "Lunar2022"
- $.specialEventsData[16].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 5000
+ $.specialEventsData[16].miscRewards[id=killerStaticReward].rewards[id=Bloodpoints].amount: 4000
- $.specialEventsData[16].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[16].ownerRewards[id=Lunar2022Reward]
- $.specialEventsData[16].scoreEventRewards[2].weight: 15
+ $.specialEventsData[16].scoreEventRewards[2].weight: 20
- $.specialEventsData[16].scoreEventRewards[3].weight: 25
+ $.specialEventsData[16].scoreEventRewards[3].weight: 20
- $.specialEventsData[16].scoreEventRewards[5].weight: 20
+ $.specialEventsData[16].scoreEventRewards[5].weight: 15
- $.specialEventsData[16].scoreEventRewards[6].weight: 10
+ $.specialEventsData[16].scoreEventRewards[6].weight: 8
- $.specialEventsData[16].scoreEventRewards[7].weight: 5
+ $.specialEventsData[16].scoreEventRewards[7].weight: 2
- $.specialEventsData[17].eventId: "Spring2024"
+ $.specialEventsData[17].eventId: "Lunar2023"
- $.specialEventsData[17].eventTrackerObjectives[id=main]
+ $.specialEventsData[17].miscRewards[id=killerStaticReward]
+ $.specialEventsData[17].ownerRewards[id=Lunar2023Reward]
+ $.specialEventsData[17].scoreEventRewards[0]
+ $.specialEventsData[17].scoreEventRewards[1]
+ $.specialEventsData[17].scoreEventRewards[2]
+ $.specialEventsData[17].scoreEventRewards[3]
+ $.specialEventsData[17].scoreEventRewards[4]
+ $.specialEventsData[17].scoreEventRewards[5]
+ $.specialEventsData[17].scoreEventRewards[6]
+ $.specialEventsData[17].scoreEventRewards[7]
- $.specialEventsData[18].eventId: "Winter2023"
+ $.specialEventsData[18].eventId: "Spring2024"
+ $.specialEventsData[18].eventTrackerObjectives[id=main]
- $.specialEventsData[18].milestoneRewards[0]
- $.specialEventsData[18].milestoneRewards[1]
- $.specialEventsData[18].milestoneRewards[2]
- $.specialEventsData[18].milestoneRewards[3]
- $.specialEventsData[18].milestoneRewards[4]
- $.specialEventsData[19].lteData
- $.specialEventsData[19].eventId: "Winter2024"
+ $.specialEventsData[19].eventId: "Winter2023"
- $.specialEventsData[19].eventPeriods[id=Winter2024]
- $.specialEventsData[19].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[19].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[19].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[19].milestoneRewards[0].rewards[id=YE_005]
- $.specialEventsData[19].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[19].milestoneRewards[1].pointsCost: 6
- $.specialEventsData[19].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[19].milestoneRewards[1].rewards[id=YE_BDG_01]
- $.specialEventsData[19].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[19].milestoneRewards[2].pointsCost: 9
- $.specialEventsData[19].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[19].milestoneRewards[2].rewards[id=YE_BNR_01]
+ $.specialEventsData[19].milestoneRewards[3]
+ $.specialEventsData[19].milestoneRewards[4]
+ $.specialEventsData[20]
```

## Could not download

- `images/T_UI_CollectionBanner_ArtistsFromTheFog_V2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_ResidentEvil_V2.png (HTTP 404)`
- `images/T_UI_SpecialPack_ResidentEvil_V2.png (HTTP 404)`
- `images/T_UI_SpecialPack_Wasteland.png (HTTP 404)`
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

