# Function: <code>HUF_readDTableX4_wksp</code>

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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583759024,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759024,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1055
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976784,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976784,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1146
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057920,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057920,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1152
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243776,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243776,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584378576,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584378576,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584950336,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584950336,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1064
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072192,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072192,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584947440,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584947440,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1081
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592333952,
      "name": "HUF_readDTableX4_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071585383296,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1281
    }
  ]
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496263296,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496263296,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1068
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229606136,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229606136,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1132
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290562080,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290562080,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1428
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275320192,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275320192,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 916
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584347312,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584347312,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282512,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282512,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330224,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330224,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "HUF_readDTableX4_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436256,
      "name": "HUF_readDTableX4_wksp",
      "external": true,
      "loc": "lib/zstd/huf_decompress.c:482",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436256,
      "name": "HUF_readDTableX4_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1139
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
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
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
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
size_t HUF_readDTableX4_wksp(HUF_DTable * DTable, const void * src, size_t srcSize, void * workspace, size_t workspaceSize)
```
</details>
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
