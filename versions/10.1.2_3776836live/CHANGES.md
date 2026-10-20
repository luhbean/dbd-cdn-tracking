# live · 10.1.2_3776836live

| | |
|---|---|
| Build date | 2026-09-14 16:30 UTC |
| CDN version | `10.1.2_3776836live-1789403411` |
| Key | `10.1.2_live` |
| Compared with | [10.1.2_3772086live](../10.1.2_3772086live/CHANGES.md) (2026-09-11 13:32 UTC) |

## Summary

**0** added · **5** modified · **0** removed · 206 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=From_The_Rift_Bundle_260922]
+ $[id=From_The_Rift_Bundle_260929]
+ $[id=From_The_Rift_Bundle_261006]
+ $[id=Recurring_Charm_Bundle_260915]
+ $[id=Recurring_Dev_Bundle_260915]
- $[id=LicensorBundle_Hellraiser].purchasable: true
+ $[id=LicensorBundle_Hellraiser].purchasable: false
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[59].collectionTitle.fr: "Twitch Shirts"
+ $.collections[59].collectionTitle.fr: "Maillots Twitch"
```

### [`dlcList.json`](dlcList.json)

[Full line-by-line diff](diffs/dlcList.json.diff)

```diff
- $.dlcList.UdonCharm.title: "DLC_UdonCharm_SHORT_NAME"
+ $.dlcList.UdonCharm.title: "@#DLC_UdonCharm_SHORT_NAME"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[7].contentVersion: "8515a69419aa56888bf5a1197d26c76168afa71f"
+ $.entries[7].contentVersion: "6d4e96d82ce8b58ecd78f12fc412a8110bbcbecd"
- $.entries[83].contentVersion: "4bf5a419eefe36e7085a22beef0118a721b0235a"
+ $.entries[83].contentVersion: "b9b249194793197b0f067393faa5f485152fb649"
- $.entries[85].contentVersion: "65cf8c39ebe92e679e5d23b24b9540f23a5bd971"
+ $.entries[85].contentVersion: "4d1c7fa0ac34de99103b50b7566e6d45e6739b7d"
- $.entries[178].contentVersion: "bff9e55b5f2f2a94a9edc37744bce70ff4587db5"
+ $.entries[178].contentVersion: "ab37c6c0d16a08399978bf60096330ec1b275968"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=Udon_W3]
```

