# Function: <code>setup_new_flex_group_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581727438,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:473",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581921312,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:473",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582011376,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:473",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582123662,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:474",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582272887,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:488",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582460919,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:491",
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
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582560330,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:495",
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733136,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:495",
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
      "addr": 18446744071582733136,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582834192,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071582834192,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1709
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583151008,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:504",
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
      "addr": 18446744071583151008,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231200,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:504",
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
      "addr": 18446744071583231200,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1909
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259616,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:504",
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
      "addr": 18446744071583259616,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1920
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:511",
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
      "addr": 18446744071583602336,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2195
    },
    {
      "addr": 18446744071592268210,
      "name": "setup_new_flex_group_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071584138784,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2300
    },
    {
      "addr": 18446744071594049651,
      "name": "setup_new_flex_group_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:525",
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
      "addr": 18446744071584772896,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2301
    },
    {
      "addr": 18446744071596082445,
      "name": "setup_new_flex_group_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:525",
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
      "addr": 18446744071584996288,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
    },
    {
      "addr": 18446744071596605923,
      "name": "setup_new_flex_group_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:529",
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
      "addr": 18446744071585228320,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2279
    },
    {
      "addr": 18446744071597511677,
      "name": "setup_new_flex_group_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494507104,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446603336494507104,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1688
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227943124,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 3227943124,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2016
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288274496,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 13835058055288274496,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1920
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273904488,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446743936273904488,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582802928,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071582802928,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1709
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740080,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071582740080,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1709
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582791808,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071582791808,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1709
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
```

```json
{
  "name": "setup_new_flex_group_blocks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582878256,
      "name": "setup_new_flex_group_blocks",
      "external": false,
      "loc": "fs/ext4/resize.c:522",
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
      "addr": 18446744071582878256,
      "name": "setup_new_flex_group_blocks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1718
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
int setup_new_flex_group_blocks(struct super_block * sb, struct ext4_new_flex_group_data * flex_gd)
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
