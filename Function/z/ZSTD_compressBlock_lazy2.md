# Function: <code>ZSTD_compressBlock_lazy2</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ZSTD_compressBlock_lazy2(ZSTD_CCtx * ctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584833296,
      "name": "ZSTD_compressBlock_lazy2",
      "external": false,
      "loc": "lib/zstd/compress.c:2051",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833296,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4768
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ZSTD_compressBlock_lazy2(ZSTD_CCtx * ctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931936,
      "name": "ZSTD_compressBlock_lazy2",
      "external": false,
      "loc": "lib/zstd/compress.c:2051",
      "file": "lib/zstd/compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931936,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5084
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_compressBlock_lazy2(ZSTD_matchState_t * ms, seqStore_t * seqStore, U32 * rep, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_lazy2",
      "external": true,
      "loc": "lib/zstd/compress/zstd_lazy.c:1132",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594177169,
      "name": "ZSTD_compressBlock_lazy2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3551
    },
    {
      "addr": 18446744071586397296,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 8649
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
size_t ZSTD_compressBlock_lazy2(ZSTD_matchState_t * ms, seqStore_t * seqStore, U32 * rep, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_lazy2",
      "external": true,
      "loc": "lib/zstd/compress/zstd_lazy.c:1727",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596184312,
      "name": "ZSTD_compressBlock_lazy2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587538688,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3023
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
size_t ZSTD_compressBlock_lazy2(ZSTD_matchState_t * ms, seqStore_t * seqStore, U32 * rep, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_lazy2",
      "external": true,
      "loc": "lib/zstd/compress/zstd_lazy.c:1727",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596709703,
      "name": "ZSTD_compressBlock_lazy2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587804288,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3179
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
size_t ZSTD_compressBlock_lazy2(ZSTD_matchState_t * ms, seqStore_t * seqStore, U32 * rep, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_compressBlock_lazy2",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_compressBlock_lazy2",
      "external": true,
      "loc": "lib/zstd/compress/zstd_lazy.c:1727",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597619380,
      "name": "ZSTD_compressBlock_lazy2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071588139072,
      "name": "ZSTD_compressBlock_lazy2",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3179
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
void ZSTD_compressBlock_lazy2(ZSTD_CCtx * ctx, const void * src, size_t srcSize)
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
void ZSTD_compressBlock_lazy2(ZSTD_CCtx * ctx, const void * src, size_t srcSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_compressBlock_lazy2(ZSTD_matchState_t * ms, seqStore_t * seqStore, U32 * rep, const void * src, size_t srcSize)
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
