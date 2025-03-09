# Function: <code>FSE_readNCount</code>

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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583797424,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583797424,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584004288,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004288,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085520,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085520,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584274384,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274384,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409184,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409184,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584925056,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584925056,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 760
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046784,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046784,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973328,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973328,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592334288,
      "name": "FSE_readNCount.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585412288,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586225349,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:236",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2",
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_default"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586226272,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587776437,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:236",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2",
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_default"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777488,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588048069,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:236",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2",
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_default"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588049120,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588382853,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/common/entropy_common.c:236",
      "file": "lib/zstd/common/entropy_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_bmi2",
        "lib/zstd/common/entropy_common.c:FSE_readNCount_body_default"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy",
        "lib/zstd/decompress/zstd_decompress.c:ZSTD_loadDEntropy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383904,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496293760,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496293760,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229629816,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229629816,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290598824,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290598824,
      "name": "FSE_readNCount",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275349936,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275349936,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584377920,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584377920,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313120,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313120,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360832,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360832,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
```

```json
{
  "name": "FSE_readNCount",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466864,
      "name": "FSE_readNCount",
      "external": true,
      "loc": "lib/zstd/entropy_common.c:59",
      "file": "lib/zstd/entropy_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_loadEntropy",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/decompress.c:ZSTD_decodeSeqHeaders",
        "lib/zstd/fse_decompress.c:FSE_decompress_wksp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466864,
      "name": "FSE_readNCount",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
size_t FSE_readNCount(short int * normalizedCounter, unsigned int * maxSVPtr, unsigned int * tableLogPtr, const void * headerBuffer, size_t hbSize)
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
