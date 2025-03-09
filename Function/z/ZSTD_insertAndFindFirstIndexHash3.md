# Function: <code>ZSTD_insertAndFindFirstIndexHash3</code>

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
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584828117,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:215",
      "file": "lib/zstd/compress.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584982029,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:215",
      "file": "lib/zstd/compress.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586474642,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:353",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip)
```

```json
{
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:382",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587620432,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596188992,
      "name": "ZSTD_insertAndFindFirstIndexHash3.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip)
```

```json
{
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:382",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885568,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071596714391,
      "name": "ZSTD_insertAndFindFirstIndexHash3.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip)
```

```json
{
  "name": "ZSTD_insertAndFindFirstIndexHash3",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:382",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220352,
      "name": "ZSTD_insertAndFindFirstIndexHash3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071597624068,
      "name": "ZSTD_insertAndFindFirstIndexHash3.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
U32 ZSTD_insertAndFindFirstIndexHash3(const ZSTD_matchState_t * ms, U32 * nextToUpdate3, const const BYTE * ip)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
