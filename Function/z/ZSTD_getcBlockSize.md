# Function: <code>ZSTD_getcBlockSize</code>

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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583794668,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779600,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996847,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986688,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584077794,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067824,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584264086,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254176,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584398886,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388976,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584970505,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584960624,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585092366,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082656,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584967403,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956720,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585406301,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585394480,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552976,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:56",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552976,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587770688,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:56",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770688,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588042304,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:56",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042304,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377088,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:56",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressFrame",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_findFrameSizeInfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377088,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496283608,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496273856,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229620804,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229614936,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290586720,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290575760,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275340998,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275330704,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584367622,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357712,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584302822,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292912,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584350534,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340624,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
```

```json
{
  "name": "ZSTD_getcBlockSize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584456566,
      "name": "ZSTD_getcBlockSize",
      "external": true,
      "loc": "lib/zstd/decompress.c:394",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446656,
      "name": "ZSTD_getcBlockSize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
size_t ZSTD_getcBlockSize(const void * src, size_t srcSize, blockProperties_t * bpPtr)
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
