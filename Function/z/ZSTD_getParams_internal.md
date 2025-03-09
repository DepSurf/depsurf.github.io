# Function: <code>ZSTD_getParams_internal</code>

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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586257424,
      "name": "ZSTD_getParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:5092",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_getParams",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257424,
      "name": "ZSTD_getParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587251520,
      "name": "ZSTD_getParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:6110",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_getParams",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251520,
      "name": "ZSTD_getParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587516208,
      "name": "ZSTD_getParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:6110",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_getParams",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516208,
      "name": "ZSTD_getParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
```

```json
{
  "name": "ZSTD_getParams_internal",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587850992,
      "name": "ZSTD_getParams_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:6110",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_getParams",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850992,
      "name": "ZSTD_getParams_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
ZSTD_parameters ZSTD_getParams_internal(int compressionLevel, long long unsigned int srcSizeHint, size_t dictSize, ZSTD_cParamMode_e mode)
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
