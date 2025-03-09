# Function: <code>ZSTD_isRLE</code>

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
int ZSTD_isRLE(const BYTE * src, size_t length)
```

```json
{
  "name": "ZSTD_isRLE",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586259728,
      "name": "ZSTD_isRLE",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2569",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586259728,
      "name": "ZSTD_isRLE",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int ZSTD_isRLE(const BYTE * src, size_t length)
```

```json
{
  "name": "ZSTD_isRLE",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587253936,
      "name": "ZSTD_isRLE",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2905",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587253936,
      "name": "ZSTD_isRLE",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
int ZSTD_isRLE(const BYTE * src, size_t length)
```

```json
{
  "name": "ZSTD_isRLE",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587518656,
      "name": "ZSTD_isRLE",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2905",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587518656,
      "name": "ZSTD_isRLE",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int ZSTD_isRLE(const BYTE * src, size_t length)
```

```json
{
  "name": "ZSTD_isRLE",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853440,
      "name": "ZSTD_isRLE",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2905",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBlock_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressSeqStore_singleBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853440,
      "name": "ZSTD_isRLE",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
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
int ZSTD_isRLE(const BYTE * src, size_t length)
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
