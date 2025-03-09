# Function: <code>HUF_readDTableX2_wksp</code>

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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583757520,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757520,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976032,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976032,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057168,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057168,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243040,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243040,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377840,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377840,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584949616,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584949616,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071440,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071440,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946688,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946688,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592333815,
      "name": "HUF_readDTableX2_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071585382480,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:626",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594194531,
      "name": "HUF_readDTableX2_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071586510208,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1401
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587709368,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1041",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587707696,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587974936,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1041",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973264,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588309720,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/decompress/huf_decompress.c:1041",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X_hufOnly_wksp"
      ],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308048,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496262408,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496262408,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229605300,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229605300,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290560864,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290560864,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275319456,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275319456,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584346576,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346576,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281776,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281776,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584329488,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329488,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX2_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584435520,
      "name": "HUF_readDTableX2_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:90",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435520,
      "name": "HUF_readDTableX2_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
size_t HUF_readDTableX2_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
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
