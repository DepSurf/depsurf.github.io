# Function: <code>HUF_isError</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797408,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004272,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085504,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274368,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274368,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409168,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409168,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925040,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compress4X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp",
        "lib/zstd/huf_compress.c:HUF_compress1X_wksp",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046752,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973296,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585412256,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586226128,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:34",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226128,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587777296,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:34",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777296,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048928,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:34",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048928,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383712,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:34",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383712,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496293744,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229629788,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290598784,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290598784,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275349914,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377904,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377904,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313104,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313104,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360816,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360816,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
```

```json
{
  "name": "HUF_isError",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466848,
      "name": "HUF_isError",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:54",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_hufOnly_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress4X_DCtx_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX4_wksp",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_readDTableX2_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466848,
      "name": "HUF_isError",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 10
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
unsigned int HUF_isError(size_t code)
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
