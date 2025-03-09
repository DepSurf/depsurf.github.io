# Function: <code>ZSTD_BtGetAllMatches</code>

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
  "name": "ZSTD_BtGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584882394,
      "name": "ZSTD_BtGetAllMatches",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:356",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_BtGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584982515,
      "name": "ZSTD_BtGetAllMatches",
      "external": false,
      "loc": "lib/zstd/zstd_opt.h:356",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
U32 ZSTD_BtGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const BYTE * ip, const const BYTE * iHighLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat)
```

```json
{
  "name": "ZSTD_BtGetAllMatches",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586475392,
      "name": "ZSTD_BtGetAllMatches",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:755",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586475392,
      "name": "ZSTD_BtGetAllMatches",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
U32 ZSTD_BtGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const BYTE * ip, const const BYTE * iHighLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
U32 ZSTD_BtGetAllMatches(ZSTD_match_t * matches, ZSTD_matchState_t * ms, U32 * nextToUpdate3, const BYTE * ip, const const BYTE * iHighLimit, const ZSTD_dictMode_e dictMode, const U32 * rep, const U32 ll0, const U32 lengthToBeat)
```
</details>
</li>
</ul>
