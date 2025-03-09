# Function: <code>ZSTD_storeSeq</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ZSTD_storeSeq(seqStore_t * seqStorePtr, size_t litLength, const void * literals, U32 offsetCode, size_t matchCode)
```

```json
{
  "name": "ZSTD_storeSeq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584868402,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress.c:861",
      "file": "lib/zstd/compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast"
      ],
      "caller_func": [
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
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
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
      "addr": 18446744071584808064,
      "name": "ZSTD_storeSeq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    },
    {
      "addr": 18446744071584808240,
      "name": "ZSTD_storeSeq.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void ZSTD_storeSeq(seqStore_t * seqStorePtr, size_t litLength, const void * literals, U32 offsetCode, size_t matchCode)
```

```json
{
  "name": "ZSTD_storeSeq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585027615,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress.c:861",
      "file": "lib/zstd/compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btopt",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy_extDict",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_greedy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_lazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_btlazy2",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_doubleFast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast_extDict_generic",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast",
        "lib/zstd/compress.c:ZSTD_compressBlock_fast"
      ],
      "caller_func": [
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
        "lib/zstd/compress.c:ZSTD_compressBlock_fast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584919344,
      "name": "ZSTD_storeSeq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071584921456,
      "name": "ZSTD_storeSeq.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_storeSeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586260640,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586321767,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586356326,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071586457219,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586464245,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586476951,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:505",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_storeSeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587254690,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358695,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376665,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587610368,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587617670,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587623674,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
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
  "name": "ZSTD_storeSeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587519477,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587622560,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640934,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587875638,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587882806,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888662,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
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
  "name": "ZSTD_storeSeq",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587854261,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreNoBlockDelim",
        "lib/zstd/compress/zstd_compress.c:ZSTD_copySequencesToSeqStoreExplicitBlockDelim"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587957344,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_double_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587975718,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_fast.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588210422,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_lazy.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588217590,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_ldm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_ldm.c:ZSTD_ldm_blockCompress"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588223446,
      "name": "ZSTD_storeSeq",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress_internal.h:588",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ZSTD_storeSeq(seqStore_t * seqStorePtr, size_t litLength, const void * literals, U32 offsetCode, size_t matchCode)
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
void ZSTD_storeSeq(seqStore_t * seqStorePtr, size_t litLength, const void * literals, U32 offsetCode, size_t matchCode)
```
</details>
</li>
</ul>
