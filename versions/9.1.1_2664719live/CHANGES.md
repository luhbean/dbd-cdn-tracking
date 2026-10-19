# live · 9.1.1_2664719live

| | |
|---|---|
| Build date | 2025-08-05 18:16 UTC |
| CDN version | `9.1.1_2664719live-1754417804` |
| Key | `9.1.1_live` |
| Compared with | [9.1.1_2664696live](../9.1.1_2664696live/CHANGES.md) (2025-08-05 18:14 UTC) |

## Summary

**0** added · **4** modified · **0** removed · 204 unchanged

## Modified files

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
+ $.ddos.CooloffTime
+ $.ddos.EscalateQuotaBadPacketsPerSec
+ $.ddos.EscalateQuotaDisconnPacketsPerSec
+ $.ddos.EscalateQuotaPacketsPerSec
+ $.ddos.EscalateTimeQuotaMSPerFrame
+ $.ddos.NetConnPacketTimeLimitMSPerFrame
+ $.ddos.PacketLimitPerFrame
+ $.ddos.PacketTimeLimitMSPerFrame
+ $.ddos.SendEscalateAnalytics
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].MapsWeight.Fin_Hideout: "0"
+ $.schedule[0].MapsWeight.Fin_Hideout: "750"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[81].contentVersion: "46a2fc31f88d050f60a9bf752a5ff1bc9ae62adf"
+ $.entries[81].contentVersion: "4afa7b5502378f1ca8f4c65311d465ef2b50c648"
- $.entries[172].contentVersion: "d38cc39e35a5375cef59c70ff7ca3768c6a22954"
+ $.entries[172].contentVersion: "13f85f269589898f5a0c9dd1db219a5a5cc5a907"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
- $.featuredCustomizationRecommendations[id=LasagnaW2].recommendations[id=S41_outfit_011]
- $.featuredCustomizationRecommendations[id=LasagnaW2].recommendations[id=S34_outfit_019]
- $.featuredCustomizationRecommendations[id=LasagnaW2].recommendations[id=GK_outfit_022]
- $.featuredCustomizationRecommendations[id=LasagnaW2].recommendations[id=K23_outfit_023]
+ $.specialsRecommendations[id=CatDay]
```

