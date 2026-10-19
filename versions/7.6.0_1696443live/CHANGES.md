# live · 7.6.0_1696443live

| | |
|---|---|
| Build date | 2024-03-31 15:33 UTC |
| CDN version | `7.6.0_1696443live-1711899232` |
| Key | `7.6.0_live` |
| Compared with | [7.5.1_1652273live](../7.5.1_1652273live/CHANGES.md) (2024-03-11 15:28 UTC) |

## Summary

**0** added · **2** modified · **0** removed · 1 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
+ $.enableContainerAgressiveMemorySaving: false
+ $.enableDSQuestsUpdate: false
+ $.enableLocalStartSnapping: true
+ $.marketing
+ $.seenPopupsConfig
- $.dlc.dlcAdditionalInfo[32].availableStartDate: "2024-01-30T01:00:00"
+ $.dlc.dlcAdditionalInfo[32].availableStartDate: "2023-07-25T01:00:00"
- $.dlc.dlcAdditionalInfo[32].dlcId: "Zodiac"
+ $.dlc.dlcAdditionalInfo[32].dlcId: "Venus"
+ $.dlc.dlcAdditionalInfo[33]
+ $.dlc.dlcAdditionalInfo[34]
- $.enableLobbyLeaveSave: false
+ $.enableLobbyLeaveSave: true
- $.hangTimes[14].hardcapTimeout: 15.0
+ $.hangTimes[14].hardcapTimeout: 30.0
- $.hangTimes[14].possibleHangTime: 5.0
+ $.hangTimes[14].possibleHangTime: 10.0
- $.hangTimes[14].stepName: "SetGameLoadedAndReadyToPlay"
+ $.hangTimes[14].stepName: "WaitingForMutatorsComponentLogic"
- $.hangTimes[15].hardcapTimeout: 210.0
+ $.hangTimes[15].hardcapTimeout: 15.0
- $.hangTimes[15].possibleHangTime: 45.0
+ $.hangTimes[15].possibleHangTime: 5.0
- $.hangTimes[15].stepName: "WaitingForIntroToBeDone"
+ $.hangTimes[15].stepName: "SetGameLoadedAndReadyToPlay"
- $.hangTimes[16].hardcapTimeout: 30.0
+ $.hangTimes[16].hardcapTimeout: 210.0
- $.hangTimes[16].possibleHangTime: 10.0
+ $.hangTimes[16].possibleHangTime: 45.0
- $.hangTimes[16].stepName: "LoadingCompleted"
+ $.hangTimes[16].stepName: "WaitingForIntroToBeDone"
+ $.hangTimes[17]
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
- $.entries[7]
- $.entries[8]
- $.entries[9]
- $.entries[10]
- $.entries[11]
- $.entries[12]
- $.entries[13]
- $.entries[14]
- $.entries[15]
- $.entries[16]
- $.entries[17]
- $.entries[18]
- $.entries[19]
- $.entries[20]
- $.entries[21]
- $.entries[22]
- $.entries[23]
- $.entries[24]
- $.entries[25]
- $.entries[26]
- $.entries[27]
- $.entries[28]
- $.entries[29]
- $.entries[30]
- $.entries[31]
- $.entries[32]
- $.entries[33]
- $.entries[34]
- $.entries[35]
- $.entries[36]
- $.entries[37]
- $.entries[38]
- $.entries[39]
- $.entries[40]
- $.entries[41]
- $.entries[42]
- $.entries[43]
- $.entries[44]
- $.entries[45]
- $.entries[46]
- $.entries[47]
- $.entries[48]
- $.entries[49]
- $.entries[50]
- $.entries[51]
- $.entries[52]
- $.entries[53]
- $.entries[54]
- $.entries[55]
- $.entries[56]
- $.entries[57]
- $.entries[58]
- $.entries[59]
- $.entries[60]
- $.entries[61]
- $.entries[62]
- $.entries[63]
- $.entries[64]
- $.entries[65]
- $.entries[66]
- $.entries[67]
- $.entries[68]
- $.entries[69]
- $.entries[70]
- $.entries[71]
- $.entries[72]
- $.entries[73]
- $.entries[74]
- $.entries[75]
- $.entries[76]
- $.entries[77]
- $.entries[78]
- $.entries[79]
- $.entries[80]
- $.entries[81]
```

