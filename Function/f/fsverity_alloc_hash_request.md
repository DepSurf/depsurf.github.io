# Function: <code>fsverity_alloc_hash_request</code>

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
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582609060,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:123",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607856,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582681812,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:123",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582680608,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582710596,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:123",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582709360,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037236,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:123",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583036000,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583511435,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:123",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583509968,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```

```json
{
  "name": "fsverity_alloc_hash_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584109083,
      "name": "fsverity_alloc_hash_request",
      "external": true,
      "loc": "fs/verity/hash_algs.c:125",
      "file": "fs/verity/hash_algs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/hash_algs.c:fsverity_hash_buffer",
        "fs/verity/hash_algs.c:fsverity_prepare_hash_state"
      ],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:fsverity_verify_bio",
        "fs/verity/verify.c:fsverity_verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584107504,
      "name": "fsverity_alloc_hash_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
struct ahash_request * fsverity_alloc_hash_request(struct fsverity_hash_alg * alg, gfp_t gfp_flags)
```
</details>
</li>
</ul>
