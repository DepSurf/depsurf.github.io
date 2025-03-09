# Function: <code>ZSTD_decodeSeqHeaders</code>

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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583770607,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583780512,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987600,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987600,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1086
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068736,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068736,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1086
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255088,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255088,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584389888,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389888,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584961536,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584961536,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083600,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083600,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584957680,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957680,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585395440,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585395440,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586554224,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:577",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554224,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772800,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:653",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772800,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588044448,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:653",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588044448,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588379232,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:653",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588379232,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 630
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496274704,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496274704,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229615772,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229615772,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290576928,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290576928,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1292
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275331518,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275331518,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584358624,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584358624,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584293824,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293824,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584341536,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584341536,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
```

```json
{
  "name": "ZSTD_decodeSeqHeaders",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447568,
      "name": "ZSTD_decodeSeqHeaders",
      "external": true,
      "loc": "lib/zstd/decompress.c:794",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447568,
      "name": "ZSTD_decodeSeqHeaders",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
size_t ZSTD_decodeSeqHeaders(ZSTD_DCtx * dctx, int * nbSeqPtr, const void * src, size_t srcSize)
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
