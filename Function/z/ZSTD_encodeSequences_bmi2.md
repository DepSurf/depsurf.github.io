# Function: <code>ZSTD_encodeSequences_bmi2</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_encodeSequences_bmi2(void * dst, size_t dstCapacity, const FSE_CTable * CTable_MatchLength, const BYTE * mlCodeTable, const FSE_CTable * CTable_OffsetBits, const BYTE * ofCodeTable, const FSE_CTable * CTable_LitLength, const BYTE * llCodeTable, const seqDef * sequences, size_t nbSeq, int longOffsets)
```

```json
{
  "name": "ZSTD_encodeSequences_bmi2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_encodeSequences_bmi2",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:400",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303632,
      "name": "ZSTD_encodeSequences_bmi2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4399
    },
    {
      "addr": 18446744071594145082,
      "name": "ZSTD_encodeSequences_bmi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_encodeSequences_bmi2(void * dst, size_t dstCapacity, const FSE_CTable * CTable_MatchLength, const BYTE * mlCodeTable, const FSE_CTable * CTable_OffsetBits, const BYTE * ofCodeTable, const FSE_CTable * CTable_LitLength, const BYTE * llCodeTable, const seqDef * sequences, size_t nbSeq, int longOffsets)
```

```json
{
  "name": "ZSTD_encodeSequences_bmi2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_encodeSequences_bmi2",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:403",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309520,
      "name": "ZSTD_encodeSequences_bmi2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4262
    },
    {
      "addr": 18446744071596138689,
      "name": "ZSTD_encodeSequences_bmi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2660
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_encodeSequences_bmi2(void * dst, size_t dstCapacity, const FSE_CTable * CTable_MatchLength, const BYTE * mlCodeTable, const FSE_CTable * CTable_OffsetBits, const BYTE * ofCodeTable, const FSE_CTable * CTable_LitLength, const BYTE * llCodeTable, const seqDef * sequences, size_t nbSeq, int longOffsets)
```

```json
{
  "name": "ZSTD_encodeSequences_bmi2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_encodeSequences_bmi2",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:403",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574480,
      "name": "ZSTD_encodeSequences_bmi2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3846
    },
    {
      "addr": 18446744071596664376,
      "name": "ZSTD_encodeSequences_bmi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2613
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
size_t ZSTD_encodeSequences_bmi2(void * dst, size_t dstCapacity, const FSE_CTable * CTable_MatchLength, const BYTE * mlCodeTable, const FSE_CTable * CTable_OffsetBits, const BYTE * ofCodeTable, const FSE_CTable * CTable_LitLength, const BYTE * llCodeTable, const seqDef * sequences, size_t nbSeq, int longOffsets)
```

```json
{
  "name": "ZSTD_encodeSequences_bmi2",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_encodeSequences_bmi2",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:403",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_encodeSequences"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587909264,
      "name": "ZSTD_encodeSequences_bmi2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3846
    },
    {
      "addr": 18446744071597574053,
      "name": "ZSTD_encodeSequences_bmi2.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2613
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
size_t ZSTD_encodeSequences_bmi2(void * dst, size_t dstCapacity, const FSE_CTable * CTable_MatchLength, const BYTE * mlCodeTable, const FSE_CTable * CTable_OffsetBits, const BYTE * ofCodeTable, const FSE_CTable * CTable_LitLength, const BYTE * llCodeTable, const seqDef * sequences, size_t nbSeq, int longOffsets)
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
