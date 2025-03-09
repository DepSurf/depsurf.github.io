# Function: <code>ZSTD_CCtx_setPledgedSrcSize</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx * cctx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_CCtx_setPledgedSrcSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586299787,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:892",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_init_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_compress_cctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275872,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx * cctx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_CCtx_setPledgedSrcSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587305355,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1009",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_reset_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_init_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_compress_cctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587275312,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx * cctx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_CCtx_setPledgedSrcSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587570283,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1009",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_reset_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_init_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_compress_cctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587540192,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx * cctx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_CCtx_setPledgedSrcSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587905067,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1009",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_srcSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingCDict_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/zstd_compress_module.c:zstd_reset_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_init_cstream",
        "lib/zstd/zstd_compress_module.c:zstd_compress_cctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587874976,
      "name": "ZSTD_CCtx_setPledgedSrcSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
size_t ZSTD_CCtx_setPledgedSrcSize(ZSTD_CCtx * cctx, long long unsigned int pledgedSrcSize)
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
