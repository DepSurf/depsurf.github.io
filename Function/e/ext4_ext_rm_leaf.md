# Function: <code>ext4_ext_rm_leaf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581755261,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2592",
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
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581950479,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2614",
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
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582040511,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2614",
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
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581903527,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2615",
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
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582053702,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2615",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, long long int * partial_cluster, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582232288,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2609",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232288,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2235
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582327408,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2660",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582327408,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3035
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497664,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2677",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497664,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597200,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597200,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582908256,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2544",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908256,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1693
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980128,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2543",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980128,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1626
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583005856,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2546",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583005856,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1619
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2584",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583342976,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1653
    },
    {
      "addr": 18446744071592252079,
      "name": "ext4_ext_rm_leaf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2583",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583852752,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1802
    },
    {
      "addr": 18446744071594033046,
      "name": "ext4_ext_rm_leaf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2590",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476880,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1803
    },
    {
      "addr": 18446744071596066283,
      "name": "ext4_ext_rm_leaf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2590",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705680,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1718
    },
    {
      "addr": 18446744071596590123,
      "name": "ext4_ext_rm_leaf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2566",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584938304,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1718
    },
    {
      "addr": 18446744071597495903,
      "name": "ext4_ext_rm_leaf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494247328,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494247328,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1572
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227678904,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227678904,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1884
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287951024,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287951024,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2220
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273698122,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273698122,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1428
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582565936,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582565936,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582503104,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503104,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582556048,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582556048,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, struct partial_cluster * partial, ext4_lblk_t start, ext4_lblk_t end)
```

```json
{
  "name": "ext4_ext_rm_leaf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637248,
      "name": "ext4_ext_rm_leaf",
      "external": false,
      "loc": "fs/ext4/extents.c:2723",
      "file": "fs/ext4/extents.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_ext_remove_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637248,
      "name": "ext4_ext_rm_leaf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1723
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int ext4_ext_rm_leaf(handle_t * handle, struct inode * inode, struct ext4_ext_path * path, long long int * partial_cluster, ext4_lblk_t start, ext4_lblk_t end)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct partial_cluster * partial</code>
</li>
<li>
<b>Param removed. </b>
<code>long long int * partial_cluster</code>
</li>
</ul>
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
