# Function: <code>ZSTD_selectBlockCompressor</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584915280,
      "name": "ZSTD_selectBlockCompressor",
      "external": false,
      "loc": "lib/zstd/compress.c:2322",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressBlock_internal"
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
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585037093,
      "name": "ZSTD_selectBlockCompressor",
      "external": false,
      "loc": "lib/zstd/compress.c:2322",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressBlock_internal"
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_dictMode_e dictMode)
```

```json
{
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586259256,
      "name": "ZSTD_selectBlockCompressor",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2322",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586284512,
      "name": "ZSTD_selectBlockCompressor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode)
```

```json
{
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587259057,
      "name": "ZSTD_selectBlockCompressor",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2633",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283936,
      "name": "ZSTD_selectBlockCompressor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode)
```

```json
{
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587523748,
      "name": "ZSTD_selectBlockCompressor",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2633",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587548800,
      "name": "ZSTD_selectBlockCompressor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_paramSwitch_e useRowMatchFinder, ZSTD_dictMode_e dictMode)
```

```json
{
  "name": "ZSTD_selectBlockCompressor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587858532,
      "name": "ZSTD_selectBlockCompressor",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress.c:2633",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSeqStore"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587883584,
      "name": "ZSTD_selectBlockCompressor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
ZSTD_blockCompressor ZSTD_selectBlockCompressor(ZSTD_strategy strat, ZSTD_dictMode_e dictMode)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>strat, dictMode</code> ➡️ <code>strat, useRowMatchFinder, dictMode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
