# Function: <code>HUF_decompress1X2_DCtx_wksp</code>

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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583763612,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757952,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583979322,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976464,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584060458,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057600,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584246374,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243456,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584381174,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378256,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584952854,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950016,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585074779,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071840,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584950059,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947088,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585386845,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382944,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586513048,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:931",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511872,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587709368,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1465",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708064,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974936,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1465",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973632,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588309720,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1465",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308416,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496266084,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496262880,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229608844,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229605804,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290565808,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290561504,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275322540,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275319872,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584349910,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346992,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584285110,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282192,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584332822,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329904,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_decompress1X2_DCtx_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584438854,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:232",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressBlock",
        "lib/zstd/decompress.c:ZSTD_decodeLiteralsBlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435936,
      "name": "HUF_decompress1X2_DCtx_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
size_t HUF_decompress1X2_DCtx_wksp(HUF_DTable * DCtx, void * dst, size_t dstSize, const void * cSrc, size_t cSrcSize, void * workspace, size_t workspaceSize)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * workSpace</code>
</li>
<li>
<b>Param added. </b>
<code>size_t wkspSize</code>
</li>
<li>
<b>Param removed. </b>
<code>void * workspace</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t workspaceSize</code>
</li>
</ul>
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
