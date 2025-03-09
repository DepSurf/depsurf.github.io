# Function: <code>ZSTD_resetCCtx_byCopyingCDict</code>

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
  "name": "ZSTD_resetCCtx_byCopyingCDict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586269849,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1821",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx * cctx, const ZSTD_CDict * cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_byCopyingCDict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2022",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587267792,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071596137934,
      "name": "ZSTD_resetCCtx_byCopyingCDict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx * cctx, const ZSTD_CDict * cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_byCopyingCDict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2022",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532480,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071596663678,
      "name": "ZSTD_resetCCtx_byCopyingCDict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx * cctx, const ZSTD_CDict * cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
```

```json
{
  "name": "ZSTD_resetCCtx_byCopyingCDict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:2022",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_usingCDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867264,
      "name": "ZSTD_resetCCtx_byCopyingCDict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071597573355,
      "name": "ZSTD_resetCCtx_byCopyingCDict.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
size_t ZSTD_resetCCtx_byCopyingCDict(ZSTD_CCtx * cctx, const ZSTD_CDict * cdict, ZSTD_CCtx_params params, U64 pledgedSrcSize, ZSTD_buffered_policy_e zbuff)
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
