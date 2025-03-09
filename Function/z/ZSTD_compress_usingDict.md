# Function: <code>ZSTD_compress_usingDict</code>

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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, ZSTD_parameters params)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918416,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress.c:2825",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918416,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1502
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, ZSTD_parameters params)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585041072,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress.c:2825",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041072,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1507
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586291184,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:3514",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291184,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587296384,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4597",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587296384,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587561328,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4597",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561328,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, int compressionLevel)
```

```json
{
  "name": "ZSTD_compress_usingDict",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587896112,
      "name": "ZSTD_compress_usingDict",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:4597",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587896112,
      "name": "ZSTD_compress_usingDict",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, ZSTD_parameters params)
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
size_t ZSTD_compress_usingDict(ZSTD_CCtx * ctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, ZSTD_parameters params)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compress_usingDict(ZSTD_CCtx * cctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, int compressionLevel)
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
