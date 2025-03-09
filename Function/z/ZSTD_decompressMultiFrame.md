# Function: <code>ZSTD_decompressMultiFrame</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583793595,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584001120,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997696,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584082352,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078864,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584269712,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266384,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584404512,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401184,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971888,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971888,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093744,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093744,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968784,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968784,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585407696,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585407696,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586525488,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress.c:873",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586525488,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587722816,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress.c:919",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587722816,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587988464,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress.c:938",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587988464,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588323248,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress.c:938",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompress_usingDict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588323248,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496288784,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496285688,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1464
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229625456,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229622204,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290592812,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290588896,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1812
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275345386,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275342732,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584373248,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369920,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584308448,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305120,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584356160,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584352832,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```

```json
{
  "name": "ZSTD_decompressMultiFrame",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584462192,
      "name": "ZSTD_decompressMultiFrame",
      "external": false,
      "loc": "lib/zstd/decompress.c:1643",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458864,
      "name": "ZSTD_decompressMultiFrame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1480
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_decompressMultiFrame(ZSTD_DCtx * dctx, void * dst, size_t dstCapacity, const void * src, size_t srcSize, const void * dict, size_t dictSize, const ZSTD_DDict * ddict)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
