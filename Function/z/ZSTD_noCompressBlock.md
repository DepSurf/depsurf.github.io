# Function: <code>ZSTD_noCompressBlock</code>

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
size_t ZSTD_noCompressBlock(void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910272,
      "name": "ZSTD_noCompressBlock",
      "external": true,
      "loc": "lib/zstd/compress.c:434",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910272,
      "name": "ZSTD_noCompressBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
size_t ZSTD_noCompressBlock(void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031968,
      "name": "ZSTD_noCompressBlock",
      "external": true,
      "loc": "lib/zstd/compress.c:434",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031968,
      "name": "ZSTD_noCompressBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586283963,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:435",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586318469,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:435",
      "file": "lib/zstd/compress/zstd_compress_superblock.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587282822,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587322662,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress_superblock.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587547691,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587586640,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress_superblock.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_noCompressBlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587882475,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587921424,
      "name": "ZSTD_noCompressBlock",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:503",
      "file": "lib/zstd/compress/zstd_compress_superblock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
size_t ZSTD_noCompressBlock(void * dst, size_t dstCapacity, const void * src, size_t srcSize)
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
size_t ZSTD_noCompressBlock(void * dst, size_t dstCapacity, const void * src, size_t srcSize)
```
</details>
</li>
</ul>
