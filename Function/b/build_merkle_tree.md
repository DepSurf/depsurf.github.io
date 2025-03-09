# Function: <code>build_merkle_tree</code>

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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582315952,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    },
    {
      "addr": 18446744071582318362,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605536,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:151",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605536,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582678528,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:151",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582678528,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707296,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:151",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707296,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:151",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033856,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071592242372,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:150",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583507840,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071594021387,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:150",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105056,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
    },
    {
      "addr": 18446744071596059058,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331296,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:72",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331296,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1271
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
int build_merkle_tree(struct file * filp, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584549120,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:72",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584549120,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493895592,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493895592,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227374964,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227374964,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287532128,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287532128,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1412
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273454120,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273454120,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582284688,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    },
    {
      "addr": 18446744071582287098,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222448,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    },
    {
      "addr": 18446744071582224858,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275168,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 991
    },
    {
      "addr": 18446744071582277578,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```

```json
{
  "name": "build_merkle_tree",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "build_merkle_tree",
      "external": false,
      "loc": "fs/verity/enable.c:113",
      "file": "fs/verity/enable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/verity/enable.c:enable_verity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353728,
      "name": "build_merkle_tree",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
    },
    {
      "addr": 18446744071582356138,
      "name": "build_merkle_tree.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int build_merkle_tree(struct inode * inode, const struct merkle_tree_params * params, u8 * root_hash)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file * filp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode * inode</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
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
