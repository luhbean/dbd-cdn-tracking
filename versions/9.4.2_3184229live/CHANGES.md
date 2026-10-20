# live · 9.4.2_3184229live

| | |
|---|---|
| Build date | 2026-03-16 13:40 UTC |
| CDN version | `9.4.2_3184229live-1773668451` |
| Key | `9.4.2_live` |
| Compared with | [9.5.0_3177946live](../9.5.0_3177946live/CHANGES.md) (2026-03-12 13:45 UTC) |

## Summary

**3** added · **75** modified · **9** removed · 133 unchanged

## New or updated images

<a href="images/T_UI_CollectionBanner_EldritchNightmares.png"><img src="images/T_UI_CollectionBanner_EldritchNightmares.png" alt="T_UI_CollectionBanner_EldritchNightmares.png" width="240"></a>
<a href="images/T_UI_SpecialPack_EldritchNightmares.png"><img src="images/T_UI_SpecialPack_EldritchNightmares.png" alt="T_UI_SpecialPack_EldritchNightmares.png" width="240"></a>
<a href="images/T_UI_SpecialPack_ModernTales.png"><img src="images/T_UI_SpecialPack_ModernTales.png" alt="T_UI_SpecialPack_ModernTales.png" width="240"></a>

## Removed files

- `images/T_UI_ChapterBundle_AllKillComeback.png`
- `images/T_UI_CollectionBanner_AllKillComeback.png`
- `images/T_UI_CollectionBanner_Bloodmoon_Quiche.png`
- `images/T_UI_SpecialPack_AllKillComeback.png`
- `images/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.png`
- `images/T_UI_SpecialPack_Bloodmoon_Bundle.png`
- `images/T_UI_SpecialPack_Bloodmoon_Quiche.png`
- `images/T_UI_SpecialPack_EntombedRemains.png`
- `images/T_UI_SpecialPack_MiNABundle.png`

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.BHVRDynamicContent
- $.RTMHandshakeTimeoutThreshold: -1.0
- $.analyticsEndpoints
- $.analyticsPayloadSizeLimit: "102400"
- $.appsflyerCustomerIdEnabled: "false"
- $.assetManagementCdnPath: "https://cdn.live.bhvrdbd.com"
- $.banReasonEnum: "{\"0\":\"Harassment\",\"1\":\"Griefing\",\"2\":\"Exploits\",\"3\":\"Unsportsmanlike\"}"
- $.buttonSequenceEnable
- $.cancelMatchOnDisconnectDuringLoading: "true"
- $.cdnRootFolderPath: "4fabea45-bce0-4461-8950-162659636437"
- $.dbdUsingLootTables: "false"
- $.ddosDetection: "true"
- $.ddosDetectionAnalytics: "true"
- $.disableBloodlust: "false"
- $.displayRankOnTally: "false"
- $.enablePerkDescriptionOverhaul: true
- $.enableRtmValidationOnBoot: "true"
- $.enabledGPUBreadcrumbsHardware
- $.frameHikeAnalyticLogBufferSize: "5"
- $.frameHikeThreshold: "10"
- $.gameClientVersionCheckEnabled: "true"
- $.gameliftEndpoints
- $.gameliftIdleInstanceShutdownTimer: "86400"
- $.gameliftInstanceShutdownTimer: "7200"
- $.krakenRequestAnalyticsLevel: "NetworkError"
- $.krakenRsaPublicKey: "MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAuq878RHxy7gwEGnjh/vXcOH+1evTjEA9ygzmKEmG4s2xfNTXgneht6IsCSt5rGgpB3SabgdfUlfZyNNcwx18H7PGdsEwDcbrpZvNsgVt12oSXANjUaW…
- $.matchmakingAllowCrossplay: "true"
- $.matchmakingIncentiveConfig
- $.matchmakingUseQueueApi: "true"
- $.maxMessagesPerSecondConfig: "3"
- $.msEndpoint: "https://xbox1-live2.bhvrdbd.com/restservice.svc"
- $.msEndpointGrdk: "https://wstore-live2.bhvrdbd.com/restservice.svc"
- $.netconnectionClampToAverageFramerate: "true"
- $.networkFenceAnalyticsBufferSize: "30"
- $.penaltySecondsConfig: "10"
- $.prepareToMessageSecondsConfig: "2"
- $.purchaseExtraTimePremiumBundle: "12"
- $.readOnlyConfigs
- $.recommendationRecentReleaseThreshold: "7"
- $.richPresencePlayerTimerRate: "830"
- $.richPresenceServerTimerRate: "0"
- $.segmentationV2Enabled: "true"
- $.socialPlatformFriendlistQueryRate: "10"
- $.DSProviderOnShutdownNotificationDelay: 15.0
+ $.DSProviderOnShutdownNotificationDelay: 90.0
- $.RTMTimeoutThreshold: 30.0
+ $.RTMTimeoutThreshold: -1.0
+ $.dynamicContent.DynamicContentKillswitchPlatforms[]: "switch"
- $.enableAlwaysSendCrashWithUI: false
+ $.enableAlwaysSendCrashWithUI: true
```

### [`GameConfigsDS.json`](GameConfigsDS.json)

[Full line-by-line diff](diffs/GameConfigsDS.json.diff)

```diff
- $.ddosCalamari
- $.ddos.EscalateQuotaBadPacketsPerSec[]: 25
- $.ddos.EscalateQuotaBadPacketsPerSec[]: 500
+ $.ddos.EscalateQuotaBadPacketsPerSec[]: 50
+ $.ddos.EscalateQuotaBadPacketsPerSec[]: 1000
- $.ddos.EscalateQuotaDisconnPacketsPerSec[]: 2000
+ $.ddos.EscalateQuotaDisconnPacketsPerSec[]: 4000
- $.ddos.EscalateQuotaPacketsPerSec[]: 300
- $.ddos.EscalateQuotaPacketsPerSec[]: 700
+ $.ddos.EscalateQuotaPacketsPerSec[]: 600
+ $.ddos.EscalateQuotaPacketsPerSec[]: 1400
- $.ddos.EscalateTimeQuotaMSPerFrame[]: 10
- $.ddos.EscalateTimeQuotaMSPerFrame[]: 50
- $.ddos.EscalateTimeQuotaMSPerFrame[]: 66
+ $.ddos.EscalateTimeQuotaMSPerFrame[]: 20
+ $.ddos.EscalateTimeQuotaMSPerFrame[]: 100
+ $.ddos.EscalateTimeQuotaMSPerFrame[]: 132
- $.ddos.NetConnPacketTimeLimitMSPerFrame[]: 50
+ $.ddos.NetConnPacketTimeLimitMSPerFrame[]: 200
- $.ddos.PacketLimitPerFrame[]: 100
+ $.ddos.PacketLimitPerFrame[]: 200
- $.ddos.PacketTimeLimitMSPerFrame[]: 16
- $.ddos.PacketTimeLimitMSPerFrame[]: 2
+ $.ddos.PacketTimeLimitMSPerFrame[]: 32
+ $.ddos.PacketTimeLimitMSPerFrame[]: 4
```

### [`archiveJournals/archiveS3Journals.json`](archiveJournals/archiveS3Journals.json)

[Full line-by-line diff](diffs/archiveJournals/archiveS3Journals.json.diff)

```diff
- $.TOME24
- $.TOME23.startDateInMs: 1747077518
+ $.TOME23.startDateInMs: 1747077518000
- $.TOME23.vignettes[id=TOME23_01].entries[0].startDateInMs: 1758636040
+ $.TOME23.vignettes[id=TOME23_01].entries[0].startDateInMs: 1758636040000
- $.TOME23.vignettes[id=TOME23_01].entries[1].startDateInMs: 1759240840
+ $.TOME23.vignettes[id=TOME23_01].entries[1].startDateInMs: 1759240840000
- $.TOME23.vignettes[id=TOME23_01].entries[2].startDateInMs: 1759845640
+ $.TOME23.vignettes[id=TOME23_01].entries[2].startDateInMs: 1759845640000
- $.TOME23.vignettes[id=TOME23_01].entries[3].startDateInMs: 1760450440
+ $.TOME23.vignettes[id=TOME23_01].entries[3].startDateInMs: 1760450440000
- $.TOME23.vignettes[id=TOME23_01].entries[4].startDateInMs: 1761055240
+ $.TOME23.vignettes[id=TOME23_01].entries[4].startDateInMs: 1761055240000
- $.TOME23.vignettes[id=TOME23_01].entries[5].startDateInMs: 1761660040
+ $.TOME23.vignettes[id=TOME23_01].entries[5].startDateInMs: 1761660040000
- $.TOME23.vignettes[id=TOME23_01].entries[6].startDateInMs: 1762268440
+ $.TOME23.vignettes[id=TOME23_01].entries[6].startDateInMs: 1762268440000
- $.TOME23.vignettes[id=TOME23_01].entries[7].startDateInMs: 1762873240
+ $.TOME23.vignettes[id=TOME23_01].entries[7].startDateInMs: 1762873240000
- $.TOME23.vignettes[id=TOME23_01].entries[8].startDateInMs: 1763478040
+ $.TOME23.vignettes[id=TOME23_01].entries[8].startDateInMs: 1763478040000
- $.TOME23.vignettes[id=TOME23_01].entries[9].startDateInMs: 1764082840
+ $.TOME23.vignettes[id=TOME23_01].entries[9].startDateInMs: 1764082840000
- $.TOME23.vignettes[id=TOME23_01].startDateInMs: 1758636040
+ $.TOME23.vignettes[id=TOME23_01].startDateInMs: 1758636040000
- $.TOME23.vignettes[id=TOME23_02].entries[0].startDateInMs: 1764687640
+ $.TOME23.vignettes[id=TOME23_02].entries[0].startDateInMs: 1764687640000
- $.TOME23.vignettes[id=TOME23_02].entries[1].startDateInMs: 1765292440
+ $.TOME23.vignettes[id=TOME23_02].entries[1].startDateInMs: 1765292440000
- $.TOME23.vignettes[id=TOME23_02].entries[2].startDateInMs: 1765897240
+ $.TOME23.vignettes[id=TOME23_02].entries[2].startDateInMs: 1765897240000
- $.TOME23.vignettes[id=TOME23_02].entries[3].startDateInMs: 1766502040
+ $.TOME23.vignettes[id=TOME23_02].entries[3].startDateInMs: 1766502040000
- $.TOME23.vignettes[id=TOME23_02].entries[4].startDateInMs: 1767106840
+ $.TOME23.vignettes[id=TOME23_02].entries[4].startDateInMs: 1767106840000
- $.TOME23.vignettes[id=TOME23_02].entries[5].startDateInMs: 1767711640
+ $.TOME23.vignettes[id=TOME23_02].entries[5].startDateInMs: 1767711640000
- $.TOME23.vignettes[id=TOME23_02].entries[6].startDateInMs: 1768316440
+ $.TOME23.vignettes[id=TOME23_02].entries[6].startDateInMs: 1768316440000
- $.TOME23.vignettes[id=TOME23_02].entries[7].startDateInMs: 1768921240
+ $.TOME23.vignettes[id=TOME23_02].entries[7].startDateInMs: 1768921240000
- $.TOME23.vignettes[id=TOME23_02].entries[8].startDateInMs: 1769526040
+ $.TOME23.vignettes[id=TOME23_02].entries[8].startDateInMs: 1769526040000
- $.TOME23.vignettes[id=TOME23_02].entries[9].startDateInMs: 1770130840
+ $.TOME23.vignettes[id=TOME23_02].entries[9].startDateInMs: 1770130840000
- $.TOME23.vignettes[id=TOME23_02].startDateInMs: 1764687640
+ $.TOME23.vignettes[id=TOME23_02].startDateInMs: 1764687640000
- $.TOME23.vignettes[id=TOME23_03].entries[0].startDateInMs: 1770735640
+ $.TOME23.vignettes[id=TOME23_03].entries[0].startDateInMs: 1770735640000
- $.TOME23.vignettes[id=TOME23_03].entries[1].startDateInMs: 1771340440
+ $.TOME23.vignettes[id=TOME23_03].entries[1].startDateInMs: 1771340440000
- $.TOME23.vignettes[id=TOME23_03].entries[2].startDateInMs: 1771945240
+ $.TOME23.vignettes[id=TOME23_03].entries[2].startDateInMs: 1771945240000
- $.TOME23.vignettes[id=TOME23_03].entries[3].startDateInMs: 1772550040
+ $.TOME23.vignettes[id=TOME23_03].entries[3].startDateInMs: 1772550040000
- $.TOME23.vignettes[id=TOME23_03].entries[4].startDateInMs: 1773154840
+ $.TOME23.vignettes[id=TOME23_03].entries[4].startDateInMs: 1773154840000
- $.TOME23.vignettes[id=TOME23_03].entries[5]
- $.TOME23.vignettes[id=TOME23_03].startDateInMs: 1770735640
+ $.TOME23.vignettes[id=TOME23_03].startDateInMs: 1770735640000
```

### [`archiveJournals/storyJournals.json`](archiveJournals/storyJournals.json)

[Full line-by-line diff](diffs/archiveJournals/storyJournals.json.diff)

```diff
- $.TOME24
```

### [`archiveQuests/Anniversary2022.json`](archiveQuests/Anniversary2022.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2022.json.diff)

```diff
- $.Anniversary2022.level[0].startDateInMs: 1655393400
+ $.Anniversary2022.level[0].startDateInMs: 1655393400000
- $.Anniversary2022.level[1].startDateInMs: 1655998200
+ $.Anniversary2022.level[1].startDateInMs: 1655998200000
```

### [`archiveQuests/Anniversary2023.json`](archiveQuests/Anniversary2023.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2023.json.diff)

```diff
- $.Anniversary2023.level[0].startDateInMs: 1687446000
+ $.Anniversary2023.level[0].startDateInMs: 1687446000000
- $.Anniversary2023.level[1].startDateInMs: 1688050800
+ $.Anniversary2023.level[1].startDateInMs: 1688050800000
```

### [`archiveQuests/Anniversary2024.json`](archiveQuests/Anniversary2024.json)

[Full line-by-line diff](diffs/archiveQuests/Anniversary2024.json.diff)

```diff
- $.Anniversary2024.level[0].startDateInMs: 1718290800
+ $.Anniversary2024.level[0].startDateInMs: 1718290800000
- $.Anniversary2024.level[1].startDateInMs: 1718895600
+ $.Anniversary2024.level[1].startDateInMs: 1718895600000
- $.Anniversary2024.level[2].startDateInMs: 1719500400
+ $.Anniversary2024.level[2].startDateInMs: 1719500400000
```

### [`archiveQuests/CalamariV1.json`](archiveQuests/CalamariV1.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV1.json.diff)

```diff
- $.CalamariV1.level[0].startDateInMs: 1721919600
+ $.CalamariV1.level[0].startDateInMs: 1721919600000
- $.CalamariV1.level[1].startDateInMs: 1722524400
+ $.CalamariV1.level[1].startDateInMs: 1722524400000
```

### [`archiveQuests/CalamariV2.json`](archiveQuests/CalamariV2.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV2.json.diff)

```diff
- $.CalamariV2.level[0].startDateInMs: 1731427200
+ $.CalamariV2.level[0].startDateInMs: 1731427200000
- $.CalamariV2.level[1].startDateInMs: 1732032000
+ $.CalamariV2.level[1].startDateInMs: 1732032000000
```

### [`archiveQuests/CalamariV3.json`](archiveQuests/CalamariV3.json)

[Full line-by-line diff](diffs/archiveQuests/CalamariV3.json.diff)

```diff
- $.CalamariV3.level[0].startDateInMs: 1738771200
+ $.CalamariV3.level[0].startDateInMs: 1738771200000
- $.CalamariV3.level[1].startDateInMs: 1739980800
+ $.CalamariV3.level[1].startDateInMs: 1739980800000
```

### [`archiveQuests/ChocolateBoxGelato.json`](archiveQuests/ChocolateBoxGelato.json)

[Full line-by-line diff](diffs/archiveQuests/ChocolateBoxGelato.json.diff)

```diff
- $.ChocolateBoxGelato.level[0].startDateInMs: 1737043200
+ $.ChocolateBoxGelato.level[0].startDateInMs: 1737043200000
- $.ChocolateBoxGelato.level[1].startDateInMs: 1737648000
+ $.ChocolateBoxGelato.level[1].startDateInMs: 1737648000000
```

### [`archiveQuests/ChocolateBoxV1.json`](archiveQuests/ChocolateBoxV1.json)

[Full line-by-line diff](diffs/archiveQuests/ChocolateBoxV1.json.diff)

```diff
- $.ChocolateBoxV1.level[0].startDateInMs: 1714662000
+ $.ChocolateBoxV1.level[0].startDateInMs: 1714662000000
```

### [`archiveQuests/DreadByDaylightZodiac.json`](archiveQuests/DreadByDaylightZodiac.json)

[Full line-by-line diff](diffs/archiveQuests/DreadByDaylightZodiac.json.diff)

```diff
- $.DreadByDaylightZodiac.level[0].startDateInMs: 1707321600
+ $.DreadByDaylightZodiac.level[0].startDateInMs: 1707321600000
```

### [`archiveQuests/FireflyV1.json`](archiveQuests/FireflyV1.json)

[Full line-by-line diff](diffs/archiveQuests/FireflyV1.json.diff)

```diff
- $.FireflyV1.level[0].startDateInMs: 1726153200
+ $.FireflyV1.level[0].startDateInMs: 1726153200000
```

### [`archiveQuests/Halloween2021.json`](archiveQuests/Halloween2021.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2021.json.diff)

```diff
- $.Halloween2021.level[0].startDateInMs: 1634828400
+ $.Halloween2021.level[0].startDateInMs: 1634828400000
- $.Halloween2021.level[1].startDateInMs: 1635433200
+ $.Halloween2021.level[1].startDateInMs: 1635433200000
```

### [`archiveQuests/Halloween2022.json`](archiveQuests/Halloween2022.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2022.json.diff)

```diff
- $.Halloween2022.level[0].startDateInMs: 1665673200
+ $.Halloween2022.level[0].startDateInMs: 1665673200000
- $.Halloween2022.level[1].startDateInMs: 1666278000
+ $.Halloween2022.level[1].startDateInMs: 1666278000000
```

### [`archiveQuests/Halloween2023.json`](archiveQuests/Halloween2023.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2023.json.diff)

```diff
- $.Halloween2023.level[0].startDateInMs: 1697652000
+ $.Halloween2023.level[0].startDateInMs: 1697652000000
- $.Halloween2023.level[1].startDateInMs: 1698256800
+ $.Halloween2023.level[1].startDateInMs: 1698256800000
```

### [`archiveQuests/Halloween2024.json`](archiveQuests/Halloween2024.json)

[Full line-by-line diff](diffs/archiveQuests/Halloween2024.json.diff)

```diff
- $.Halloween2024.level[0].startDateInMs: 1729177200
+ $.Halloween2024.level[0].startDateInMs: 1729177200000
- $.Halloween2024.level[1].startDateInMs: 1729782000
+ $.Halloween2024.level[1].startDateInMs: 1729782000000
- $.Halloween2024.level[2].startDateInMs: 1730386800
+ $.Halloween2024.level[2].startDateInMs: 1730386800000
```

### [`archiveQuests/Spring2024.json`](archiveQuests/Spring2024.json)

[Full line-by-line diff](diffs/archiveQuests/Spring2024.json.diff)

```diff
- $.Spring2024.level[0].startDateInMs: 1710774000
+ $.Spring2024.level[0].startDateInMs: 1710774000000
- $.Spring2024.level[1].startDateInMs: 1711378800
+ $.Spring2024.level[1].startDateInMs: 1711378800000
```

### [`archiveQuests/Spring2025.json`](archiveQuests/Spring2025.json)

[Full line-by-line diff](diffs/archiveQuests/Spring2025.json.diff)

```diff
- $.Spring2025.level[0].startDateInMs: 1744038000
+ $.Spring2025.level[0].startDateInMs: 1744038000000
- $.Spring2025.level[1].startDateInMs: 1744642800
+ $.Spring2025.level[1].startDateInMs: 1744642800000
- $.Spring2025.level[2].startDateInMs: 1745247600
+ $.Spring2025.level[2].startDateInMs: 1745247600000
```

### [`archiveQuests/Summer2023.json`](archiveQuests/Summer2023.json)

[Full line-by-line diff](diffs/archiveQuests/Summer2023.json.diff)

```diff
- $.Summer2023.level[0].startDateInMs: 1691074800
+ $.Summer2023.level[0].startDateInMs: 1691074800000
- $.Summer2023.level[1].startDateInMs: 1691679600
+ $.Summer2023.level[1].startDateInMs: 1691679600000
```

### [`archiveQuests/Tome01.json`](archiveQuests/Tome01.json)

[Full line-by-line diff](diffs/archiveQuests/Tome01.json.diff)

```diff
- $.Tome01.level[0].startDateInMs: 1572307200
+ $.Tome01.level[0].startDateInMs: 1572307200000
- $.Tome01.level[1].startDateInMs: 1573660800
+ $.Tome01.level[1].startDateInMs: 1573660800000
- $.Tome01.level[2].startDateInMs: 1574870400
+ $.Tome01.level[2].startDateInMs: 1574870400000
- $.Tome01.level[3].startDateInMs: 1576684800
+ $.Tome01.level[3].startDateInMs: 1576684800000
```

### [`archiveQuests/Tome02.json`](archiveQuests/Tome02.json)

[Full line-by-line diff](diffs/archiveQuests/Tome02.json.diff)

```diff
- $.Tome02.level[0].startDateInMs: 1579708800
+ $.Tome02.level[0].startDateInMs: 1579708800000
- $.Tome02.level[1].startDateInMs: 1580832000
+ $.Tome02.level[1].startDateInMs: 1580832000000
- $.Tome02.level[2].startDateInMs: 1581955200
+ $.Tome02.level[2].startDateInMs: 1581955200000
- $.Tome02.level[3].startDateInMs: 1583766000
+ $.Tome02.level[3].startDateInMs: 1583766000000
```

### [`archiveQuests/Tome03.json`](archiveQuests/Tome03.json)

[Full line-by-line diff](diffs/archiveQuests/Tome03.json.diff)

```diff
- $.Tome03.level[0].startDateInMs: 1588172400
+ $.Tome03.level[0].startDateInMs: 1588172400000
- $.Tome03.level[1].startDateInMs: 1589382000
+ $.Tome03.level[1].startDateInMs: 1589382000000
- $.Tome03.level[2].startDateInMs: 1590591600
+ $.Tome03.level[2].startDateInMs: 1590591600000
- $.Tome03.level[3].startDateInMs: 1592406000
+ $.Tome03.level[3].startDateInMs: 1592406000000
```

### [`archiveQuests/Tome04.json`](archiveQuests/Tome04.json)

[Full line-by-line diff](diffs/archiveQuests/Tome04.json.diff)

```diff
- $.Tome04.level[0].startDateInMs: 1596034800
+ $.Tome04.level[0].startDateInMs: 1596034800000
- $.Tome04.level[1].startDateInMs: 1597244400
+ $.Tome04.level[1].startDateInMs: 1597244400000
- $.Tome04.level[2].startDateInMs: 1598454000
+ $.Tome04.level[2].startDateInMs: 1598454000000
- $.Tome04.level[3].startDateInMs: 1600268400
+ $.Tome04.level[3].startDateInMs: 1600268400000
```

### [`archiveQuests/Tome05.json`](archiveQuests/Tome05.json)

[Full line-by-line diff](diffs/archiveQuests/Tome05.json.diff)

```diff
- $.Tome05.level[0].startDateInMs: 1603292400
+ $.Tome05.level[0].startDateInMs: 1603292400000
- $.Tome05.level[1].startDateInMs: 1604505600
+ $.Tome05.level[1].startDateInMs: 1604505600000
- $.Tome05.level[2].startDateInMs: 1605715200
+ $.Tome05.level[2].startDateInMs: 1605715200000
- $.Tome05.level[3].startDateInMs: 1607529600
+ $.Tome05.level[3].startDateInMs: 1607529600000
```

### [`archiveQuests/Tome06.json`](archiveQuests/Tome06.json)

[Full line-by-line diff](diffs/archiveQuests/Tome06.json.diff)

```diff
- $.Tome06.level[0].startDateInMs: 1612972800
+ $.Tome06.level[0].startDateInMs: 1612972800000
- $.Tome06.level[1].startDateInMs: 1614182400
+ $.Tome06.level[1].startDateInMs: 1614182400000
- $.Tome06.level[2].startDateInMs: 1615392000
+ $.Tome06.level[2].startDateInMs: 1615392000000
- $.Tome06.level[3].startDateInMs: 1617202800
+ $.Tome06.level[3].startDateInMs: 1617202800000
```

### [`archiveQuests/Tome07.json`](archiveQuests/Tome07.json)

[Full line-by-line diff](diffs/archiveQuests/Tome07.json.diff)

```diff
- $.Tome07.level[0].startDateInMs: 1620226800
+ $.Tome07.level[0].startDateInMs: 1620226800000
- $.Tome07.level[1].startDateInMs: 1621436400
+ $.Tome07.level[1].startDateInMs: 1621436400000
- $.Tome07.level[2].startDateInMs: 1622646000
+ $.Tome07.level[2].startDateInMs: 1622646000000
- $.Tome07.level[3].startDateInMs: 1624460400
+ $.Tome07.level[3].startDateInMs: 1624460400000
```

### [`archiveQuests/Tome08.json`](archiveQuests/Tome08.json)

[Full line-by-line diff](diffs/archiveQuests/Tome08.json.diff)

```diff
- $.Tome08.level[0].startDateInMs: 1627484400
+ $.Tome08.level[0].startDateInMs: 1627484400000
- $.Tome08.level[1].startDateInMs: 1628694000
+ $.Tome08.level[1].startDateInMs: 1628694000000
- $.Tome08.level[2].startDateInMs: 1629903600
+ $.Tome08.level[2].startDateInMs: 1629903600000
- $.Tome08.level[3].startDateInMs: 1631718000
+ $.Tome08.level[3].startDateInMs: 1631718000000
```

### [`archiveQuests/Tome09.json`](archiveQuests/Tome09.json)

[Full line-by-line diff](diffs/archiveQuests/Tome09.json.diff)

```diff
- $.Tome09.level[0].startDateInMs: 1634742000
+ $.Tome09.level[0].startDateInMs: 1634742000000
- $.Tome09.level[1].startDateInMs: 1635951600
+ $.Tome09.level[1].startDateInMs: 1635951600000
- $.Tome09.level[2].startDateInMs: 1637164800
+ $.Tome09.level[2].startDateInMs: 1637164800000
- $.Tome09.level[3].startDateInMs: 1638979200
+ $.Tome09.level[3].startDateInMs: 1638979200000
```

### [`archiveQuests/Tome10.json`](archiveQuests/Tome10.json)

[Full line-by-line diff](diffs/archiveQuests/Tome10.json.diff)

```diff
- $.Tome10.level[0].startDateInMs: 1643212800
+ $.Tome10.level[0].startDateInMs: 1643212800000
- $.Tome10.level[1].startDateInMs: 1644422400
+ $.Tome10.level[1].startDateInMs: 1644422400000
- $.Tome10.level[2].startDateInMs: 1645632000
+ $.Tome10.level[2].startDateInMs: 1645632000000
- $.Tome10.level[3].startDateInMs: 1647442800
+ $.Tome10.level[3].startDateInMs: 1647442800000
```

### [`archiveQuests/Tome11.json`](archiveQuests/Tome11.json)

[Full line-by-line diff](diffs/archiveQuests/Tome11.json.diff)

```diff
- $.Tome11.level[0].startDateInMs: 1651158000
+ $.Tome11.level[0].startDateInMs: 1651158000000
- $.Tome11.level[1].startDateInMs: 1652281200
+ $.Tome11.level[1].startDateInMs: 1652281200000
- $.Tome11.level[2].startDateInMs: 1653490800
+ $.Tome11.level[2].startDateInMs: 1653490800000
- $.Tome11.level[3].startDateInMs: 1655305200
+ $.Tome11.level[3].startDateInMs: 1655305200000
```

### [`archiveQuests/Tome12.json`](archiveQuests/Tome12.json)

[Full line-by-line diff](diffs/archiveQuests/Tome12.json.diff)

```diff
- $.Tome12.level[0].startDateInMs: 1658329200
+ $.Tome12.level[0].startDateInMs: 1658329200000
- $.Tome12.level[1].startDateInMs: 1659538800
+ $.Tome12.level[1].startDateInMs: 1659538800000
- $.Tome12.level[2].startDateInMs: 1660748400
+ $.Tome12.level[2].startDateInMs: 1660748400000
- $.Tome12.level[3].startDateInMs: 1662562800
+ $.Tome12.level[3].startDateInMs: 1662562800000
```

### [`archiveQuests/Tome13.json`](archiveQuests/Tome13.json)

[Full line-by-line diff](diffs/archiveQuests/Tome13.json.diff)

```diff
- $.Tome13.level[0].startDateInMs: 1665586800
+ $.Tome13.level[0].startDateInMs: 1665586800000
- $.Tome13.level[1].startDateInMs: 1666796400
+ $.Tome13.level[1].startDateInMs: 1666796400000
- $.Tome13.level[2].startDateInMs: 1668009600
+ $.Tome13.level[2].startDateInMs: 1668009600000
- $.Tome13.level[3].startDateInMs: 1669824000
+ $.Tome13.level[3].startDateInMs: 1669824000000
```

### [`archiveQuests/Tome14.json`](archiveQuests/Tome14.json)

[Full line-by-line diff](diffs/archiveQuests/Tome14.json.diff)

```diff
- $.Tome14.level[0].startDateInMs: 1674662400
+ $.Tome14.level[0].startDateInMs: 1674662400000
- $.Tome14.level[1].startDateInMs: 1675872000
+ $.Tome14.level[1].startDateInMs: 1675872000000
- $.Tome14.level[2].startDateInMs: 1677081600
+ $.Tome14.level[2].startDateInMs: 1677081600000
- $.Tome14.level[3].startDateInMs: 1678892400
+ $.Tome14.level[3].startDateInMs: 1678892400000
```

### [`archiveQuests/Tome15.json`](archiveQuests/Tome15.json)

[Full line-by-line diff](diffs/archiveQuests/Tome15.json.diff)

```diff
- $.Tome15.level[0].startDateInMs: 1681916400
+ $.Tome15.level[0].startDateInMs: 1681916400000
- $.Tome15.level[1].startDateInMs: 1683126000
+ $.Tome15.level[1].startDateInMs: 1683126000000
- $.Tome15.level[2].startDateInMs: 1684335600
+ $.Tome15.level[2].startDateInMs: 1684335600000
- $.Tome15.level[3].startDateInMs: 1686150000
+ $.Tome15.level[3].startDateInMs: 1686150000000
```

### [`archiveQuests/Tome16.json`](archiveQuests/Tome16.json)

[Full line-by-line diff](diffs/archiveQuests/Tome16.json.diff)

```diff
- $.Tome16.level[0].startDateInMs: 1690383600
+ $.Tome16.level[0].startDateInMs: 1690383600000
- $.Tome16.level[1].startDateInMs: 1691593200
+ $.Tome16.level[1].startDateInMs: 1691593200000
- $.Tome16.level[2].startDateInMs: 1692802800
+ $.Tome16.level[2].startDateInMs: 1692802800000
- $.Tome16.level[3].startDateInMs: 1694617200
+ $.Tome16.level[3].startDateInMs: 1694617200000
```

### [`archiveQuests/Tome17.json`](archiveQuests/Tome17.json)

[Full line-by-line diff](diffs/archiveQuests/Tome17.json.diff)

```diff
- $.Tome17.level[0].startDateInMs: 1697036400
+ $.Tome17.level[0].startDateInMs: 1697036400000
- $.Tome17.level[1].startDateInMs: 1698246000
+ $.Tome17.level[1].startDateInMs: 1698246000000
- $.Tome17.level[2].startDateInMs: 1699455600
+ $.Tome17.level[2].startDateInMs: 1699455600000
- $.Tome17.level[3].startDateInMs: 1701270000
+ $.Tome17.level[3].startDateInMs: 1701270000000
```

### [`archiveQuests/Tome18.json`](archiveQuests/Tome18.json)

[Full line-by-line diff](diffs/archiveQuests/Tome18.json.diff)

```diff
- $.Tome18.level[0].startDateInMs: 1706716800
+ $.Tome18.level[0].startDateInMs: 1706716800000
- $.Tome18.level[1].startDateInMs: 1707926400
+ $.Tome18.level[1].startDateInMs: 1707926400000
- $.Tome18.level[2].startDateInMs: 1709136000
+ $.Tome18.level[2].startDateInMs: 1709136000000
- $.Tome18.level[3].startDateInMs: 1710946800
+ $.Tome18.level[3].startDateInMs: 1710946800000
```

### [`archiveQuests/Tome19.json`](archiveQuests/Tome19.json)

[Full line-by-line diff](diffs/archiveQuests/Tome19.json.diff)

```diff
- $.Tome19.level[0].startDateInMs: 1713884400
+ $.Tome19.level[0].startDateInMs: 1713884400000
- $.Tome19.level[1].startDateInMs: 1715094000
+ $.Tome19.level[1].startDateInMs: 1715094000000
- $.Tome19.level[2].startDateInMs: 1716303600
+ $.Tome19.level[2].startDateInMs: 1716303600000
- $.Tome19.level[3].startDateInMs: 1718118000
+ $.Tome19.level[3].startDateInMs: 1718118000000
```

### [`archiveQuests/Tome20.json`](archiveQuests/Tome20.json)

[Full line-by-line diff](diffs/archiveQuests/Tome20.json.diff)

```diff
- $.Tome20.level[0].startDateInMs: 1721142000
+ $.Tome20.level[0].startDateInMs: 1721142000000
- $.Tome20.level[1].startDateInMs: 1722351600
+ $.Tome20.level[1].startDateInMs: 1722351600000
- $.Tome20.level[2].startDateInMs: 1723561200
+ $.Tome20.level[2].startDateInMs: 1723561200000
- $.Tome20.level[3].startDateInMs: 1725375600
+ $.Tome20.level[3].startDateInMs: 1725375600000
```

### [`archiveQuests/Tome21.json`](archiveQuests/Tome21.json)

[Full line-by-line diff](diffs/archiveQuests/Tome21.json.diff)

```diff
- $.Tome21.level[0].startDateInMs: 1728399600
+ $.Tome21.level[0].startDateInMs: 1728399600000
- $.Tome21.level[1].startDateInMs: 1730822400
+ $.Tome21.level[1].startDateInMs: 1730822400000
- $.Tome21.level[2].startDateInMs: 1732636800
+ $.Tome21.level[2].startDateInMs: 1732636800000
- $.Tome21.level[3].startDateInMs: 1735056000
+ $.Tome21.level[3].startDateInMs: 1735056000000
```

### [`archiveQuests/Tome22.json`](archiveQuests/Tome22.json)

[Full line-by-line diff](diffs/archiveQuests/Tome22.json.diff)

```diff
- $.Tome22.level[0].startDateInMs: 1738080000
+ $.Tome22.level[0].startDateInMs: 1738080000000
- $.Tome22.level[1].startDateInMs: 1739894400
+ $.Tome22.level[1].startDateInMs: 1739894400000
- $.Tome22.level[2].startDateInMs: 1741705200
+ $.Tome22.level[2].startDateInMs: 1741705200000
- $.Tome22.level[3].startDateInMs: 1743519600
+ $.Tome22.level[3].startDateInMs: 1743519600000
```

### [`archiveQuests/Winter2022.json`](archiveQuests/Winter2022.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2022.json.diff)

```diff
- $.Winter2022.level[0].startDateInMs: 1670515200
+ $.Winter2022.level[0].startDateInMs: 1670515200000
- $.Winter2022.level[1].startDateInMs: 1671120000
+ $.Winter2022.level[1].startDateInMs: 1671120000000
```

### [`archiveQuests/Winter2023.json`](archiveQuests/Winter2023.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2023.json.diff)

```diff
- $.Winter2023.level[0].startDateInMs: 1702569600
+ $.Winter2023.level[0].startDateInMs: 1702569600000
- $.Winter2023.level[1].startDateInMs: 1703174400
+ $.Winter2023.level[1].startDateInMs: 1703174400000
- $.Winter2023.level[2].startDateInMs: 1703779200
+ $.Winter2023.level[2].startDateInMs: 1703779200000
```

### [`archiveQuests/Winter2024.json`](archiveQuests/Winter2024.json)

[Full line-by-line diff](diffs/archiveQuests/Winter2024.json.diff)

```diff
- $.Winter2024.level[0].startDateInMs: 1734019200
+ $.Winter2024.level[0].startDateInMs: 1734019200000
- $.Winter2024.level[1].startDateInMs: 1734624000
+ $.Winter2024.level[1].startDateInMs: 1734624000000
- $.Winter2024.level[2].startDateInMs: 1735228800
+ $.Winter2024.level[2].startDateInMs: 1735228800000
```

### [`archiveRewardData/content.json`](archiveRewardData/content.json)

[Full line-by-line diff](diffs/archiveRewardData/content.json.diff)

```diff
- $.Tome01.endDateInMs: 1578499200
+ $.Tome01.endDateInMs: 1578499200000
- $.Tome01.postEndDateInMs: 1578499200
+ $.Tome01.postEndDateInMs: 1578499200000
- $.Tome01.preStartDateInMs: 1572307200
+ $.Tome01.preStartDateInMs: 1572307200000
- $.Tome01.startDateInMs: 1572307200
+ $.Tome01.startDateInMs: 1572307200000
- $.Tome02.endDateInMs: 1585753200
+ $.Tome02.endDateInMs: 1585753200000
- $.Tome02.postEndDateInMs: 1585753200
+ $.Tome02.postEndDateInMs: 1585753200000
- $.Tome02.preStartDateInMs: 1578412800
+ $.Tome02.preStartDateInMs: 1578412800000
- $.Tome02.startDateInMs: 1579708800
+ $.Tome02.startDateInMs: 1579708800000
- $.Tome03.endDateInMs: 1595430000
+ $.Tome03.endDateInMs: 1595430000000
- $.Tome03.postEndDateInMs: 1595430000
+ $.Tome03.postEndDateInMs: 1595430000000
- $.Tome03.preStartDateInMs: 1588172400
+ $.Tome03.preStartDateInMs: 1588172400000
- $.Tome03.startDateInMs: 1588172400
+ $.Tome03.startDateInMs: 1588172400000
- $.Tome04.endDateInMs: 1602082800
+ $.Tome04.endDateInMs: 1602082800000
- $.Tome04.postEndDateInMs: 1602082800
+ $.Tome04.postEndDateInMs: 1602082800000
- $.Tome04.preStartDateInMs: 1596034800
+ $.Tome04.preStartDateInMs: 1596034800000
- $.Tome04.startDateInMs: 1596034800
+ $.Tome04.startDateInMs: 1596034800000
- $.Tome05.endDateInMs: 1609948800
+ $.Tome05.endDateInMs: 1609948800000
- $.Tome05.postEndDateInMs: 1609948800
+ $.Tome05.postEndDateInMs: 1609948800000
- $.Tome05.preStartDateInMs: 1603292400
+ $.Tome05.preStartDateInMs: 1603292400000
- $.Tome05.startDateInMs: 1603292400
+ $.Tome05.startDateInMs: 1603292400000
- $.Tome06.endDateInMs: 1619017200
+ $.Tome06.endDateInMs: 1619017200000
- $.Tome06.postEndDateInMs: 1619017200
+ $.Tome06.postEndDateInMs: 1619017200000
- $.Tome06.preStartDateInMs: 1612972800
+ $.Tome06.preStartDateInMs: 1612972800000
- $.Tome06.startDateInMs: 1612972800
+ $.Tome06.startDateInMs: 1612972800000
- $.Tome07.endDateInMs: 1626879600
+ $.Tome07.endDateInMs: 1626879600000
- $.Tome07.postEndDateInMs: 1626879600
+ $.Tome07.postEndDateInMs: 1626879600000
- $.Tome07.preStartDateInMs: 1620226800
+ $.Tome07.preStartDateInMs: 1620226800000
- $.Tome07.startDateInMs: 1620226800
+ $.Tome07.startDateInMs: 1620226800000
- $.Tome08.endDateInMs: 1634137200
+ $.Tome08.endDateInMs: 1634137200000
- $.Tome08.postEndDateInMs: 1634137200
+ $.Tome08.postEndDateInMs: 1634137200000
- $.Tome08.preStartDateInMs: 1627484400
+ $.Tome08.preStartDateInMs: 1627484400000
- $.Tome08.startDateInMs: 1627484400
+ $.Tome08.startDateInMs: 1627484400000
- $.Tome09.endDateInMs: 1641398400
+ $.Tome09.endDateInMs: 1641398400000
- $.Tome09.postEndDateInMs: 1641398400
+ $.Tome09.postEndDateInMs: 1641398400000
- $.Tome09.preStartDateInMs: 1634742000
+ $.Tome09.preStartDateInMs: 1634742000000
- $.Tome09.startDateInMs: 1634742000
+ $.Tome09.startDateInMs: 1634742000000
- $.Tome10.endDateInMs: 1649257200
+ $.Tome10.endDateInMs: 1649257200000
- $.Tome10.postEndDateInMs: 1649257200
+ $.Tome10.postEndDateInMs: 1649257200000
- $.Tome10.preStartDateInMs: 1643212800
+ $.Tome10.preStartDateInMs: 1643212800000
- $.Tome10.startDateInMs: 1643212800
+ $.Tome10.startDateInMs: 1643212800000
- $.Tome11.endDateInMs: 1657206000
+ $.Tome11.endDateInMs: 1657206000000
- $.Tome11.postEndDateInMs: 1657206000
+ $.Tome11.postEndDateInMs: 1657206000000
- $.Tome11.preStartDateInMs: 1651158000
+ $.Tome11.preStartDateInMs: 1651158000000
- $.Tome11.startDateInMs: 1651158000
+ $.Tome11.startDateInMs: 1651158000000
- $.Tome12.endDateInMs: 1664377200
+ $.Tome12.endDateInMs: 1664377200000
- $.Tome12.postEndDateInMs: 1664377200
+ $.Tome12.postEndDateInMs: 1664377200000
- $.Tome12.preStartDateInMs: 1658329200
+ $.Tome12.preStartDateInMs: 1658329200000
- $.Tome12.startDateInMs: 1658329200
+ $.Tome12.startDateInMs: 1658329200000
- $.Tome13.endDateInMs: 1673452800
+ $.Tome13.endDateInMs: 1673452800000
- $.Tome13.postEndDateInMs: 1673452800
+ $.Tome13.postEndDateInMs: 1673452800000
- $.Tome13.preStartDateInMs: 1665586800
+ $.Tome13.preStartDateInMs: 1665586800000
- $.Tome13.startDateInMs: 1665586800
+ $.Tome13.startDateInMs: 1665586800000
- $.Tome14.endDateInMs: 1680706800
+ $.Tome14.endDateInMs: 1680706800000
- $.Tome14.postEndDateInMs: 1680706800
+ $.Tome14.postEndDateInMs: 1680706800000
- $.Tome14.preStartDateInMs: 1674662400
+ $.Tome14.preStartDateInMs: 1674662400000
- $.Tome14.startDateInMs: 1674662400
+ $.Tome14.startDateInMs: 1674662400000
- $.Tome15.endDateInMs: 1689260400
+ $.Tome15.endDateInMs: 1689260400000
- $.Tome15.postEndDateInMs: 1689260400
+ $.Tome15.postEndDateInMs: 1689260400000
- $.Tome15.preStartDateInMs: 1681916400
+ $.Tome15.preStartDateInMs: 1681916400000
- $.Tome15.startDateInMs: 1681916400
+ $.Tome15.startDateInMs: 1681916400000
- $.Tome16.endDateInMs: 1696431600
+ $.Tome16.endDateInMs: 1696431600000
- $.Tome16.postEndDateInMs: 1696431600
+ $.Tome16.postEndDateInMs: 1696431600000
- $.Tome16.preStartDateInMs: 1690383600
+ $.Tome16.preStartDateInMs: 1690383600000
- $.Tome16.startDateInMs: 1690383600
+ $.Tome16.startDateInMs: 1690383600000
- $.Tome17.endDateInMs: 1704380400
+ $.Tome17.endDateInMs: 1704380400000
- $.Tome17.postEndDateInMs: 1704380400
+ $.Tome17.postEndDateInMs: 1704380400000
- $.Tome17.preStartDateInMs: 1697036400
+ $.Tome17.preStartDateInMs: 1697036400000
- $.Tome17.startDateInMs: 1697036400
+ $.Tome17.startDateInMs: 1697036400000
- $.Tome18.endDateInMs: 1712761200
+ $.Tome18.endDateInMs: 1712761200000
- $.Tome18.postEndDateInMs: 1712761200
+ $.Tome18.postEndDateInMs: 1712761200000
- $.Tome18.preStartDateInMs: 1706716800
+ $.Tome18.preStartDateInMs: 1706716800000
- $.Tome18.startDateInMs: 1706716800
+ $.Tome18.startDateInMs: 1706716800000
- $.Tome19.endDateInMs: 1721138400
+ $.Tome19.endDateInMs: 1721138400000
- $.Tome19.postEndDateInMs: 1721138400
+ $.Tome19.postEndDateInMs: 1721138400000
- $.Tome19.preStartDateInMs: 1713884400
+ $.Tome19.preStartDateInMs: 1713884400000
- $.Tome19.startDateInMs: 1713884400
+ $.Tome19.startDateInMs: 1713884400000
- $.Tome20.endDateInMs: 1728396000
+ $.Tome20.endDateInMs: 1728396000000
- $.Tome20.postEndDateInMs: 1728396000
+ $.Tome20.postEndDateInMs: 1728396000000
- $.Tome20.preStartDateInMs: 1721142000
+ $.Tome20.preStartDateInMs: 1721142000000
- $.Tome20.startDateInMs: 1721142000
+ $.Tome20.startDateInMs: 1721142000000
- $.Tome21.endDateInMs: 1738076400
+ $.Tome21.endDateInMs: 1738076400000
- $.Tome21.postEndDateInMs: 1738076400
+ $.Tome21.postEndDateInMs: 1738076400000
- $.Tome21.preStartDateInMs: 1728399600
+ $.Tome21.preStartDateInMs: 1728399600000
- $.Tome21.startDateInMs: 1728399600
+ $.Tome21.startDateInMs: 1728399600000
- $.Tome22.endDateInMs: 1746543600
+ $.Tome22.endDateInMs: 1746543600000
- $.Tome22.postEndDateInMs: 1746543600
+ $.Tome22.postEndDateInMs: 1746543600000
- $.Tome22.preStartDateInMs: 1738080000
+ $.Tome22.preStartDateInMs: 1738080000000
- $.Tome22.startDateInMs: 1738080000
+ $.Tome22.startDateInMs: 1738080000000
```

### [`bloodwebGenerationRules.json`](bloodwebGenerationRules.json)

[Full line-by-line diff](diffs/bloodwebGenerationRules.json.diff)

```diff
- $.BulkCost[9].CostList[0].Value[]: 13250
- $.BulkCost[9].CostList[0].Value[]: 27500
- $.BulkCost[9].CostList[0].Value[]: 28000
- $.BulkCost[9].CostList[0].Value[]: 32500
- $.BulkCost[9].CostList[0].Value[]: 35750
+ $.BulkCost[9].CostList[0].Value[]: 26750
+ $.BulkCost[9].CostList[0].Value[]: 34500
- $.BulkCost[9].CostList[1].Value[]: 13250
- $.BulkCost[9].CostList[1].Value[]: 29500
- $.BulkCost[9].CostList[1].Value[]: 27500
- $.BulkCost[9].CostList[1].Value[]: 28000
- $.BulkCost[9].CostList[1].Value[]: 35250
+ $.BulkCost[9].CostList[1].Value[]: 30000
+ $.BulkCost[9].CostList[1].Value[]: 26750
+ $.BulkCost[9].CostList[1].Value[]: 34500
- $.BulkCost[9].CostList[2].Value[]: 13250
- $.BulkCost[9].CostList[2].Value[]: 27500
- $.BulkCost[9].CostList[2].Value[]: 28000
+ $.BulkCost[9].CostList[2].Value[]: 26750
- $.BulkCost[9].CostList[3].Value[]: 13250
- $.BulkCost[9].CostList[3].Value[]: 27500
- $.BulkCost[9].CostList[3].Value[]: 28000
+ $.BulkCost[9].CostList[3].Value[]: 26750
- $.BulkCost[9].CostList[4].Value[]: 13250
- $.BulkCost[9].CostList[4].Value[]: 27500
- $.BulkCost[9].CostList[4].Value[]: 28000
+ $.BulkCost[9].CostList[4].Value[]: 26750
- $.BulkCost[9].CostList[5].Value[]: 13250
- $.BulkCost[9].CostList[5].Value[]: 27500
- $.BulkCost[9].CostList[5].Value[]: 28000
+ $.BulkCost[9].CostList[5].Value[]: 26750
- $.BulkCost[13].CostList[0].Value[]: 14000
- $.BulkCost[13].CostList[0].Value[]: 18500
- $.BulkCost[13].CostList[0].Value[]: 13250
- $.BulkCost[13].CostList[0].Value[]: 22250
- $.BulkCost[13].CostList[0].Value[]: 28250
- $.BulkCost[13].CostList[0].Value[]: 28000
- $.BulkCost[13].CostList[0].Value[]: 31500
- $.BulkCost[13].CostList[0].Value[]: 32500
- $.BulkCost[13].CostList[0].Value[]: 36500
+ $.BulkCost[13].CostList[0].Value[]: 12500
+ $.BulkCost[13].CostList[0].Value[]: 26750
+ $.BulkCost[13].CostList[0].Value[]: 34500
- $.BulkCost[13].CostList[1].Value[]: 14000
- $.BulkCost[13].CostList[1].Value[]: 18500
- $.BulkCost[13].CostList[1].Value[]: 13250
- $.BulkCost[13].CostList[1].Value[]: 22250
- $.BulkCost[13].CostList[1].Value[]: 28250
- $.BulkCost[13].CostList[1].Value[]: 28000
- $.BulkCost[13].CostList[1].Value[]: 31500
- $.BulkCost[13].CostList[1].Value[]: 33250
- $.BulkCost[13].CostList[1].Value[]: 37250
+ $.BulkCost[13].CostList[1].Value[]: 26750
+ $.BulkCost[13].CostList[1].Value[]: 35250
- $.BulkCost[13].CostList[2].Value[]: 14000
- $.BulkCost[13].CostList[2].Value[]: 18500
- $.BulkCost[13].CostList[2].Value[]: 13250
- $.BulkCost[13].CostList[2].Value[]: 22250
- $.BulkCost[13].CostList[2].Value[]: 28250
- $.BulkCost[13].CostList[2].Value[]: 28750
- $.BulkCost[13].CostList[2].Value[]: 31500
- $.BulkCost[13].CostList[2].Value[]: 33250
- $.BulkCost[13].CostList[2].Value[]: 37250
+ $.BulkCost[13].CostList[2].Value[]: 12500
+ $.BulkCost[13].CostList[2].Value[]: 23500
+ $.BulkCost[13].CostList[2].Value[]: 26750
+ $.BulkCost[13].CostList[2].Value[]: 27500
+ $.BulkCost[13].CostList[2].Value[]: 30750
- $.BulkCost[13].CostList[3].Value[]: 14000
- $.BulkCost[13].CostList[3].Value[]: 18500
- $.BulkCost[13].CostList[3].Value[]: 13250
- $.BulkCost[13].CostList[3].Value[]: 22250
- $.BulkCost[13].CostList[3].Value[]: 28250
- $.BulkCost[13].CostList[3].Value[]: 28750
- $.BulkCost[13].CostList[3].Value[]: 31500
- $.BulkCost[13].CostList[3].Value[]: 33250
- $.BulkCost[13].CostList[3].Value[]: 37250
+ $.BulkCost[13].CostList[3].Value[]: 12500
+ $.BulkCost[13].CostList[3].Value[]: 23500
+ $.BulkCost[13].CostList[3].Value[]: 26750
+ $.BulkCost[13].CostList[3].Value[]: 27500
+ $.BulkCost[13].CostList[3].Value[]: 30750
- $.BulkCost[13].CostList[4].Value[]: 14000
- $.BulkCost[13].CostList[4].Value[]: 18500
- $.BulkCost[13].CostList[4].Value[]: 13250
- $.BulkCost[13].CostList[4].Value[]: 22250
- $.BulkCost[13].CostList[4].Value[]: 28250
- $.BulkCost[13].CostList[4].Value[]: 28750
- $.BulkCost[13].CostList[4].Value[]: 31500
- $.BulkCost[13].CostList[4].Value[]: 33250
- $.BulkCost[13].CostList[4].Value[]: 37250
+ $.BulkCost[13].CostList[4].Value[]: 12500
+ $.BulkCost[13].CostList[4].Value[]: 26750
+ $.BulkCost[13].CostList[4].Value[]: 27500
+ $.BulkCost[13].CostList[4].Value[]: 30750
- $.BulkCost[13].CostList[5].Value[]: 14000
- $.BulkCost[13].CostList[5].Value[]: 18500
- $.BulkCost[13].CostList[5].Value[]: 13250
- $.BulkCost[13].CostList[5].Value[]: 22250
- $.BulkCost[13].CostList[5].Value[]: 28250
- $.BulkCost[13].CostList[5].Value[]: 28750
- $.BulkCost[13].CostList[5].Value[]: 31500
- $.BulkCost[13].CostList[5].Value[]: 33250
- $.BulkCost[13].CostList[5].Value[]: 37250
+ $.BulkCost[13].CostList[5].Value[]: 12500
+ $.BulkCost[13].CostList[5].Value[]: 23500
+ $.BulkCost[13].CostList[5].Value[]: 26750
+ $.BulkCost[13].CostList[5].Value[]: 27500
+ $.BulkCost[13].CostList[5].Value[]: 30750
- $.BulkCost[17]
- $.EventChestProbability[14]
```

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
- $[id=S52]
- $[id=HK_Body027]
- $[id=HK_Head027]
- $[id=HK_W027]
- $[id=JP_Head033]
- $[id=JP_Legs033]
- $[id=JP_Torso033]
- $[id=K01_BDG_P100]
- $[id=K01_BDG_P25]
- $[id=K01_BDG_P50]
- $[id=K01_BDG_P75]
- $[id=K02_BDG_P100]
- $[id=K02_BDG_P25]
- $[id=K02_BDG_P50]
- $[id=K02_BDG_P75]
- $[id=K03_BDG_P100]
- $[id=K03_BDG_P25]
- $[id=K03_BDG_P50]
- $[id=K03_BDG_P75]
- $[id=K04_BDG_P100]
- $[id=K04_BDG_P25]
- $[id=K04_BDG_P50]
- $[id=K04_BDG_P75]
- $[id=K05_BDG_P100]
- $[id=K05_BDG_P25]
- $[id=K05_BDG_P50]
- $[id=K05_BDG_P75]
- $[id=K06_BDG_P100]
- $[id=K06_BDG_P25]
- $[id=K06_BDG_P50]
- $[id=K06_BDG_P75]
- $[id=K07_BDG_P100]
- $[id=K07_BDG_P25]
- $[id=K07_BDG_P50]
- $[id=K07_BDG_P75]
- $[id=K08_BDG_P100]
- $[id=K08_BDG_P25]
- $[id=K08_BDG_P50]
- $[id=K08_BDG_P75]
- $[id=K09_BDG_P100]
- $[id=K09_BDG_P25]
- $[id=K09_BDG_P50]
- $[id=K09_BDG_P75]
- $[id=K10_BDG_P100]
- $[id=K10_BDG_P25]
- $[id=K10_BDG_P50]
- $[id=K10_BDG_P75]
- $[id=K11_BDG_P100]
- $[id=K11_BDG_P25]
- $[id=K11_BDG_P50]
- $[id=K11_BDG_P75]
- $[id=K12_BDG_P100]
- $[id=K12_BDG_P25]
- $[id=K12_BDG_P50]
- $[id=K12_BDG_P75]
- $[id=K13_BDG_P100]
- $[id=K13_BDG_P25]
- $[id=K13_BDG_P50]
- $[id=K13_BDG_P75]
- $[id=K14_BDG_P100]
- $[id=K14_BDG_P25]
- $[id=K14_BDG_P50]
- $[id=K14_BDG_P75]
- $[id=K15_BDG_P100]
- $[id=K15_BDG_P25]
- $[id=K15_BDG_P50]
- $[id=K15_BDG_P75]
- $[id=K16_BDG_P100]
- $[id=K16_BDG_P25]
- $[id=K16_BDG_P50]
- $[id=K16_BDG_P75]
- $[id=K17_BDG_P100]
- $[id=K17_BDG_P25]
- $[id=K17_BDG_P50]
- $[id=K17_BDG_P75]
- $[id=K18_BDG_P100]
- $[id=K18_BDG_P25]
- $[id=K18_BDG_P50]
- $[id=K18_BDG_P75]
- $[id=K19_BDG_P100]
- $[id=K19_BDG_P25]
- $[id=K19_BDG_P50]
- $[id=K19_BDG_P75]
- $[id=K20_BDG_P100]
- $[id=K20_BDG_P25]
- $[id=K20_BDG_P50]
- $[id=K20_BDG_P75]
- $[id=K21_BDG_P100]
- $[id=K21_BDG_P25]
- $[id=K21_BDG_P50]
- $[id=K21_BDG_P75]
- $[id=K21_Body022]
- $[id=K21_Head022]
- $[id=K21_W022]
- $[id=K22_BDG_P100]
- $[id=K22_BDG_P25]
- $[id=K22_BDG_P50]
- $[id=K22_BDG_P75]
- $[id=K23_BDG_P100]
- $[id=K23_BDG_P25]
- $[id=K23_BDG_P50]
- $[id=K23_BDG_P75]
- $[id=K23_Body019]
- $[id=K23_Head019]
- $[id=K23_W019]
- $[id=K24_BDG_P100]
- $[id=K24_BDG_P25]
- $[id=K24_BDG_P50]
- $[id=K24_BDG_P75]
- $[id=K25_BDG_P100]
- $[id=K25_BDG_P25]
- $[id=K25_BDG_P50]
- $[id=K25_BDG_P75]
- $[id=K26_BDG_P100]
- $[id=K26_BDG_P25]
- $[id=K26_BDG_P50]
- $[id=K26_BDG_P75]
- $[id=K27_BDG_P100]
- $[id=K27_BDG_P25]
- $[id=K27_BDG_P50]
- $[id=K27_BDG_P75]
- $[id=K28_BDG_P100]
- $[id=K28_BDG_P25]
- $[id=K28_BDG_P50]
- $[id=K28_BDG_P75]
- $[id=K28_W018]
- $[id=K29_BDG_P100]
- $[id=K29_BDG_P25]
- $[id=K29_BDG_P50]
- $[id=K29_BDG_P75]
- $[id=K30_BDG_P100]
- $[id=K30_BDG_P25]
- $[id=K30_BDG_P50]
- $[id=K30_BDG_P75]
- $[id=K31_BDG_P100]
- $[id=K31_BDG_P25]
- $[id=K31_BDG_P50]
- $[id=K31_BDG_P75]
- $[id=K32_BDG_P100]
- $[id=K32_BDG_P25]
- $[id=K32_BDG_P50]
- $[id=K32_BDG_P75]
- $[id=K33_BDG_P100]
- $[id=K33_BDG_P25]
- $[id=K33_BDG_P50]
- $[id=K33_BDG_P75]
- $[id=K34_BDG_P100]
- $[id=K34_BDG_P25]
- $[id=K34_BDG_P50]
- $[id=K34_BDG_P75]
- $[id=K35_BDG_P100]
- $[id=K35_BDG_P25]
- $[id=K35_BDG_P50]
- $[id=K35_BDG_P75]
- $[id=K36_BDG_P100]
- $[id=K36_BDG_P25]
- $[id=K36_BDG_P50]
- $[id=K36_BDG_P75]
- $[id=K37_BDG_P100]
- $[id=K37_BDG_P25]
- $[id=K37_BDG_P50]
- $[id=K37_BDG_P75]
- $[id=K38_BDG_P100]
- $[id=K38_BDG_P25]
- $[id=K38_BDG_P50]
- $[id=K38_BDG_P75]
- $[id=K39_BDG_P100]
- $[id=K39_BDG_P25]
- $[id=K39_BDG_P50]
- $[id=K39_BDG_P75]
- $[id=K40_BDG_P100]
- $[id=K40_BDG_P25]
- $[id=K40_BDG_P50]
- $[id=K40_BDG_P75]
- $[id=K41_BDG_P100]
- $[id=K41_BDG_P25]
- $[id=K41_BDG_P50]
- $[id=K41_BDG_P75]
- $[id=K42_BDG_P100]
- $[id=K42_BDG_P25]
- $[id=K42_BDG_P50]
- $[id=K42_BDG_P75]
- $[id=KS_Torso024]
- $[id=MK_W019]
- $[id=MT_Torso034]
- $[id=QUI_002]
- $[id=QUI_003]
- $[id=QUI_004]
- $[id=QUI_005]
- $[id=QUI_006]
- $[id=QUI_007]
- $[id=QUI_BDG_01]
- $[id=QUI_BDG_02]
- $[id=QUI_BDG_03]
- $[id=QUI_BDG_04]
- $[id=QUI_BDG_05]
- $[id=QUI_BDG_06]
- $[id=QUI_BDG_07]
- $[id=QUI_BDG_08]
- $[id=QUI_BDG_09]
… 26929 more change(s) — see the commit diff for everything
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[462].text: "KAPITELQUESTS – WOCHE 1"
+ $.locText[462].text: "KAPITELQUESTS – TEIL 1"
- $.locText[463].text: "KAPITELQUESTS – WOCHE 2"
+ $.locText[463].text: "KAPITELQUESTS – TEIL 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_en.json`](challengeLocs/challengeText_en.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_en.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[462].text: "MISIONES DE CAPÍTULO - SEMANA 1"
+ $.locText[462].text: "MISIONES DE CAPÍTULO - PARTE 1"
- $.locText[463].text: "MISIONES DE CAPÍTULO - SEMANA 2"
+ $.locText[463].text: "MISIONES DE CAPÍTULO - PARTE 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[462].text: "MISIONES DEL CAPÍTULO - SEMANA 1"
+ $.locText[462].text: "MISIONES DEL CAPÍTULO: PARTE 1"
- $.locText[463].text: "MISIONES DEL CAPÍTULO - SEMANA 2"
+ $.locText[463].text: "MISIONES DEL CAPÍTULO: PARTE 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_fr.json`](challengeLocs/challengeText_fr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_fr.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[462].text: "MISSIONI CAPITOLO: SETTIMANA 1"
+ $.locText[462].text: "MISSIONI CAPITOLO: PARTE 1"
- $.locText[463].text: "MISSIONI CAPITOLO: SETTIMANA 2"
+ $.locText[463].text: "MISSIONI CAPITOLO: PARTE 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_ja.json`](challengeLocs/challengeText_ja.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ja.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_ko.json`](challengeLocs/challengeText_ko.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ko.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_pl.json`](challengeLocs/challengeText_pl.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pl.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[462].text: "MISSÕES DO CAPÍTULO - SEMANA 1"
+ $.locText[462].text: "MISSÕES DE CAPÍTULO – PARTE 1"
- $.locText[463].text: "MISSÕES DO CAPÍTULO - SEMANA 2"
+ $.locText[463].text: "MISSÕES DE CAPÍTULO – PARTE 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_ru.json`](challengeLocs/challengeText_ru.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_ru.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[462].text: "เควสต์ประจำบท - สัปดาห์ที่ 1"
+ $.locText[462].text: "เควสต์ประจำบท - ส่วนที่ 1"
- $.locText[463].text: "เควสต์ประจำบท - สัปดาห์ที่ 2"
+ $.locText[463].text: "เควสต์ประจำบท - ส่วนที่ 2"
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_tr.json`](challengeLocs/challengeText_tr.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_tr.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_zh-Hans.json`](challengeLocs/challengeText_zh-Hans.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hans.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeLocs/challengeText_zh-Hant.json`](challengeLocs/challengeText_zh-Hant.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_zh-Hant.json.diff)

```diff
- $.locText[565]
- $.locText[566]
- $.locText[567]
- $.locText[568]
- $.locText[569]
- $.locText[570]
- $.locText[571]
- $.locText[572]
- $.locText[573]
- $.locText[574]
- $.locText[575]
- $.locText[576]
- $.locText[577]
- $.locText[578]
- $.locText[579]
- $.locText[580]
- $.locText[581]
- $.locText[582]
- $.locText[583]
- $.locText[584]
- $.locText[585]
```

### [`challengeRewardTrackers.json`](challengeRewardTrackers.json)

[Full line-by-line diff](diffs/challengeRewardTrackers.json.diff)

```diff
- $.Rift_01.endDateInMs: 1753801200
+ $.Rift_01.endDateInMs: 1753801200000
- $.Rift_01.startDateInMs: 1746543600
+ $.Rift_01.startDateInMs: 1746543600000
- $.Rift_02.endDateInMs: 1759849200
+ $.Rift_02.endDateInMs: 1759849200000
- $.Rift_02.startDateInMs: 1753801200
+ $.Rift_02.startDateInMs: 1753801200000
- $.Rift_03.endDateInMs: 1769529540
+ $.Rift_03.endDateInMs: 1769529540000
- $.Rift_03.startDateInMs: 1759849200
+ $.Rift_03.startDateInMs: 1759849200000
- $.Rift_04.endDateInMs: 1777388340
+ $.Rift_04.endDateInMs: 1777388340000
- $.Rift_04.startDateInMs: 1769529600
+ $.Rift_04.startDateInMs: 1769529600000
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.BloodMoon_Quiche
- $.ChapterQuests_Quiche
- $.CalamariPoutine.endDateInMs: 1772553600
+ $.CalamariPoutine.endDateInMs: 1772553600000
- $.CalamariPoutine.startDateInMs: 1770739200
+ $.CalamariPoutine.startDateInMs: 1770739200000
- $.Daily_Set.startDateInMs: 1712156400
+ $.Daily_Set.startDateInMs: 1712156400000
- $.Milestone_04_Set.endDateInMs: 1777388340
+ $.Milestone_04_Set.endDateInMs: 1777388340000
- $.Milestone_04_Set.startDateInMs: 1769529600
+ $.Milestone_04_Set.startDateInMs: 1769529600000
- $.Onboarding_Set.startDateInMs: 1747443737
+ $.Onboarding_Set.startDateInMs: 1747443737000
- $.Rift_04_QuestSet.endDateInMs: 1777388340
+ $.Rift_04_QuestSet.endDateInMs: 1777388340000
- $.Rift_04_QuestSet.startDateInMs: 1769529600
+ $.Rift_04_QuestSet.startDateInMs: 1769529600000
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
+ $.collections[1].limitedAvailabilityEndDate: "2025-04-10T15:00:00Z"
+ $.collections[1].limitedAvailabilityStartDate: "2025-04-07T15:00:00Z"
+ $.collections[1].visibleAfterEndDate: false
+ $.collections[1].visibleBeforeStartDate: false
- $.collections[1].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
+ $.collections[1].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_Bloodmoon.T_UI_SpecialPack_Bloodmoon"
- $.collections[1].collectionId: "Techwear"
+ $.collections[1].collectionId: "Bloodmoon"
- $.collections[1].collectionTitle.de: "Techbekleidung"
+ $.collections[1].collectionTitle.de: "Blutmond"
- $.collections[1].collectionTitle.en: "Techwear"
+ $.collections[1].collectionTitle.en: "Blood Moon"
- $.collections[1].collectionTitle.es: "Colección de Equipo técnico"
+ $.collections[1].collectionTitle.es: "Luna de sangre"
- $.collections[1].collectionTitle["es-MX"]: "Colección Indumentaria tecnológica"
+ $.collections[1].collectionTitle["es-MX"]: "Luna de sangre"
- $.collections[1].collectionTitle.fr: "Technovêtements"
+ $.collections[1].collectionTitle.fr: "Lune de sang"
- $.collections[1].collectionTitle.it: "Collezione Techwear"
+ $.collections[1].collectionTitle.it: "Luna sanguinosa"
- $.collections[1].collectionTitle.ja: "テックウェア"
+ $.collections[1].collectionTitle.ja: "ブラッドムーン"
- $.collections[1].collectionTitle.ko: "테크웨어 컬렉션"
+ $.collections[1].collectionTitle.ko: "핏빛 달"
- $.collections[1].collectionTitle.pl: "Kolekcja odzieży technicznej"
+ $.collections[1].collectionTitle.pl: "Krwawy księżyc"
- $.collections[1].collectionTitle["pt-BR"]: "Coleção da Roupa Tecnológica"
+ $.collections[1].collectionTitle["pt-BR"]: "Lua de Sangue"
- $.collections[1].collectionTitle.ru: "Коллекция «Техно»"
+ $.collections[1].collectionTitle.ru: "Кровавая луна"
- $.collections[1].collectionTitle.th: "อุปกรณ์เทคโนโลยี"
+ $.collections[1].collectionTitle.th: "จันทราโลหิต"
- $.collections[1].collectionTitle.tr: "Teknolojik Kıyafet Koleksiyonu"
+ $.collections[1].collectionTitle.tr: "Kanlı Ay"
- $.collections[1].collectionTitle["zh-Hans"]: "机能服装系列"
+ $.collections[1].collectionTitle["zh-Hans"]: "血月"
- $.collections[1].collectionTitle["zh-Hant"]: "機能服飾收藏"
+ $.collections[1].collectionTitle["zh-Hant"]: "血月"
- $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
+ $.collections[1].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_Bloodmoon.T_UI_CollectionBanner_Bloodmoon"
- $.collections[1].inclusionVersion: "7.7.0"
+ $.collections[1].inclusionVersion: "8.6.0"
- $.collections[1].items[]: "AV_outfit_026"
- $.collections[1].items[]: "DK_outfit_022"
- $.collections[1].items[]: "DO_outfit_026"
- $.collections[1].items[]: "FM_outfit_038"
- $.collections[1].items[]: "GS_outfit_029"
- $.collections[1].items[]: "K23_outfit_021"
- $.collections[1].items[]: "K31_outfit_017"
- $.collections[1].items[]: "KK_outfit_025"
- $.collections[1].items[]: "MT_outfit_023"
- $.collections[1].items[]: "NK_outfit_029"
- $.collections[1].items[]: "S23_outfit_031"
- $.collections[1].items[]: "S25_outfit_015"
- $.collections[1].items[]: "S28_outfit_018"
- $.collections[1].items[]: "S29_outfit_017"
- $.collections[1].items[]: "S34_outfit_011"
- $.collections[1].items[]: "US_Outfit_023"
+ $.collections[1].items[]: "AV_outfit_022"
+ $.collections[1].items[]: "CM_outfit_030"
+ $.collections[1].items[]: "DO_outfit_020"
+ $.collections[1].items[]: "K26_outfit_019"
+ $.collections[1].items[]: "K30_outfit_012"
+ $.collections[1].items[]: "K31_outfit_012"
+ $.collections[1].items[]: "K38_outfit_007"
+ $.collections[1].items[]: "S24_outfit_021"
+ $.collections[1].items[]: "S28_outfit_023"
+ $.collections[1].items[]: "S45_outfit_011"
+ $.collections[1].items[]: "SwedenKiller_outfit_021"
- $.collections[1].sortOrder: "-105"
+ $.collections[1].sortOrder: "-104"
- $.collections[1].updatedDate: "2025-04-21T13:25:07.469Z"
+ $.collections[1].updatedDate: "2025-01-08T21:01:45.055Z"
- $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Jerky/T_UI_SpecialPack_SteadyPulse.T_UI_SpecialPack_SteadyPulse"
+ $.collections[2].additionalImages[0].path: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/IceCream/T_UI_SpecialPack_Techwear.T_UI_SpecialPack_Techwear"
- $.collections[2].collectionId: "SteadyPulse"
+ $.collections[2].collectionId: "Techwear"
- $.collections[2].collectionTitle.de: "Steady Pulse"
+ $.collections[2].collectionTitle.de: "Techbekleidung"
- $.collections[2].collectionTitle.en: "Steady Pulse"
+ $.collections[2].collectionTitle.en: "Techwear"
- $.collections[2].collectionTitle.es: "Steady Pulse"
+ $.collections[2].collectionTitle.es: "Colección de Equipo técnico"
- $.collections[2].collectionTitle["es-MX"]: "Steady Pulse"
+ $.collections[2].collectionTitle["es-MX"]: "Colección Indumentaria tecnológica"
- $.collections[2].collectionTitle.fr: "Steady Pulse"
+ $.collections[2].collectionTitle.fr: "Technovêtements"
- $.collections[2].collectionTitle.it: "Steady Pulse"
+ $.collections[2].collectionTitle.it: "Collezione Techwear"
- $.collections[2].collectionTitle.ja: "Steady Pulse"
+ $.collections[2].collectionTitle.ja: "テックウェア"
- $.collections[2].collectionTitle.ko: "Steady Pulse"
+ $.collections[2].collectionTitle.ko: "테크웨어 컬렉션"
- $.collections[2].collectionTitle.pl: "Steady Pulse"
+ $.collections[2].collectionTitle.pl: "Kolekcja odzieży technicznej"
- $.collections[2].collectionTitle["pt-BR"]: "Steady Pulse"
+ $.collections[2].collectionTitle["pt-BR"]: "Coleção da Roupa Tecnológica"
- $.collections[2].collectionTitle.ru: "«Ровный пульс»"
+ $.collections[2].collectionTitle.ru: "Коллекция «Техно»"
- $.collections[2].collectionTitle.th: "Steady Pulse"
+ $.collections[2].collectionTitle.th: "อุปกรณ์เทคโนโลยี"
- $.collections[2].collectionTitle.tr: "Steady Pulse"
+ $.collections[2].collectionTitle.tr: "Teknolojik Kıyafet Koleksiyonu"
- $.collections[2].collectionTitle["zh-Hans"]: "《Steady Pulse》"
+ $.collections[2].collectionTitle["zh-Hans"]: "机能服装系列"
- $.collections[2].collectionTitle["zh-Hant"]: "穩定脈搏"
+ $.collections[2].collectionTitle["zh-Hant"]: "機能服飾收藏"
- $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
+ $.collections[2].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/IceCream/T_UI_CollectionBanner_Techwear_2.T_UI_CollectionBanner_Techwear_2"
- $.collections[2].inclusionVersion: "8.7.0"
+ $.collections[2].inclusionVersion: "7.7.0"
- $.collections[2].items[]: "S46_outfit_006"
- $.collections[2].items[]: "S46_outfit_006_01"
- $.collections[2].items[]: "S46_outfit_01_01"
- $.collections[2].items[]: "S46_outfit_01_02"
- $.collections[2].items[]: "S46_outfit_01_03"
- $.collections[2].items[]: "S46_outfit_01_CV01"
- $.collections[2].items[]: "S46_outfit_01_CV02"
- $.collections[2].items[]: "S46_outfit_01_CV03"
- $.collections[2].items[]: "S46_outfit_01_CV04"
- $.collections[2].items[]: "S46_outfit_02"
- $.collections[2].items[]: "S46_outfit_02_01"
+ $.collections[2].items[]: "AV_outfit_026"
+ $.collections[2].items[]: "DK_outfit_022"
+ $.collections[2].items[]: "DO_outfit_026"
+ $.collections[2].items[]: "FM_outfit_038"
+ $.collections[2].items[]: "GS_outfit_029"
+ $.collections[2].items[]: "K23_outfit_021"
+ $.collections[2].items[]: "K31_outfit_017"
+ $.collections[2].items[]: "KK_outfit_025"
+ $.collections[2].items[]: "MT_outfit_023"
+ $.collections[2].items[]: "NK_outfit_029"
+ $.collections[2].items[]: "S23_outfit_031"
+ $.collections[2].items[]: "S25_outfit_015"
+ $.collections[2].items[]: "S28_outfit_018"
+ $.collections[2].items[]: "S29_outfit_017"
+ $.collections[2].items[]: "S34_outfit_011"
+ $.collections[2].items[]: "US_Outfit_023"
- $.collections[2].sortOrder: "-108"
+ $.collections[2].sortOrder: "-105"
- $.collections[2].updatedDate: "2025-02-28T13:55:18.092Z"
+ $.collections[2].updatedDate: "2025-04-21T13:25:07.469Z"
+ $.collections[3].additionalImages[0]
- $.collections[3].collectionId: "Alien"
+ $.collections[3].collectionId: "SteadyPulse"
- $.collections[3].collectionTitle.de: "Alien"
+ $.collections[3].collectionTitle.de: "Steady Pulse"
- $.collections[3].collectionTitle.en: "Alien"
+ $.collections[3].collectionTitle.en: "Steady Pulse"
- $.collections[3].collectionTitle.es: "Alien"
+ $.collections[3].collectionTitle.es: "Steady Pulse"
- $.collections[3].collectionTitle["es-MX"]: "Alien"
+ $.collections[3].collectionTitle["es-MX"]: "Steady Pulse"
- $.collections[3].collectionTitle.fr: "Alien"
+ $.collections[3].collectionTitle.fr: "Steady Pulse"
- $.collections[3].collectionTitle.it: "Alien"
+ $.collections[3].collectionTitle.it: "Steady Pulse"
- $.collections[3].collectionTitle.ja: "エイリアン"
+ $.collections[3].collectionTitle.ja: "Steady Pulse"
- $.collections[3].collectionTitle.ko: "에이리언"
+ $.collections[3].collectionTitle.ko: "Steady Pulse"
- $.collections[3].collectionTitle.pl: "Obcy"
+ $.collections[3].collectionTitle.pl: "Steady Pulse"
- $.collections[3].collectionTitle["pt-BR"]: "Alien"
+ $.collections[3].collectionTitle["pt-BR"]: "Steady Pulse"
- $.collections[3].collectionTitle.ru: "Чужой"
+ $.collections[3].collectionTitle.ru: "«Ровный пульс»"
- $.collections[3].collectionTitle.th: "เอเลี่ยน"
+ $.collections[3].collectionTitle.th: "Steady Pulse"
- $.collections[3].collectionTitle.tr: "Alien"
+ $.collections[3].collectionTitle.tr: "Steady Pulse"
- $.collections[3].collectionTitle["zh-Hans"]: "异形"
+ $.collections[3].collectionTitle["zh-Hans"]: "《Steady Pulse》"
- $.collections[3].collectionTitle["zh-Hant"]: "《異形》"
+ $.collections[3].collectionTitle["zh-Hant"]: "穩定脈搏"
- $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Fudge/T_UI_CollectionBanner_AlienReimagined_BC.T_UI_CollectionBanner_AlienReimagined_BC"
+ $.collections[3].heroImage.path: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Jerky/T_UI_CollectionBanner_SteadyPulse.T_UI_CollectionBanner_SteadyPulse"
- $.collections[3].inclusionVersion: "7.7.0 PTB"
+ $.collections[3].inclusionVersion: "8.7.0"
- $.collections[3].items[]: "K33_outfit_006"
- $.collections[3].items[]: "K33_outfit_007"
- $.collections[3].items[]: "K33_outfit_008"
- $.collections[3].items[]: "K33_outfit_010"
- $.collections[3].items[]: "K33_outfit_011"
- $.collections[3].items[]: "K33_outfit_012"
- $.collections[3].items[]: "K33_outfit_02"
- $.collections[3].items[]: "S39_outfit_006"
- $.collections[3].items[]: "S39_outfit_007"
- $.collections[3].items[]: "S39_outfit_009"
- $.collections[3].items[]: "S39_outfit_010"
- $.collections[3].items[]: "S39_outfit_011"
+ $.collections[3].items[]: "S46_outfit_006"
+ $.collections[3].items[]: "S46_outfit_006_01"
+ $.collections[3].items[]: "S46_outfit_01_01"
+ $.collections[3].items[]: "S46_outfit_01_02"
+ $.collections[3].items[]: "S46_outfit_01_03"
+ $.collections[3].items[]: "S46_outfit_01_CV01"
+ $.collections[3].items[]: "S46_outfit_01_CV02"
+ $.collections[3].items[]: "S46_outfit_01_CV03"
+ $.collections[3].items[]: "S46_outfit_01_CV04"
… 5762 more change(s) — see the commit diff for everything
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[0].MapsWeight.Qui_Level_01: "200"
- $.schedule[4].MapsWeight.Apl_Level_01: "35"
- $.schedule[4].MapsWeight.Apl_Shack: "35"
- $.schedule[4].MapsWeight.Brl_Temple: "45"
- $.schedule[4].MapsWeight.Ecl_level_01: "0"
- $.schedule[4].MapsWeight.Ecl_level_WestSide: "45"
- $.schedule[4].MapsWeight.End_Street_01: "0"
- $.schedule[4].MapsWeight.Fin_Hideout: "0"
- $.schedule[4].MapsWeight.Hos_Treatment: "0"
- $.schedule[4].MapsWeight.Ukr_Saloon: "45"
+ $.schedule[4].MapsWeight.Eng_Street_01: "100"
- $.schedule[4].MapsWeight.Qat_Lab: "0"
+ $.schedule[4].MapsWeight.Qat_Lab: "100"
- $.schedule[4].MapsWeight.Qtm_Level_02: "0"
+ $.schedule[4].MapsWeight.Qtm_Level_02: "100"
- $.schedule[4].MapsWeight.Wal_Level_01: "0"
+ $.schedule[4].MapsWeight.Wal_Level_01: "100"
- $.schedule[5].LinkedEventId: "MapShowcaseQuiche"
- $.schedule[5].Description: "MapShowcase Map List"
+ $.schedule[5].Description: "Winterevent_adjust"
- $.schedule[5].GameModes[]: "MapShowcase"
+ $.schedule[5].GameModes[]: "SeasonalEvent"
- $.schedule[5].MapsWeight.Qui_Level_01: "1300"
+ $.schedule[5].MapsWeight.Apl_Level_01: "45"
+ $.schedule[5].MapsWeight.Apl_Level_02: "45"
+ $.schedule[5].MapsWeight.Apl_Shack: "70"
+ $.schedule[5].MapsWeight.Asy_Asylum: "90"
+ $.schedule[5].MapsWeight.Asy_Chapel: "110"
+ $.schedule[5].MapsWeight.Brl_MaHouse: "90"
+ $.schedule[5].MapsWeight.Brl_Temple: "0"
+ $.schedule[5].MapsWeight.Ecl_Level_01: "45"
+ $.schedule[5].MapsWeight.Ecl_Level_WestSide: "45"
+ $.schedule[5].MapsWeight.Eng_Street_01: "100"
+ $.schedule[5].MapsWeight.Fin_Hideout: "100"
+ $.schedule[5].MapsWeight.Frm_Barn: "60"
+ $.schedule[5].MapsWeight.Frm_Cornfield: "60"
+ $.schedule[5].MapsWeight.Frm_Farmhouse: "100"
+ $.schedule[5].MapsWeight.Frm_Silo: "60"
+ $.schedule[5].MapsWeight.Frm_Slaughterhouse: "60"
+ $.schedule[5].MapsWeight.Glo_Level_01: "200"
+ $.schedule[5].MapsWeight.Hos_Treatment: "0"
+ $.schedule[5].MapsWeight.Hti_Manor: "100"
+ $.schedule[5].MapsWeight.Hti_Shrine: "100"
+ $.schedule[5].MapsWeight.Ind_CoalTower: "110"
+ $.schedule[5].MapsWeight.Ind_Forest: "100"
+ $.schedule[5].MapsWeight.Ind_Foundry: "60"
+ $.schedule[5].MapsWeight.Ind_Mine: "100"
+ $.schedule[5].MapsWeight.Ind_Storehouse: "100"
+ $.schedule[5].MapsWeight.Ion_Shack: "60"
+ $.schedule[5].MapsWeight.Ion_level_01: "45"
+ $.schedule[5].MapsWeight.Jnk_Garage: "60"
+ $.schedule[5].MapsWeight.Jnk_GasStation: "100"
+ $.schedule[5].MapsWeight.Jnk_Lodge: "60"
+ $.schedule[5].MapsWeight.Jnk_Office: "60"
+ $.schedule[5].MapsWeight.Jnk_Scrapyard: "100"
+ $.schedule[5].MapsWeight.Kny_Cottage: "200"
+ $.schedule[5].MapsWeight.Mtr_Level_1: "70"
+ $.schedule[5].MapsWeight.Qat_Lab: "45"
+ $.schedule[5].MapsWeight.Qtm_Level_01: "90"
+ $.schedule[5].MapsWeight.Qtm_Level_02: "0"
+ $.schedule[5].MapsWeight.Sub_Street: "0"
+ $.schedule[5].MapsWeight.Swp_GrimPantry: "90"
+ $.schedule[5].MapsWeight.Swp_PaleRose: "90"
+ $.schedule[5].MapsWeight.Uba_Level_01: "100"
+ $.schedule[5].MapsWeight.Ukr_Saloon: "200"
+ $.schedule[5].MapsWeight.Wal_Level_01: "0"
+ $.schedule[5].MapsWeight.Wrm_Level_01: "90"
- $.schedule[5].Priority: "6"
+ $.schedule[5].Priority: "7"
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.Quiche
- $.dlcList.Aurora.availableEndDateInMs: 1704726000
+ $.dlcList.Aurora.availableEndDateInMs: 1704726000000
- $.dlcList.Aurora.availableStartDateInMs: 1577854800
+ $.dlcList.Aurora.availableStartDateInMs: 1577854800000
- $.dlcList.ChurrosCust.availableStartDateInMs: 1717444800
+ $.dlcList.ChurrosCust.availableStartDateInMs: 1717444800000
- $.dlcList.Comet.availableEndDateInMs: 1704726000
+ $.dlcList.Comet.availableEndDateInMs: 1704726000000
- $.dlcList.Comet.availableStartDateInMs: 1577854800
+ $.dlcList.Comet.availableStartDateInMs: 1577854800000
- $.dlcList.DonutCust.availableStartDateInMs: 1721160000
+ $.dlcList.DonutCust.availableStartDateInMs: 1721160000000
- $.dlcList.Guam.availableEndDateInMs: 1704726000
+ $.dlcList.Guam.availableEndDateInMs: 1704726000000
- $.dlcList.Guam.availableStartDateInMs: 1577854800
+ $.dlcList.Guam.availableStartDateInMs: 1577854800000
- $.dlcList.Haiti.availableEndDateInMs: 1704726000
+ $.dlcList.Haiti.availableEndDateInMs: 1704726000000
- $.dlcList.Haiti.availableStartDateInMs: 1577854800
+ $.dlcList.Haiti.availableStartDateInMs: 1577854800000
- $.dlcList.HeritagePack1.availableStartDateInMs: 1704726000
+ $.dlcList.HeritagePack1.availableStartDateInMs: 1704726000000
- $.dlcList.HeritagePack2.availableStartDateInMs: 1704726000
+ $.dlcList.HeritagePack2.availableStartDateInMs: 1704726000000
- $.dlcList.HeritagePack3.availableStartDateInMs: 1704726000
+ $.dlcList.HeritagePack3.availableStartDateInMs: 1704726000000
- $.dlcList.HeritagePack4.availableStartDateInMs: 1715698800
+ $.dlcList.HeritagePack4.availableStartDateInMs: 1715698800000
- $.dlcList.Hubble.availableEndDateInMs: 1704726000
+ $.dlcList.Hubble.availableEndDateInMs: 1704726000000
- $.dlcList.Hubble.availableStartDateInMs: 1577854800
+ $.dlcList.Hubble.availableStartDateInMs: 1577854800000
- $.dlcList.Ion.availableEndDateInMs: 1715698800
+ $.dlcList.Ion.availableEndDateInMs: 1715698800000
- $.dlcList.Ion.availableStartDateInMs: 1577854800
+ $.dlcList.Ion.availableStartDateInMs: 1577854800000
- $.dlcList.Kenya.availableEndDateInMs: 1704726000
+ $.dlcList.Kenya.availableEndDateInMs: 1704726000000
- $.dlcList.Kenya.availableStartDateInMs: 1577854800
+ $.dlcList.Kenya.availableStartDateInMs: 1577854800000
- $.dlcList.Mali.availableEndDateInMs: 1704726000
+ $.dlcList.Mali.availableEndDateInMs: 1704726000000
- $.dlcList.Mali.availableStartDateInMs: 1577854800
+ $.dlcList.Mali.availableStartDateInMs: 1577854800000
- $.dlcList.Meteor.availableEndDateInMs: 1715698800
+ $.dlcList.Meteor.availableEndDateInMs: 1715698800000
- $.dlcList.Meteor.availableStartDateInMs: 1577854800
+ $.dlcList.Meteor.availableStartDateInMs: 1577854800000
- $.dlcList.Quantum.availableEndDateInMs: 1715698800
+ $.dlcList.Quantum.availableEndDateInMs: 1715698800000
- $.dlcList.Quantum.availableStartDateInMs: 1577854800
+ $.dlcList.Quantum.availableStartDateInMs: 1577854800000
- $.dlcList.Saturn.availableEndDateInMs: 1715698800
+ $.dlcList.Saturn.availableEndDateInMs: 1715698800000
- $.dlcList.Saturn.availableStartDateInMs: 1577854800
+ $.dlcList.Saturn.availableStartDateInMs: 1577854800000
- $.dlcList.Sweden.availableEndDateInMs: 1704726000
+ $.dlcList.Sweden.availableEndDateInMs: 1704726000000
- $.dlcList.Sweden.availableStartDateInMs: 1577854800
+ $.dlcList.Sweden.availableStartDateInMs: 1577854800000
- $.dlcList.Ukraine.availableEndDateInMs: 1704726000
+ $.dlcList.Ukraine.availableEndDateInMs: 1704726000000
- $.dlcList.Ukraine.availableStartDateInMs: 1577854800
+ $.dlcList.Ukraine.availableStartDateInMs: 1577854800000
- $.dlcList.UmbraCust1.availableEndDateInMs: 1689703200
+ $.dlcList.UmbraCust1.availableEndDateInMs: 1689703200000
- $.dlcList.UmbraCust1.availableStartDateInMs: 1577854800
+ $.dlcList.UmbraCust1.availableStartDateInMs: 1577854800000
- $.dlcList.UmbraCust2.availableEndDateInMs: 1689703200
+ $.dlcList.UmbraCust2.availableEndDateInMs: 1689703200000
- $.dlcList.UmbraCust2.availableStartDateInMs: 1577854800
+ $.dlcList.UmbraCust2.availableStartDateInMs: 1577854800000
- $.dlcList.Venus.availableStartDateInMs: 1690261200
+ $.dlcList.Venus.availableStartDateInMs: 1690261200000
- $.dlcList.Wormhole.availableStartDateInMs: 1693285200
+ $.dlcList.Wormhole.availableStartDateInMs: 1693285200000
- $.dlcList.Yemen.availableEndDateInMs: 1704726000
+ $.dlcList.Yemen.availableEndDateInMs: 1704726000000
- $.dlcList.Yemen.availableStartDateInMs: 1577854800
+ $.dlcList.Yemen.availableStartDateInMs: 1577854800000
- $.dlcList.Yerkes.availableStartDateInMs: 1701147600
+ $.dlcList.Yerkes.availableStartDateInMs: 1701147600000
- $.dlcList.fleshAndMud.availableEndDateInMs: 1704726000
+ $.dlcList.fleshAndMud.availableEndDateInMs: 1704726000000
- $.dlcList.fleshAndMud.availableStartDateInMs: 1577854800
+ $.dlcList.fleshAndMud.availableStartDateInMs: 1577854800000
- $.dlcList.halloween.availableEndDateInMs: 1768838400
+ $.dlcList.halloween.availableEndDateInMs: 1768838400000
- $.dlcList.sparkofMadness.availableEndDateInMs: 1704726000
+ $.dlcList.sparkofMadness.availableEndDateInMs: 1704726000000
- $.dlcList.sparkofMadness.availableStartDateInMs: 1577854800
+ $.dlcList.sparkofMadness.availableStartDateInMs: 1577854800000
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[0].contentVersion: "372f56e4ce889f50dc5ac47446d35c1dea0ee9ca"
+ $.entries[0].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
- $.entries[0].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Bloodmoon_Bundle.T_UI_SpecialPack_Bloodmoon_Bundle"
+ $.entries[0].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
- $.entries[0].uri: "images/T_UI_SpecialPack_Bloodmoon_Bundle.png"
+ $.entries[0].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
- $.entries[1].contentVersion: "cf7cf00b919d33db2cac5803060754bacc45871e"
+ $.entries[1].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
- $.entries[1].downloadStrategy: "preferRemote"
+ $.entries[1].downloadStrategy: "preferPackaged"
- $.entries[1].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_MiNABundle.T_UI_SpecialPack_MiNABundle"
+ $.entries[1].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
- $.entries[1].uri: "images/T_UI_SpecialPack_MiNABundle.png"
+ $.entries[1].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
- $.entries[2].contentVersion: "7b6a8c3f1f8a8150a5bfc76ffb1c0308d8d00dae"
+ $.entries[2].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
- $.entries[2].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/ChapterBundles/T_UI_ChapterBundle_AllKillComeback.T_UI_ChapterBundle_AllKillComeback"
+ $.entries[2].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
- $.entries[2].uri: "images/T_UI_ChapterBundle_AllKillComeback.png"
+ $.entries[2].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
- $.entries[3].contentVersion: "f7c93776f522193fdbac58c1416ed2bb8ee190ec"
+ $.entries[3].contentVersion: "71da739acc05234bcde2dc3f02f5b684af477eba"
- $.entries[3].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_GenQuest1.T_UI_Tutorial_ImageBG_GenQuest1"
+ $.entries[3].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Poutine/T_UI_CollectionBanner_EldritchNightmares.T_UI_CollectionBanner_EldritchNightmares"
- $.entries[3].uri: "images/T_UI_Tutorial_ImageBG_GenQuest1.png"
+ $.entries[3].uri: "images/T_UI_CollectionBanner_EldritchNightmares.png"
- $.entries[4].contentVersion: "4ae305ae1f966db3228ce77826da57e2ece140b4"
+ $.entries[4].contentVersion: "9555817f05628fe8332fe67c508a029dce563092"
- $.entries[4].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_cosmetic.T_UI_Tutorial_ImageBG_cosmetic"
+ $.entries[4].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_EldritchNightmares.T_UI_SpecialPack_EldritchNightmares"
- $.entries[4].uri: "images/T_UI_Tutorial_ImageBG_cosmetic.png"
+ $.entries[4].uri: "images/T_UI_SpecialPack_EldritchNightmares.png"
- $.entries[5].contentVersion: "f8c74b123d0ba3a66d82d9ba6e26486b88797b88"
+ $.entries[5].contentVersion: "84fb38c2c918b402b996ddf9911c599300b41eba"
- $.entries[5].packagedPath: "/DBDUICore/Assets/HUD/Tutorial/T_UI_Tutorial_ImageBG_gift.T_UI_Tutorial_ImageBG_gift"
+ $.entries[5].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Poutine/T_UI_SpecialPack_ModernTales.T_UI_SpecialPack_ModernTales"
- $.entries[5].uri: "images/T_UI_Tutorial_ImageBG_gift.png"
+ $.entries[5].uri: "images/T_UI_SpecialPack_ModernTales.png"
- $.entries[6].contentVersion: "91e8518ba9c09aef7d41865cbd8fbe7f4fdf5fb3"
+ $.entries[6].contentVersion: "c5faeea010ee675875faafdeb984b354451e5965"
- $.entries[6].downloadStrategy: "preferPackaged"
+ $.entries[6].downloadStrategy: "preferRemote"
- $.entries[6].enableChecksum: false
+ $.entries[6].enableChecksum: true
- $.entries[6].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.T_UI_SpecialPack_ArtistsFromTheFog_Haddie"
+ $.entries[6].packagedPath: ""
- $.entries[6].schema: "s3verbin://"
+ $.entries[6].schema: "s3ver://"
- $.entries[6].uri: "images/T_UI_SpecialPack_ArtistsFromTheFog_Haddie.png"
+ $.entries[6].uri: "catalog.json"
- $.entries[7].contentVersion: "959fabeeccb034819147e5d0ba2cdd5401766d60"
+ $.entries[7].contentVersion: "8901b96443a3bdf0e321f2d21a08066573a8ecfa"
- $.entries[7].downloadStrategy: "preferPackaged"
+ $.entries[7].downloadStrategy: "preferRemote"
- $.entries[7].enableChecksum: false
+ $.entries[7].enableChecksum: true
- $.entries[7].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_Bloodmoon_Quiche.T_UI_CollectionBanner_Bloodmoon_Quiche"
+ $.entries[7].packagedPath: ""
- $.entries[7].schema: "s3verbin://"
+ $.entries[7].schema: "s3ver://"
- $.entries[7].uri: "images/T_UI_CollectionBanner_Bloodmoon_Quiche.png"
+ $.entries[7].uri: "bonusPointEventsContent.json"
- $.entries[8].contentVersion: "78209c89723d44a3f77e31b1fedcc4ad9cad795b"
+ $.entries[8].contentVersion: "000828fd3685b8f4d440884f8e72171f7a64cc2b"
- $.entries[8].downloadStrategy: "preferPackaged"
+ $.entries[8].downloadStrategy: "preferRemote"
- $.entries[8].enableChecksum: false
+ $.entries[8].enableChecksum: true
- $.entries[8].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_Bloodmoon_Quiche.T_UI_SpecialPack_Bloodmoon_Quiche"
+ $.entries[8].packagedPath: ""
- $.entries[8].schema: "s3verbin://"
+ $.entries[8].schema: "s3ver://"
- $.entries[8].uri: "images/T_UI_SpecialPack_Bloodmoon_Quiche.png"
+ $.entries[8].uri: "freetoplay/NA/event.json"
- $.entries[9].contentVersion: "708c753f60235b611acd71990e30ee888440e536"
+ $.entries[9].contentVersion: "000828fd3685b8f4d440884f8e72171f7a64cc2b"
- $.entries[9].downloadStrategy: "preferPackaged"
+ $.entries[9].downloadStrategy: "preferRemote"
- $.entries[9].enableChecksum: false
+ $.entries[9].enableChecksum: true
- $.entries[9].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/CollectionBanners/Quiche/T_UI_CollectionBanner_AllKillComeback.T_UI_CollectionBanner_AllKillComeback"
+ $.entries[9].packagedPath: ""
- $.entries[9].schema: "s3verbin://"
+ $.entries[9].schema: "s3ver://"
- $.entries[9].uri: "images/T_UI_CollectionBanner_AllKillComeback.png"
+ $.entries[9].uri: "freetoplay/EU/event.json"
- $.entries[10].contentVersion: "f10501984992cfbf10084409d5d0bc4a69117c54"
+ $.entries[10].contentVersion: "c3c51e5edccd798d77c87f4785ed5f31ef01345c"
- $.entries[10].downloadStrategy: "preferPackaged"
+ $.entries[10].downloadStrategy: "preferRemote"
- $.entries[10].enableChecksum: false
+ $.entries[10].enableChecksum: true
- $.entries[10].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_AllKillComeback.T_UI_SpecialPack_AllKillComeback"
+ $.entries[10].packagedPath: ""
- $.entries[10].schema: "s3verbin://"
+ $.entries[10].schema: "s3ver://"
- $.entries[10].uri: "images/T_UI_SpecialPack_AllKillComeback.png"
+ $.entries[10].uri: "archiveQuests/Anniversary2022.json"
- $.entries[11].contentVersion: "618875b6f64dbdcbcf0224a32a85a5c84083dc5c"
+ $.entries[11].contentVersion: "7277c6af4bc32f2c1a87b44c468a42cc0bb686e8"
- $.entries[11].downloadStrategy: "preferPackaged"
+ $.entries[11].downloadStrategy: "preferRemote"
- $.entries[11].enableChecksum: false
+ $.entries[11].enableChecksum: true
- $.entries[11].packagedPath: "/Game/UI/UMGAssets/Icons/Banners/BundleBanners/SpecialPack/Quiche/T_UI_SpecialPack_EntombedRemains.T_UI_SpecialPack_EntombedRemains"
+ $.entries[11].packagedPath: ""
- $.entries[11].schema: "s3verbin://"
+ $.entries[11].schema: "s3ver://"
- $.entries[11].uri: "images/T_UI_SpecialPack_EntombedRemains.png"
+ $.entries[11].uri: "archiveQuests/Anniversary2023.json"
- $.entries[12].contentVersion: "5661753775083f394ec9a92806abe8984bb88336"
+ $.entries[12].contentVersion: "9e6ee5737633dd18437234ed7decb88a5185d441"
- $.entries[12].uri: "catalog.json"
+ $.entries[12].uri: "archiveQuests/Anniversary2024.json"
- $.entries[13].contentVersion: "5b039bbeee491d0b93ceda679c4ace6bbf1de269"
+ $.entries[13].contentVersion: "ec03257afd65f264325c5dfa0b43ebbec5eff7a1"
- $.entries[13].uri: "bonusPointEventsContent.json"
+ $.entries[13].uri: "archiveQuests/CalamariV1.json"
- $.entries[14].contentVersion: "24497671b5d28e596507549ba1b390368e004229"
+ $.entries[14].contentVersion: "177df261327224cd17602dd79af0a8b8d9c52089"
- $.entries[14].uri: "freetoplay/NA/event.json"
+ $.entries[14].uri: "archiveQuests/CalamariV2.json"
- $.entries[15].contentVersion: "24497671b5d28e596507549ba1b390368e004229"
+ $.entries[15].contentVersion: "e2e49a6146f15761220cd7270d4e167682230bab"
- $.entries[15].uri: "freetoplay/EU/event.json"
+ $.entries[15].uri: "archiveQuests/CalamariV3.json"
- $.entries[16].contentVersion: "a6ab361537fd669c667020c309c139dd9169726a"
+ $.entries[16].contentVersion: "4fc5a0bf7a72ff84264548cfd2d08390d3974e87"
- $.entries[16].uri: "archiveQuests/Anniversary2022.json"
+ $.entries[16].uri: "archiveQuests/ChocolateBoxGelato.json"
- $.entries[17].contentVersion: "7af95658408629d63b385a32df713142dc4daf9a"
+ $.entries[17].contentVersion: "1e82b18193419f6d0af92b5c572f4902650d6a23"
- $.entries[17].uri: "archiveQuests/Anniversary2023.json"
+ $.entries[17].uri: "archiveQuests/ChocolateBoxV1.json"
- $.entries[18].contentVersion: "caedd3c30c156efdba80ba2450969344f3f06de8"
+ $.entries[18].contentVersion: "a9c9cd37d6f39209631eadedbf10ce82de1bc8dd"
- $.entries[18].uri: "archiveQuests/Anniversary2024.json"
+ $.entries[18].uri: "archiveQuests/DreadByDaylightZodiac.json"
- $.entries[19].contentVersion: "2c2d8c2f09d5ec34505cd93465105517e954dd1f"
+ $.entries[19].contentVersion: "892b1f512fe83d710222440f1772af7c9fd1713c"
- $.entries[19].uri: "archiveQuests/CalamariV1.json"
+ $.entries[19].uri: "archiveQuests/FireflyV1.json"
- $.entries[20].contentVersion: "fb525c4d73f0614c7a23505500fde5d54327c1a5"
+ $.entries[20].contentVersion: "adb9e2fd4753272ce9c08facc1b9d1f928db528f"
- $.entries[20].uri: "archiveQuests/CalamariV2.json"
+ $.entries[20].uri: "archiveQuests/Halloween2021.json"
- $.entries[21].contentVersion: "e82aae4ae097d3fb68186c0a39dd153ec885130c"
+ $.entries[21].contentVersion: "c52062446c838514ac4ee08d7d50ee91d2268c25"
- $.entries[21].uri: "archiveQuests/CalamariV3.json"
+ $.entries[21].uri: "archiveQuests/Halloween2022.json"
- $.entries[22].contentVersion: "5086ad9a1a1a189159c66c03828a2ca5633b45bc"
+ $.entries[22].contentVersion: "493aa5e353a0b33ef2a0765d1a0b05e81ad32e8e"
- $.entries[22].uri: "archiveQuests/ChocolateBoxGelato.json"
+ $.entries[22].uri: "archiveQuests/Halloween2023.json"
- $.entries[23].contentVersion: "0a0fb13155fa8131aa1dffec559ed4cea9ee1248"
+ $.entries[23].contentVersion: "8dacb61a1a7bf9f7a180b06e534a52eca0f1ec0e"
- $.entries[23].uri: "archiveQuests/ChocolateBoxV1.json"
+ $.entries[23].uri: "archiveQuests/Halloween2024.json"
- $.entries[24].contentVersion: "d8a5bf3acb11316221ac613a48ef082d54295cd7"
+ $.entries[24].contentVersion: "5b56ac557499d92e339e8e64fed9b3765e64dcac"
- $.entries[24].uri: "archiveQuests/DreadByDaylightZodiac.json"
+ $.entries[24].uri: "archiveQuests/Spring2024.json"
- $.entries[25].contentVersion: "5f9ca96219895f64faf52892740543ff15386289"
+ $.entries[25].contentVersion: "5ba24237a3d4b6b305d1a1b929a6d5ec375e79bf"
- $.entries[25].uri: "archiveQuests/FireflyV1.json"
+ $.entries[25].uri: "archiveQuests/Spring2025.json"
- $.entries[26].contentVersion: "01097afbbdec37d09ff591dd9bb6ef310e525ba5"
+ $.entries[26].contentVersion: "ccc30dd584f57917f268766bf0d63d0858562059"
- $.entries[26].uri: "archiveQuests/Halloween2021.json"
+ $.entries[26].uri: "archiveQuests/Summer2023.json"
- $.entries[27].contentVersion: "b185cd1ff0408d8ec7bd78e651adcf2239efa6a1"
+ $.entries[27].contentVersion: "f0b83c18cc60807c15a09c3a419a7fe1279c2594"
- $.entries[27].uri: "archiveQuests/Halloween2022.json"
+ $.entries[27].uri: "archiveQuests/Tome01.json"
- $.entries[28].contentVersion: "8f0046ba012d7daa8a3788679ec72153b27d45c5"
+ $.entries[28].contentVersion: "2c49c3e2b9cd76c82a736fcbd4c60bab49c32cec"
- $.entries[28].uri: "archiveQuests/Halloween2023.json"
+ $.entries[28].uri: "archiveQuests/Tome02.json"
- $.entries[29].contentVersion: "330f90e261b32487bb4580abaa84230ac8bf7b77"
+ $.entries[29].contentVersion: "12b81ef02a3a86e72003d2c5831f965b1f78af1c"
- $.entries[29].uri: "archiveQuests/Halloween2024.json"
+ $.entries[29].uri: "archiveQuests/Tome03.json"
- $.entries[30].contentVersion: "4eb83fa8ed7a4a416f976130cd94eeaee376e8cc"
+ $.entries[30].contentVersion: "1ca66012ea3ee6d0f5f91cc40765144d78deb39e"
- $.entries[30].uri: "archiveQuests/Spring2024.json"
+ $.entries[30].uri: "archiveQuests/Tome04.json"
- $.entries[31].contentVersion: "dbeedabe9895f8b3749a1d64d34632b37b62363e"
+ $.entries[31].contentVersion: "e5f0adc141c67bc5de0ccfc29ef559fa612c1026"
- $.entries[31].uri: "archiveQuests/Spring2025.json"
+ $.entries[31].uri: "archiveQuests/Tome05.json"
- $.entries[32].contentVersion: "812912c39d847143b58a5213124a79536b0d05fb"
+ $.entries[32].contentVersion: "9f7a38a9c8026444e5b1a193445edcb8552b4c8a"
- $.entries[32].uri: "archiveQuests/Summer2023.json"
+ $.entries[32].uri: "archiveQuests/Tome06.json"
- $.entries[33].contentVersion: "ce214f39ff186560de95d48fadd6adf831517bc5"
+ $.entries[33].contentVersion: "fa7a722610132cbd7aa909dfe92c4eca5fe0d4c3"
- $.entries[33].uri: "archiveQuests/Tome01.json"
+ $.entries[33].uri: "archiveQuests/Tome07.json"
- $.entries[34].contentVersion: "f78eec7cd065aeb81c3015ddd80b359e19f1215e"
+ $.entries[34].contentVersion: "3eff5b70af5470fd84d06f6af449cd2b81762816"
… 752 more change(s) — see the commit diff for everything
```

### [`onboarding/onboarding.json`](onboarding/onboarding.json)

[Full line-by-line diff](diffs/onboarding/onboarding.json.diff)

```diff
- $.characters[0].accountCreatedBeforeInMs: 1623769200
+ $.characters[0].accountCreatedBeforeInMs: 1623769200000
- $.characters[1].accountCreatedBeforeInMs: 1623769200
+ $.characters[1].accountCreatedBeforeInMs: 1623769200000
- $.modes[0].createdBeforeInMs: 1683133200
+ $.modes[0].createdBeforeInMs: 1683133200000
- $.modes[1].endDateInMs: 1684256400
+ $.modes[1].endDateInMs: 1684256400000
- $.modes[1].startDateInMs: 1683133200
+ $.modes[1].startDateInMs: 1683133200000
```

### [`prestige/prestige.json`](prestige/prestige.json)

[Full line-by-line diff](diffs/prestige/prestige.json.diff)

```diff
- $.rewards.S52
- $.rewards.Ace[9]
- $.rewards.Ace[10]
- $.rewards.Ace[11]
- $.rewards.Ace[12]
- $.rewards.Adam[9]
- $.rewards.Adam[10]
- $.rewards.Adam[11]
- $.rewards.Adam[12]
- $.rewards.Ash[9]
- $.rewards.Ash[10]
- $.rewards.Ash[11]
- $.rewards.Ash[12]
- $.rewards.Bear[9]
- $.rewards.Bear[10]
- $.rewards.Bear[11]
- $.rewards.Bear[12]
- $.rewards.Bill[9]
- $.rewards.Bill[10]
- $.rewards.Bill[11]
- $.rewards.Bill[12]
- $.rewards.Bob[9]
- $.rewards.Bob[10]
- $.rewards.Bob[11]
- $.rewards.Bob[12]
- $.rewards.Cannibal[9]
- $.rewards.Cannibal[10]
- $.rewards.Cannibal[11]
- $.rewards.Cannibal[12]
- $.rewards.Chuckles[9]
- $.rewards.Chuckles[10]
- $.rewards.Chuckles[11]
- $.rewards.Chuckles[12]
- $.rewards.Claudette[9]
- $.rewards.Claudette[10]
- $.rewards.Claudette[11]
- $.rewards.Claudette[12]
- $.rewards.Clown[9]
- $.rewards.Clown[10]
- $.rewards.Clown[11]
- $.rewards.Clown[12]
- $.rewards.Demogorgon[9]
- $.rewards.Demogorgon[10]
- $.rewards.Demogorgon[11]
- $.rewards.Demogorgon[12]
- $.rewards.Dwight[9]
- $.rewards.Dwight[10]
- $.rewards.Dwight[11]
- $.rewards.Dwight[12]
- $.rewards.Eric[9]
- $.rewards.Eric[10]
- $.rewards.Eric[11]
- $.rewards.Eric[12]
- $.rewards.Feng[9]
- $.rewards.Feng[10]
- $.rewards.Feng[11]
- $.rewards.Feng[12]
- $.rewards.Ghostface[9]
- $.rewards.Ghostface[10]
- $.rewards.Ghostface[11]
- $.rewards.Ghostface[12]
- $.rewards.Gunslinger[9]
- $.rewards.Gunslinger[10]
- $.rewards.Gunslinger[11]
- $.rewards.Gunslinger[12]
- $.rewards.HillBilly[9]
- $.rewards.HillBilly[10]
- $.rewards.HillBilly[11]
- $.rewards.HillBilly[12]
- $.rewards.Jake[9]
- $.rewards.Jake[10]
- $.rewards.Jake[11]
- $.rewards.Jake[12]
- $.rewards.Jane[9]
- $.rewards.Jane[10]
- $.rewards.Jane[11]
- $.rewards.Jane[12]
- $.rewards.Jeff[9]
- $.rewards.Jeff[10]
- $.rewards.Jeff[11]
- $.rewards.Jeff[12]
- $.rewards.K20[9]
- $.rewards.K20[10]
- $.rewards.K20[11]
- $.rewards.K20[12]
- $.rewards.K21[9]
- $.rewards.K21[10]
- $.rewards.K21[11]
- $.rewards.K21[12]
- $.rewards.K22[9]
- $.rewards.K22[10]
- $.rewards.K22[11]
- $.rewards.K22[12]
- $.rewards.K23[9]
- $.rewards.K23[10]
- $.rewards.K23[11]
- $.rewards.K23[12]
- $.rewards.K24[9]
- $.rewards.K24[10]
- $.rewards.K24[11]
- $.rewards.K24[12]
- $.rewards.K25[9]
- $.rewards.K25[10]
- $.rewards.K25[11]
- $.rewards.K25[12]
- $.rewards.K26[9]
- $.rewards.K26[10]
- $.rewards.K26[11]
- $.rewards.K26[12]
- $.rewards.K27[9]
- $.rewards.K27[10]
- $.rewards.K27[11]
- $.rewards.K27[12]
- $.rewards.K28[9]
- $.rewards.K28[10]
- $.rewards.K28[11]
- $.rewards.K28[12]
- $.rewards.K29[9]
- $.rewards.K29[10]
- $.rewards.K29[11]
- $.rewards.K29[12]
- $.rewards.K30[9]
- $.rewards.K30[10]
- $.rewards.K30[11]
- $.rewards.K30[12]
- $.rewards.K31[9]
- $.rewards.K31[10]
- $.rewards.K31[11]
- $.rewards.K31[12]
- $.rewards.K32[9]
- $.rewards.K32[10]
- $.rewards.K32[11]
- $.rewards.K32[12]
- $.rewards.K33[9]
- $.rewards.K33[10]
- $.rewards.K33[11]
- $.rewards.K33[12]
- $.rewards.K34[9]
- $.rewards.K34[10]
- $.rewards.K34[11]
- $.rewards.K34[12]
- $.rewards.K35[9]
- $.rewards.K35[10]
- $.rewards.K35[11]
- $.rewards.K35[12]
- $.rewards.K36[9]
- $.rewards.K36[10]
- $.rewards.K36[11]
- $.rewards.K36[12]
- $.rewards.K37[9]
- $.rewards.K37[10]
- $.rewards.K37[11]
- $.rewards.K37[12]
- $.rewards.K38[9]
- $.rewards.K38[10]
- $.rewards.K38[11]
- $.rewards.K38[12]
- $.rewards.K39[9]
- $.rewards.K39[10]
- $.rewards.K39[11]
- $.rewards.K39[12]
- $.rewards.K40[9]
- $.rewards.K40[10]
- $.rewards.K40[11]
- $.rewards.K40[12]
- $.rewards.K41[9]
- $.rewards.K41[10]
- $.rewards.K41[11]
- $.rewards.K41[12]
- $.rewards.K42[9]
- $.rewards.K42[10]
- $.rewards.K42[11]
- $.rewards.K42[12]
- $.rewards.Kate[9]
- $.rewards.Kate[10]
- $.rewards.Kate[11]
- $.rewards.Kate[12]
- $.rewards.Killer07[9]
- $.rewards.Killer07[10]
- $.rewards.Killer07[11]
- $.rewards.Killer07[12]
- $.rewards.Laurie[9]
- $.rewards.Laurie[10]
- $.rewards.Laurie[11]
- $.rewards.Laurie[12]
- $.rewards.Legion[9]
- $.rewards.Legion[10]
- $.rewards.Legion[11]
- $.rewards.Legion[12]
- $.rewards.Meg[9]
- $.rewards.Meg[10]
- $.rewards.Meg[11]
- $.rewards.Meg[12]
- $.rewards.Nancy[9]
- $.rewards.Nancy[10]
- $.rewards.Nancy[11]
- $.rewards.Nancy[12]
- $.rewards.Nea[9]
- $.rewards.Nea[10]
- $.rewards.Nea[11]
… 173 more change(s) — see the commit diff for everything
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
- $.featuredCard[id=QuicheW1]
- $.featuredCard[id=QuicheW1_2]
- $.featuredCard[id=QuicheW2]
- $.featuredCard[id=QuicheW3]
- $.featuredCard[id=QuicheW4]
- $.featuredCard[id=QuicheW5]
- $.featuredCard[id=QuicheW6]
+ $.featuredCard[id=PoutineW8]
- $.featuredCard[id=FeaturedCrossPromo].activeFromInMs: 1721156400
+ $.featuredCard[id=FeaturedCrossPromo].activeFromInMs: 1721156400000
- $.featuredCard[id=FeaturedCrossPromo].activeToInMs: 1725217200
+ $.featuredCard[id=FeaturedCrossPromo].activeToInMs: 1725217200000
- $.featuredCard[id=FeaturedCrossPromo_Purchase].activeFromInMs: 1725390000
+ $.featuredCard[id=FeaturedCrossPromo_Purchase].activeFromInMs: 1725390000000
- $.featuredCard[id=FeaturedCrossPromo_Purchase].activeToInMs: 1726081200
+ $.featuredCard[id=FeaturedCrossPromo_Purchase].activeToInMs: 1726081200000
- $.featuredCard[id=FeaturedCrossPromo_Purchase_Live].activeFromInMs: 1726081200
+ $.featuredCard[id=FeaturedCrossPromo_Purchase_Live].activeFromInMs: 1726081200000
- $.featuredCard[id=FeaturedCrossPromo_Purchase_Live].activeToInMs: 1733252400
+ $.featuredCard[id=FeaturedCrossPromo_Purchase_Live].activeToInMs: 1733252400000
- $.featuredCard[id=HotdogW3].activeFromInMs: 1739203200
+ $.featuredCard[id=HotdogW3].activeFromInMs: 1739203200000
- $.featuredCard[id=HotdogW3].activeToInMs: 1740499200
+ $.featuredCard[id=HotdogW3].activeToInMs: 1740499200000
- $.featuredCard[id=HotdogW4].activeFromInMs: 1740499200
+ $.featuredCard[id=HotdogW4].activeFromInMs: 1740499200000
- $.featuredCard[id=HotdogW4].activeToInMs: 1741104000
+ $.featuredCard[id=HotdogW4].activeToInMs: 1741104000000
- $.featuredCard[id=HotdogW5].activeFromInMs: 1741104000
+ $.featuredCard[id=HotdogW5].activeFromInMs: 1741104000000
- $.featuredCard[id=HotdogW5].activeToInMs: 1741705200
+ $.featuredCard[id=HotdogW5].activeToInMs: 1741705200000
- $.featuredCard[id=HotdogW6].activeFromInMs: 1741705200
+ $.featuredCard[id=HotdogW6].activeFromInMs: 1741705200000
- $.featuredCard[id=HotdogW6].activeToInMs: 1742310000
+ $.featuredCard[id=HotdogW6].activeToInMs: 1742310000000
- $.featuredCard[id=HotdogW7].activeFromInMs: 1742310000
+ $.featuredCard[id=HotdogW7].activeFromInMs: 1742310000000
- $.featuredCard[id=HotdogW7].activeToInMs: 1742914800
+ $.featuredCard[id=HotdogW7].activeToInMs: 1742914800000
- $.featuredCard[id=HotdogW8].activeFromInMs: 1742914800
+ $.featuredCard[id=HotdogW8].activeFromInMs: 1742914800000
- $.featuredCard[id=HotdogW8].activeToInMs: 1743606000
+ $.featuredCard[id=HotdogW8].activeToInMs: 1743606000000
- $.featuredCard[id=IcecreamW1].activeFromInMs: 1743606000
+ $.featuredCard[id=IcecreamW1].activeFromInMs: 1743606000000
- $.featuredCard[id=IcecreamW1].activeToInMs: 1744038000
+ $.featuredCard[id=IcecreamW1].activeToInMs: 1744038000000
- $.featuredCard[id=IcecreamW2].activeFromInMs: 1744038000
+ $.featuredCard[id=IcecreamW2].activeFromInMs: 1744038000000
- $.featuredCard[id=IcecreamW2].activeToInMs: 1745334000
+ $.featuredCard[id=IcecreamW2].activeToInMs: 1745334000000
- $.featuredCard[id=Jerky_W1].activeFromInMs: 1746543600
+ $.featuredCard[id=Jerky_W1].activeFromInMs: 1746543600000
- $.featuredCard[id=Jerky_W1].activeToInMs: 1746716400
+ $.featuredCard[id=Jerky_W1].activeToInMs: 1746716400000
- $.featuredCard[id=Jerky_W2].activeFromInMs: 1746716400
+ $.featuredCard[id=Jerky_W2].activeFromInMs: 1746716400000
- $.featuredCard[id=Jerky_W2].activeToInMs: 1747062000
+ $.featuredCard[id=Jerky_W2].activeToInMs: 1747062000000
- $.featuredCard[id=Jerky_W3].activeFromInMs: 1747062000
+ $.featuredCard[id=Jerky_W3].activeFromInMs: 1747062000000
- $.featuredCard[id=Jerky_W3].activeToInMs: 1747321200
+ $.featuredCard[id=Jerky_W3].activeToInMs: 1747321200000
- $.featuredCard[id=Jerky_W4].activeFromInMs: 1747321200
+ $.featuredCard[id=Jerky_W4].activeFromInMs: 1747321200000
- $.featuredCard[id=Jerky_W4].activeToInMs: 1747753200
+ $.featuredCard[id=Jerky_W4].activeToInMs: 1747753200000
- $.featuredCard[id=Jerky_W5].activeFromInMs: 1747753200
+ $.featuredCard[id=Jerky_W5].activeFromInMs: 1747753200000
- $.featuredCard[id=Jerky_W5].activeToInMs: 1748358000
+ $.featuredCard[id=Jerky_W5].activeToInMs: 1748358000000
- $.featuredCard[id=Jerky_W6].activeFromInMs: 1748358000
+ $.featuredCard[id=Jerky_W6].activeFromInMs: 1748358000000
- $.featuredCard[id=Jerky_W6].activeToInMs: 1748962800
+ $.featuredCard[id=Jerky_W6].activeToInMs: 1748962800000
- $.featuredCard[id=KetchupW1].activeFromInMs: 1747494000
+ $.featuredCard[id=KetchupW1].activeFromInMs: 1747494000000
- $.featuredCard[id=KetchupW1].activeToInMs: 1750950000
+ $.featuredCard[id=KetchupW1].activeToInMs: 1750950000000
- $.featuredCard[id=KetchupW2].activeFromInMs: 1750950000
+ $.featuredCard[id=KetchupW2].activeFromInMs: 1750950000000
- $.featuredCard[id=KetchupW2].activeToInMs: 1751468400
+ $.featuredCard[id=KetchupW2].activeToInMs: 1751468400000
- $.featuredCard[id=KetchupW3].activeFromInMs: 1751468400
+ $.featuredCard[id=KetchupW3].activeFromInMs: 1751468400000
- $.featuredCard[id=KetchupW3].activeToInMs: 1751986800
+ $.featuredCard[id=KetchupW3].activeToInMs: 1751986800000
- $.featuredCard[id=KetchupW4].activeFromInMs: 1751986800
+ $.featuredCard[id=KetchupW4].activeFromInMs: 1751986800000
- $.featuredCard[id=KetchupW4].activeToInMs: 1752764400
+ $.featuredCard[id=KetchupW4].activeToInMs: 1752764400000
- $.featuredCard[id=Lasagna].activeFromInMs: 1753801200
+ $.featuredCard[id=Lasagna].activeFromInMs: 1753801200000
- $.featuredCard[id=Lasagna].activeToInMs: 1754406000
+ $.featuredCard[id=Lasagna].activeToInMs: 1754406000000
- $.featuredCard[id=Lasagna_W2].activeFromInMs: 1754406000
+ $.featuredCard[id=Lasagna_W2].activeFromInMs: 1754406000000
- $.featuredCard[id=Lasagna_W2].activeToInMs: 1755010800
+ $.featuredCard[id=Lasagna_W2].activeToInMs: 1755010800000
- $.featuredCard[id=Lasagna_W3].activeFromInMs: 1755010800
+ $.featuredCard[id=Lasagna_W3].activeFromInMs: 1755010800000
- $.featuredCard[id=Lasagna_W3].activeToInMs: 1755615600
+ $.featuredCard[id=Lasagna_W3].activeToInMs: 1755615600000
- $.featuredCard[id=Lasagna_W4].activeFromInMs: 1755615600
+ $.featuredCard[id=Lasagna_W4].activeFromInMs: 1755615600000
- $.featuredCard[id=Lasagna_W4].activeToInMs: 1756825200
+ $.featuredCard[id=Lasagna_W4].activeToInMs: 1756825200000
- $.featuredCard[id=Lasagna_W5].activeFromInMs: 1756825200
+ $.featuredCard[id=Lasagna_W5].activeFromInMs: 1756825200000
- $.featuredCard[id=Lasagna_W5].activeToInMs: 1757430000
+ $.featuredCard[id=Lasagna_W5].activeToInMs: 1757430000000
- $.featuredCard[id=Lasagna_W6].activeFromInMs: 1757430000
+ $.featuredCard[id=Lasagna_W6].activeFromInMs: 1757430000000
- $.featuredCard[id=Lasagna_W6].activeToInMs: 1758034800
+ $.featuredCard[id=Lasagna_W6].activeToInMs: 1758034800000
- $.featuredCard[id=Lasagna_W7].activeFromInMs: 1758034800
+ $.featuredCard[id=Lasagna_W7].activeFromInMs: 1758034800000
- $.featuredCard[id=Lasagna_W7].activeToInMs: 1758639600
+ $.featuredCard[id=Lasagna_W7].activeToInMs: 1758639600000
- $.featuredCard[id=Maple].activeFromInMs: 1756306800
+ $.featuredCard[id=Maple].activeFromInMs: 1756306800000
- $.featuredCard[id=Maple].activeToInMs: 1759244400
+ $.featuredCard[id=Maple].activeToInMs: 1759244400000
- $.featuredCard[id=Maple_W2].activeFromInMs: 1759244400
+ $.featuredCard[id=Maple_W2].activeFromInMs: 1759244400000
- $.featuredCard[id=Maple_W2].activeToInMs: 1759849200
+ $.featuredCard[id=Maple_W2].activeToInMs: 1759849200000
- $.featuredCard[id=Maple_W3].activeFromInMs: 1759849200
+ $.featuredCard[id=Maple_W3].activeFromInMs: 1759849200000
- $.featuredCard[id=Maple_W3].activeToInMs: 1760022000
+ $.featuredCard[id=Maple_W3].activeToInMs: 1760022000000
- $.featuredCard[id=Maple_W4].activeFromInMs: 1760022000
+ $.featuredCard[id=Maple_W4].activeFromInMs: 1760022000000
- $.featuredCard[id=Maple_W4].activeToInMs: 1760454000
+ $.featuredCard[id=Maple_W4].activeToInMs: 1760454000000
- $.featuredCard[id=Maple_W5].activeFromInMs: 1760454000
+ $.featuredCard[id=Maple_W5].activeFromInMs: 1760454000000
- $.featuredCard[id=Maple_W5].activeToInMs: 1761663600
+ $.featuredCard[id=Maple_W5].activeToInMs: 1761663600000
- $.featuredCard[id=Maple_W6].activeFromInMs: 1761663600
+ $.featuredCard[id=Maple_W6].activeFromInMs: 1761663600000
- $.featuredCard[id=Maple_W6].activeToInMs: 1761922800
+ $.featuredCard[id=Maple_W6].activeToInMs: 1761922800000
- $.featuredCard[id=Maple_W7].activeFromInMs: 1761922800
+ $.featuredCard[id=Maple_W7].activeFromInMs: 1761922800000
- $.featuredCard[id=Maple_W7].activeToInMs: 1762444800
+ $.featuredCard[id=Maple_W7].activeToInMs: 1762444800000
- $.featuredCard[id=Maple_W8].activeFromInMs: 1762444800
+ $.featuredCard[id=Maple_W8].activeFromInMs: 1762444800000
- $.featuredCard[id=Maple_W8].activeToInMs: 1763481600
+ $.featuredCard[id=Maple_W8].activeToInMs: 1763481600000
- $.featuredCard[id=Maple_W9].activeFromInMs: 1763481600
+ $.featuredCard[id=Maple_W9].activeFromInMs: 1763481600000
- $.featuredCard[id=Maple_W9].activeToInMs: 1764086400
+ $.featuredCard[id=Maple_W9].activeToInMs: 1764086400000
- $.featuredCard[id=Omelet].activeFromInMs: 1764086400
+ $.featuredCard[id=Omelet].activeFromInMs: 1764086400000
- $.featuredCard[id=Omelet].activeToInMs: 1764604800
+ $.featuredCard[id=Omelet].activeToInMs: 1764604800000
- $.featuredCard[id=Omelet_W2].activeFromInMs: 1764604800
+ $.featuredCard[id=Omelet_W2].activeFromInMs: 1764604800000
- $.featuredCard[id=Omelet_W2].activeToInMs: 1765296000
+ $.featuredCard[id=Omelet_W2].activeToInMs: 1765296000000
- $.featuredCard[id=Omelet_W3].activeFromInMs: 1765296000
+ $.featuredCard[id=Omelet_W3].activeFromInMs: 1765296000000
- $.featuredCard[id=Omelet_W3].activeToInMs: 1767715200
+ $.featuredCard[id=Omelet_W3].activeToInMs: 1767715200000
- $.featuredCard[id=Omelet_W4].activeFromInMs: 1767715200
+ $.featuredCard[id=Omelet_W4].activeFromInMs: 1767715200000
- $.featuredCard[id=Omelet_W4].activeToInMs: 1768320000
+ $.featuredCard[id=Omelet_W4].activeToInMs: 1768320000000
- $.featuredCard[id=Omelet_W5].activeFromInMs: 1768320000
+ $.featuredCard[id=Omelet_W5].activeFromInMs: 1768320000000
- $.featuredCard[id=Omelet_W5].activeToInMs: 1769184000
+ $.featuredCard[id=Omelet_W5].activeToInMs: 1769184000000
- $.featuredCard[id=Omelet_W6].activeFromInMs: 1769184000
+ $.featuredCard[id=Omelet_W6].activeFromInMs: 1769184000000
- $.featuredCard[id=Omelet_W6].activeToInMs: 1769529600
+ $.featuredCard[id=Omelet_W6].activeToInMs: 1769529600000
- $.featuredCard[id=PoutinePTB].activeFromInMs: 1766073600
+ $.featuredCard[id=PoutinePTB].activeFromInMs: 1766073600000
- $.featuredCard[id=PoutinePTB].activeToInMs: 1769529600
+ $.featuredCard[id=PoutinePTB].activeToInMs: 1769529600000
- $.featuredCard[id=PoutineW1].activeFromInMs: 1769529600
+ $.featuredCard[id=PoutineW1].activeFromInMs: 1769529600000
- $.featuredCard[id=PoutineW1].activeToInMs: 1770134400
+ $.featuredCard[id=PoutineW1].activeToInMs: 1770134400000
- $.featuredCard[id=PoutineW2].activeFromInMs: 1770134400
+ $.featuredCard[id=PoutineW2].activeFromInMs: 1770134400000
- $.featuredCard[id=PoutineW2].activeToInMs: 1770739200
+ $.featuredCard[id=PoutineW2].activeToInMs: 1770739200000
- $.featuredCard[id=PoutineW3].activeFromInMs: 1770739200
+ $.featuredCard[id=PoutineW3].activeFromInMs: 1770739200000
- $.featuredCard[id=PoutineW3].activeToInMs: 1770912000
+ $.featuredCard[id=PoutineW3].activeToInMs: 1770912000000
- $.featuredCard[id=PoutineW4].activeFromInMs: 1770912000
+ $.featuredCard[id=PoutineW4].activeFromInMs: 1770912000000
- $.featuredCard[id=PoutineW4].activeToInMs: 1771948800
+ $.featuredCard[id=PoutineW4].activeToInMs: 1771948800000
… 392 more change(s) — see the commit diff for everything
```

### [`specialEventsContent.json`](specialEventsContent.json)

[Full line-by-line diff](diffs/specialEventsContent.json.diff)

```diff
+ $.specialEvents[65].eventName
+ $.specialEvents[65].eventType: "MapShowcase"
- $.specialEvents[65].eventId: "Spring2026"
+ $.specialEvents[65].eventId: "MapShowcase_Omelet_01"
- $.specialEvents[65].mainEndTime: "2026-04-16T15:00:00"
+ $.specialEvents[65].mainEndTime: "2025-12-05T15:59:42"
- $.specialEvents[65].postEndTime: "2026-04-16T15:00:00"
+ $.specialEvents[65].postEndTime: "2025-12-05T15:59:42"
- $.specialEvents[65].startTime: "2026-03-26T15:00:00"
+ $.specialEvents[65].startTime: "2025-12-01T16:00:00"
- $.specialEvents[65].useCommonData: false
+ $.specialEvents[65].useCommonData: true
+ $.specialEvents[66].eventName
+ $.specialEvents[66].eventType: "MapShowcase"
- $.specialEvents[66].eventId: "Spring2026Regular"
+ $.specialEvents[66].eventId: "MapShowcase_Omelet_02"
- $.specialEvents[66].mainEndTime: "2026-04-16T15:00:00"
+ $.specialEvents[66].mainEndTime: "2025-12-09T15:59:42"
- $.specialEvents[66].postEndTime: "2026-04-16T15:00:00"
+ $.specialEvents[66].postEndTime: "2025-12-09T15:59:42"
- $.specialEvents[66].startTime: "2026-03-26T15:00:00"
+ $.specialEvents[66].startTime: "2025-12-05T16:00:00"
- $.specialEvents[66].useCommonData: false
+ $.specialEvents[66].useCommonData: true
- $.specialEvents[67]
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod1].endDateInMs: 1678892400
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod1].endDateInMs: 1678892400000
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod1].startDateInMs: 1678806000
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod1].startDateInMs: 1678806000000
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod2].endDateInMs: 1679065200
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod2].endDateInMs: 1679065200000
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod2].startDateInMs: 1678978800
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod2].startDateInMs: 1678978800000
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod3].endDateInMs: 1679324400
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod3].endDateInMs: 1679324400000
- $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod3].startDateInMs: 1679151600
+ $.specialEventsData[4].eventPeriods[id=Barrel2023EventPeriod3].startDateInMs: 1679151600000
- $.specialEventsData[25].eventPeriods[id=Halloween2024].endDateInMs: 1730991600
+ $.specialEventsData[25].eventPeriods[id=Halloween2024].endDateInMs: 1730991600000
- $.specialEventsData[25].eventPeriods[id=Halloween2024].startDateInMs: 1729177200
+ $.specialEventsData[25].eventPeriods[id=Halloween2024].startDateInMs: 1729177200000
- $.specialEventsData[30].eventId: "MapShowcaseQuiche"
+ $.specialEventsData[30].eventId: "MapShowcase_Omelet_01"
+ $.specialEventsData[31].lteData
- $.specialEventsData[31].eventId: "Spring2024"
+ $.specialEventsData[31].eventId: "MapShowcase_Omelet_02"
- $.specialEventsData[31].eventTrackerObjectives[id=main]
- $.specialEventsData[32].lteData
- $.specialEventsData[32].eventId: "Spring2025"
+ $.specialEventsData[32].eventId: "Spring2024"
- $.specialEventsData[32].eventTrackerObjectives[id=main].additionalEventIdsWithMilestoneBonus
- $.specialEventsData[32].eventTrackerObjectives[id=main].questEventConditions
- $.specialEventsData[32].eventTrackerObjectives[id=main].questEvents
+ $.specialEventsData[32].eventTrackerObjectives[id=main].questEventId: "QuestEvent.SpringEventPlaceZone"
+ $.specialEventsData[32].eventTrackerObjectives[id=main].questEventParams: "instigator:me"
- $.specialEventsData[32].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 16
+ $.specialEventsData[32].eventTrackerObjectives[id=main].maxProgressionPerMatchPlayer: 10
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.0
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 2.0
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[1].neededProgression: 7000000
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 3.0
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[2].neededProgression: 20000000
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 4.0
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
+ $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[3].neededProgression: 35000000
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[4]
- $.specialEventsData[32].eventTrackerObjectives[id=main].milestones[5]
- $.specialEventsData[32].milestoneRewards[0]
- $.specialEventsData[32].milestoneRewards[1]
- $.specialEventsData[32].milestoneRewards[2]
- $.specialEventsData[33].eventId: "Spring2026"
+ $.specialEventsData[33].eventId: "Spring2025"
- $.specialEventsData[33].eventPeriods[id=Spring2025]
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.5
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[0].additiveMultiplier: 1.25
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.75
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].additiveMultiplier: 1.5
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].neededProgression: 5000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[1].neededProgression: 2500000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.25
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].additiveMultiplier: 2.0
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].neededProgression: 15000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[2].neededProgression: 10000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 3.0
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].additiveMultiplier: 2.75
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].neededProgression: 25000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[3].neededProgression: 22500000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].additiveMultiplier: 4.0
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].additiveMultiplier: 3.75
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].neededProgression: 40000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[4].neededProgression: 35000000
- $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[5].neededProgression: 55000000
+ $.specialEventsData[33].eventTrackerObjectives[id=main].milestones[5].neededProgression: 50000000
- $.specialEventsData[33].lteData.gameModeQueue: "Spring2026"
+ $.specialEventsData[33].lteData.gameModeQueue: "Spring2025"
+ $.specialEventsData[33].milestoneRewards[0]
+ $.specialEventsData[33].milestoneRewards[1]
+ $.specialEventsData[33].milestoneRewards[2]
- $.specialEventsData[35].eventPeriods[id=Winter2024].endDateInMs: 1736265600
+ $.specialEventsData[35].eventPeriods[id=Winter2024].endDateInMs: 1736265600000
- $.specialEventsData[35].eventPeriods[id=Winter2024].startDateInMs: 1734019200
+ $.specialEventsData[35].eventPeriods[id=Winter2024].startDateInMs: 1734019200000
```

