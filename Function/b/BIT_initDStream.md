# Function: <code>BIT_initDStream</code>

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
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583742041,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583771206,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583799098,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583959863,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989092,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584006927,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584040055,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070228,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584088208,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584225498,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256595,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584277051,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584360298,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584391395,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584411851,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584927779,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584931898,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584963043,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585049544,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585053711,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085128,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584929250,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959192,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584976095,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585365042,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585396933,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415119,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
size_t BIT_initDStream(BIT_DStream_t * bitD, const void * srcBuffer, size_t srcSize)
```

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586227344,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/common/fse_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable"
      ]
    },
    {
      "addr": 18446744071586481760,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default"
      ]
    },
    {
      "addr": 18446744071586533184,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586227344,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071586481760,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071586533184,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
size_t BIT_initDStream(BIT_DStream_t * bitD, const void * srcBuffer, size_t srcSize)
```

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587668928,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2"
      ]
    },
    {
      "addr": 18446744071587732320,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587778640,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/common/fse_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587668928,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071587732320,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    },
    {
      "addr": 18446744071587778640,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
size_t BIT_initDStream(BIT_DStream_t * bitD, const void * srcBuffer, size_t srcSize)
```

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587934288,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2"
      ]
    },
    {
      "addr": 18446744071587998112,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588050288,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/common/fse_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934288,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071587998112,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071588050288,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
size_t BIT_initDStream(BIT_DStream_t * bitD, const void * srcBuffer, size_t srcSize)
```

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588269072,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/huf_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X2_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress1X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_default",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2",
        "lib/zstd/decompress/huf_decompress.c:HUF_decompress4X1_usingDTable_internal_bmi2"
      ]
    },
    {
      "addr": 18446744071588332896,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588385072,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/common/bitstream.h:258",
      "file": "lib/zstd/common/fse_decompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_bmi2",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_wksp_body_default",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/common/fse_decompress.c:FSE_decompress_usingDTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269072,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071588332896,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
    },
    {
      "addr": 18446744071588385072,
      "name": "BIT_initDStream",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336496248692,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496275996,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496295556,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229592412,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 3229617072,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 3229631648,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290542480,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290578616,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290601340,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275299402,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275332584,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275351746,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584329034,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584360131,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584380587,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584264234,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295331,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584315787,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584311946,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343043,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584363499,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "BIT_initDStream",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584417978,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/huf_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X4_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal",
        "lib/zstd/huf_decompress.c:HUF_decompress1X2_usingDTable_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584449075,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/decompress.c:ZSTD_decompressSequencesLong",
        "lib/zstd/decompress.c:ZSTD_decompressSequences"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584469531,
      "name": "BIT_initDStream",
      "external": false,
      "loc": "lib/zstd/bitstream.h:239",
      "file": "lib/zstd/fse_decompress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable",
        "lib/zstd/fse_decompress.c:FSE_decompress_usingDTable"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t BIT_initDStream(BIT_DStream_t * bitD, const void * srcBuffer, size_t srcSize)
```
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
