# live · 8.5.0_2335221live

| | |
|---|---|
| Build date | 2025-03-18 14:31 UTC |
| CDN version | `8.5.0_2335221live-1742308313` |
| Key | `8.5.0_live` |
| Compared with | [8.5.1_2282865live](../8.5.1_2282865live/CHANGES.md) (2025-02-11 16:07 UTC) |

## Summary

**0** added · **11** modified · **0** removed · 174 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.afk.minimumMatchTime: 60
+ $.afk.minimumMatchTime: 120
- $.analytics.detailedScoreTypeBlacklist[]: "GameEvent.CamperInjuredBleedoutKO"
- $.analytics.gameInitVerbose: false
+ $.analytics.gameInitVerbose: true
- $.analyticsRules.BL[]: "RTMAnalytics"
+ $.analyticsRules.KL[]: "RTMAnalytics"
- $.contentVersion.clientNewContentRebootMaxSeconds: 30.0
+ $.contentVersion.clientNewContentRebootMaxSeconds: 60.0
- $.dedicatedServer.endpointsUDP[14]
- $.dedicatedServer.useUDPLatencyPings: false
+ $.dedicatedServer.useUDPLatencyPings: true
- $.enableLobbyKickPlayerForCharacterOwnership: false
+ $.enableLobbyKickPlayerForCharacterOwnership: true
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
- $.analyticsRulesDedicatedServer.BL[]: "RTMAnalytics"
+ $.analyticsRulesDedicatedServer.KL[]: "RTMAnalytics"
```

### [`bonusPointEventsContent.json`](bonusPointEventsContent.json)

[Full line-by-line diff](diffs/bonusPointEventsContent.json.diff)

```diff
- $.bonusPointEvents[0].endTime: "2025-02-10T15:59:00"
+ $.bonusPointEvents[0].endTime: "2025-03-31T14:59:00"
- $.bonusPointEvents[0].startTime: "2025-02-04T16:00:00"
+ $.bonusPointEvents[0].startTime: "2025-03-18T15:00:00"
- $.bonusPointEvents[1].endTime: "2025-01-28T15:59:00"
+ $.bonusPointEvents[1].endTime: "2025-02-10T15:59:00"
- $.bonusPointEvents[1].startTime: "2025-01-21T16:00:00"
+ $.bonusPointEvents[1].startTime: "2025-02-04T16:00:00"
- $.bonusPointEvents[2].endTime: "2025-01-07T15:59:00"
+ $.bonusPointEvents[2].endTime: "2025-01-28T15:59:00"
- $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[2].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[2].multiplier: 3.0
+ $.bonusPointEvents[2].multiplier: 2.0
- $.bonusPointEvents[2].startTime: "2024-12-26T16:00:00"
+ $.bonusPointEvents[2].startTime: "2025-01-21T16:00:00"
- $.bonusPointEvents[3].endTime: "2024-12-26T15:59:00"
+ $.bonusPointEvents[3].endTime: "2025-01-07T15:59:00"
- $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[3].multiplier: 2.0
+ $.bonusPointEvents[3].multiplier: 3.0
- $.bonusPointEvents[3].startTime: "2024-12-19T16:00:00"
+ $.bonusPointEvents[3].startTime: "2024-12-26T16:00:00"
- $.bonusPointEvents[4].endTime: "2024-11-28T16:00:00"
+ $.bonusPointEvents[4].endTime: "2024-12-26T15:59:00"
- $.bonusPointEvents[4].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[4].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[4].multiplier: 3.0
+ $.bonusPointEvents[4].multiplier: 2.0
- $.bonusPointEvents[4].startTime: "2024-11-22T20:00:00"
+ $.bonusPointEvents[4].startTime: "2024-12-19T16:00:00"
- $.bonusPointEvents[5].endTime: "2024-10-01T15:00:00"
+ $.bonusPointEvents[5].endTime: "2024-11-28T16:00:00"
- $.bonusPointEvents[5].startTime: "2024-09-24T15:00:00"
+ $.bonusPointEvents[5].startTime: "2024-11-22T20:00:00"
- $.bonusPointEvents[6].endTime: "2024-09-12T15:00:00"
+ $.bonusPointEvents[6].endTime: "2024-10-01T15:00:00"
- $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[6].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[6].multiplier: 2.0
+ $.bonusPointEvents[6].multiplier: 3.0
- $.bonusPointEvents[6].startTime: "2024-09-05T15:00:00"
+ $.bonusPointEvents[6].startTime: "2024-09-24T15:00:00"
- $.bonusPointEvents[7].endTime: "2024-06-13T15:00:00"
+ $.bonusPointEvents[7].endTime: "2024-09-12T15:00:00"
- $.bonusPointEvents[7].startTime: "2024-06-03T15:00:00"
+ $.bonusPointEvents[7].startTime: "2024-09-05T15:00:00"
- $.bonusPointEvents[8].endTime: "2024-05-21T15:00:00"
+ $.bonusPointEvents[8].endTime: "2024-06-13T15:00:00"
- $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[8].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[8].multiplier: 3.0
+ $.bonusPointEvents[8].multiplier: 2.0
- $.bonusPointEvents[8].startTime: "2024-05-14T16:00:00"
+ $.bonusPointEvents[8].startTime: "2024-06-03T15:00:00"
- $.bonusPointEvents[9].endTime: "2024-02-20T16:00:00"
+ $.bonusPointEvents[9].endTime: "2024-05-21T15:00:00"
- $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[9].multiplier: 1.5
+ $.bonusPointEvents[9].multiplier: 3.0
- $.bonusPointEvents[9].startTime: "2024-02-14T16:00:00"
+ $.bonusPointEvents[9].startTime: "2024-05-14T16:00:00"
- $.bonusPointEvents[10].endTime: "2023-09-19T15:00:00"
+ $.bonusPointEvents[10].endTime: "2024-02-20T16:00:00"
- $.bonusPointEvents[10].startTime: "2023-09-12T15:00:00"
+ $.bonusPointEvents[10].startTime: "2024-02-14T16:00:00"
- $.bonusPointEvents[11].endTime: "2023-07-13T15:00:00"
+ $.bonusPointEvents[11].endTime: "2023-09-19T15:00:00"
- $.bonusPointEvents[11].startTime: "2023-07-07T15:00:00"
+ $.bonusPointEvents[11].startTime: "2023-09-12T15:00:00"
- $.bonusPointEvents[12].endTime: "2023-05-30T15:00:00"
+ $.bonusPointEvents[12].endTime: "2023-07-13T15:00:00"
- $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[12].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[12].multiplier: 2.0
+ $.bonusPointEvents[12].multiplier: 1.5
- $.bonusPointEvents[12].startTime: "2023-05-23T15:00:00"
+ $.bonusPointEvents[12].startTime: "2023-07-07T15:00:00"
- $.bonusPointEvents[13].endTime: "2022-11-29T16:00:00"
+ $.bonusPointEvents[13].endTime: "2023-05-30T15:00:00"
- $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[13].startTime: "2022-11-22T16:00:00"
+ $.bonusPointEvents[13].startTime: "2023-05-23T15:00:00"
- $.bonusPointEvents[14].endTime: "2022-06-27T15:00:00"
+ $.bonusPointEvents[14].endTime: "2022-11-29T16:00:00"
- $.bonusPointEvents[14].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[14].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[14].startTime: "2022-06-23T15:00:00"
+ $.bonusPointEvents[14].startTime: "2022-11-22T16:00:00"
- $.bonusPointEvents[15].endTime: "2022-05-30T15:00:00"
+ $.bonusPointEvents[15].endTime: "2022-06-27T15:00:00"
- $.bonusPointEvents[15].startTime: "2022-05-23T15:00:00"
+ $.bonusPointEvents[15].startTime: "2022-06-23T15:00:00"
- $.bonusPointEvents[16].endTime: "2022-03-07T16:00:00"
+ $.bonusPointEvents[16].endTime: "2022-05-30T15:00:00"
- $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[16].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[16].multiplier: 1.5
+ $.bonusPointEvents[16].multiplier: 2.0
- $.bonusPointEvents[16].startTime: "2022-02-28T16:00:00"
+ $.bonusPointEvents[16].startTime: "2022-05-23T15:00:00"
- $.bonusPointEvents[17].endTime: "2022-01-21T16:00:00"
+ $.bonusPointEvents[17].endTime: "2022-03-07T16:00:00"
- $.bonusPointEvents[17].startTime: "2022-01-14T16:00:00"
+ $.bonusPointEvents[17].startTime: "2022-02-28T16:00:00"
- $.bonusPointEvents[18].endTime: "2021-11-29T16:00:00"
+ $.bonusPointEvents[18].endTime: "2022-01-21T16:00:00"
- $.bonusPointEvents[18].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[18].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[18].multiplier: 2.0
+ $.bonusPointEvents[18].multiplier: 1.5
- $.bonusPointEvents[18].startTime: "2021-11-25T16:00:00"
+ $.bonusPointEvents[18].startTime: "2022-01-14T16:00:00"
- $.bonusPointEvents[19].endTime: "2021-08-03T15:00:00"
+ $.bonusPointEvents[19].endTime: "2021-11-29T16:00:00"
- $.bonusPointEvents[19].startTime: "2021-07-29T15:00:00"
+ $.bonusPointEvents[19].startTime: "2021-11-25T16:00:00"
- $.bonusPointEvents[20].endTime: "2021-01-22T16:00:00"
+ $.bonusPointEvents[20].endTime: "2021-08-03T15:00:00"
- $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[20].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[20].multiplier: 1.5
+ $.bonusPointEvents[20].multiplier: 2.0
- $.bonusPointEvents[20].startTime: "2021-01-15T16:00:00"
+ $.bonusPointEvents[20].startTime: "2021-07-29T15:00:00"
- $.bonusPointEvents[21].endTime: "2020-11-02T16:29:59"
+ $.bonusPointEvents[21].endTime: "2021-01-22T16:00:00"
- $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[21].multiplier: 2.0
+ $.bonusPointEvents[21].multiplier: 1.5
- $.bonusPointEvents[21].startTime: "2020-10-29T15:00:00"
+ $.bonusPointEvents[21].startTime: "2021-01-15T16:00:00"
- $.bonusPointEvents[22].endTime: "2020-04-15T15:00:00"
+ $.bonusPointEvents[22].endTime: "2020-11-02T16:29:59"
- $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[22].multiplier: 1.5
+ $.bonusPointEvents[22].multiplier: 2.0
- $.bonusPointEvents[22].startTime: "2020-03-25T15:00:00"
+ $.bonusPointEvents[22].startTime: "2020-10-29T15:00:00"
- $.bonusPointEvents[23].endTime: "2020-01-06T16:00:00"
+ $.bonusPointEvents[23].endTime: "2020-04-15T15:00:00"
- $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[23].multiplier: 2.0
+ $.bonusPointEvents[23].multiplier: 1.5
- $.bonusPointEvents[23].startTime: "2020-01-02T16:00:00"
+ $.bonusPointEvents[23].startTime: "2020-03-25T15:00:00"
- $.bonusPointEvents[24].endTime: "2019-11-04T15:00:00"
+ $.bonusPointEvents[24].endTime: "2020-01-06T16:00:00"
- $.bonusPointEvents[24].startTime: "2019-10-31T15:00:00"
+ $.bonusPointEvents[24].startTime: "2020-01-02T16:00:00"
- $.bonusPointEvents[25].endTime: "2019-09-30T15:00:00"
+ $.bonusPointEvents[25].endTime: "2019-11-04T15:00:00"
- $.bonusPointEvents[25].startTime: "2019-09-26T15:00:00"
+ $.bonusPointEvents[25].startTime: "2019-10-31T15:00:00"
- $.bonusPointEvents[26].endTime: "2019-06-20T18:00:00"
+ $.bonusPointEvents[26].endTime: "2019-09-30T15:00:00"
- $.bonusPointEvents[26].startTime: "2019-06-14T18:00:00"
+ $.bonusPointEvents[26].startTime: "2019-09-26T15:00:00"
- $.bonusPointEvents[27].endTime: "2019-05-06T18:00:00"
+ $.bonusPointEvents[27].endTime: "2019-06-20T18:00:00"
- $.bonusPointEvents[27].startTime: "2019-05-02T18:00:00"
+ $.bonusPointEvents[27].startTime: "2019-06-14T18:00:00"
- $.bonusPointEvents[28].endTime: "2019-01-03T19:00:00"
+ $.bonusPointEvents[28].endTime: "2019-05-06T18:00:00"
- $.bonusPointEvents[28].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
+ $.bonusPointEvents[28].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[28].startTime: "2018-12-27T19:00:00"
+ $.bonusPointEvents[28].startTime: "2019-05-02T18:00:00"
- $.bonusPointEvents[29].endTime: "2018-11-12T19:00:00"
+ $.bonusPointEvents[29].endTime: "2019-01-03T19:00:00"
- $.bonusPointEvents[29].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[29].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
- $.bonusPointEvents[29].multiplier: 1.5
+ $.bonusPointEvents[29].multiplier: 2.0
- $.bonusPointEvents[29].startTime: "2018-11-05T19:00:00"
+ $.bonusPointEvents[29].startTime: "2018-12-27T19:00:00"
- $.bonusPointEvents[30].endTime: "2018-09-27T00:00:00"
+ $.bonusPointEvents[30].endTime: "2018-11-12T19:00:00"
- $.bonusPointEvents[30].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[30].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[30].multiplier: 2.0
+ $.bonusPointEvents[30].multiplier: 1.5
- $.bonusPointEvents[30].startTime: "2018-09-21T00:00:00"
+ $.bonusPointEvents[30].startTime: "2018-11-05T19:00:00"
- $.bonusPointEvents[31].endTime: "2023-11-06T16:00:00"
+ $.bonusPointEvents[31].endTime: "2018-09-27T00:00:00"
- $.bonusPointEvents[31].startTime: "2023-10-30T15:00:00"
+ $.bonusPointEvents[31].startTime: "2018-09-21T00:00:00"
- $.bonusPointEvents[32].endTime: "2015-10-13T00:00:00"
+ $.bonusPointEvents[32].endTime: "2023-11-06T16:00:00"
- $.bonusPointEvents[32].startTime: "2015-10-11T00:00:00"
+ $.bonusPointEvents[32].startTime: "2023-10-30T15:00:00"
- $.bonusPointEvents[33].endTime: "2015-09-12T00:00:00"
+ $.bonusPointEvents[33].endTime: "2015-10-13T00:00:00"
… 11 more change(s) — see the commit diff for everything
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=HO_BDG_02]
- $[id=HO_BNR_02]
- $[id=K24_Body008]
- $[id=K24_Head008]
- $[id=K24_W008]
- $[id=K29_Body008]
- $[id=K29_Head008]
- $[id=K29_W008]
- $[id=S26_Head011]
- $[id=S26_Legs011]
- $[id=S26_Torso011]
- $[id=S27_Head010]
- $[id=S27_Legs010]
- $[id=S27_Torso010]
- $[id=S32_Head009]
- $[id=S32_Legs009]
- $[id=S32_Torso009]
- $[id=S33_Head008]
- $[id=S33_Legs008]
- $[id=S33_Torso008]
- $[id=K24_outfit_008]
- $[id=K29_outfit_008]
- $[id=S26_Outfit_011]
- $[id=S27_Outfit_010]
- $[id=S32_outfit_009]
- $[id=S33_outfit_008]
- $[id=LicensorBundle_Castlevania]
- $[id=LicensorBundle_IronMaiden]
- $[id=LicensorBundle_Slipknot]
- $[id=ProjectW_Survivor_Outfit_Bundle]
- $[id=ResidentEvil_Killer_Bundle]
- $[id=ResidentEvil_Killer_Outfit_Bundle]
- $[id=ResidentEvil_Survivor_Bundle]
- $[id=ResidentEvil_Survivor_Outfit_Bundle]
+ $[id=Recurring_Charm_Bundle_250218]
+ $[id=Recurring_Charm_Bundle_250225]
+ $[id=Recurring_Charm_Bundle_250304]
+ $[id=Recurring_Charm_Bundle_250311]
+ $[id=Recurring_Charm_Bundle_250318]
+ $[id=Recurring_Dev_Bundle_250218]
+ $[id=Recurring_Dev_Bundle_250225]
+ $[id=Recurring_Dev_Bundle_250304]
+ $[id=Recurring_Dev_Bundle_250311]
+ $[id=Recurring_Dev_Bundle_250318]
+ $[id=From_The_Rift_Bundle_250218]
+ $[id=From_The_Rift_Bundle_250225]
+ $[id=From_The_Rift_Bundle_250304]
+ $[id=From_The_Rift_Bundle_250311]
+ $[id=From_The_Rift_Bundle_250318]
+ $[id=Recurring_Killer_Bundle_250218]
+ $[id=Recurring_Killer_Bundle_250225]
+ $[id=Recurring_Killer_Bundle_250304]
+ $[id=Recurring_Killer_Bundle_250311]
+ $[id=Recurring_Killer_Bundle_250318]
+ $[id=Recurring_Survivor_Bundle_250218]
+ $[id=Recurring_Survivor_Bundle_250225]
+ $[id=Recurring_Survivor_Bundle_250304]
+ $[id=Recurring_Survivor_Bundle_250311]
+ $[id=Recurring_Survivor_Bundle_250318]
+ $[id=Recurring_Survivor_Bundle_2_250318]
- $[id=S26].eventCostList
- $[id=S26].metaData.temporaryDiscounts
- $[id=S27].eventCostList
- $[id=S27].metaData.temporaryDiscounts
- $[id=K24].eventCostList
- $[id=K24].metaData.temporaryDiscounts
+ $[id=K25].eventCostList
+ $[id=K25].metaData.temporaryDiscounts
- $[id=K29].eventCostList
- $[id=K29].metaData.temporaryDiscounts
- $[id=S32].eventCostList
- $[id=S32].metaData.temporaryDiscounts
- $[id=S33].eventCostList
- $[id=S33].metaData.temporaryDiscounts
+ $[id=S43].eventCostList
+ $[id=S43].metaData.temporaryDiscounts
- $[id=BE_Body018].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=BE_Body018].metaData.releaseDate: "2025-03-18T15:00:00"
- $[id=BE_Body018].purchasable: false
+ $[id=BE_Body018].purchasable: true
- $[id=BE_Mask018].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=BE_Mask018].metaData.releaseDate: "2025-03-18T15:00:00"
- $[id=BE_Mask018].purchasable: false
+ $[id=BE_Mask018].purchasable: true
- $[id=BE_W018].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=BE_W018].metaData.releaseDate: "2025-03-18T15:00:00"
- $[id=BE_W018].purchasable: false
+ $[id=BE_W018].purchasable: true
+ $[id=CM_Head017].defaultCost[1]
+ $[id=CM_Legs017].defaultCost[1]
+ $[id=CM_Torso017].defaultCost[1]
+ $[id=DF_Head029].defaultCost[1]
- $[id=DF_Head03_01].defaultCost[0].price: 100
+ $[id=DF_Head03_01].defaultCost[0].price: 250
- $[id=DF_Head03_01].defaultCost[1].price: 1800
+ $[id=DF_Head03_01].defaultCost[1].price: 4500
+ $[id=DF_Legs029].defaultCost[1]
+ $[id=DF_Torso029].defaultCost[1]
+ $[id=DO_Body021].defaultCost[1]
- $[id=DO_Body021].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=DO_Body021].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=DO_Head021].defaultCost[1]
- $[id=DO_Head021].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=DO_Head021].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=DO_W021].defaultCost[1]
- $[id=DO_W021].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=DO_W021].metaData.releaseDate: "2025-01-21T16:00:00"
- $[id=FM_Head027].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Head027].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=FM_Head027].purchasable: false
+ $[id=FM_Head027].purchasable: true
- $[id=FM_Legs027].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Legs027].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=FM_Legs027].purchasable: false
+ $[id=FM_Legs027].purchasable: true
- $[id=FM_Torso027].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=FM_Torso027].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=FM_Torso027].purchasable: false
+ $[id=FM_Torso027].purchasable: true
+ $[id=JP_Head016].defaultCost[1]
+ $[id=JP_Head024].defaultCost[1]
- $[id=JP_Head024].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=JP_Head024].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=JP_Legs016].defaultCost[1]
+ $[id=JP_Legs024].defaultCost[1]
- $[id=JP_Legs024].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=JP_Legs024].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=JP_Torso016].defaultCost[1]
+ $[id=JP_Torso024].defaultCost[1]
- $[id=JP_Torso024].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=JP_Torso024].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=K21_Body009].defaultCost[1]
- $[id=K21_Body009].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=K21_Body009].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=K21_Head009].defaultCost[1]
- $[id=K21_Head009].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=K21_Head009].metaData.releaseDate: "2025-01-21T16:00:00"
+ $[id=K21_W009].defaultCost[1]
- $[id=K21_W009].metaData.releaseDate: "2025-01-25T16:00:00"
+ $[id=K21_W009].metaData.releaseDate: "2025-01-21T16:00:00"
- $[id=K23_Body022].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K23_Body022].metaData.releaseDate: "2025-03-11T15:00:00"
- $[id=K23_Body022].purchasable: false
+ $[id=K23_Body022].purchasable: true
- $[id=K23_Head022].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K23_Head022].metaData.releaseDate: "2025-03-11T15:00:00"
- $[id=K23_Head022].purchasable: false
+ $[id=K23_Head022].purchasable: true
- $[id=K23_Weapon022].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K23_Weapon022].metaData.releaseDate: "2025-03-11T15:00:00"
- $[id=K23_Weapon022].purchasable: false
+ $[id=K23_Weapon022].purchasable: true
+ $[id=K25_Body006].metaData.limitedTimeEndDate: "2025-04-04T15:00:00"
+ $[id=K25_Body02].metaData.limitedTimeEndDate: "2025-04-04T15:00:00"
+ $[id=K25_Head02].metaData.limitedTimeEndDate: "2025-04-04T15:00:00"
+ $[id=K25_W006].metaData.limitedTimeEndDate: "2025-04-04T15:00:00"
+ $[id=K25_W02].metaData.limitedTimeEndDate: "2025-04-04T15:00:00"
- $[id=K26_Body01_02].defaultCost[0].price: 100
+ $[id=K26_Body01_02].defaultCost[0].price: 250
- $[id=K26_Body01_02].defaultCost[1].price: 1800
+ $[id=K26_Body01_02].defaultCost[1].price: 4500
- $[id=K26_Head01_02].defaultCost[0].price: 100
+ $[id=K26_Head01_02].defaultCost[0].price: 250
- $[id=K26_Head01_02].defaultCost[1].price: 1800
+ $[id=K26_Head01_02].defaultCost[1].price: 4500
- $[id=K28_Body011].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K28_Body011].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=K28_Body011].purchasable: false
+ $[id=K28_Body011].purchasable: true
- $[id=K28_Head011].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K28_Head011].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=K28_Head011].purchasable: false
+ $[id=K28_Head011].purchasable: true
- $[id=K28_W011].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=K28_W011].metaData.releaseDate: "2025-03-04T16:00:00"
- $[id=K28_W011].purchasable: false
+ $[id=K28_W011].purchasable: true
+ $[id=K31_Body016].defaultCost[1]
+ $[id=K31_Head016].defaultCost[1]
+ $[id=K31_W016].defaultCost[1]
+ $[id=KK_Body019_01].defaultCost[1]
- $[id=KK_Body019_01].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=KK_Body019_01].metaData.releaseDate: "2025-02-14T16:00:00"
- $[id=KK_Body019_01].purchasable: false
+ $[id=KK_Body019_01].purchasable: true
+ $[id=KK_Mask019_01].defaultCost[1]
- $[id=KK_Mask019_01].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=KK_Mask019_01].metaData.releaseDate: "2025-02-14T16:00:00"
- $[id=KK_Mask019_01].purchasable: false
+ $[id=KK_Mask019_01].purchasable: true
+ $[id=KK_W019_01].defaultCost[1]
- $[id=KK_W019_01].metaData.releaseDate: "2018-06-12T00:00:00"
+ $[id=KK_W019_01].metaData.releaseDate: "2025-02-14T16:00:00"
- $[id=KK_W019_01].purchasable: false
+ $[id=KK_W019_01].purchasable: true
- $[id=KS_Head01_4A].defaultCost[0].price: 400
+ $[id=KS_Head01_4A].defaultCost[0].price: 250
- $[id=KS_Head01_4A].defaultCost[1].price: 7200
+ $[id=KS_Head01_4A].defaultCost[1].price: 4500
- $[id=KS_Head01_5A].defaultCost[0].price: 400
… 532 more change(s) — see the commit diff for everything
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[0].additionalImages[0]
- $.collections[0].collectionId: "Hanami"
+ $.collections[0].collectionId: "IronMaiden"
- $.collections[0].collectionTitle.de: "Hanami "
+ $.collections[0].collectionTitle.de: "Iron Maiden"
- $.collections[0].collectionTitle.en: "Hanami "
+ $.collections[0].collectionTitle.en: "Iron Maiden"
- $.collections[0].collectionTitle.es: "Hanami "
+ $.collections[0].collectionTitle.es: "Doncella de hierro"
- $.collections[0].collectionTitle["es-MX"]: "Hanami "
+ $.collections[0].collectionTitle["es-MX"]: "Iron Maiden"
- $.collections[0].collectionTitle.fr: "Hanami "
+ $.collections[0].collectionTitle.fr: "Iron Maiden"
- $.collections[0].collectionTitle.it: "Hanami "
+ $.collections[0].collectionTitle.it: "Iron Maiden"
- $.collections[0].collectionTitle.ja: "花見 "
+ $.collections[0].collectionTitle.ja: "アイアンメイデン"
- $.collections[0].collectionTitle.ko: "벚꽃 축제 "
+ $.collections[0].collectionTitle.ko: "아이언 메이든"
- $.collections[0].collectionTitle.pl: "Hanami "
+ $.collections[0].collectionTitle.pl: "Żelazna dziewica"
- $.collections[0].collectionTitle["pt-BR"]: "Hanami "
+ $.collections[0].collectionTitle["pt-BR"]: "Iron Maiden"
- $.collections[0].collectionTitle.ru: "Ханами "
+ $.collections[0].collectionTitle.ru: "Железная дева"
- $.collections[0].collectionTitle.th: "ฮานามิ "
+ $.collections[0].collectionTitle.th: "เครื่องทรมานสตรีเหล็ก"
- $.collections[0].collectionTitle.tr: "Hanami "
+ $.collections[0].collectionTitle.tr: "Çivili Tabut"
- $.collections[0].collectionTitle["zh-Hans"]: "花见 "
+ $.collections[0].collectionTitle["zh-Hans"]: "铁娘子"
- $.collections[0].collectionTitle["zh-Hant"]: "賞花 "
+ $.collections[0].collectionTitle["zh-Hant"]: "鐵處女"
- $.collections[0].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
+ $.collections[0].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_IronMaiden.T_UI_CollectionBanner_IronMaiden"
- $.collections[0].items[]: "MS_outfit_016"
- $.collections[0].items[]: "SwedenSurvivor_outfit_015"
- $.collections[0].items[]: "HK_outfit_014"
+ $.collections[0].items[]: "K28_outfit_013"
+ $.collections[0].items[]: "DO_outfit_019"
+ $.collections[0].items[]: "UK_outfit_015"
+ $.collections[0].items[]: "SwedenKiller_outfit_020"
+ $.collections[0].items[]: "DF_Torso030"
+ $.collections[0].items[]: "MT_Torso028"
+ $.collections[0].items[]: "CM_Torso027"
+ $.collections[0].items[]: "JP_Torso022"
+ $.collections[0].items[]: "NK_Torso028"
+ $.collections[0].items[]: "AV_Torso021"
+ $.collections[0].items[]: "FM_Torso030"
+ $.collections[0].items[]: "DK_Torso021"
+ $.collections[0].items[]: "GS_Torso028"
+ $.collections[0].items[]: "HS_Torso022"
+ $.collections[0].items[]: "KS_Torso021"
+ $.collections[0].items[]: "MS_Torso022"
+ $.collections[0].items[]: "SwedenSurvivor_Torso023"
+ $.collections[0].items[]: "US_Torso022"
+ $.collections[0].items[]: "S23_Torso026"
+ $.collections[0].items[]: "S24_Torso020"
+ $.collections[0].items[]: "S25_Torso022"
+ $.collections[0].items[]: "S28_Torso022"
+ $.collections[0].items[]: "S29_Torso016"
+ $.collections[0].items[]: "S31_Torso015"
+ $.collections[0].items[]: "S34_Torso016"
+ $.collections[0].items[]: "S35_Torso014"
+ $.collections[0].items[]: "S36_Torso015"
+ $.collections[0].items[]: "S37_Torso014"
+ $.collections[0].items[]: "S41_Torso015"
+ $.collections[0].items[]: "S45_Torso009"
- $.collections[0].sortOrder: "-13"
+ $.collections[0].sortOrder: "-100"
- $.collections[0].updatedDate: "2024-02-01T17:19:10Z"
+ $.collections[0].updatedDate: "2025-02-24T13:14:16.963Z"
- $.collections[1].collectionId: "Rockabilly"
+ $.collections[1].collectionId: "Gold&Silk"
- $.collections[1].collectionTitle.de: "Rockabilly"
+ $.collections[1].collectionTitle.de: "Gold und Seide"
- $.collections[1].collectionTitle.en: "Rockabilly"
+ $.collections[1].collectionTitle.en: "Gold & Silk"
- $.collections[1].collectionTitle.es: "Rockabilly"
+ $.collections[1].collectionTitle.es: "Oro y seda"
- $.collections[1].collectionTitle["es-MX"]: "Rockabilly"
+ $.collections[1].collectionTitle["es-MX"]: "Oro y seda"
- $.collections[1].collectionTitle.fr: "Rockabilly"
+ $.collections[1].collectionTitle.fr: "Or et soie"
- $.collections[1].collectionTitle.it: "Rockabilly"
+ $.collections[1].collectionTitle.it: "Oro e seta"
- $.collections[1].collectionTitle.ja: "ロカビリー "
+ $.collections[1].collectionTitle.ja: "黄金と絹"
- $.collections[1].collectionTitle.ko: "로커빌리"
+ $.collections[1].collectionTitle.ko: "황금 & 실크"
- $.collections[1].collectionTitle.pl: "Rockabilly"
+ $.collections[1].collectionTitle.pl: "Wieczorna elegancja"
- $.collections[1].collectionTitle["pt-BR"]: "Rockabilly"
+ $.collections[1].collectionTitle["pt-BR"]: "Ouro e Seda"
- $.collections[1].collectionTitle.ru: "Рокабилли"
+ $.collections[1].collectionTitle.ru: "Золото и шелк"
- $.collections[1].collectionTitle.th: "ร็อกอะบิลลี่"
+ $.collections[1].collectionTitle.th: "ทองกับผ้าไหม"
- $.collections[1].collectionTitle.tr: "Rockabilly"
+ $.collections[1].collectionTitle.tr: "Altın ve İpek"
- $.collections[1].collectionTitle["zh-Hans"]: "山区摇滚"
+ $.collections[1].collectionTitle["zh-Hans"]: "金丝华服"
- $.collections[1].collectionTitle["zh-Hant"]: "鄉村搖滾"
+ $.collections[1].collectionTitle["zh-Hant"]: "黃金&絲綢"
- $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Rockabilly.T_UI_CollectionBanner_Rockabilly"
+ $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_GoldAndSilk.T_UI_CollectionBanner_GoldAndSilk"
- $.collections[1].inclusionVersion: "7.7.0 PTB"
+ $.collections[1].inclusionVersion: "8.5.0"
- $.collections[1].items[]: "AV_outfit_015"
- $.collections[1].items[]: "MS_outfit_014"
- $.collections[1].items[]: "GS_outfit_014"
- $.collections[1].items[]: "MT_outfit_015"
- $.collections[1].items[]: "NK_outfit_014"
- $.collections[1].items[]: "S23_outfit_016"
- $.collections[1].items[]: "S24_outfit_013"
+ $.collections[1].items[]: "Claudette_outfit_010_01"
+ $.collections[1].items[]: "CM_outfit_010_01"
+ $.collections[1].items[]: "Kate_outfit_009_01"
+ $.collections[1].items[]: "Jeff_outfit_008"
+ $.collections[1].items[]: "S23_outfit_012"
+ $.collections[1].items[]: "S24_outfit_011"
+ $.collections[1].items[]: "Killer07_outfit_008_01"
+ $.collections[1].items[]: "Witch_outfit_006_01"
+ $.collections[1].items[]: "MT_outfit_013"
+ $.collections[1].items[]: "JP_outfit_024"
+ $.collections[1].items[]: "TR_outfit_023"
+ $.collections[1].items[]: "K23_outfit_022"
+ $.collections[1].items[]: "US_Outfit_024"
- $.collections[1].sortOrder: "-14"
+ $.collections[1].sortOrder: "-101"
- $.collections[1].updatedDate: "0001-01-01T00:00:00Z"
+ $.collections[1].updatedDate: "2025-03-11T13:55:53.737Z"
- $.collections[2].collectionId: "SpringEnsembles"
+ $.collections[2].collectionId: "Hanami"
- $.collections[2].collectionTitle.de: "Frühlings-Ensembles"
+ $.collections[2].collectionTitle.de: "Hanami "
- $.collections[2].collectionTitle.en: "Spring Ensembles"
+ $.collections[2].collectionTitle.en: "Hanami "
- $.collections[2].collectionTitle.es: "Conjuntos de primavera"
+ $.collections[2].collectionTitle.es: "Hanami "
- $.collections[2].collectionTitle["es-MX"]: "Conjuntos de primavera"
+ $.collections[2].collectionTitle["es-MX"]: "Hanami "
- $.collections[2].collectionTitle.fr: "Ensembles printaniers"
+ $.collections[2].collectionTitle.fr: "Hanami "
- $.collections[2].collectionTitle.it: "Completi primaverili"
+ $.collections[2].collectionTitle.it: "Hanami "
- $.collections[2].collectionTitle.ja: "春のアンサンブル"
+ $.collections[2].collectionTitle.ja: "花見 "
- $.collections[2].collectionTitle.ko: "봄의 조화"
+ $.collections[2].collectionTitle.ko: "벚꽃 축제 "
- $.collections[2].collectionTitle.pl: "Wiosenne stroje"
+ $.collections[2].collectionTitle.pl: "Hanami "
- $.collections[2].collectionTitle["pt-BR"]: "Conjuntos de Primavera"
+ $.collections[2].collectionTitle["pt-BR"]: "Hanami "
- $.collections[2].collectionTitle.ru: "Весенний ансамбль"
+ $.collections[2].collectionTitle.ru: "Ханами "
- $.collections[2].collectionTitle.th: "เครื่องแต่งกายฤดูใบไม้ผลิ"
+ $.collections[2].collectionTitle.th: "ฮานามิ "
- $.collections[2].collectionTitle.tr: "Bahar Kreasyonu"
+ $.collections[2].collectionTitle.tr: "Hanami "
- $.collections[2].collectionTitle["zh-Hans"]: "春日套装"
+ $.collections[2].collectionTitle["zh-Hans"]: "花见 "
- $.collections[2].collectionTitle["zh-Hant"]: "春天靈魂"
+ $.collections[2].collectionTitle["zh-Hant"]: "賞花 "
- $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_SpringEnsembles.T_UI_CollectionBanner_SpringEnsembles"
+ $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_Hanami.T_UI_CollectionBanner_Hanami"
- $.collections[2].items[]: "Ace_outfit_008_01"
- $.collections[2].items[]: "HillBilly_outfit_008_01"
- $.collections[2].items[]: "FM_outfit_011"
- $.collections[2].items[]: "FM_outfit_011_01"
- $.collections[2].items[]: "S28_outfit_011"
- $.collections[2].items[]: "US_outfit_015"
- $.collections[2].items[]: "K21_outfit_010"
- $.collections[2].items[]: "K26_outfit_007"
- $.collections[2].items[]: "GK_outfit_013"
- $.collections[2].items[]: "S29_outfit_008"
+ $.collections[2].items[]: "MS_outfit_016"
+ $.collections[2].items[]: "SwedenSurvivor_outfit_015"
+ $.collections[2].items[]: "HK_outfit_014"
- $.collections[2].sortOrder: "-15"
+ $.collections[2].sortOrder: "-13"
- $.collections[2].updatedDate: "2024-02-20T17:45:49Z"
+ $.collections[2].updatedDate: "2024-02-01T17:19:10Z"
- $.collections[3].collectionId: "PopSuperstar"
+ $.collections[3].collectionId: "Rockabilly"
- $.collections[3].collectionTitle.de: "Superpopstar"
+ $.collections[3].collectionTitle.de: "Rockabilly"
- $.collections[3].collectionTitle.en: "Pop Superstar"
+ $.collections[3].collectionTitle.en: "Rockabilly"
- $.collections[3].collectionTitle.es: "Superestrella del pop"
+ $.collections[3].collectionTitle.es: "Rockabilly"
- $.collections[3].collectionTitle["es-MX"]: "Superestrella del pop"
+ $.collections[3].collectionTitle["es-MX"]: "Rockabilly"
- $.collections[3].collectionTitle.fr: "Superstar de la pop"
+ $.collections[3].collectionTitle.fr: "Rockabilly"
- $.collections[3].collectionTitle.it: "Superstar pop"
+ $.collections[3].collectionTitle.it: "Rockabilly"
- $.collections[3].collectionTitle.ja: "ポップスター"
+ $.collections[3].collectionTitle.ja: "ロカビリー "
- $.collections[3].collectionTitle.ko: "팝 슈퍼스타"
… 2827 more change(s) — see the commit diff for everything
```

### [`contentMetadata.json`](contentMetadata.json)

[Full line-by-line diff](diffs/contentMetadata.json.diff)

```diff
- $.deploymentDate: "2025-02-11 16:05:32Z"
+ $.deploymentDate: "2025-03-18 14:30:59Z"
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[1].MapsWeight.Ecl_Level03_Calamari: "2500"
+ $.schedule[1].MapsWeight.Ecl_Level03_Calamari: "500"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[1].contentVersion: "a376acfc87e5939f7f625755a9f1a39c886334bd"
+ $.entries[1].contentVersion: "c83b395285eedb20d5731ee161c8c95d6694acae"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ResidentEvil_V2.T_UI_CollectionBanner_ResidentEvil_V2"
+ $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_Tome22.T_UI_SpecialPack_Tome22"
- $.entries[1].uri: "images/T_UI_CollectionBanner_ResidentEvil_V2.png"
+ $.entries[1].uri: "images/T_UI_SpecialPack_Tome22.png"
- $.entries[2].contentVersion: "53964bcb15e57ecf8ea8c3fb65b6991aa31f8b12"
+ $.entries[2].contentVersion: "4a8dc6836775f6b633fec22081aeb9b07f45724a"
- $.entries[2].downloadStrategy: "preferPackaged"
+ $.entries[2].downloadStrategy: "preferRemote"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_ResidentEvil_V2.T_UI_SpecialPack_ResidentEvil_V2"
+ $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_IronMaiden.T_UI_SpecialPack_IronMaiden"
- $.entries[2].uri: "images/T_UI_SpecialPack_ResidentEvil_V2.png"
+ $.entries[2].uri: "images/T_UI_SpecialPack_IronMaiden.png"
- $.entries[3].contentVersion: "046cd26cefdc52db4b6e33c63284a66b5f3f45df"
+ $.entries[3].contentVersion: "a376acfc87e5939f7f625755a9f1a39c886334bd"
- $.entries[3].downloadStrategy: "preferPackaged"
+ $.entries[3].downloadStrategy: "preferRemote"
- $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ArtistsFromTheFog_V2.T_UI_CollectionBanner_ArtistsFromTheFog_V2"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ResidentEvil_V2.T_UI_CollectionBanner_ResidentEvil_V2"
- $.entries[3].uri: "images/T_UI_CollectionBanner_ArtistsFromTheFog_V2.png"
+ $.entries[3].uri: "images/T_UI_CollectionBanner_ResidentEvil_V2.png"
- $.entries[4].contentVersion: "67c93987330b11212afe4082b156c42ed073f6fe"
+ $.entries[4].contentVersion: "53964bcb15e57ecf8ea8c3fb65b6991aa31f8b12"
- $.entries[4].enableChecksum: true
+ $.entries[4].enableChecksum: false
- $.entries[4].packagedPath: ""
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_ResidentEvil_V2.T_UI_SpecialPack_ResidentEvil_V2"
- $.entries[4].schema: "s3ver://"
+ $.entries[4].schema: "s3verbin://"
- $.entries[4].uri: "catalog.json"
+ $.entries[4].uri: "images/T_UI_SpecialPack_ResidentEvil_V2.png"
- $.entries[5].contentVersion: "788b6e45e5f6f0f29d5237db487c0666397b6528"
+ $.entries[5].contentVersion: "046cd26cefdc52db4b6e33c63284a66b5f3f45df"
- $.entries[5].downloadStrategy: "preferRemote"
+ $.entries[5].downloadStrategy: "preferPackaged"
- $.entries[5].enableChecksum: true
+ $.entries[5].enableChecksum: false
- $.entries[5].packagedPath: ""
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_ArtistsFromTheFog_V2.T_UI_CollectionBanner_ArtistsFromTheFog_V2"
- $.entries[5].schema: "s3ver://"
+ $.entries[5].schema: "s3verbin://"
- $.entries[5].uri: "bonusPointEventsContent.json"
+ $.entries[5].uri: "images/T_UI_CollectionBanner_ArtistsFromTheFog_V2.png"
- $.entries[6].contentVersion: "6655edc636a0770868614915ae463e2342631a2a"
+ $.entries[6].contentVersion: "6b6cc597f89669c958c0f2180cc08d20d368d896"
- $.entries[6].downloadStrategy: "preferRemote"
+ $.entries[6].downloadStrategy: "preferPackaged"
- $.entries[6].enableChecksum: true
+ $.entries[6].enableChecksum: false
- $.entries[6].packagedPath: ""
+ $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_ArtistsFromTheFog.T_UI_SpecialPack_ArtistsFromTheFog"
- $.entries[6].schema: "s3ver://"
+ $.entries[6].schema: "s3verbin://"
- $.entries[6].uri: "freetoplay/NA/event.json"
+ $.entries[6].uri: "images/T_UI_SpecialPack_ArtistsFromTheFog.png"
- $.entries[7].contentVersion: "6655edc636a0770868614915ae463e2342631a2a"
+ $.entries[7].contentVersion: "0e887f7f4810dad4a46b8d4cbcb4b36b2d2a67c5"
- $.entries[7].downloadStrategy: "preferRemote"
+ $.entries[7].downloadStrategy: "preferPackaged"
- $.entries[7].enableChecksum: true
+ $.entries[7].enableChecksum: false
- $.entries[7].packagedPath: ""
+ $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/T_UI_CollectionBanner_LunarNewYear2025.T_UI_CollectionBanner_LunarNewYear2025"
- $.entries[7].schema: "s3ver://"
+ $.entries[7].schema: "s3verbin://"
- $.entries[7].uri: "freetoplay/EU/event.json"
+ $.entries[7].uri: "images/T_UI_CollectionBanner_LunarNewYear2025.png"
- $.entries[8].contentVersion: "543cd72e4e78a2b2222587d307e0db8cb593e032"
+ $.entries[8].contentVersion: "2982adcbf6304b4510b40e1f62ba09a384b8499c"
- $.entries[8].downloadStrategy: "preferRemote"
+ $.entries[8].downloadStrategy: "preferPackaged"
- $.entries[8].enableChecksum: true
+ $.entries[8].enableChecksum: false
- $.entries[8].packagedPath: ""
+ $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/T_UI_SpecialPack_LunarNewYear2025.T_UI_SpecialPack_LunarNewYear2025"
- $.entries[8].schema: "s3ver://"
+ $.entries[8].schema: "s3verbin://"
- $.entries[8].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[8].uri: "images/T_UI_SpecialPack_LunarNewYear2025.png"
- $.entries[9].contentVersion: "8273e156250160bdcd648b2c30a93a8c51c9f22f"
+ $.entries[9].contentVersion: "40bacfa0cfb91ee0682afcad0b976f0eb8811913"
- $.entries[9].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[9].uri: "catalog.json"
- $.entries[10].contentVersion: "bc3a487e7fd70ceb6c50b76d3ce3cec9260988dd"
+ $.entries[10].contentVersion: "4c08a2553fd3679b8f0847453afaf80ff937d48a"
- $.entries[10].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[10].uri: "bonusPointEventsContent.json"
- $.entries[11].contentVersion: "a408fa0d35cd973148d69b66da450e6061df4e72"
+ $.entries[11].contentVersion: "0c805e05a4d450919eb0559d457340ec1132ee28"
- $.entries[11].uri: "archiveQuests/CalamariV1.json"
+ $.entries[11].uri: "freetoplay/NA/event.json"
- $.entries[12].contentVersion: "71ad6e3e2c1d333a18f5e73e68b8ee4658dbd556"
+ $.entries[12].contentVersion: "0c805e05a4d450919eb0559d457340ec1132ee28"
- $.entries[12].uri: "archiveQuests/CalamariV2.json"
+ $.entries[12].uri: "freetoplay/EU/event.json"
- $.entries[13].contentVersion: "963cf47cc485623f3a1a5965bf8b3299d610c3e2"
+ $.entries[13].contentVersion: "46b10f27c38075004e18952439dcf2335b7f2bae"
- $.entries[13].uri: "archiveQuests/CalamariV3.json"
+ $.entries[13].uri: "archiveQuests/Anniversary2022.json"
- $.entries[14].contentVersion: "407b1d48b0b6d1ffb96f5a1dae5585e019b419cc"
+ $.entries[14].contentVersion: "b30ad432f9321c9eca5072c2e7a8654f45d33913"
- $.entries[14].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[14].uri: "archiveQuests/Anniversary2023.json"
- $.entries[15].contentVersion: "2262e42dcf42eb7387966da10979b40715e1cdf9"
+ $.entries[15].contentVersion: "6598fa9ab37dbce6fb86dd31bae207898e82e8ef"
- $.entries[15].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[15].uri: "archiveQuests/Anniversary2024.json"
- $.entries[16].contentVersion: "6b12ac012f05769e892c082f6518ebd32f610eab"
+ $.entries[16].contentVersion: "d0b0a380642085ccd59643fb0d250f1f96a26972"
- $.entries[16].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[16].uri: "archiveQuests/CalamariV1.json"
- $.entries[17].contentVersion: "80a29841bca62c52e00331de3bc2bb4e20509060"
+ $.entries[17].contentVersion: "4b8b9534c7f1c7dd42e82190a69fd978ce1544b9"
- $.entries[17].uri: "archiveQuests/FireflyV1.json"
+ $.entries[17].uri: "archiveQuests/CalamariV2.json"
- $.entries[18].contentVersion: "7c01b56b768aa030f6ecc2327dd34eb38a2a44a6"
+ $.entries[18].contentVersion: "4416ef4cd4846e4907c0a88c13465b1960734c93"
- $.entries[18].uri: "archiveQuests/Halloween2021.json"
+ $.entries[18].uri: "archiveQuests/CalamariV3.json"
- $.entries[19].contentVersion: "57e4ff1396924d2086371eadec19248faf05ac83"
+ $.entries[19].contentVersion: "6c3e87772d6217628dabd7672d131ddc0a83ee5d"
- $.entries[19].uri: "archiveQuests/Halloween2022.json"
+ $.entries[19].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[20].contentVersion: "5b218ca07d7df70ac32c6e16621c520a04587efe"
+ $.entries[20].contentVersion: "a247517cddce7cfa0f4b81564cbd272166c56361"
- $.entries[20].uri: "archiveQuests/Halloween2023.json"
+ $.entries[20].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[21].contentVersion: "61d0e728f66fa0af60b6faba8a0c27dd7c5e65fb"
+ $.entries[21].contentVersion: "4315f96dae67085847bb72975e6381b1dda3395b"
- $.entries[21].uri: "archiveQuests/Halloween2024.json"
+ $.entries[21].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[22].contentVersion: "c225ca9dbc1a433a739e2f2ec350b6260e5b1a9f"
+ $.entries[22].contentVersion: "1062ef8360209c2da91e037555c8c713ae528320"
- $.entries[22].uri: "archiveQuests/Spring2024.json"
+ $.entries[22].uri: "archiveQuests/FireflyV1.json"
- $.entries[23].contentVersion: "12e1fa2470d5a0812664c0c922fa61a667b09c6f"
+ $.entries[23].contentVersion: "33faa556b13db0569edb9021cb63e7ff86cdb922"
- $.entries[23].uri: "archiveQuests/Summer2023.json"
+ $.entries[23].uri: "archiveQuests/Halloween2021.json"
- $.entries[24].contentVersion: "4f81d96a4a7e8f5c6091bcd265c63303e5f64855"
+ $.entries[24].contentVersion: "ae2d0b9dcb88d278ea4cdfe6826599ccda6e0d2b"
- $.entries[24].uri: "archiveQuests/Tome01.json"
+ $.entries[24].uri: "archiveQuests/Halloween2022.json"
- $.entries[25].contentVersion: "cd3746537274d6874f044b382efaa5fe8333c928"
+ $.entries[25].contentVersion: "ee137fdb9a0f9f905493cff8d8683f27ed17a095"
- $.entries[25].uri: "archiveQuests/Tome02.json"
+ $.entries[25].uri: "archiveQuests/Halloween2023.json"
- $.entries[26].contentVersion: "9847d4aad35952d72c0d3932dfb6283829fc8cac"
+ $.entries[26].contentVersion: "0ed663a9ee71a6934f06e116d596d576381c3f4b"
- $.entries[26].uri: "archiveQuests/Tome03.json"
+ $.entries[26].uri: "archiveQuests/Halloween2024.json"
- $.entries[27].contentVersion: "5d8c114b55ae6821c795376ea6cb488f7f21449d"
+ $.entries[27].contentVersion: "7db83d4d533bdc22db92a9390ccbe20b06a21af4"
- $.entries[27].uri: "archiveQuests/Tome04.json"
+ $.entries[27].uri: "archiveQuests/Spring2024.json"
- $.entries[28].contentVersion: "c657b5e7066a6175ee306b511e9360509594b777"
+ $.entries[28].contentVersion: "3bfe564c7fa1c7df3e1b9a179bf95e906c6ab69d"
- $.entries[28].uri: "archiveQuests/Tome05.json"
+ $.entries[28].uri: "archiveQuests/Summer2023.json"
- $.entries[29].contentVersion: "6f1942f0d4adcf5e663b798ed66148af57df46f4"
+ $.entries[29].contentVersion: "a55a2d271c5bfc01529a7fb8cd1e2b1e34d7b942"
- $.entries[29].uri: "archiveQuests/Tome06.json"
+ $.entries[29].uri: "archiveQuests/Tome01.json"
- $.entries[30].contentVersion: "bbfef48e50487debc04d01d0e3f29e7494e38b5c"
+ $.entries[30].contentVersion: "0997a07b8c444b2edf29a545f49598a3edcaed9b"
- $.entries[30].uri: "archiveQuests/Tome07.json"
+ $.entries[30].uri: "archiveQuests/Tome02.json"
- $.entries[31].contentVersion: "3f501474d90b4734b0e63230770844af65a19ae6"
+ $.entries[31].contentVersion: "73819905307fe0506c6b903a307f6137505aaf6d"
- $.entries[31].uri: "archiveQuests/Tome08.json"
+ $.entries[31].uri: "archiveQuests/Tome03.json"
- $.entries[32].contentVersion: "f387646c722c10de1889a50eeec1f67cdc783ce4"
+ $.entries[32].contentVersion: "b31c09305af6668f8e3775b7661a03b9d51798c6"
- $.entries[32].uri: "archiveQuests/Tome09.json"
+ $.entries[32].uri: "archiveQuests/Tome04.json"
- $.entries[33].contentVersion: "64077f50db4bdfb2cca60ff5bcf9f7cfac62ddf7"
+ $.entries[33].contentVersion: "39f22c4741a8477b9c7c1fca01381a86c25688dc"
- $.entries[33].uri: "archiveQuests/Tome10.json"
+ $.entries[33].uri: "archiveQuests/Tome05.json"
- $.entries[34].contentVersion: "4e4a0b0407317fbc2d8bb6cf0796b00ab996c2c1"
+ $.entries[34].contentVersion: "d3ad12cbc6985f5d53967372283655e7bc17f8ca"
- $.entries[34].uri: "archiveQuests/Tome11.json"
+ $.entries[34].uri: "archiveQuests/Tome06.json"
- $.entries[35].contentVersion: "d7221731d2d834cb3551c160e766ad4cf5f60ee0"
+ $.entries[35].contentVersion: "34ec480819e5e2e141a20efbdb642e89e14a0a66"
- $.entries[35].uri: "archiveQuests/Tome12.json"
+ $.entries[35].uri: "archiveQuests/Tome07.json"
- $.entries[36].contentVersion: "33a105c6dbbba31758c19b359c65e68849976b87"
+ $.entries[36].contentVersion: "b7b2c7a8e828d5c884d45b4da2b3311145465413"
- $.entries[36].uri: "archiveQuests/Tome13.json"
+ $.entries[36].uri: "archiveQuests/Tome08.json"
- $.entries[37].contentVersion: "c14ac1c93887519dab614aad9edac4e1cde894f3"
+ $.entries[37].contentVersion: "ff12a1645d17031b23a0494abccf90e96aef17a4"
- $.entries[37].uri: "archiveQuests/Tome14.json"
+ $.entries[37].uri: "archiveQuests/Tome09.json"
- $.entries[38].contentVersion: "d0c22309377e813e8d7ff1af7104e3a97a672e5d"
+ $.entries[38].contentVersion: "89712dc50fa971c2734f2c30d77fe89a825fede0"
- $.entries[38].uri: "archiveQuests/Tome15.json"
+ $.entries[38].uri: "archiveQuests/Tome10.json"
… 713 more change(s) — see the commit diff for everything
```

### [`ranksThresholds.json`](ranksThresholds.json)

[Full line-by-line diff](diffs/ranksThresholds.json.diff)

```diff
- $.globalData.hourOfReset: 16
+ $.globalData.hourOfReset: 15
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCard[id=HotdogW3]
- $.featuredCharacterRecommendations[0].activeFrom: "2023-09-04T00:00:00Z"
+ $.featuredCharacterRecommendations[0].activeFrom: "2025-03-04T16:00:00Z"
- $.featuredCharacterRecommendations[0].activeTo: "2033-09-04T00:00:00Z"
+ $.featuredCharacterRecommendations[0].activeTo: "2025-04-04T16:00:00Z"
- $.featuredCharacterRecommendations[0].characters[0].characterIndex: "268435465"
+ $.featuredCharacterRecommendations[0].characters[0].characterIndex: "268435480"
- $.featuredCharacterRecommendations[0].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/England/K10_TheNightmare_Portrait.K10_TheNightmare_Portrait"
+ $.featuredCharacterRecommendations[0].characters[0].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gemini/K25_TheCenobite_Portrait.K25_TheCenobite_Portrait"
- $.featuredCharacterRecommendations[0].characters[1].characterIndex: "11"
+ $.featuredCharacterRecommendations[0].characters[1].characterIndex: "268435493"
- $.featuredCharacterRecommendations[0].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/England/S11_QuentinSmith_Portrait.S11_QuentinSmith_Portrait"
+ $.featuredCharacterRecommendations[0].characters[1].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
- $.featuredCharacterRecommendations[0].characters[2].characterIndex: "268435493"
+ $.featuredCharacterRecommendations[0].characters[2].characterIndex: "44"
- $.featuredCharacterRecommendations[0].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/K38_TheHoundmaster_Portrait.K38_TheHoundmaster_Portrait"
+ $.featuredCharacterRecommendations[0].characters[2].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
- $.featuredCharacterRecommendations[0].characters[3].characterIndex: "44"
+ $.featuredCharacterRecommendations[0].characters[3].characterIndex: "268435492"
- $.featuredCharacterRecommendations[0].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gelato/S45_TaurieCain_Portrait.S45_TaurieCain_Portrait"
+ $.featuredCharacterRecommendations[0].characters[3].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
- $.featuredCharacterRecommendations[0].characters[4].characterIndex: "268435492"
+ $.featuredCharacterRecommendations[0].characters[4].characterIndex: "43"
- $.featuredCharacterRecommendations[0].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/K37_TheDracula_Portrait.K37_TheDracula_Portrait"
+ $.featuredCharacterRecommendations[0].characters[4].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
- $.featuredCharacterRecommendations[0].characters[5].characterIndex: "43"
+ $.featuredCharacterRecommendations[0].characters[5].characterIndex: "268435480"
- $.featuredCharacterRecommendations[0].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Eclair/S44_TrevorBelmont_Portrait.S44_TrevorBelmont_Portrait"
+ $.featuredCharacterRecommendations[0].characters[5].image.path: "/Game/UI/UMGAssets/Icons/CharPortraits/Gemini/K25_TheCenobite_Portrait.K25_TheCenobite_Portrait"
+ $.featuredCharacterRecommendations[0].characters[6]
+ $.featuredCharacterRecommendations[0].characters[7]
+ $.featuredCharacterRecommendations[0].characters[8]
+ $.featuredCharacterRecommendations[0].characters[9]
+ $.featuredCharacterRecommendations[0].characters[10]
+ $.featuredCharacterRecommendations[0].characters[11]
+ $.featuredCharacterRecommendations[0].characters[12]
+ $.featuredCharacterRecommendations[0].characters[13]
+ $.featuredCharacterRecommendations[1]
+ $.featuredCharacterRecommendations[2]
- $.featuredCustomizationRecommendations[id=HotdogW3]
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[6].id: "S41_outfit_014"
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[6].id: "S37_outfit_018"
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[6].weight: 13
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[6].weight: 2
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[7].id: "K35_outfit_011"
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[7].id: "S41_outfit_014"
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[7].weight: 12
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[7].weight: 13
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[8].id: "JP_outfit_016"
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[8].id: "K35_outfit_011"
- $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[8].weight: 10
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[8].weight: 12
+ $.featuredCustomizationRecommendations[id=HotdogW2].recommendations[9]
- $.specialsRecommendations[id=ResidentEvil]
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
- $.specialEvents[43].mainEndTime: "2025-02-25T16:00:00"
+ $.specialEvents[43].mainEndTime: "2025-03-04T16:00:00"
- $.specialEvents[43].postEndTime: "2025-02-25T16:00:00"
+ $.specialEvents[43].postEndTime: "2025-03-04T16:00:00"
```

## Could not download

- `images/T_UI_CollectionBanner_ArtistsFromTheFog_V2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_LunarNewYear2025.png (HTTP 404)`
- `images/T_UI_CollectionBanner_ResidentEvil_V2.png (HTTP 404)`
- `images/T_UI_SpecialPack_ArtistsFromTheFog.png (HTTP 404)`
- `images/T_UI_SpecialPack_IronMaiden.png (HTTP 404)`
- `images/T_UI_SpecialPack_LunarNewYear2025.png (HTTP 404)`
- `images/T_UI_SpecialPack_ResidentEvil_V2.png (HTTP 404)`
- `images/T_UI_SpecialPack_Tome22.png (HTTP 404)`
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

