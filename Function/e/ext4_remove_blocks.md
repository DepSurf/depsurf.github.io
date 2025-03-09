# Function: <code>ext4_remove_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581755261,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2476",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581950595,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2498",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582040627,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2498",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581903643,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2499",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582053822,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2499",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582232641,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2493",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582327747,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2524",
      "file": "fs/ext4/extents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582492624,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2541",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582492624,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592160,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592160,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582904832,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2408",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582904832,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582976688,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2407",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582976688,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002432,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2410",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002432,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1154
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2448",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341584,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
    },
    {
      "addr": 18446744071592251801,
      "name": "ext4_remove_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2447",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583851280,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
    },
    {
      "addr": 18446744071594032758,
      "name": "ext4_remove_blocks.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2454",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475296,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1253
    },
    {
      "addr": 18446744071596066005,
      "name": "ext4_remove_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2454",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704144,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
    },
    {
      "addr": 18446744071596589944,
      "name": "ext4_remove_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2430",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584936768,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
    },
    {
      "addr": 18446744071597495724,
      "name": "ext4_remove_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494242432,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494242432,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227671308,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227671308,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1600
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287942832,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287942832,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273693870,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273693870,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1132
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560896,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560896,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582498064,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582498064,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582551008,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582551008,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
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
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```

```json
{
  "name": "ext4_remove_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582632176,
      "name": "ext4_remove_blocks",
      "external": false,
      "loc": "fs/ext4/extents.c:2587",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_rm_leaf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582632176,
      "name": "ext4_remove_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ext4_remove_blocks(handle_t * handle, struct inode * inode, struct ext4_extent * ex, struct partial_cluster * partial, ext4_lblk_t from, ext4_lblk_t to)
```
</details>
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
