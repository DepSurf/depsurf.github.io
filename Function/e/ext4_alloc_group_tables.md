# Function: <code>ext4_alloc_group_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581736030,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:244",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581931358,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:244",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582021422,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:244",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582130757,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:245",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582280097,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:246",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582467948,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:249",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582567670,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:251",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:251",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582728560,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1078
    },
    {
      "addr": 18446744071582742831,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582843693,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583147616,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
    },
    {
      "addr": 18446744071583158500,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228384,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
    },
    {
      "addr": 18446744071591347626,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257216,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1213
    },
    {
      "addr": 18446744071591290460,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:283",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599920,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1219
    },
    {
      "addr": 18446744071592268151,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:294",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584135616,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
    },
    {
      "addr": 18446744071594049521,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:297",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584769664,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
    },
    {
      "addr": 18446744071596082335,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:297",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584993008,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1385
    },
    {
      "addr": 18446744071596605813,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, unsigned int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:302",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585224992,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1385
    },
    {
      "addr": 18446744071597511536,
      "name": "ext4_alloc_group_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494503928,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494503928,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1028
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227940612,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227940612,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1396
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288269792,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288269792,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273901302,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_resize_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273901302,
      "name": "ext4_alloc_group_tables",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 882
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582812429,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582749581,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582801309,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
  "name": "ext4_alloc_group_tables",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582887885,
      "name": "ext4_alloc_group_tables",
      "external": false,
      "loc": "fs/ext4/resize.c:278",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_resize_fs"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flexbg_size</code> ➡️ <code>unsigned int flexbg_size</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int ext4_alloc_group_tables(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd, int flexbg_size)
```
</details>
</li>
</ul>
