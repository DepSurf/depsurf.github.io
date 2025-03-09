# Function: <code>fsverity_hash_page</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320240,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582319392,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:233",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609531,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582608576,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:233",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343268,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582681328,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:233",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591286008,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071582710112,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:233",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592242686,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583036752,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:233",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594021690,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583510832,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584108416,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:235",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree_level",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584108416,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493899656,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493899656,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227379168,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227379168,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287536688,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287536688,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273457246,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273457246,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288976,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582288128,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226736,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582225888,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279456,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582278608,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```

```json
{
  "name": "fsverity_hash_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_hash_page",
      "external": true,
      "loc": "fs/verity/hash_algs.c:184",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree",
        "fs/verity/verify.c:verify_page",
        "fs/verity/verify.c:verify_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358016,
      "name": "fsverity_hash_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582357168,
      "name": "fsverity_hash_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
int fsverity_hash_page(const struct merkle_tree_params * params, const struct inode * inode, struct ahash_request * req, struct page * page, u8 * out)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
