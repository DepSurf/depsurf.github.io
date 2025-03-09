# Function: <code>ZSTD_CCtx_loadDictionary_advanced</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_CCtx_loadDictionary_advanced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586299618,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:945",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292864,
      "name": "ZSTD_CCtx_loadDictionary_advanced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071586294480,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_CCtx_loadDictionary_advanced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587305170,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1062",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298064,
      "name": "ZSTD_CCtx_loadDictionary_advanced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071587299840,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_CCtx_loadDictionary_advanced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587570098,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1062",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562992,
      "name": "ZSTD_CCtx_loadDictionary_advanced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071587564768,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
```

```json
{
  "name": "ZSTD_CCtx_loadDictionary_advanced",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904882,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1062",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference",
        "lib/zstd/compress/zstd_compress.c:ZSTD_CCtx_loadDictionary_byReference"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_usingDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_advanced",
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCStream_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897776,
      "name": "ZSTD_CCtx_loadDictionary_advanced.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071587899552,
      "name": "ZSTD_CCtx_loadDictionary_advanced",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
size_t ZSTD_CCtx_loadDictionary_advanced(ZSTD_CCtx * cctx, const void * dict, size_t dictSize, ZSTD_dictLoadMethod_e dictLoadMethod, ZSTD_dictContentType_e dictContentType)
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
