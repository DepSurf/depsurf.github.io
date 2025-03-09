# Function: <code>ZSTD_count_2segments</code>

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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584877604,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress.c:940",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
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
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822560,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585007498,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress.c:940",
      "file": "lib/zstd/compress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_BtGetAllMatches_selectMLS_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_insertBtAndFindBestMatch"
      ],
      "caller_func": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
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
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937024,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586319728,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:641",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState"
      ]
    },
    {
      "addr": 18446744071586355618,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:641",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState"
      ]
    },
    {
      "addr": 18446744071586446952,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:641",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState"
      ]
    },
    {
      "addr": 18446744071586460619,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:641",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586471473,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:641",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBtAndGetAllMatches"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586319728,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071586354464,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071586381920,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    },
    {
      "addr": 18446744071586469696,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587323856,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4"
      ]
    },
    {
      "addr": 18446744071587375429,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ]
    },
    {
      "addr": 18446744071587596276,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState"
      ]
    },
    {
      "addr": 18446744071587613843,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587656126,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587323856,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587363840,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587422256,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587627296,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587587824,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4"
      ]
    },
    {
      "addr": 18446744071587639697,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ]
    },
    {
      "addr": 18446744071587861362,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState"
      ]
    },
    {
      "addr": 18446744071587879004,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587921704,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587587824,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587628112,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587686576,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587892256,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```

```json
{
  "name": "ZSTD_count_2segments",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587922608,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_7",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_dictMatchState_4"
      ]
    },
    {
      "addr": 18446744071587974481,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0"
      ]
    },
    {
      "addr": 18446744071588196146,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_DUBT_findBestMatch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_insertDUBT1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_dictMatchState"
      ]
    },
    {
      "addr": 18446744071588213788,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_generateSequences_internal"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588256488,
      "name": "ZSTD_count_2segments",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:767",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_insertBt1"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_dictMatchState_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_6",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_5",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_4",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3",
        "lib/zstd/compress/zstd_opt.c:ZSTD_btGetAllMatches_extDict_3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587922608,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071587962896,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071588021360,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
    },
    {
      "addr": 18446744071588227040,
      "name": "ZSTD_count_2segments",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
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
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
size_t ZSTD_count_2segments(const BYTE * ip, const BYTE * match, const BYTE * iEnd, const BYTE * mEnd, const BYTE * iStart)
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
