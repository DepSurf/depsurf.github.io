# Function: <code>FSE_buildCTable_wksp</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584793120,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/fse_compress.c:92",
      "file": "lib/zstd/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compressWeights_wksp",
        "lib/zstd/huf_compress.c:HUF_compressWeights_wksp",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793120,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workspace, size_t workspaceSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906512,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/fse_compress.c:92",
      "file": "lib/zstd/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/huf_compress.c:HUF_compressWeights_wksp",
        "lib/zstd/huf_compress.c:HUF_compressWeights_wksp",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_loadZstdDictionary",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal",
        "lib/zstd/compress.c:ZSTD_compressSequences_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906512,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
    }
  ]
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/compress/fse_compress.c:67",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594141754,
      "name": "FSE_buildCTable_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    },
    {
      "addr": 18446744071586243952,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/compress/fse_compress.c:67",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596127592,
      "name": "FSE_buildCTable_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071587222768,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/compress/fse_compress.c:67",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596653343,
      "name": "FSE_buildCTable_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071587487024,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workSpace, size_t wkspSize)
```

```json
{
  "name": "FSE_buildCTable_wksp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "FSE_buildCTable_wksp",
      "external": true,
      "loc": "lib/zstd/compress/fse_compress.c:67",
      "file": "lib/zstd/compress/fse_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/huf_compress.c:HUF_writeCTable_wksp",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress.c:ZSTD_loadCEntropy",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable",
        "lib/zstd/compress/zstd_compress_sequences.c:ZSTD_buildCTable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597563020,
      "name": "FSE_buildCTable_wksp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071587821808,
      "name": "FSE_buildCTable_wksp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workspace, size_t workspaceSize)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workspace, size_t workspaceSize)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t FSE_buildCTable_wksp(FSE_CTable * ct, const short int * normalizedCounter, unsigned int maxSymbolValue, unsigned int tableLog, void * workSpace, size_t wkspSize)
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
