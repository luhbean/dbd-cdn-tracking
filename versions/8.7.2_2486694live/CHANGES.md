# live · 8.7.2_2486694live

| | |
|---|---|
| Build date | 2025-06-03 14:38 UTC |
| CDN version | `8.7.2_2486694live-1748961506` |
| Key | `8.7.2_live` |
| Compared with | [8.7.2_2485436live](../8.7.2_2485436live/CHANGES.md) (2025-06-02 18:34 UTC) |

## Summary

**0** added · **3** modified · **0** removed · 199 unchanged

## Modified files

### [`GameConfigs.json`](GameConfigs.json)

[Full line-by-line diff](diffs/GameConfigs.json.diff)

```diff
- $.contentVersion.clientNewContentRebootMaxSeconds: 600.0
+ $.contentVersion.clientNewContentRebootMaxSeconds: 1800.0
```

### [`bonusPointEventsContent.json`](bonusPointEventsContent.json)

[Full line-by-line diff](diffs/bonusPointEventsContent.json.diff)

```diff
- $.bonusPointEvents[0].endTime: "2025-03-31T14:59:00"
+ $.bonusPointEvents[0].endTime: "2025-06-17T14:59:00"
- $.bonusPointEvents[0].startTime: "2025-03-18T15:00:00"
+ $.bonusPointEvents[0].startTime: "2025-06-03T15:00:00"
- $.bonusPointEvents[1].endTime: "2025-02-10T15:59:00"
+ $.bonusPointEvents[1].endTime: "2025-03-31T14:59:00"
- $.bonusPointEvents[1].startTime: "2025-02-04T16:00:00"
+ $.bonusPointEvents[1].startTime: "2025-03-18T15:00:00"
- $.bonusPointEvents[2].endTime: "2025-01-28T15:59:00"
+ $.bonusPointEvents[2].endTime: "2025-02-10T15:59:00"
- $.bonusPointEvents[2].startTime: "2025-01-21T16:00:00"
+ $.bonusPointEvents[2].startTime: "2025-02-04T16:00:00"
- $.bonusPointEvents[3].endTime: "2025-01-07T15:59:00"
+ $.bonusPointEvents[3].endTime: "2025-01-28T15:59:00"
- $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[3].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[3].multiplier: 3.0
+ $.bonusPointEvents[3].multiplier: 2.0
- $.bonusPointEvents[3].startTime: "2024-12-26T16:00:00"
+ $.bonusPointEvents[3].startTime: "2025-01-21T16:00:00"
- $.bonusPointEvents[4].endTime: "2024-12-26T15:59:00"
+ $.bonusPointEvents[4].endTime: "2025-01-07T15:59:00"
- $.bonusPointEvents[4].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[4].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[4].multiplier: 2.0
+ $.bonusPointEvents[4].multiplier: 3.0
- $.bonusPointEvents[4].startTime: "2024-12-19T16:00:00"
+ $.bonusPointEvents[4].startTime: "2024-12-26T16:00:00"
- $.bonusPointEvents[5].endTime: "2024-11-28T16:00:00"
+ $.bonusPointEvents[5].endTime: "2024-12-26T15:59:00"
- $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[5].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[5].multiplier: 3.0
+ $.bonusPointEvents[5].multiplier: 2.0
- $.bonusPointEvents[5].startTime: "2024-11-22T20:00:00"
+ $.bonusPointEvents[5].startTime: "2024-12-19T16:00:00"
- $.bonusPointEvents[6].endTime: "2024-10-01T15:00:00"
+ $.bonusPointEvents[6].endTime: "2024-11-28T16:00:00"
- $.bonusPointEvents[6].startTime: "2024-09-24T15:00:00"
+ $.bonusPointEvents[6].startTime: "2024-11-22T20:00:00"
- $.bonusPointEvents[7].endTime: "2024-09-12T15:00:00"
+ $.bonusPointEvents[7].endTime: "2024-10-01T15:00:00"
- $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[7].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[7].multiplier: 2.0
+ $.bonusPointEvents[7].multiplier: 3.0
- $.bonusPointEvents[7].startTime: "2024-09-05T15:00:00"
+ $.bonusPointEvents[7].startTime: "2024-09-24T15:00:00"
- $.bonusPointEvents[8].endTime: "2024-06-13T15:00:00"
+ $.bonusPointEvents[8].endTime: "2024-09-12T15:00:00"
- $.bonusPointEvents[8].startTime: "2024-06-03T15:00:00"
+ $.bonusPointEvents[8].startTime: "2024-09-05T15:00:00"
- $.bonusPointEvents[9].endTime: "2024-05-21T15:00:00"
+ $.bonusPointEvents[9].endTime: "2024-06-13T15:00:00"
- $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodfeast_NAME"
+ $.bonusPointEvents[9].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[9].multiplier: 3.0
+ $.bonusPointEvents[9].multiplier: 2.0
- $.bonusPointEvents[9].startTime: "2024-05-14T16:00:00"
+ $.bonusPointEvents[9].startTime: "2024-06-03T15:00:00"
- $.bonusPointEvents[10].endTime: "2024-02-20T16:00:00"
+ $.bonusPointEvents[10].endTime: "2024-05-21T15:00:00"
- $.bonusPointEvents[10].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[10].eventTitle: "BPEVENT_Bloodfeast_NAME"
- $.bonusPointEvents[10].multiplier: 1.5
+ $.bonusPointEvents[10].multiplier: 3.0
- $.bonusPointEvents[10].startTime: "2024-02-14T16:00:00"
+ $.bonusPointEvents[10].startTime: "2024-05-14T16:00:00"
- $.bonusPointEvents[11].endTime: "2023-09-19T15:00:00"
+ $.bonusPointEvents[11].endTime: "2024-02-20T16:00:00"
- $.bonusPointEvents[11].startTime: "2023-09-12T15:00:00"
+ $.bonusPointEvents[11].startTime: "2024-02-14T16:00:00"
- $.bonusPointEvents[12].endTime: "2023-07-13T15:00:00"
+ $.bonusPointEvents[12].endTime: "2023-09-19T15:00:00"
- $.bonusPointEvents[12].startTime: "2023-07-07T15:00:00"
+ $.bonusPointEvents[12].startTime: "2023-09-12T15:00:00"
- $.bonusPointEvents[13].endTime: "2023-05-30T15:00:00"
+ $.bonusPointEvents[13].endTime: "2023-07-13T15:00:00"
- $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[13].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[13].multiplier: 2.0
+ $.bonusPointEvents[13].multiplier: 1.5
- $.bonusPointEvents[13].startTime: "2023-05-23T15:00:00"
+ $.bonusPointEvents[13].startTime: "2023-07-07T15:00:00"
- $.bonusPointEvents[14].endTime: "2022-11-29T16:00:00"
+ $.bonusPointEvents[14].endTime: "2023-05-30T15:00:00"
- $.bonusPointEvents[14].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[14].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[14].startTime: "2022-11-22T16:00:00"
+ $.bonusPointEvents[14].startTime: "2023-05-23T15:00:00"
- $.bonusPointEvents[15].endTime: "2022-06-27T15:00:00"
+ $.bonusPointEvents[15].endTime: "2022-11-29T16:00:00"
- $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[15].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[15].startTime: "2022-06-23T15:00:00"
+ $.bonusPointEvents[15].startTime: "2022-11-22T16:00:00"
- $.bonusPointEvents[16].endTime: "2022-05-30T15:00:00"
+ $.bonusPointEvents[16].endTime: "2022-06-27T15:00:00"
- $.bonusPointEvents[16].startTime: "2022-05-23T15:00:00"
+ $.bonusPointEvents[16].startTime: "2022-06-23T15:00:00"
- $.bonusPointEvents[17].endTime: "2022-03-07T16:00:00"
+ $.bonusPointEvents[17].endTime: "2022-05-30T15:00:00"
- $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[17].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[17].multiplier: 1.5
+ $.bonusPointEvents[17].multiplier: 2.0
- $.bonusPointEvents[17].startTime: "2022-02-28T16:00:00"
+ $.bonusPointEvents[17].startTime: "2022-05-23T15:00:00"
- $.bonusPointEvents[18].endTime: "2022-01-21T16:00:00"
+ $.bonusPointEvents[18].endTime: "2022-03-07T16:00:00"
- $.bonusPointEvents[18].startTime: "2022-01-14T16:00:00"
+ $.bonusPointEvents[18].startTime: "2022-02-28T16:00:00"
- $.bonusPointEvents[19].endTime: "2021-11-29T16:00:00"
+ $.bonusPointEvents[19].endTime: "2022-01-21T16:00:00"
- $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[19].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[19].multiplier: 2.0
+ $.bonusPointEvents[19].multiplier: 1.5
- $.bonusPointEvents[19].startTime: "2021-11-25T16:00:00"
+ $.bonusPointEvents[19].startTime: "2022-01-14T16:00:00"
- $.bonusPointEvents[20].endTime: "2021-08-03T15:00:00"
+ $.bonusPointEvents[20].endTime: "2021-11-29T16:00:00"
- $.bonusPointEvents[20].startTime: "2021-07-29T15:00:00"
+ $.bonusPointEvents[20].startTime: "2021-11-25T16:00:00"
- $.bonusPointEvents[21].endTime: "2021-01-22T16:00:00"
+ $.bonusPointEvents[21].endTime: "2021-08-03T15:00:00"
- $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[21].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[21].multiplier: 1.5
+ $.bonusPointEvents[21].multiplier: 2.0
- $.bonusPointEvents[21].startTime: "2021-01-15T16:00:00"
+ $.bonusPointEvents[21].startTime: "2021-07-29T15:00:00"
- $.bonusPointEvents[22].endTime: "2020-11-02T16:29:59"
+ $.bonusPointEvents[22].endTime: "2021-01-22T16:00:00"
- $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[22].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[22].multiplier: 2.0
+ $.bonusPointEvents[22].multiplier: 1.5
- $.bonusPointEvents[22].startTime: "2020-10-29T15:00:00"
+ $.bonusPointEvents[22].startTime: "2021-01-15T16:00:00"
- $.bonusPointEvents[23].endTime: "2020-04-15T15:00:00"
+ $.bonusPointEvents[23].endTime: "2020-11-02T16:29:59"
- $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[23].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[23].multiplier: 1.5
+ $.bonusPointEvents[23].multiplier: 2.0
- $.bonusPointEvents[23].startTime: "2020-03-25T15:00:00"
+ $.bonusPointEvents[23].startTime: "2020-10-29T15:00:00"
- $.bonusPointEvents[24].endTime: "2020-01-06T16:00:00"
+ $.bonusPointEvents[24].endTime: "2020-04-15T15:00:00"
- $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[24].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[24].multiplier: 2.0
+ $.bonusPointEvents[24].multiplier: 1.5
- $.bonusPointEvents[24].startTime: "2020-01-02T16:00:00"
+ $.bonusPointEvents[24].startTime: "2020-03-25T15:00:00"
- $.bonusPointEvents[25].endTime: "2019-11-04T15:00:00"
+ $.bonusPointEvents[25].endTime: "2020-01-06T16:00:00"
- $.bonusPointEvents[25].startTime: "2019-10-31T15:00:00"
+ $.bonusPointEvents[25].startTime: "2020-01-02T16:00:00"
- $.bonusPointEvents[26].endTime: "2019-09-30T15:00:00"
+ $.bonusPointEvents[26].endTime: "2019-11-04T15:00:00"
- $.bonusPointEvents[26].startTime: "2019-09-26T15:00:00"
+ $.bonusPointEvents[26].startTime: "2019-10-31T15:00:00"
- $.bonusPointEvents[27].endTime: "2019-06-20T18:00:00"
+ $.bonusPointEvents[27].endTime: "2019-09-30T15:00:00"
- $.bonusPointEvents[27].startTime: "2019-06-14T18:00:00"
+ $.bonusPointEvents[27].startTime: "2019-09-26T15:00:00"
- $.bonusPointEvents[28].endTime: "2019-05-06T18:00:00"
+ $.bonusPointEvents[28].endTime: "2019-06-20T18:00:00"
- $.bonusPointEvents[28].startTime: "2019-05-02T18:00:00"
+ $.bonusPointEvents[28].startTime: "2019-06-14T18:00:00"
- $.bonusPointEvents[29].endTime: "2019-01-03T19:00:00"
+ $.bonusPointEvents[29].endTime: "2019-05-06T18:00:00"
- $.bonusPointEvents[29].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
+ $.bonusPointEvents[29].eventTitle: "BPEVENT_Bloodhunt_NAME"
- $.bonusPointEvents[29].startTime: "2018-12-27T19:00:00"
+ $.bonusPointEvents[29].startTime: "2019-05-02T18:00:00"
- $.bonusPointEvents[30].endTime: "2018-11-12T19:00:00"
+ $.bonusPointEvents[30].endTime: "2019-01-03T19:00:00"
- $.bonusPointEvents[30].eventTitle: "BPEVENT_Bloodrush_NAME"
+ $.bonusPointEvents[30].eventTitle: "BPEVENT_WinterBloodhunt_NAME"
- $.bonusPointEvents[30].multiplier: 1.5
+ $.bonusPointEvents[30].multiplier: 2.0
- $.bonusPointEvents[30].startTime: "2018-11-05T19:00:00"
+ $.bonusPointEvents[30].startTime: "2018-12-27T19:00:00"
- $.bonusPointEvents[31].endTime: "2018-09-27T00:00:00"
+ $.bonusPointEvents[31].endTime: "2018-11-12T19:00:00"
- $.bonusPointEvents[31].eventTitle: "BPEVENT_Bloodhunt_NAME"
+ $.bonusPointEvents[31].eventTitle: "BPEVENT_Bloodrush_NAME"
- $.bonusPointEvents[31].multiplier: 2.0
+ $.bonusPointEvents[31].multiplier: 1.5
- $.bonusPointEvents[31].startTime: "2018-09-21T00:00:00"
+ $.bonusPointEvents[31].startTime: "2018-11-05T19:00:00"
- $.bonusPointEvents[32].endTime: "2023-11-06T16:00:00"
+ $.bonusPointEvents[32].endTime: "2018-09-27T00:00:00"
- $.bonusPointEvents[32].startTime: "2023-10-30T15:00:00"
+ $.bonusPointEvents[32].startTime: "2018-09-21T00:00:00"
- $.bonusPointEvents[33].endTime: "2015-10-13T00:00:00"
+ $.bonusPointEvents[33].endTime: "2023-11-06T16:00:00"
… 15 more change(s) — see the commit diff for everything
```

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[8].contentVersion: "e2c44787c91b72d276a57f262d5ebc8000dfa42f"
+ $.entries[8].contentVersion: "48c434c9568206d7a07219a16bb6030660ccbd0d"
```

## Could not download

- `images/T_UI_CollectionBanner_CatsAndDogs_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_Chrysalis_2.png (HTTP 404)`
- `images/T_UI_CollectionBanner_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_CatsAndDogs.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcher.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherBundle.png (HTTP 404)`
- `images/T_UI_SpecialPack_TheWitcherCharacters.png (HTTP 404)`
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

