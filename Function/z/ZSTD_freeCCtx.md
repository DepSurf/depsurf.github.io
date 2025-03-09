# Function: <code>ZSTD_freeCCtx</code>

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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584923308,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:132",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_freeCStream",
        "lib/zstd/compress.c:ZSTD_freeCStream",
        "lib/zstd/compress.c:ZSTD_freeCDict",
        "lib/zstd/compress.c:ZSTD_freeCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910128,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585044961,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress.c:132",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_freeCStream",
        "lib/zstd/compress.c:ZSTD_freeCStream",
        "lib/zstd/compress.c:ZSTD_freeCDict",
        "lib/zstd/compress.c:ZSTD_freeCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict",
        "lib/zstd/compress.c:ZSTD_initCDict"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031792,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586292480,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:154",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292480,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587297664,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:169",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587297664,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587562608,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:169",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587562608,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```

```json
{
  "name": "ZSTD_freeCCtx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587897392,
      "name": "ZSTD_freeCCtx",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:169",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_freeCStream",
        "lib/zstd/compress/zstd_compress.c:ZSTD_compress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897392,
      "name": "ZSTD_freeCCtx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
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
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_freeCCtx(ZSTD_CCtx * cctx)
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
