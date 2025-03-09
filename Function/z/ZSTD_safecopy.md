# Function: <code>ZSTD_safecopy</code>

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
void ZSTD_safecopy(BYTE * op, const BYTE * oend_w, const BYTE * ip, ptrdiff_t length, ZSTD_overlap_e ovtype)
```

```json
{
  "name": "ZSTD_safecopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586535712,
      "name": "ZSTD_safecopy",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:720",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586535712,
      "name": "ZSTD_safecopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void ZSTD_safecopy(BYTE * op, const const BYTE * oend_w, const BYTE * ip, ptrdiff_t length, ZSTD_overlap_e ovtype)
```

```json
{
  "name": "ZSTD_safecopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587730768,
      "name": "ZSTD_safecopy",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:792",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587730768,
      "name": "ZSTD_safecopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 606
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
void ZSTD_safecopy(BYTE * op, const const BYTE * oend_w, const BYTE * ip, ptrdiff_t length, ZSTD_overlap_e ovtype)
```

```json
{
  "name": "ZSTD_safecopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996432,
      "name": "ZSTD_safecopy",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:792",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996432,
      "name": "ZSTD_safecopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
void ZSTD_safecopy(BYTE * op, const const BYTE * oend_w, const BYTE * ip, ptrdiff_t length, ZSTD_overlap_e ovtype)
```

```json
{
  "name": "ZSTD_safecopy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588331216,
      "name": "ZSTD_safecopy",
      "external": false,
      "loc": "lib/zstd/decompress/zstd_decompress_block.c:792",
      "file": "lib/zstd/decompress/zstd_decompress_block.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEndSplitLitBuffer",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd",
        "lib/zstd/decompress/zstd_decompress_block.c:ZSTD_execSequenceEnd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331216,
      "name": "ZSTD_safecopy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
void ZSTD_safecopy(BYTE * op, const BYTE * oend_w, const BYTE * ip, ptrdiff_t length, ZSTD_overlap_e ovtype)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const BYTE * oend_w</code> ➡️ <code>const const BYTE * oend_w</code>
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
