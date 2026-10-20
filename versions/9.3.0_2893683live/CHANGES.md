# live · 9.3.0_2893683live

| | |
|---|---|
| Build date | 2025-12-02 15:55 UTC |
| CDN version | `9.3.0_2893683live-1764690930` |
| Key | `9.3.0_live` |
| Compared with | [9.3.0_2891560live](../9.3.0_2891560live/CHANGES.md) (2025-12-01 16:39 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 201 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_251202]
+ $[id=Recurring_Charm_Bundle_251202]
+ $[id=Recurring_Dev_Bundle_251202]
+ $[id=Recurring_Killer_Bundle_251202]
+ $[id=Recurring_Survivor_Bundle_251202]
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[6].LinkedEventId: "MapShowcase_PTB1"
+ $.schedule[6].LinkedEventId: "MapShowcase_Omelet_01"
- $.schedule[6].MapsWeight.Jnk_GasStation: "1300"
+ $.schedule[6].MapsWeight.Kny_Cottage: "1300"
- $.schedule[7].LinkedEventId: "MapShowcase_PTB2"
+ $.schedule[7].LinkedEventId: "MapShowcase_Omelet_02"
- $.schedule[7].MapsWeight.Jnk_Office: "1300"
+ $.schedule[7].MapsWeight.Glo_Level_01: "1300"
- $.schedule[8]
- $.schedule[9]
- $.schedule[10]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[9].contentVersion: "e1bc7da6272e069372ce49c9c53012e2b61b7cac"
+ $.entries[9].contentVersion: "61463ac27abf4b2e895e2b8e464e0f7054f92055"
- $.entries[169].contentVersion: "202a56493b6effbada0d351bf876f2615d376c95"
+ $.entries[169].contentVersion: "b5fb37bd123a217dbc62c7e89d2d2eebd2bca733"
- $.entries[177].contentVersion: "7205d4fb288b603cccdb19dd6aa3259542b7cdec"
+ $.entries[177].contentVersion: "8f47d045f8772b8863d7e2e65dca178b98e6db47"
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[61]
+ $.specialEvents[62]
+ $.specialEventsData[28].lteData
- $.specialEventsData[28].eventId: "Spring2024"
+ $.specialEventsData[28].eventId: "MapShowcase_Omelet_01"
- $.specialEventsData[28].eventTrackerObjectives[id=main]
- $.specialEventsData[29].eventId: "Spring2025"
+ $.specialEventsData[29].eventId: "MapShowcase_Omelet_02"
- $.specialEventsData[29].eventTrackerObjectives[id=main]
- $.specialEventsData[29].lteData.gameModeQueue: "Spring2025"
+ $.specialEventsData[29].lteData.gameModeQueue: "MapShowcase"
- $.specialEventsData[29].lteData.gameType: "SeasonalEvent_FuelGenerator"
+ $.specialEventsData[29].lteData.gameType: "MapShowcase"
- $.specialEventsData[29].milestoneRewards[0]
- $.specialEventsData[29].milestoneRewards[1]
- $.specialEventsData[29].milestoneRewards[2]
- $.specialEventsData[30].eventId: "Winter2023"
+ $.specialEventsData[30].eventId: "Spring2024"
+ $.specialEventsData[30].eventTrackerObjectives[id=main]
- $.specialEventsData[30].milestoneRewards[0]
- $.specialEventsData[30].milestoneRewards[1]
- $.specialEventsData[30].milestoneRewards[2]
- $.specialEventsData[30].milestoneRewards[3]
- $.specialEventsData[30].milestoneRewards[4]
- $.specialEventsData[31].eventId: "Winter2024"
+ $.specialEventsData[31].eventId: "Spring2025"
- $.specialEventsData[31].eventPeriods[id=Winter2024]
+ $.specialEventsData[31].eventTrackerObjectives[id=main]
- $.specialEventsData[31].lteData.gameModeQueue: "Winter2024"
+ $.specialEventsData[31].lteData.gameModeQueue: "Spring2025"
- $.specialEventsData[31].lteData.gameType: "SeasonalEvent"
+ $.specialEventsData[31].lteData.gameType: "SeasonalEvent_FuelGenerator"
- $.specialEventsData[31].lteData.incentiveBonus: 100.0
+ $.specialEventsData[31].lteData.incentiveBonus: 0.0
- $.specialEventsData[31].milestoneRewards[0].pointsCost: 6
+ $.specialEventsData[31].milestoneRewards[0].pointsCost: 3
- $.specialEventsData[31].milestoneRewards[0].rewards[id=GEL_001]
+ $.specialEventsData[31].milestoneRewards[0].rewards[id=IC_001]
- $.specialEventsData[31].milestoneRewards[1].pointsCost: 12
+ $.specialEventsData[31].milestoneRewards[1].pointsCost: 8
- $.specialEventsData[31].milestoneRewards[1].rewards[id=GE_BDG_08]
+ $.specialEventsData[31].milestoneRewards[1].rewards[id=IC_BDG_03]
- $.specialEventsData[31].milestoneRewards[2].pointsCost: 21
+ $.specialEventsData[31].milestoneRewards[2].pointsCost: 15
- $.specialEventsData[31].milestoneRewards[2].rewards[id=GE_BNR_07]
+ $.specialEventsData[31].milestoneRewards[2].rewards[id=IC_BNR_03]
- $.specialEventsData[32].lteData
- $.specialEventsData[32].eventId: "Winter2025"
+ $.specialEventsData[32].eventId: "Winter2023"
+ $.specialEventsData[32].milestoneRewards[0]
+ $.specialEventsData[32].milestoneRewards[1]
+ $.specialEventsData[32].milestoneRewards[2]
+ $.specialEventsData[32].milestoneRewards[3]
+ $.specialEventsData[32].milestoneRewards[4]
+ $.specialEventsData[33]
+ $.specialEventsData[34]
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

