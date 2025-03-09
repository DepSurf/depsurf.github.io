# Function: <code>ZSTD_checkCParams</code>

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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584841827,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress.c:148",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805648,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961864,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress.c:148",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919232,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276000,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1046",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276000,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587275472,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1163",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587275472,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587540352,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1163",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540352,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```

```json
{
  "name": "ZSTD_checkCParams",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875136,
      "name": "ZSTD_checkCParams",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1163",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_init_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875136,
      "name": "ZSTD_checkCParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
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
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_checkCParams(ZSTD_compressionParameters cParams)
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
