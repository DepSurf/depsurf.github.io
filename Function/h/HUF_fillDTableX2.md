# Function: <code>HUF_fillDTableX2</code>

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
  "name": "HUF_fillDTableX2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_fillDTableX2",
      "external": false,
      "loc": "lib/zstd/decompress/huf_decompress.c:571",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482192,
      "name": "HUF_fillDTableX2.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
    },
    {
      "addr": 18446744071594194359,
      "name": "HUF_fillDTableX2.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void HUF_fillDTableX2(HUF_DEltX2 * DTable, const U32 targetLog, const sortedSymbol_t * sortedList, const U32 * rankStart, rankValCol_t * rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline)
```

```json
{
  "name": "HUF_fillDTableX2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668144,
      "name": "HUF_fillDTableX2",
      "external": false,
      "loc": "lib/zstd/decompress/huf_decompress.c:986",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668144,
      "name": "HUF_fillDTableX2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
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
void HUF_fillDTableX2(HUF_DEltX2 * DTable, const U32 targetLog, const sortedSymbol_t * sortedList, const U32 * rankStart, rankValCol_t * rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline)
```

```json
{
  "name": "HUF_fillDTableX2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933488,
      "name": "HUF_fillDTableX2",
      "external": false,
      "loc": "lib/zstd/decompress/huf_decompress.c:986",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933488,
      "name": "HUF_fillDTableX2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
void HUF_fillDTableX2(HUF_DEltX2 * DTable, const U32 targetLog, const sortedSymbol_t * sortedList, const U32 * rankStart, rankValCol_t * rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline)
```

```json
{
  "name": "HUF_fillDTableX2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588268272,
      "name": "HUF_fillDTableX2",
      "external": false,
      "loc": "lib/zstd/decompress/huf_decompress.c:986",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_readDTableX2_wksp_bmi2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268272,
      "name": "HUF_fillDTableX2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
void HUF_fillDTableX2(HUF_DEltX2 * DTable, const U32 targetLog, const sortedSymbol_t * sortedList, const U32 * rankStart, rankValCol_t * rankValOrigin, const U32 maxWeight, const U32 nbBitsBaseline)
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
