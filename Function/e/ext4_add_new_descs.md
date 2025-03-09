# Function: <code>ext4_add_new_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581728644,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1150",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581922497,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1150",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582012561,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1150",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120176,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1151",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120176,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2848
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269328,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1177",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269328,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1180",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582457728,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3014
    },
    {
      "addr": 18446744071582470640,
      "name": "ext4_add_new_descs.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1180",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582557328,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2822
    },
    {
      "addr": 18446744071582569992,
      "name": "ext4_add_new_descs.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734880,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1188",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734880,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1749
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837792,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837792,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1725
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583154096,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1197",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154096,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235360,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1202",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235360,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583263526,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1202",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583606625,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1211",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584146854,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1233",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584781330,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1249",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585004658,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1249",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585236809,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1251",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494511464,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494511464,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1668
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227948768,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227948768,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1764
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288279640,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273907736,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/resize.c:ext4_flex_group_add"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806528,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806528,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1725
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582743680,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743680,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1725
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795408,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795408,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1725
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
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```

```json
{
  "name": "ext4_add_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582881904,
      "name": "ext4_add_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1219",
      "file": "fs/ext4/resize.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/resize.c:ext4_flex_group_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881904,
      "name": "ext4_add_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1744
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ext4_add_new_descs(handle_t * handle, struct super_block * sb, ext4_group_t group, struct inode * resize_inode, ext4_group_t count)
```
</details>
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
