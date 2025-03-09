# Function: <code>ZSTD_safecopyLiterals</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void ZSTD_safecopyLiterals(BYTE * op, const BYTE * ip, const const BYTE * iend, const BYTE * ilimit_w)
```

```json
{
  "name": "ZSTD_safecopyLiterals",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586260128,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ]
    },
    {
      "addr": 18446744071586319552,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
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
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast"
      ]
    },
    {
      "addr": 18446744071586354288,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_extDict_generic",
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
      ]
    },
    {
      "addr": 18446744071586380160,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2"
      ]
    },
    {
      "addr": 18446744071586464254,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586477219,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:488",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260128,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071586319552,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071586354288,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071586380160,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void ZSTD_safecopyLiterals(BYTE * op, const BYTE * ip, const const BYTE * iend, const BYTE * ilimit_w)
```

```json
{
  "name": "ZSTD_safecopyLiterals",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587250128,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ]
    },
    {
      "addr": 18446744071587323664,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
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
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4"
      ]
    },
    {
      "addr": 18446744071587361168,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
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
      ]
    },
    {
      "addr": 18446744071587400496,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2"
      ]
    },
    {
      "addr": 18446744071587617681,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587618448,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587250128,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587323664,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587361168,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587400496,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587618448,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void ZSTD_safecopyLiterals(BYTE * op, const BYTE * ip, const const BYTE * iend, const BYTE * ilimit_w)
```

```json
{
  "name": "ZSTD_safecopyLiterals",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587514816,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ]
    },
    {
      "addr": 18446744071587587632,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
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
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4"
      ]
    },
    {
      "addr": 18446744071587625424,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
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
      ]
    },
    {
      "addr": 18446744071587664592,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2"
      ]
    },
    {
      "addr": 18446744071587882817,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587883584,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587514816,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587587632,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587625424,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587664592,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587883584,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void ZSTD_safecopyLiterals(BYTE * op, const BYTE * ip, const const BYTE * iend, const BYTE * ilimit_w)
```

```json
{
  "name": "ZSTD_safecopyLiterals",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587849600,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ]
    },
    {
      "addr": 18446744071587922416,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_extDict_generic",
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
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_6",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_5",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4",
        "lib/zstd/compress/zstd_double_fast.c:ZSTD_compressBlock_doubleFast_noDict_4"
      ]
    },
    {
      "addr": 18446744071587960208,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_7_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_6_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_5_0",
        "lib/zstd/compress/zstd_fast.c:ZSTD_compressBlock_fast_dictMatchState_4_0",
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
      ]
    },
    {
      "addr": 18446744071587999376,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dictMatchState_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_row",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2_dedicatedDictSearch",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_greedy_dictMatchState",
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
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress/zstd_lazy.c:ZSTD_compressBlock_btlazy2"
      ]
    },
    {
      "addr": 18446744071588217601,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588218368,
      "name": "ZSTD_safecopyLiterals",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:557",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587849600,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587922416,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587960208,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071587999376,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
    },
    {
      "addr": 18446744071588218368,
      "name": "ZSTD_safecopyLiterals",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void ZSTD_safecopyLiterals(BYTE * op, const BYTE * ip, const const BYTE * iend, const BYTE * ilimit_w)
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
