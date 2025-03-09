# Function: <code>ZSTD_compressBegin_internal</code>

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
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584841990,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2738",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_compressCCtx",
        "lib/zstd/compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress.c:ZSTD_compressBegin"
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
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584962027,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress.c:2738",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_compressCCtx",
        "lib/zstd/compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress.c:ZSTD_compressBegin"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_compressBegin_internal(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict * cdict, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586286992,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3316",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286992,
      "name": "ZSTD_compressBegin_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
size_t ZSTD_compressBegin_internal(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict * cdict, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587293760,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4398",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587291616,
      "name": "ZSTD_compressBegin_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
size_t ZSTD_compressBegin_internal(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict * cdict, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587558736,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4398",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587556592,
      "name": "ZSTD_compressBegin_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
size_t ZSTD_compressBegin_internal(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict * cdict, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_compressBegin_internal",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587893520,
      "name": "ZSTD_compressBegin_internal",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:4398",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingDict"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_init_compressStream2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_usingCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressBegin_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891376,
      "name": "ZSTD_compressBegin_internal",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
size_t ZSTD_compressBegin_internal(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictContentType_e dictContentType, ZSTD_dictTableLoadMethod_e dtlm, const ZSTD_CDict * cdict, const ZSTD_CCtx_params * params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
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
