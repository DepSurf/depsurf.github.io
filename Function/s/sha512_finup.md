# Function: <code>sha512_finup</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sha512_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out, sha512_block_fn * sha512_xform)
```

```json
{
  "name": "sha512_finup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765600,
      "name": "sha512_finup",
      "external": false,
      "loc": "arch/x86/crypto/sha512_ssse3_glue.c:67",
      "file": "arch/x86/crypto/sha512_ssse3_glue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_avx2_final",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_avx_final",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579765600,
      "name": "sha512_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
int sha512_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out, sha512_block_fn * sha512_xform)
```

```json
{
  "name": "sha512_finup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579800544,
      "name": "sha512_finup",
      "external": false,
      "loc": "arch/x86/crypto/sha512_ssse3_glue.c:67",
      "file": "arch/x86/crypto/sha512_ssse3_glue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_avx2_final",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_avx_final",
        "arch/x86/crypto/sha512_ssse3_glue.c:sha512_ssse3_final"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800544,
      "name": "sha512_finup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int sha512_finup(struct shash_desc * desc, const u8 * data, unsigned int len, u8 * out, sha512_block_fn * sha512_xform)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
