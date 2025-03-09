# Function: <code>HUF_getNbBits</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
U32 HUF_getNbBits(const void * symbolTable, U32 symbolValue)
```

```json
{
  "name": "HUF_getNbBits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586253648,
      "name": "HUF_getNbBits",
      "external": true,
      "loc": "lib/zstd/compress/huf_compress.c:209",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_rescaleFreqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586253648,
      "name": "HUF_getNbBits",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_getNbBits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587249130,
      "name": "HUF_getNbBits",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:128",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_getNbBitsFromCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_getNbBits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587513819,
      "name": "HUF_getNbBits",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:128",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_getNbBitsFromCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "HUF_getNbBits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587848603,
      "name": "HUF_getNbBits",
      "external": false,
      "loc": "lib/zstd/compress/huf_compress.c:128",
      "file": "lib/zstd/compress/huf_compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress_internal",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_default",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_compress1X_usingCTable_internal_bmi2",
        "lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp",
        "lib/zstd/compress/huf_compress.c:HUF_getNbBitsFromCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_readCTable",
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp"
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
U32 HUF_getNbBits(const void * symbolTable, U32 symbolValue)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
U32 HUF_getNbBits(const void * symbolTable, U32 symbolValue)
```
</details>
</li>
</ul>
