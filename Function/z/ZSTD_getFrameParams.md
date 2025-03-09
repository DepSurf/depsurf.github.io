# Function: <code>ZSTD_getFrameParams</code>

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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583792414,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766576,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 517
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583982881,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980592,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584064977,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061728,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584251233,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584247648,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584386033,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584382448,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957745,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954128,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585079734,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076144,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584955557,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584951408,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585393141,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressMultiFrame",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585388432,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496271024,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496267344,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229613792,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229610124,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290572144,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290567360,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275329388,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275323894,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354769,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351184,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584289969,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286384,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584337681,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334096,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_getFrameParams",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584443713,
      "name": "ZSTD_getFrameParams",
      "external": true,
      "loc": "lib/zstd/decompress.c:207",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_getDictID_fromFrame",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressStream",
        "lib/zstd/decompress.c:ZSTD_decompressContinue",
        "lib/zstd/decompress.c:ZSTD_decompressDCtx",
        "lib/zstd/decompress.c:ZSTD_findFrameCompressedSize",
        "lib/zstd/decompress.c:ZSTD_findDecompressedSize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440128,
      "name": "ZSTD_getFrameParams",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
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
size_t ZSTD_getFrameParams(ZSTD_frameParams * fparamsPtr, const void * src, size_t srcSize)
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
