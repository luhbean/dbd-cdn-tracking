# live · 8.3.1_2085946live

| | |
|---|---|
| Build date | 2024-10-22 19:46 UTC |
| CDN version | `8.3.1_2085946live-1729626411` |
| Key | `8.3.1_live` |
| Compared with | [8.2.0_2054297live](../8.2.0_2054297live/CHANGES.md) (2024-10-03 14:48 UTC) |

## Summary

**0** added · **2** modified · **7** removed · 1 unchanged

## Removed files

- `images/T_UI_CollectionBanner_AutumnFashion.png`
- `images/T_UI_CollectionBanner_Castlevania.png`
- `images/T_UI_CollectionBanner_Chucky2.png`
- `images/T_UI_CollectionBanner_Ghostface.png`
- `images/T_UI_SpecialPack_DaysGoneBy.png`
- `images/T_UI_SpecialPack_Dredge.png`
- `images/T_UI_SpecialPack_Firemoon.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.enableConsoleSuspendSave: true
- $.enableLobbyLeaveSave: true
+ $.enableLobbyKickPlayerForCharacterOwnership: false
- $.analytics.autoflushInGameFrequency: 60
+ $.analytics.autoflushInGameFrequency: 3600
- $.enableSimulateMovementOptimization[]: "switch"
+ $.enableSimulateMovementOptimization[]: "Switch"
+ $.enableSimulateMovementOptimization[]: "PS4"
+ $.enableSimulateMovementOptimization[]: "Steam"
+ $.enableSimulateMovementOptimization[]: "WinGDK"
+ $.enableSimulateMovementOptimization[]: "Xbox"
+ $.enableSimulateMovementOptimization[]: "PS5"
+ $.enableSimulateMovementOptimization[]: "Epic"
+ $.enableSimulateMovementOptimization[]: "XSX"
- $.hangTimes[15].stepName: "SetGameLoadedAndReadyToPlay"
+ $.hangTimes[15].stepName: "WaitingForAIInitialization"
- $.hangTimes[16].hardcapTimeout: 210.0
+ $.hangTimes[16].hardcapTimeout: 15.0
- $.hangTimes[16].possibleHangTime: 45.0
+ $.hangTimes[16].possibleHangTime: 5.0
- $.hangTimes[16].stepName: "WaitingForIntroToBeDone"
+ $.hangTimes[16].stepName: "SetGameLoadedAndReadyToPlay"
- $.hangTimes[17].hardcapTimeout: 30.0
+ $.hangTimes[17].hardcapTimeout: 210.0
- $.hangTimes[17].possibleHangTime: 10.0
+ $.hangTimes[17].possibleHangTime: 45.0
- $.hangTimes[17].stepName: "LoadingCompleted"
+ $.hangTimes[17].stepName: "WaitingForIntroToBeDone"
+ $.hangTimes[18]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0]
- $.entries[1]
- $.entries[2]
- $.entries[3]
- $.entries[4]
- $.entries[5]
- $.entries[6]
```

