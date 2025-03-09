# Function: <code>HUF_compressCTable_internal</code>

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
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584805154,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:633",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp"
      ],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584918727,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:634",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE * op, const BYTE * oend, const void * src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt * CTable, const int bmi2)
```

```json
{
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586251040,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:734",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586251040,
      "name": "HUF_compressCTable_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE * op, const BYTE * oend, const void * src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt * CTable, const int bmi2)
```

```json
{
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587244064,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1141",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587244064,
      "name": "HUF_compressCTable_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE * op, const BYTE * oend, const void * src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt * CTable, const int bmi2)
```

```json
{
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587508496,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1141",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587508496,
      "name": "HUF_compressCTable_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE * op, const BYTE * oend, const void * src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt * CTable, const int bmi2)
```

```json
{
  "name": "HUF_compressCTable_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843280,
      "name": "HUF_compressCTable_internal",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:1141",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843280,
      "name": "HUF_compressCTable_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
size_t HUF_compressCTable_internal(const BYTE * ostart, BYTE * op, const BYTE * oend, const void * src, size_t srcSize, HUF_nbStreams_e nbStreams, const HUF_CElt * CTable, const int bmi2)
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
