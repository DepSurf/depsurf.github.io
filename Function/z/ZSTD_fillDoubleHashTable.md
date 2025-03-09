# Function: <code>ZSTD_fillDoubleHashTable</code>

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
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584838206,
      "name": "ZSTD_fillDoubleHashTable",
      "external": false,
      "loc": "lib/zstd/compress.c:1235",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
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
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584958227,
      "name": "ZSTD_fillDoubleHashTable",
      "external": false,
      "loc": "lib/zstd/compress.c:1235",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t * ms, const void * end, ZSTD_dictTableLoadMethod_e dtlm)
```

```json
{
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_fillDoubleHashTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_double_fast.c:15",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594157456,
      "name": "ZSTD_fillDoubleHashTable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071586324528,
      "name": "ZSTD_fillDoubleHashTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t * ms, const void * end, ZSTD_dictTableLoadMethod_e dtlm)
```

```json
{
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_fillDoubleHashTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_double_fast.c:15",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596150980,
      "name": "ZSTD_fillDoubleHashTable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071587356432,
      "name": "ZSTD_fillDoubleHashTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t * ms, const void * end, ZSTD_dictTableLoadMethod_e dtlm)
```

```json
{
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_fillDoubleHashTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_double_fast.c:15",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596675889,
      "name": "ZSTD_fillDoubleHashTable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071587620656,
      "name": "ZSTD_fillDoubleHashTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t * ms, const void * end, ZSTD_dictTableLoadMethod_e dtlm)
```

```json
{
  "name": "ZSTD_fillDoubleHashTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_fillDoubleHashTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_double_fast.c:15",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597585566,
      "name": "ZSTD_fillDoubleHashTable.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
    },
    {
      "addr": 18446744071587955440,
      "name": "ZSTD_fillDoubleHashTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
void ZSTD_fillDoubleHashTable(ZSTD_matchState_t * ms, const void * end, ZSTD_dictTableLoadMethod_e dtlm)
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
