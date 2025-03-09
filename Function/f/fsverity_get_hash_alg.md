# Function: <code>fsverity_get_hash_alg</code>

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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320027,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071582318608,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:41",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582609363,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582607568,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:41",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591343100,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582680320,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:41",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591285840,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071582709072,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:41",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592242519,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071583035648,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:41",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594021523,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071583509584,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106944,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:43",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106944,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 535
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334016,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:42",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334016,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584551840,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:42",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584551840,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493898616,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493898616,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227378152,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227378152,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287535344,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287535344,
      "name": "fsverity_get_hash_alg",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273456416,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273456416,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288763,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071582287344,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582226523,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071582225104,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279243,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071582277824,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```

```json
{
  "name": "fsverity_get_hash_alg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "fsverity_get_hash_alg",
      "external": true,
      "loc": "fs/verity/hash_algs.c:39",
      "file": "fs/verity/hash_algs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/open.c:fsverity_init_merkle_tree_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357803,
      "name": "fsverity_get_hash_alg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071582356384,
      "name": "fsverity_get_hash_alg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
const struct fsverity_hash_alg * fsverity_get_hash_alg(const struct inode * inode, unsigned int num)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>const struct fsverity_hash_alg *</code> ➡️ <code>struct fsverity_hash_alg *</code>
</li>
</ul>
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct fsverity_hash_alg *</code> ➡️ <code>const struct fsverity_hash_alg *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
