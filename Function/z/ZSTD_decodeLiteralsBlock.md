# Function: <code>ZSTD_decodeLiteralsBlock</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583795523,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764992,
      "name": "ZSTD_decodeLiteralsBlock.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071583779680,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986768,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986768,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067904,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067904,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 829
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584265385,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254256,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584400185,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389056,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584960704,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960704,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585082752,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082752,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 837
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584956816,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956816,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585394576,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394576,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553088,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:79",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553088,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1027
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize, void * dst, size_t dstCapacity, const streaming_operation streaming)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587770816,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:119",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770816,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1849
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize, void * dst, size_t dstCapacity, const streaming_operation streaming)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588042432,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:119",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042432,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1877
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize, void * dst, size_t dstCapacity, const streaming_operation streaming)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377216,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:119",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377216,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1877
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496284824,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496273936,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229621392,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229615028,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 744
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290587756,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290575872,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275341960,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275330792,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 726
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584368921,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357792,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584304121,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292992,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584351833,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340704,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeLiteralsBlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584457865,
      "name": "ZSTD_decodeLiteralsBlock",
      "external": true,
      "loc": "lib/zstd/decompress.c:432",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446736,
      "name": "ZSTD_decodeLiteralsBlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_decodeLiteralsBlock(ZSTD_DCtx * dctx, const void * src, size_t srcSize)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * dst</code>
</li>
<li>
<b>Param added. </b>
<code>size_t dstCapacity</code>
</li>
<li>
<b>Param added. </b>
<code>const streaming_operation streaming</code>
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
