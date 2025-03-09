# Function: <code>ext4_setup_new_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581730563,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1236",
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
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581923756,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1236",
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
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582013820,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1236",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582126187,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1237",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582275503,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1263",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582462652,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1266",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582562018,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1266",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736640,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1274",
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
      "addr": 18446744071582736640,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 674
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582835936,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446744071582835936,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143760,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1284",
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
      "addr": 18446744071583143760,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583223328,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1289",
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
      "addr": 18446744071583223328,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251200,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1289",
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
      "addr": 18446744071583251200,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583593648,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1299",
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
      "addr": 18446744071583593648,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 697
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132384,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1321",
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
      "addr": 18446744071584132384,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584766208,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1337",
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
      "addr": 18446744071584766208,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 773
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989568,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1336",
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
      "addr": 18446744071584989568,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585221216,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1338",
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
      "addr": 18446744071585221216,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494506120,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446603336494506120,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227946696,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 3227946696,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288276496,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 13835058055288276496,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273905856,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446743936273905856,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804672,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446744071582804672,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582741824,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446744071582741824,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582793552,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446744071582793552,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 687
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "ext4_setup_new_descs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880016,
      "name": "ext4_setup_new_descs",
      "external": false,
      "loc": "fs/ext4/resize.c:1306",
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
      "addr": 18446744071582880016,
      "name": "ext4_setup_new_descs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 698
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
int ext4_setup_new_descs(handle_t * handle, struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
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
