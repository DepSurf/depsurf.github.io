# Function: <code>build_merkle_tree_level</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582316120,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:44",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604592,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 937
    },
    {
      "addr": 18446744071582607249,
      "name": "build_merkle_tree_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:44",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677584,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
    },
    {
      "addr": 18446744071591342888,
      "name": "build_merkle_tree_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:44",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582706352,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071591285631,
      "name": "build_merkle_tree_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:44",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583032912,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
    },
    {
      "addr": 18446744071592242252,
      "name": "build_merkle_tree_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:43",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506784,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071594021265,
      "name": "build_merkle_tree_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103424,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:43",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:build_merkle_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103424,
      "name": "build_merkle_tree_level",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1606
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493895756,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227375208,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287532416,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273454270,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582284856,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582222616,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582275336,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_merkle_tree_level",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582353896,
      "name": "build_merkle_tree_level",
      "external": false,
      "loc": "fs/verity/enable.c:16",
      "file": "fs/verity/enable.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:build_merkle_tree"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
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
int build_merkle_tree_level(struct file * filp, unsigned int level, u64 num_blocks_to_hash, const struct merkle_tree_params * params, u8 * pending_hashes, struct ahash_request * req)
```
</details>
</li>
</ul>
