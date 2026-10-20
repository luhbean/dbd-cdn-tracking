# live · 9.5.1_3205696live

| | |
|---|---|
| Build date | 2026-03-24 13:06 UTC |
| CDN version | `9.5.1_3205696live-1774357612` |
| Key | `9.5.1_live` |
| Compared with | [9.5.1_3203471live](../9.5.1_3203471live/CHANGES.md) (2026-03-23 17:06 UTC) |

## Summary

**0** added · **10** modified · **0** removed · 199 unchanged

## Modified files

### [`catalog.json`](catalog.json)

[Full line-by-line diff](diffs/catalog.json.diff)

```diff
+ $[id=DF_Head024].metaData.availablePeriods
+ $[id=HS_Head016].metaData.availablePeriods[1]
- $[id=HS_Head016].metaData.limitedTimeEndDate: "2025-04-08T15:00:00"
+ $[id=HS_Head016].metaData.limitedTimeEndDate: "2026-04-08T15:00:00"
- $[id=HS_Head016].metaData.limitedTimeEndDateInMs: 1744124400
+ $[id=HS_Head016].metaData.limitedTimeEndDateInMs: 1775660400
+ $[id=K35_Head012].metaData.availablePeriods[1]
- $[id=K35_Head012].metaData.limitedTimeEndDate: "2025-04-08T15:00:00"
+ $[id=K35_Head012].metaData.limitedTimeEndDate: "2026-04-08T15:00:00"
- $[id=K35_Head012].metaData.limitedTimeEndDateInMs: 1744124400
+ $[id=K35_Head012].metaData.limitedTimeEndDateInMs: 1775660400
+ $[id=S34_Head018].metaData.availablePeriods[1]
- $[id=S34_Head018].metaData.limitedTimeEndDate: "2025-04-08T15:00:00"
+ $[id=S34_Head018].metaData.limitedTimeEndDate: "2026-04-08T15:00:00"
- $[id=S34_Head018].metaData.limitedTimeEndDateInMs: 1744124400
+ $[id=S34_Head018].metaData.limitedTimeEndDateInMs: 1775660400
- $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle["zh-Hans"]: "MiNA Bundle"
+ $[id=9.5.0_Trickster_Bundle].metaData.specialPackTitle["zh-Hans"]: "米娜组合包"
- $[id=St_Patricks_2026].metaData.specialPackTitle.de: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle.de: "„St. Patrick’s Day“-Paket"
- $[id=St_Patricks_2026].metaData.specialPackTitle.es: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle.es: "Paquete de Día de San Patricio"
- $[id=St_Patricks_2026].metaData.specialPackTitle["es-MX"]: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle["es-MX"]: "Paquete Día de San Patricio"
- $[id=St_Patricks_2026].metaData.specialPackTitle.it: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle.it: "Bundle San Patrizio"
- $[id=St_Patricks_2026].metaData.specialPackTitle["pt-BR"]: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle["pt-BR"]: "Pacote do Dia de São Patrício"
- $[id=St_Patricks_2026].metaData.specialPackTitle.th: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle.th: "แพ็กรวมวันเซนต์แพทริก"
- $[id=St_Patricks_2026].metaData.specialPackTitle["zh-Hans"]: "St. Patrick's Day Bundle"
+ $[id=St_Patricks_2026].metaData.specialPackTitle["zh-Hans"]: "圣帕特里克节组合包"
```

### [`challengeLocs/challengeText_de.json`](challengeLocs/challengeText_de.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_de.json.diff)

```diff
- $.locText[580].text: "Fülle {0}-mal einen Blutkanister."
+ $.locText[580].text: "Fülle insgesamt {0} Blutkanister."
```

### [`challengeLocs/challengeText_es-MX.json`](challengeLocs/challengeText_es-MX.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es-MX.json.diff)

```diff
- $.locText[580].text: "Llena un bidón de sangre {0} vez/veces."
+ $.locText[580].text: "Llena un total de {0} bidón/bidones de sangre"
```

### [`challengeLocs/challengeText_es.json`](challengeLocs/challengeText_es.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_es.json.diff)

```diff
- $.locText[580].text: "Llena un bidón de sangre {0} vez/veces."
+ $.locText[580].text: "Llena {0} bidón/bidones de sangre."
```

### [`challengeLocs/challengeText_it.json`](challengeLocs/challengeText_it.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_it.json.diff)

```diff
- $.locText[580].text: "Riempi una tanica di sangue {0} volta/e"
+ $.locText[580].text: "Riempi {0} tanica/che di sangue"
```

### [`challengeLocs/challengeText_pt-BR.json`](challengeLocs/challengeText_pt-BR.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_pt-BR.json.diff)

```diff
- $.locText[580].text: "Encha um Galão de Sangue {0} vez(es)"
+ $.locText[580].text: "Encha um total de {0} Galão(ões) de Sangue"
```

### [`challengeLocs/challengeText_th.json`](challengeLocs/challengeText_th.json)

[Full line-by-line diff](diffs/challengeLocs/challengeText_th.json.diff)

```diff
- $.locText[580].text: "เติมกระป๋องเลือด {0} ครั้ง"
+ $.locText[580].text: "เติมกระป๋องเลือดรวม {0} ใบ"
```

### [`collections.json`](collections.json)

[Full line-by-line diff](diffs/collections.json.diff)

```diff
- $.collections[51].collectionTitle["zh-Hans"]: "All-Kill: Comeback"
+ $.collections[51].collectionTitle["zh-Hans"]: "赶尽杀绝：回归"
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[4].contentVersion: "73a150e6a1fc9d6e9b0a94cc35d50a5b513ea7a6"
+ $.entries[4].contentVersion: "f96e178df03be94168cc35d126b67d8c2604cb19"
- $.entries[80].contentVersion: "0279cc96815c91f9ca4ba5b7653668aaa9ef1218"
+ $.entries[80].contentVersion: "ce6b5238c307948aa03dacff49335ea5857bb640"
- $.entries[175].contentVersion: "8e4eac016f3c35029420028a1f059fff57c1d0a5"
+ $.entries[175].contentVersion: "d0f5203eec4f02cf145ae5a31836d9eec9d27a1a"
- $.entries[192].contentVersion: "fb6bd7abd4597bca621e1bd5c9ee86797006c44f"
+ $.entries[192].contentVersion: "e2b5d7a992bc8e5b74ecf7fe56f014d029bd9962"
- $.entries[193].contentVersion: "6089c34863adefb68742cf71a46c64e5a632f9bc"
+ $.entries[193].contentVersion: "b7c41d918812583de3b9b690262b8ad925754542"
- $.entries[194].contentVersion: "763fec2152e89c020ce7caa3f0b01a5dabf49282"
+ $.entries[194].contentVersion: "9acadaf7ae686bf9184b4d4cedf07d77f2bd2bbd"
- $.entries[196].contentVersion: "a7820e8710ecc473b6275e60840ee0f42687545d"
+ $.entries[196].contentVersion: "e97de188fceb39505d6b4ded0c394e181a8debe7"
- $.entries[200].contentVersion: "0fa9d81b1844fb900dc40edf97345076a34e68ff"
+ $.entries[200].contentVersion: "f72a88f7044b81328afe24a8a695e2375fb531e0"
- $.entries[202].contentVersion: "74d34df65d9acd12ce9a8d4b399e9eca4bf00148"
+ $.entries[202].contentVersion: "85867ef4b855926ce79738be3423bc7427816958"
```

### [`recommendations.json`](recommendations.json)

[Full line-by-line diff](diffs/recommendations.json.diff)

```diff
+ $.featuredCustomizationRecommendations[id=Quiche_W3_AprilFools]
+ $.featuredCustomizationRecommendations[id=Quiche_W3_2]
- $.featuredCustomizationRecommendations[id=Quiche_W3].activeTo: "2026-04-07T15:00:00"
+ $.featuredCustomizationRecommendations[id=Quiche_W3].activeTo: "2026-04-01T15:00:00"
- $.featuredCustomizationRecommendations[id=Quiche_W3].activeToInMs: 1775574000
+ $.featuredCustomizationRecommendations[id=Quiche_W3].activeToInMs: 1775055600
```

