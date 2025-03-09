# Function: <code>ZSTD_getParams</code>

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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814208,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress.c:3437",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBegin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814208,
      "name": "ZSTD_getParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923248,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress.c:3437",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBegin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923248,
      "name": "ZSTD_getParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586302016,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:5106",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_get_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586302016,
      "name": "ZSTD_getParams",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587307840,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6124",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_get_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587307840,
      "name": "ZSTD_getParams",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587572800,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6124",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_get_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572800,
      "name": "ZSTD_getParams",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
```

```json
{
  "name": "ZSTD_getParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587907584,
      "name": "ZSTD_getParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:6124",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_get_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907584,
      "name": "ZSTD_getParams",
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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
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
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSize, size_t dictSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
ZSTD_parameters ZSTD_getParams(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize)
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
