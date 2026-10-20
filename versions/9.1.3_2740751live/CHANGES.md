# live · 9.1.3_2740751live

| | |
|---|---|
| Build date | 2025-09-15 20:02 UTC |
| CDN version | `9.1.3_2740751live-1757966574` |
| Key | `9.1.3_live` |
| Compared with | [9.1.3_2740219live](../9.1.3_2740219live/CHANGES.md) (2025-09-15 15:47 UTC) |

## Summary

**16** added · **1** modified · **16** removed · 189 unchanged

## Added files

- [`consents/privacy/v4/de.json`](consents/privacy/v4/de.json)
- [`consents/privacy/v4/definition.json`](consents/privacy/v4/definition.json)
- [`consents/privacy/v4/en.json`](consents/privacy/v4/en.json)
- [`consents/privacy/v4/es-MX.json`](consents/privacy/v4/es-MX.json)
- [`consents/privacy/v4/es.json`](consents/privacy/v4/es.json)
- [`consents/privacy/v4/fr.json`](consents/privacy/v4/fr.json)
- [`consents/privacy/v4/it.json`](consents/privacy/v4/it.json)
- [`consents/privacy/v4/ja.json`](consents/privacy/v4/ja.json)
- [`consents/privacy/v4/ko.json`](consents/privacy/v4/ko.json)
- [`consents/privacy/v4/pl.json`](consents/privacy/v4/pl.json)
- [`consents/privacy/v4/pt-BR.json`](consents/privacy/v4/pt-BR.json)
- [`consents/privacy/v4/ru.json`](consents/privacy/v4/ru.json)
- [`consents/privacy/v4/th.json`](consents/privacy/v4/th.json)
- [`consents/privacy/v4/tr.json`](consents/privacy/v4/tr.json)
- [`consents/privacy/v4/zh-Hans.json`](consents/privacy/v4/zh-Hans.json)
- [`consents/privacy/v4/zh-Hant.json`](consents/privacy/v4/zh-Hant.json)

## Removed files

- `consents/privacy/v3/de.json`
- `consents/privacy/v3/definition.json`
- `consents/privacy/v3/en.json`
- `consents/privacy/v3/es-MX.json`
- `consents/privacy/v3/es.json`
- `consents/privacy/v3/fr.json`
- `consents/privacy/v3/it.json`
- `consents/privacy/v3/ja.json`
- `consents/privacy/v3/ko.json`
- `consents/privacy/v3/pl.json`
- `consents/privacy/v3/pt-BR.json`
- `consents/privacy/v3/ru.json`
- `consents/privacy/v3/th.json`
- `consents/privacy/v3/tr.json`
- `consents/privacy/v3/zh-Hans.json`
- `consents/privacy/v3/zh-Hant.json`

## Modified files

### [`dynamicContent/DynamicContent.json`](dynamicContent/DynamicContent.json)

[Full line-by-line diff](diffs/dynamicContent/DynamicContent.json.diff)

```diff
- $.entries[130].uri: "consents/privacy/v3/definition.json"
+ $.entries[130].uri: "consents/privacy/v4/definition.json"
- $.entries[131].contentVersion: "476147af73e53fcdcb0bbef2718d393edaad355d"
+ $.entries[131].contentVersion: "89c9cccce5edb8e007caf2f17de5c66495e59794"
- $.entries[131].uri: "consents/privacy/v3/de.json"
+ $.entries[131].uri: "consents/privacy/v4/de.json"
- $.entries[132].contentVersion: "4a896208dd99153d7c426eea51114043f33b2830"
+ $.entries[132].contentVersion: "664d9b1e915be958e81affa7c28183acfc551cad"
- $.entries[132].uri: "consents/privacy/v3/en.json"
+ $.entries[132].uri: "consents/privacy/v4/en.json"
- $.entries[133].contentVersion: "f9440d89457427e3a1e6823d6dc93ff477ae176c"
+ $.entries[133].contentVersion: "53f8685c461518469b653146f06279509ac5d76f"
- $.entries[133].uri: "consents/privacy/v3/es.json"
+ $.entries[133].uri: "consents/privacy/v4/es.json"
- $.entries[134].contentVersion: "21440e0fbfce0508f625a6eb60bc18d7e381e7d1"
+ $.entries[134].contentVersion: "51c90c6280b833d6d504f25078c20dfe25785881"
- $.entries[134].uri: "consents/privacy/v3/es-MX.json"
+ $.entries[134].uri: "consents/privacy/v4/es-MX.json"
- $.entries[135].contentVersion: "fb7715b8f24a1882a79559f464b8dff5a1716596"
+ $.entries[135].contentVersion: "beef48f03ff4ac7262a59a2b24f1fa8c5f3720f3"
- $.entries[135].uri: "consents/privacy/v3/fr.json"
+ $.entries[135].uri: "consents/privacy/v4/fr.json"
- $.entries[136].contentVersion: "a36df159d806e5c6980d5e230ffc8c98445d1dce"
+ $.entries[136].contentVersion: "e5bf4cef5f9220b1d369283f55a79ab5ec8f4623"
- $.entries[136].uri: "consents/privacy/v3/it.json"
+ $.entries[136].uri: "consents/privacy/v4/it.json"
- $.entries[137].contentVersion: "086cdbd119e343e04705cf74705fa290bbd577c4"
+ $.entries[137].contentVersion: "03e9a38cd76f686de83dd9b8139030c36106698b"
- $.entries[137].uri: "consents/privacy/v3/ja.json"
+ $.entries[137].uri: "consents/privacy/v4/ja.json"
- $.entries[138].contentVersion: "7df35283d787efb6e3542d77f5a11c75e64d4362"
+ $.entries[138].contentVersion: "b2e78ddbd51c6dd29d87a4bb47eb8a94539fa699"
- $.entries[138].uri: "consents/privacy/v3/ko.json"
+ $.entries[138].uri: "consents/privacy/v4/ko.json"
- $.entries[139].contentVersion: "dd11fa9711412ca3f079533561c775eb50d94bdd"
+ $.entries[139].contentVersion: "7d77774e67e7d1742da89de9643c20c2f6ddfb40"
- $.entries[139].uri: "consents/privacy/v3/pl.json"
+ $.entries[139].uri: "consents/privacy/v4/pl.json"
- $.entries[140].contentVersion: "1a7ffc13114c4645d870075e5756fc91cf83c5c0"
+ $.entries[140].contentVersion: "2ca94745d35328567f33aa47c0b1c228760ec1dd"
- $.entries[140].uri: "consents/privacy/v3/pt-BR.json"
+ $.entries[140].uri: "consents/privacy/v4/pt-BR.json"
- $.entries[141].contentVersion: "e5a6ed9ed471927e4291cb8abc9cecd5d7ea5f4f"
+ $.entries[141].contentVersion: "8d8dc7b9bb6ed7f1d3e89c5061ed834db7e61804"
- $.entries[141].uri: "consents/privacy/v3/ru.json"
+ $.entries[141].uri: "consents/privacy/v4/ru.json"
- $.entries[142].contentVersion: "5e3c49e5c9878618a99c13402731e389bf2751bc"
+ $.entries[142].contentVersion: "4683ab35de30bbfb21c6e82eb48719666e683b75"
- $.entries[142].uri: "consents/privacy/v3/th.json"
+ $.entries[142].uri: "consents/privacy/v4/th.json"
- $.entries[143].contentVersion: "62c76ba6274d855b3ed147f5d827db54df877935"
+ $.entries[143].contentVersion: "2d3c2f01a89caa3565ab48fa75b9fcf7be7e4c03"
- $.entries[143].uri: "consents/privacy/v3/tr.json"
+ $.entries[143].uri: "consents/privacy/v4/tr.json"
- $.entries[144].contentVersion: "50855c073c0b2f41f2871a775584982b6a0b4222"
+ $.entries[144].contentVersion: "070c383f81a7df6ea5fdfa96660720a6a747677a"
- $.entries[144].uri: "consents/privacy/v3/zh-Hans.json"
+ $.entries[144].uri: "consents/privacy/v4/zh-Hans.json"
- $.entries[145].contentVersion: "853593ee583b691d75f7572cce2a826c95ffa416"
+ $.entries[145].contentVersion: "bcdf795316efc63154c0153edd8d843d2546a0c0"
- $.entries[145].uri: "consents/privacy/v3/zh-Hant.json"
+ $.entries[145].uri: "consents/privacy/v4/zh-Hant.json"
```

