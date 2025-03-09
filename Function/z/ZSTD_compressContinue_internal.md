# Function: <code>ZSTD_compressContinue_internal</code>

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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584915552,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2490",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_flushStream",
        "lib/zstd/compress.c:ZSTD_compressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915552,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585037360,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2490",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_flushStream",
        "lib/zstd/compress.c:ZSTD_compressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037360,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1164
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586282464,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2961",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282464,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288496,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4020",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288496,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587553360,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4020",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553360,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```

```json
{
  "name": "ZSTD_compressContinue_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587888144,
      "name": "ZSTD_compressContinue_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4020",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressEnd",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587888144,
      "name": "ZSTD_compressContinue_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
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
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compressContinue_internal(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame, U32 lastFrameChunk)
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
