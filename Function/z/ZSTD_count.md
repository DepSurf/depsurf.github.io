# Function: <code>ZSTD_count</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584807504,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress.c:907",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_updateTree",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584807504,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584921312,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress.c:907",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_updateTree",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584921312,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586259863,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_isRLE"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594152748,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586355634,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586449056,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ]
    },
    {
      "addr": 18446744071586460639,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586471096,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:615",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586379904,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587254071,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_isRLE"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587344250,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375185,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587596292,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row"
      ]
    },
    {
      "addr": 18446744071587613863,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587654878,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400688,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587518792,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_isRLE"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587608411,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587639453,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587861378,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row"
      ]
    },
    {
      "addr": 18446744071587879024,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587920194,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664784,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```

```json
{
  "name": "ZSTD_count",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587853576,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_isRLE"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587943195,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_count_2segments"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587974237,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_7_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_6_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_5_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_noDict_4_1"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588196162,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row"
      ]
    },
    {
      "addr": 18446744071588213808,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal",
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588254978,
      "name": "ZSTD_count",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:741",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_noDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999568,
      "name": "ZSTD_count",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
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
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_count(const BYTE * pIn, const BYTE * pMatch, const const BYTE * pInLimit)
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
