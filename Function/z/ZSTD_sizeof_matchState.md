# Function: <code>ZSTD_sizeof_matchState</code>

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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const U32 forCCtx)
```

```json
{
  "name": "ZSTD_sizeof_matchState",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586291797,
      "name": "ZSTD_sizeof_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1231",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586257632,
      "name": "ZSTD_sizeof_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071594143277,
      "name": "ZSTD_sizeof_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx)
```

```json
{
  "name": "ZSTD_sizeof_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_sizeof_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1348",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587251744,
      "name": "ZSTD_sizeof_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071596136867,
      "name": "ZSTD_sizeof_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx)
```

```json
{
  "name": "ZSTD_sizeof_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_sizeof_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1348",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587516432,
      "name": "ZSTD_sizeof_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071596662614,
      "name": "ZSTD_sizeof_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const U32 enableDedicatedDictSearch, const U32 forCCtx)
```

```json
{
  "name": "ZSTD_sizeof_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_sizeof_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1348",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initStaticCDict",
        "lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCDictSize",
        "lib/zstd/compress/zstd_compress.c:ZSTD_estimateCCtxSize_usingCCtxParams_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851216,
      "name": "ZSTD_sizeof_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
    },
    {
      "addr": 18446744071597572291,
      "name": "ZSTD_sizeof_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
size_t ZSTD_sizeof_matchState(const const ZSTD_compressionParameters * cParams, const U32 forCCtx)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param added. </b>
<code>const U32 enableDedicatedDictSearch</code>
</li>
<li>
<b>Param reordered. </b>
<code>cParams, forCCtx</code> ➡️ <code>cParams, useRowMatchFinder, enableDedicatedDictSearch, forCCtx</code>
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
