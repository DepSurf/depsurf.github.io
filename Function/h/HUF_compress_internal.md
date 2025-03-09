# Function: <code>HUF_compress_internal</code>

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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584804746,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:653",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp"
      ],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/huf_compress.c:HUF_compress1X_repeat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584802736,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1216
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584918319,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:654",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp"
      ],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/huf_compress.c:HUF_compress1X_repeat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916272,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void * workSpace_align4, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat, const int bmi2)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586254592,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:764",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586254592,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587248064,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1175",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248064,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1178
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587512752,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1175",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587512752,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847536,
      "name": "HUF_compress_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1175",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_repeat",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847536,
      "name": "HUF_compress_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1179
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat)
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
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, unsigned int singleStream, void * workSpace, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t HUF_compress_internal(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, HUF_nbStreams_e nbStreams, void * workSpace_align4, size_t wkspSize, HUF_CElt * oldHufTable, HUF_repeat * repeat, int preferRepeat, const int bmi2)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int suspectUncompressible</code>
</li>
<li>
<b>Param removed. </b>
<code>void * workSpace_align4</code>
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
