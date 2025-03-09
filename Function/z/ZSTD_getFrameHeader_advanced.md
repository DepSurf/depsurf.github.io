# Function: <code>ZSTD_getFrameHeader_advanced</code>

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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader * zfhPtr, const void * src, size_t srcSize, ZSTD_format_e format)
```

```json
{
  "name": "ZSTD_getFrameHeader_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586518848,
      "name": "ZSTD_getFrameHeader_advanced",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:409",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518848,
      "name": "ZSTD_getFrameHeader_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader * zfhPtr, const void * src, size_t srcSize, ZSTD_format_e format)
```

```json
{
  "name": "ZSTD_getFrameHeader_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715520,
      "name": "ZSTD_getFrameHeader_advanced",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:425",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715520,
      "name": "ZSTD_getFrameHeader_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader * zfhPtr, const void * src, size_t srcSize, ZSTD_format_e format)
```

```json
{
  "name": "ZSTD_getFrameHeader_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587981072,
      "name": "ZSTD_getFrameHeader_advanced",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:425",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587981072,
      "name": "ZSTD_getFrameHeader_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader * zfhPtr, const void * src, size_t srcSize, ZSTD_format_e format)
```

```json
{
  "name": "ZSTD_getFrameHeader_advanced",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588315856,
      "name": "ZSTD_getFrameHeader_advanced",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:425",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_estimateDStreamSize_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_getDecompressedSize",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588315856,
      "name": "ZSTD_getFrameHeader_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
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
size_t ZSTD_getFrameHeader_advanced(ZSTD_frameHeader * zfhPtr, const void * src, size_t srcSize, ZSTD_format_e format)
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
