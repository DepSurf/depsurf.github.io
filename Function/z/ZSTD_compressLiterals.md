# Function: <code>ZSTD_compressLiterals</code>

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
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584910713,
      "name": "ZSTD_compressLiterals",
      "external": false,
      "loc": "lib/zstd/compress.c:482",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
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
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585032425,
      "name": "ZSTD_compressLiterals",
      "external": false,
      "loc": "lib/zstd/compress.c:482",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t * prevHuf, ZSTD_hufCTables_t * nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void * dst, size_t dstCapacity, const void * src, size_t srcSize, void * entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2)
```

```json
{
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressLiterals",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_literals.c:70",
      "file": "lib/zstd/compress/zstd_compress_literals.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594145037,
      "name": "ZSTD_compressLiterals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    },
    {
      "addr": 18446744071586302480,
      "name": "ZSTD_compressLiterals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 869
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
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t * prevHuf, ZSTD_hufCTables_t * nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void * dst, size_t dstCapacity, const void * src, size_t srcSize, void * entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressLiterals",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_literals.c:70",
      "file": "lib/zstd/compress/zstd_compress_literals.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596138652,
      "name": "ZSTD_compressLiterals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587308352,
      "name": "ZSTD_compressLiterals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t * prevHuf, ZSTD_hufCTables_t * nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void * dst, size_t dstCapacity, const void * src, size_t srcSize, void * entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressLiterals",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_literals.c:70",
      "file": "lib/zstd/compress/zstd_compress_literals.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596664339,
      "name": "ZSTD_compressLiterals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587573312,
      "name": "ZSTD_compressLiterals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t * prevHuf, ZSTD_hufCTables_t * nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void * dst, size_t dstCapacity, const void * src, size_t srcSize, void * entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2, unsigned int suspectUncompressible)
```

```json
{
  "name": "ZSTD_compressLiterals",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressLiterals",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_literals.c:70",
      "file": "lib/zstd/compress/zstd_compress_literals.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597574016,
      "name": "ZSTD_compressLiterals.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071587908096,
      "name": "ZSTD_compressLiterals",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 858
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
size_t ZSTD_compressLiterals(const ZSTD_hufCTables_t * prevHuf, ZSTD_hufCTables_t * nextHuf, ZSTD_strategy strategy, int disableLiteralCompression, void * dst, size_t dstCapacity, const void * src, size_t srcSize, void * entropyWorkspace, size_t entropyWorkspaceSize, const int bmi2)
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
