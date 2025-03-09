# Function: <code>HUF_compress1X_repeat</code>

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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804656,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/huf_compress.c:754",
      "file": "lib/zstd/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804656,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918208,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/huf_compress.c:755",
      "file": "lib/zstd/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918208,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat, int bmi2)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586255952,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:865",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255952,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587249888,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:1293",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249888,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587514576,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:1293",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514576,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat, int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "HUF_compress1X_repeat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587849360,
      "name": "HUF_compress1X_repeat",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:1293",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_literals.c:ZSTD_compressLiterals"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587849360,
      "name": "HUF_compress1X_repeat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat)
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
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t HUF_compress1X_repeat(void * dst, size_t dstSize, const void * src, size_t srcSize, unsigned int maxSymbolValue, unsigned int huffLog, void * workSpace, size_t wkspSize, HUF_CElt * hufTable, HUF_repeat * repeat, int preferRepeat, int bmi2)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int suspectUncompressible</code>
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
