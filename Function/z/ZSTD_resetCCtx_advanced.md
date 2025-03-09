# Function: <code>ZSTD_resetCCtx_advanced</code>

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
size_t ZSTD_resetCCtx_advanced(ZSTD_CCtx * zc, ZSTD_parameters params, U64 frameContentSize, const ZSTD_compResetPolicy_e crp)
```

```json
{
  "name": "ZSTD_resetCCtx_advanced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584917148,
      "name": "ZSTD_resetCCtx_advanced",
      "external": false,
      "loc": "lib/zstd/compress.c:242",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressCCtx",
        "lib/zstd/compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress.c:ZSTD_compressBegin"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584806176,
      "name": "ZSTD_resetCCtx_advanced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1157
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
size_t ZSTD_resetCCtx_advanced(ZSTD_CCtx * zc, ZSTD_parameters params, U64 frameContentSize, const ZSTD_compResetPolicy_e crp)
```

```json
{
  "name": "ZSTD_resetCCtx_advanced",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585038961,
      "name": "ZSTD_resetCCtx_advanced",
      "external": false,
      "loc": "lib/zstd/compress.c:242",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressCCtx",
        "lib/zstd/compress.c:ZSTD_compress_usingDict",
        "lib/zstd/compress.c:ZSTD_compressBegin"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_resetCStream",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919984,
      "name": "ZSTD_resetCCtx_advanced",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1162
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
size_t ZSTD_resetCCtx_advanced(ZSTD_CCtx * zc, ZSTD_parameters params, U64 frameContentSize, const ZSTD_compResetPolicy_e crp)
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
size_t ZSTD_resetCCtx_advanced(ZSTD_CCtx * zc, ZSTD_parameters params, U64 frameContentSize, const ZSTD_compResetPolicy_e crp)
```
</details>
</li>
</ul>
