# Function: <code>ZSTD_insertBtAndGetAllMatches</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iLimit, U32 nbCompares, const U32 mls, U32 extDict, ZSTD_match_t * matches, const U32 minMatchLen)
```

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584882483,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:235",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827056,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1399
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iLimit, U32 nbCompares, const U32 mls, U32 extDict, ZSTD_match_t * matches, const U32 minMatchLen)
```

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585005108,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:235",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980832,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1594
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip, const const BYTE * iLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat, const U32 mls)
```

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:521",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_BtGetAllMatches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470272,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5111
    },
    {
      "addr": 18446744071594193647,
      "name": "ZSTD_insertBtAndGetAllMatches.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 712
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587654270,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:556",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587919563,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:556",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertBtAndGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588254347,
      "name": "ZSTD_insertBtAndGetAllMatches",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:556",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iLimit, U32 nbCompares, const U32 mls, U32 extDict, ZSTD_match_t * matches, const U32 minMatchLen)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iLimit, U32 nbCompares, const U32 mls, U32 extDict, ZSTD_match_t * matches, const U32 minMatchLen)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip, const const BYTE * iLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat, const U32 mls)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
U32 ZSTD_insertBtAndGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip, const const BYTE * iLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat, const U32 mls)
```
</details>
</li>
</ul>
