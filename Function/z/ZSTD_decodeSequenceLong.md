# Function: <code>ZSTD_decodeSequenceLong</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583774190,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984624,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984624,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1731
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065760,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065760,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1731
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584252080,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584252080,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386880,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386880,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584958544,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584958544,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1756
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585080544,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585080544,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584960472,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953712,
      "name": "ZSTD_decodeSequenceLong.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585398173,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585390864,
      "name": "ZSTD_decodeSequenceLong.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1160
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496271856,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496271856,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1696
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290573184,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290573184,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2184
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275327480,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275327480,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1908
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355616,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355616,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290816,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290816,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584338528,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584338528,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```

```json
{
  "name": "ZSTD_decodeSequenceLong",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584444560,
      "name": "ZSTD_decodeSequenceLong",
      "external": false,
      "loc": "lib/zstd/decompress.c:1253",
      "file": "lib/zstd/decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584444560,
      "name": "ZSTD_decodeSequenceLong",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
seq_t ZSTD_decodeSequenceLong(seqState_t * seqState, const unsigned int windowSize)
```
</details>
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
