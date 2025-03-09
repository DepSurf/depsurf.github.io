# Function: <code>ZSTD_resetCCtx_internal</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx * zc, ZSTD_CCtx_params params, const U64 pledgedSrcSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1558",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266432,
      "name": "ZSTD_resetCCtx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2923
    },
    {
      "addr": 18446744071594144029,
      "name": "ZSTD_resetCCtx_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx * zc, const ZSTD_CCtx_params * params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1748",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264400,
      "name": "ZSTD_resetCCtx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3372
    },
    {
      "addr": 18446744071596137637,
      "name": "ZSTD_resetCCtx_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx * zc, const ZSTD_CCtx_params * params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1748",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529072,
      "name": "ZSTD_resetCCtx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3383
    },
    {
      "addr": 18446744071596663384,
      "name": "ZSTD_resetCCtx_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx * zc, const ZSTD_CCtx_params * params, const U64 pledgedSrcSize, const size_t loadedDictSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1748",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_byCopyingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587863856,
      "name": "ZSTD_resetCCtx_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3383
    },
    {
      "addr": 18446744071597573061,
      "name": "ZSTD_resetCCtx_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
size_t ZSTD_resetCCtx_internal(ZSTD_CCtx * zc, ZSTD_CCtx_params params, const U64 pledgedSrcSize, const ZSTD_compResetPolicy_e crp, const ZSTD_buffered_policy_e zbuff)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const size_t loadedDictSize</code>
</li>
<li>
<b>Param reordered. </b>
<code>zc, params, pledgedSrcSize, crp, zbuff</code> ➡️ <code>zc, params, pledgedSrcSize, loadedDictSize, crp, zbuff</code>
</li>
<li>
<b>Param type changed. </b>
<code>ZSTD_CCtx_params params</code> ➡️ <code>const ZSTD_CCtx_params * params</code>
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
