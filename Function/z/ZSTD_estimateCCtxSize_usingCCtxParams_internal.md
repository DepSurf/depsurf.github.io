# Function: <code>ZSTD_estimateCCtxSize_usingCCtxParams_internal</code>

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
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters * cParams, const ldmParams_t * ldmParams, const int isStatic, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize)
```

```json
{
  "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1258",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258320,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
    },
    {
      "addr": 18446744071594143383,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters * cParams, const ldmParams_t * ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize)
```

```json
{
  "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1389",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252688,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071596136973,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters * cParams, const ldmParams_t * ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize)
```

```json
{
  "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1389",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517392,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071596662720,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters * cParams, const ldmParams_t * ldmParams, const int isStatic, const ZSTD_paramSwitch_e useRowMatchFinder, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize)
```

```json
{
  "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1389",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587852176,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071597572397,
      "name": "ZSTD_estimateCCtxSize_usingCCtxParams_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
size_t ZSTD_estimateCCtxSize_usingCCtxParams_internal(const ZSTD_compressionParameters * cParams, const ldmParams_t * ldmParams, const int isStatic, const size_t buffInSize, const size_t buffOutSize, const U64 pledgedSrcSize)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>cParams, ldmParams, isStatic, buffInSize, buffOutSize, pledgedSrcSize</code> ➡️ <code>cParams, ldmParams, isStatic, useRowMatchFinder, buffInSize, buffOutSize, pledgedSrcSize</code>
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
