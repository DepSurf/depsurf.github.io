# Function: <code>ZSTD_selectEncodingType</code>

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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat * repeatMode, const unsigned int * count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable * prevCTable, const short int * defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy)
```

```json
{
  "name": "ZSTD_selectEncodingType",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_selectEncodingType",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:155",
      "file": "lib/zstd/compress/zstd_compress_sequences.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594150501,
      "name": "ZSTD_selectEncodingType.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071586312800,
      "name": "ZSTD_selectEncodingType",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat * repeatMode, const unsigned int * count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable * prevCTable, const short int * defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy)
```

```json
{
  "name": "ZSTD_selectEncodingType",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_selectEncodingType",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:157",
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
      "addr": 18446744071596144472,
      "name": "ZSTD_selectEncodingType.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071587318656,
      "name": "ZSTD_selectEncodingType",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat * repeatMode, const unsigned int * count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable * prevCTable, const short int * defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy)
```

```json
{
  "name": "ZSTD_selectEncodingType",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_selectEncodingType",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:157",
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
      "addr": 18446744071596669529,
      "name": "ZSTD_selectEncodingType.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587582592,
      "name": "ZSTD_selectEncodingType",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat * repeatMode, const unsigned int * count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable * prevCTable, const short int * defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy)
```

```json
{
  "name": "ZSTD_selectEncodingType",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_selectEncodingType",
      "external": true,
      "loc": "lib/zstd/compress/zstd_compress_sequences.c:157",
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
      "addr": 18446744071597579206,
      "name": "ZSTD_selectEncodingType.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071587917376,
      "name": "ZSTD_selectEncodingType",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
symbolEncodingType_e ZSTD_selectEncodingType(FSE_repeat * repeatMode, const unsigned int * count, const unsigned int max, const size_t mostFrequent, size_t nbSeq, const unsigned int FSELog, const FSE_CTable * prevCTable, const short int * defaultNorm, U32 defaultNormLog, const ZSTD_defaultPolicy_e isDefaultAllowed, const ZSTD_strategy strategy)
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
