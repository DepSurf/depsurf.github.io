# Function: <code>HUF_decodeLastSymbolX4</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583743076,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583740560,
      "name": "HUF_decodeLastSymbolX4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583958384,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583958384,
      "name": "HUF_decodeLastSymbolX4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584039616,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584039616,
      "name": "HUF_decodeLastSymbolX4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584226539,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584361339,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584932974,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585054787,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584930343,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585366135,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496249676,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229593304,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290541776,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290541776,
      "name": "HUF_decodeLastSymbolX4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275300670,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584330075,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584265275,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584312987,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_decodeLastSymbolX4",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584419019,
      "name": "HUF_decodeLastSymbolX4",
      "external": false,
      "loc": "lib/zstd/huf_decompress.c:603",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
U32 HUF_decodeLastSymbolX4(void * op, BIT_DStream_t * DStream, const HUF_DEltX4 * dt, const U32 dtLog)
```
</details>
</li>
</ul>
