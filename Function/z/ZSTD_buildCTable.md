# Function: <code>ZSTD_buildCTable</code>

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
size_t ZSTD_buildCTable(void * dst, size_t dstCapacity, FSE_CTable * nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int * count, U32 max, const BYTE * codeTable, size_t nbSeq, const S16 * defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable * prevCTable, size_t prevCTableSize, void * entropyWorkspace, size_t entropyWorkspaceSize)
```

```json
{
  "name": "ZSTD_buildCTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586313440,
      "name": "ZSTD_buildCTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:241",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586313440,
      "name": "ZSTD_buildCTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
size_t ZSTD_buildCTable(void * dst, size_t dstCapacity, FSE_CTable * nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int * count, U32 max, const BYTE * codeTable, size_t nbSeq, const S16 * defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable * prevCTable, size_t prevCTableSize, void * entropyWorkspace, size_t entropyWorkspaceSize)
```

```json
{
  "name": "ZSTD_buildCTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587319312,
      "name": "ZSTD_buildCTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:243",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587319312,
      "name": "ZSTD_buildCTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
size_t ZSTD_buildCTable(void * dst, size_t dstCapacity, FSE_CTable * nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int * count, U32 max, const BYTE * codeTable, size_t nbSeq, const S16 * defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable * prevCTable, size_t prevCTableSize, void * entropyWorkspace, size_t entropyWorkspaceSize)
```

```json
{
  "name": "ZSTD_buildCTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587583264,
      "name": "ZSTD_buildCTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:243",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587583264,
      "name": "ZSTD_buildCTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
size_t ZSTD_buildCTable(void * dst, size_t dstCapacity, FSE_CTable * nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int * count, U32 max, const BYTE * codeTable, size_t nbSeq, const S16 * defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable * prevCTable, size_t prevCTableSize, void * entropyWorkspace, size_t entropyWorkspaceSize)
```

```json
{
  "name": "ZSTD_buildCTable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587918048,
      "name": "ZSTD_buildCTable",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:243",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics",
        "lib/zstd/compress/zstd_compress.c:ZSTD_buildSequencesStatistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587918048,
      "name": "ZSTD_buildCTable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 415
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
size_t ZSTD_buildCTable(void * dst, size_t dstCapacity, FSE_CTable * nextCTable, U32 FSELog, symbolEncodingType_e type, unsigned int * count, U32 max, const BYTE * codeTable, size_t nbSeq, const S16 * defaultNorm, U32 defaultNormLog, U32 defaultMax, const FSE_CTable * prevCTable, size_t prevCTableSize, void * entropyWorkspace, size_t entropyWorkspaceSize)
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
