# Function: <code>ZSTD_findFrameCompressedSize</code>

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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583768131,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769808,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981104,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981104,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062240,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062240,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584250864,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248176,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584385664,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382976,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584956869,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954640,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585078858,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/decompress_unzstd.c:decompress_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076656,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584951936,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584951936,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585389056,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389056,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586532273,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:700",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586523200,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587730037,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:746",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720368,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587995697,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:746",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986016,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588330481,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress.c:746",
      "file": "lib/zstd/decompress/zstd_decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/zstd_decompress_module.c:zstd_find_frame_compressed_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320800,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496270668,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496267816,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229613400,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229610648,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290571516,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290567936,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275326776,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275324490,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354400,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351712,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584289600,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286912,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584337312,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334624,
      "name": "ZSTD_findFrameCompressedSize",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_findFrameCompressedSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443344,
      "name": "ZSTD_findFrameCompressedSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:1510",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440656,
      "name": "ZSTD_findFrameCompressedSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
size_t ZSTD_findFrameCompressedSize(const void * src, size_t srcSize)
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
