# live · 9.4.2_3093271live

| | |
|---|---|
| Build date | 2026-02-11 15:11 UTC |
| CDN version | `9.4.2_3093271live-1770822687` |
| Key | `9.4.2_live` |
| Compared with | [9.4.2_3088141live](../9.4.2_3088141live/CHANGES.md) (2026-02-10 13:12 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 206 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_260217]
+ $[id=Recurring_Charm_Bundle_260217]
+ $[id=Recurring_Dev_Bundle_260217]
+ $[id=Recurring_Killer_Bundle_260217]
+ $[id=Recurring_Survivor_Bundle_260217]
- $[id=LNY_2026_Bundle].metaData.endDate: "2026-02-24T16:00:00"
+ $[id=LNY_2026_Bundle].metaData.endDate: "2026-02-26T16:00:00"
- $[id=LNY_2026_Bundle].metaData.startDate: "2026-02-17T16:00:00"
+ $[id=LNY_2026_Bundle].metaData.startDate: "2026-02-12T16:00:00"
```

### [`challengeSets.json`](challengeSets.json)

[Full line-by-line diff](diffs/challengeSets.json.diff)

```diff
- $.SilentHillMovie_Set
```

### [`contentSchedule.json`](contentSchedule.json)

[Full line-by-line diff](diffs/contentSchedule.json.diff)

```diff
- $.schedule[6]
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[6].contentVersion: "5114ba5ec9ed06e5bd9946635c0d50e0883a4341"
+ $.entries[6].contentVersion: "0dc2411f85b2c1324e2a91e7705bd08e1662cda5"
- $.entries[80].contentVersion: "11828434adf8b74b27ed437e1359510833c200a1"
+ $.entries[80].contentVersion: "fdf708a54a5cc91c997e3cb3c862a70b31442ad4"
- $.entries[82].contentVersion: "1e0926bfa709c99ed1f718fea3f76bc5a6be7d9f"
+ $.entries[82].contentVersion: "ffe3f79fcfabe56827164af31bca563ec1259a30"
- $.entries[174].contentVersion: "162bcb44a14083d8381e3d1508b218a2bb7324f2"
+ $.entries[174].contentVersion: "9d6f2d4cfff1d393fad48b51de69e2ed32f88aae"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCard[id=PoutineW4]
+ $.featuredCard[id=PoutineW5]
+ $.featuredCard[id=PoutineW6]
+ $.featuredCard[id=PoutineW7]
- $.featuredCard[id=PoutineW3].activeTo: "2026-02-17T16:00:00"
+ $.featuredCard[id=PoutineW3].activeTo: "2026-02-12T16:00:00"
+ $.featuredCustomizationRecommendations[id=Poutine_W4]
+ $.featuredCustomizationRecommendations[id=Poutine_W5]
- $.featuredCustomizationRecommendations[id=Poutine_W3].activeTo: "2026-02-17T16:00:00"
+ $.featuredCustomizationRecommendations[id=Poutine_W3].activeTo: "2026-02-24T16:00:00"
```

