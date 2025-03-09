# Function: <code>ZSTD_reset_matchState</code>

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
size_t ZSTD_reset_matchState(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_compressionParameters * cParams, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho)
```

```json
{
  "name": "ZSTD_reset_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_reset_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1484",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264880,
      "name": "ZSTD_reset_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1542
    },
    {
      "addr": 18446744071594143941,
      "name": "ZSTD_reset_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
size_t ZSTD_reset_matchState(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho)
```

```json
{
  "name": "ZSTD_reset_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_reset_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1642",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587261872,
      "name": "ZSTD_reset_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2502
    },
    {
      "addr": 18446744071596137540,
      "name": "ZSTD_reset_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
size_t ZSTD_reset_matchState(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho)
```

```json
{
  "name": "ZSTD_reset_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_reset_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1642",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587526544,
      "name": "ZSTD_reset_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2502
    },
    {
      "addr": 18446744071596663287,
      "name": "ZSTD_reset_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
size_t ZSTD_reset_matchState(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_compressionParameters * cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho)
```

```json
{
  "name": "ZSTD_reset_matchState",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ZSTD_reset_matchState",
      "external": false,
      "loc": "lib/zstd/compress/zstd_compress.c:1642",
      "file": "lib/zstd/compress/zstd_compress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal",
        "lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861328,
      "name": "ZSTD_reset_matchState",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2502
    },
    {
      "addr": 18446744071597572964,
      "name": "ZSTD_reset_matchState.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
size_t ZSTD_reset_matchState(ZSTD_matchState_t * ms, ZSTD_cwksp * ws, const ZSTD_compressionParameters * cParams, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>ms, ws, cParams, crp, forceResetIndex, forWho</code> ➡️ <code>ms, ws, cParams, useRowMatchFinder, crp, forceResetIndex, forWho</code>
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
