# Function: <code>ZSTD_customMalloc</code>

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
void * ZSTD_customMalloc(size_t size, ZSTD_customMem customMem)
```

```json
{
  "name": "ZSTD_customMalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586239440,
      "name": "ZSTD_customMalloc",
      "external": true,
      "loc": "lib/zstd/common/zstd_common.c:56",
      "file": "lib/zstd/common/zstd_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_createDStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_createDCtx_advanced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586239440,
      "name": "ZSTD_customMalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * ZSTD_customMalloc(size_t size, ZSTD_customMem customMem)
```

```json
{
  "name": "ZSTD_customMalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789312,
      "name": "ZSTD_customMalloc",
      "external": true,
      "loc": "lib/zstd/common/zstd_common.c:56",
      "file": "lib/zstd/common/zstd_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789312,
      "name": "ZSTD_customMalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * ZSTD_customMalloc(size_t size, ZSTD_customMem customMem)
```

```json
{
  "name": "ZSTD_customMalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588060544,
      "name": "ZSTD_customMalloc",
      "external": true,
      "loc": "lib/zstd/common/zstd_common.c:56",
      "file": "lib/zstd/common/zstd_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588060544,
      "name": "ZSTD_customMalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * ZSTD_customMalloc(size_t size, ZSTD_customMem customMem)
```

```json
{
  "name": "ZSTD_customMalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588395328,
      "name": "ZSTD_customMalloc",
      "external": true,
      "loc": "lib/zstd/common/zstd_common.c:56",
      "file": "lib/zstd/common/zstd_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_generateSequences",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCCtx_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_byReference",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_createDDict_advanced",
        "lib/zstd/decompress/zstd_ddict.c:ZSTD_initDDict_internal",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588395328,
      "name": "ZSTD_customMalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void * ZSTD_customMalloc(size_t size, ZSTD_customMem customMem)
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
