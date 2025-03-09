# Function: <code>ext4_rereserve_cluster</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582319888,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2508",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582319888,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486992,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2525",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486992,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586240,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582586240,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582896224,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2392",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582896224,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582968192,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2391",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582968192,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994256,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2394",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994256,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2432",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583330720,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071592251025,
      "name": "ext4_rereserve_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2431",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583839888,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071594032052,
      "name": "ext4_rereserve_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2438",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463264,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071596065337,
      "name": "ext4_rereserve_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2438",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584692160,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071596589259,
      "name": "ext4_rereserve_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2414",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924848,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    },
    {
      "addr": 18446744071597495043,
      "name": "ext4_rereserve_cluster.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494238152,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494238152,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227668904,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227668904,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287939712,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287939712,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273690702,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273690702,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554976,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554976,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492144,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492144,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545088,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545088,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```

```json
{
  "name": "ext4_rereserve_cluster",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582626208,
      "name": "ext4_rereserve_cluster",
      "external": false,
      "loc": "fs/ext4/extents.c:2571",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/extents.c:ext4_remove_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582626208,
      "name": "ext4_rereserve_cluster",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void ext4_rereserve_cluster(struct inode * inode, ext4_lblk_t lblk)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
