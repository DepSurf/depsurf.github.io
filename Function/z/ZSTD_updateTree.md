# Function: <code>ZSTD_updateTree</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584816272,
      "name": "ZSTD_updateTree",
      "external": false,
      "loc": "lib/zstd/compress.c:1724",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816272,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925328,
      "name": "ZSTD_updateTree",
      "external": false,
      "loc": "lib/zstd/compress.c:1724",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925328,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t * ms, const BYTE * ip, const BYTE * iend)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586480448,
      "name": "ZSTD_updateTree",
      "external": true,
      "loc": "lib/zstd/compress/zstd_opt.c:516",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586480448,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t * ms, const BYTE * ip, const BYTE * iend)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587666080,
      "name": "ZSTD_updateTree",
      "external": true,
      "loc": "lib/zstd/compress/zstd_opt.c:551",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587666080,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t * ms, const BYTE * ip, const BYTE * iend)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587931408,
      "name": "ZSTD_updateTree",
      "external": true,
      "loc": "lib/zstd/compress/zstd_opt.c:551",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587931408,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t * ms, const BYTE * ip, const BYTE * iend)
```

```json
{
  "name": "ZSTD_updateTree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588266192,
      "name": "ZSTD_updateTree",
      "external": true,
      "loc": "lib/zstd/compress/zstd_opt.c:551",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266192,
      "name": "ZSTD_updateTree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ZSTD_updateTree(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls)
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
void ZSTD_updateTree(ZSTD_CCtx * zc, const const BYTE * ip, const const BYTE * iend, const U32 nbCompares, const U32 mls)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void ZSTD_updateTree(ZSTD_matchState_t * ms, const BYTE * ip, const BYTE * iend)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
