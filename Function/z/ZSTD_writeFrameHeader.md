# Function: <code>ZSTD_writeFrameHeader</code>

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
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584807648,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress.c:2431",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807648,
      "name": "ZSTD_writeFrameHeader.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584921600,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress.c:2431",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584921600,
      "name": "ZSTD_writeFrameHeader.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
size_t ZSTD_writeFrameHeader(void * dst, size_t dstCapacity, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, U32 dictID)
```

```json
{
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2862",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257824,
      "name": "ZSTD_writeFrameHeader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071594143331,
      "name": "ZSTD_writeFrameHeader.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
size_t ZSTD_writeFrameHeader(void * dst, size_t dstCapacity, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, U32 dictID)
```

```json
{
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3921",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587252176,
      "name": "ZSTD_writeFrameHeader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071596136921,
      "name": "ZSTD_writeFrameHeader.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
size_t ZSTD_writeFrameHeader(void * dst, size_t dstCapacity, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, U32 dictID)
```

```json
{
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3921",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516864,
      "name": "ZSTD_writeFrameHeader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071596662668,
      "name": "ZSTD_writeFrameHeader.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
size_t ZSTD_writeFrameHeader(void * dst, size_t dstCapacity, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, U32 dictID)
```

```json
{
  "name": "ZSTD_writeFrameHeader",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_writeFrameHeader",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3921",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851648,
      "name": "ZSTD_writeFrameHeader",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
    },
    {
      "addr": 18446744071597572345,
      "name": "ZSTD_writeFrameHeader.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
size_t ZSTD_writeFrameHeader(void * dst, size_t dstCapacity, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, U32 dictID)
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
