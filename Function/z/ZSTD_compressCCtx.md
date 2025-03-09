# Function: <code>ZSTD_compressCCtx</code>

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
size_t ZSTD_compressCCtx(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, ZSTD_parameters params)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917056,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:2831",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917056,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1360
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
size_t ZSTD_compressCCtx(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, ZSTD_parameters params)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038864,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:2831",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038864,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1365
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586294064,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:3530",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291552,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587299376,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4612",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296656,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587564304,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4612",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561600,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compressCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587899088,
      "name": "ZSTD_compressCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4612",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896384,
      "name": "ZSTD_compressCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
size_t ZSTD_compressCCtx(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, ZSTD_parameters params)
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
size_t ZSTD_compressCCtx(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, ZSTD_parameters params)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compressCCtx(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, int compressionLevel)
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
