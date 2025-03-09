# Function: <code>ZSTD_getCParams</code>

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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584814237,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress.c:3411",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_getParams"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584813024,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584923282,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress.c:3411",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_getParams"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922016,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586298287,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:5082",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586301904,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587292470,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6100",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307712,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587557446,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6100",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572672,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587892230,
      "name": "ZSTD_getCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6100",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907456,
      "name": "ZSTD_getCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
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
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
ZSTD_compressionParameters ZSTD_getCParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
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
