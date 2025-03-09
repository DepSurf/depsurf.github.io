# Function: <code>ZSTD_overflowCorrectIfNeeded</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_overflowCorrectIfNeeded",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586264576,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2756",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263376,
      "name": "ZSTD_overflowCorrectIfNeeded.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071594143711,
      "name": "ZSTD_overflowCorrectIfNeeded.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_CCtx_params * params, const void * ip, const void * iend)
```

```json
{
  "name": "ZSTD_overflowCorrectIfNeeded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3810",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260144,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071596137345,
      "name": "ZSTD_overflowCorrectIfNeeded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_CCtx_params * params, const void * ip, const void * iend)
```

```json
{
  "name": "ZSTD_overflowCorrectIfNeeded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3810",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524800,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071596663092,
      "name": "ZSTD_overflowCorrectIfNeeded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_CCtx_params * params, const void * ip, const void * iend)
```

```json
{
  "name": "ZSTD_overflowCorrectIfNeeded",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:3810",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadDictionaryContent",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compressContinue_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress_frameChunk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587859584,
      "name": "ZSTD_overflowCorrectIfNeeded",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    },
    {
      "addr": 18446744071597572769,
      "name": "ZSTD_overflowCorrectIfNeeded.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ZSTD_overflowCorrectIfNeeded(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_CCtx_params * params, const void * ip, const void * iend)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
