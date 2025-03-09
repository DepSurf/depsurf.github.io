# Function: <code>ZSTD_copyCCtx</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584841504,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:348",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_resetCStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814704,
      "name": "ZSTD_copyCCtx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1526
    },
    {
      "addr": 18446744071584816240,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961541,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:348",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_resetCStream"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_resetCStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923760,
      "name": "ZSTD_copyCCtx.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1531
    },
    {
      "addr": 18446744071584925296,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586278928,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:1981",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278928,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587278800,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2207",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587278800,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543664,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2207",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543664,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```

```json
{
  "name": "ZSTD_copyCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587878448,
      "name": "ZSTD_copyCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2207",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878448,
      "name": "ZSTD_copyCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
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
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_copyCCtx(ZSTD_CCtx * dstCCtx, const ZSTD_CCtx * srcCCtx, long long unsigned int pledgedSrcSize)
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
