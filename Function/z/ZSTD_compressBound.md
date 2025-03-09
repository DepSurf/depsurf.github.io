# Function: <code>ZSTD_compressBound</code>

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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584921717,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress.c:38",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_flushStream",
        "lib/zstd/compress.c:ZSTD_compressStream",
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict",
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict",
        "lib/zstd/compress.c:ZSTD_CStreamOutSize",
        "lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584805968,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585040400,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress.c:38",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_endStream",
        "lib/zstd/compress.c:ZSTD_flushStream",
        "lib/zstd/compress.c:ZSTD_compressStream",
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict",
        "lib/zstd/compress.c:ZSTD_initCStream_usingCDict",
        "lib/zstd/compress.c:ZSTD_CStreamOutSize",
        "lib/zstd/compress.c:ZSTD_CStreamWorkspaceBound"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919744,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586289548,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:53",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_compress_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586271232,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587294812,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:64",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_compress_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587270128,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587559683,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:64",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_compress_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587534816,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
size_t ZSTD_compressBound(size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBound",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587894467,
      "name": "ZSTD_compressBound",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:64",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressStream_generic",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_compress_bound"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587869600,
      "name": "ZSTD_compressBound",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
size_t ZSTD_compressBound(size_t srcSize)
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
size_t ZSTD_compressBound(size_t srcSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compressBound(size_t srcSize)
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
