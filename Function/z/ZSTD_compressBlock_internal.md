# Function: <code>ZSTD_compressBlock_internal</code>

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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584915280,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2333",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584915280,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585037088,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2333",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressContinue_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037088,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2612",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586280816,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
    },
    {
      "addr": 18446744071594144594,
      "name": "ZSTD_compressBlock_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3672",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283408,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071596138364,
      "name": "ZSTD_compressBlock_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3672",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548272,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071596664051,
      "name": "ZSTD_compressBlock_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame)
```

```json
{
  "name": "ZSTD_compressBlock_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3672",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883056,
      "name": "ZSTD_compressBlock_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071597573728,
      "name": "ZSTD_compressBlock_internal.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize)
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
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compressBlock_internal(ZSTD_CCtx * zc, void * dst, size_t dstCapacity, const void * src, size_t srcSize, U32 frame)
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
