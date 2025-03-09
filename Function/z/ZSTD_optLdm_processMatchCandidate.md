# Function: <code>ZSTD_optLdm_processMatchCandidate</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ZSTD_optLdm_processMatchCandidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586476294,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:895",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic"
      ],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586465920,
      "name": "ZSTD_optLdm_processMatchCandidate.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t * optLdm, ZSTD_match_t * matches, U32 * nbMatches, U32 currPosInBlock, U32 remainingBytes)
```

```json
{
  "name": "ZSTD_optLdm_processMatchCandidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587619584,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:987",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587619584,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t * optLdm, ZSTD_match_t * matches, U32 * nbMatches, U32 currPosInBlock, U32 remainingBytes)
```

```json
{
  "name": "ZSTD_optLdm_processMatchCandidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587884720,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:987",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884720,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t * optLdm, ZSTD_match_t * matches, U32 * nbMatches, U32 currPosInBlock, U32 remainingBytes)
```

```json
{
  "name": "ZSTD_optLdm_processMatchCandidate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588219504,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "external": false,
      "loc": "lib/zstd/compress/zstd_opt.c:987",
      "file": "lib/zstd/compress/zstd_opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0",
        "lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588219504,
      "name": "ZSTD_optLdm_processMatchCandidate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t * optLdm, ZSTD_match_t * matches, U32 * nbMatches, U32 currPosInBlock, U32 remainingBytes)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
