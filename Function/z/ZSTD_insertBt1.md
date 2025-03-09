# Function: <code>ZSTD_insertBt1</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584816396,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress.c:1561",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_updateTree"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584847760,
      "name": "ZSTD_insertBt1.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584925457,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress.c:1561",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_updateTree"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967792,
      "name": "ZSTD_insertBt1.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
U32 ZSTD_insertBt1(ZSTD_matchState_t * ms, const const BYTE * ip, const const BYTE * iend, const U32 mls, const int extDict)
```

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:381",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_BtGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_updateTree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467664,
      "name": "ZSTD_insertBt1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2017
    },
    {
      "addr": 18446744071594193427,
      "name": "ZSTD_insertBt1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t * ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict)
```

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:411",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_updateTree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587627872,
      "name": "ZSTD_insertBt1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2121
    },
    {
      "addr": 18446744071596189390,
      "name": "ZSTD_insertBt1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t * ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict)
```

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:411",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_updateTree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587892832,
      "name": "ZSTD_insertBt1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2086
    },
    {
      "addr": 18446744071596714789,
      "name": "ZSTD_insertBt1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
U32 ZSTD_insertBt1(const ZSTD_matchState_t * ms, const const BYTE * ip, const const BYTE * iend, const U32 target, const U32 mls, const int extDict)
```

```json
{
  "name": "ZSTD_insertBt1",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertBt1",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:411",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_updateTree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227616,
      "name": "ZSTD_insertBt1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2086
    },
    {
      "addr": 18446744071597624466,
      "name": "ZSTD_insertBt1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 370
    }
  ]
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
U32 ZSTD_insertBt1(ZSTD_matchState_t * ms, const const BYTE * ip, const const BYTE * iend, const U32 mls, const int extDict)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const U32 target</code>
</li>
<li>
<b>Param reordered. </b>
<code>ms, ip, iend, mls, extDict</code> ➡️ <code>ms, ip, iend, target, mls, extDict</code>
</li>
<li>
<b>Param type changed. </b>
<code>ZSTD_matchState_t * ms</code> ➡️ <code>const ZSTD_matchState_t * ms</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
