# Function: <code>HUF_estimateCompressedSize</code>

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
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584803315,
      "name": "HUF_estimateCompressedSize",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:501",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584916856,
      "name": "HUF_estimateCompressedSize",
      "external": false,
      "loc": "lib/zstd/huf_compress.c:501",
      "file": "lib/zstd/huf_compress.c",
      "inline": "not declared, inlined",
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_estimateCompressedSize(const HUF_CElt * CTable, const unsigned int * count, unsigned int maxSymbolValue)
```

```json
{
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586255100,
      "name": "HUF_estimateCompressedSize",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:541",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255568,
      "name": "HUF_estimateCompressedSize",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_estimateCompressedSize(const HUF_CElt * CTable, const unsigned int * count, unsigned int maxSymbolValue)
```

```json
{
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587249115,
      "name": "HUF_estimateCompressedSize",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:707",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249264,
      "name": "HUF_estimateCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
size_t HUF_estimateCompressedSize(const HUF_CElt * CTable, const unsigned int * count, unsigned int maxSymbolValue)
```

```json
{
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587513804,
      "name": "HUF_estimateCompressedSize",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:707",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587513952,
      "name": "HUF_estimateCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
size_t HUF_estimateCompressedSize(const HUF_CElt * CTable, const unsigned int * count, unsigned int maxSymbolValue)
```

```json
{
  "name": "HUF_estimateCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587848588,
      "name": "HUF_estimateCompressedSize",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:707",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildEntropyStatisticsAndEstimateSubBlockSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildBlockEntropyStats_literals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587848736,
      "name": "HUF_estimateCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
size_t HUF_estimateCompressedSize(const HUF_CElt * CTable, const unsigned int * count, unsigned int maxSymbolValue)
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
