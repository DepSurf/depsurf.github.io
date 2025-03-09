# Function: <code>ZSTD_getCParamsFromCCtxParams</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params * CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getCParamsFromCCtxParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586277120,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1215",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277120,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params * CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getCParamsFromCCtxParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276576,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1332",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276576,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params * CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getCParamsFromCCtxParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587541456,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1332",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587541456,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params * CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getCParamsFromCCtxParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587876240,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1332",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587876240,
      "name": "ZSTD_getCParamsFromCCtxParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
ZSTD_compressionParameters ZSTD_getCParamsFromCCtxParams(const ZSTD_CCtx_params * CCtxParams, U64 srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
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
