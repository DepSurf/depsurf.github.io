# Function: <code>descriptor_loc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581715732,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2429",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581908155,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2574",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998194,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2601",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super"
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582224317,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2680",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582224317,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371037,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2683",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371037,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582504896,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2755",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504896,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582605168,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2817",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582605168,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582777120,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2856",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582777120,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880240,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880240,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583195312,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3028",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583195312,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583290544,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3233",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583290544,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314672,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3263",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314672,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657824,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3086",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657824,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227664,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3481",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227664,
      "name": "descriptor_loc",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584869264,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3470",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init",
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584869264,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093936,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3524",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init",
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093936,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585325632,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:3530",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init",
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325632,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494532736,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494532736,
      "name": "descriptor_loc",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227995828,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227995828,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288342432,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288342432,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273939516,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273939516,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848976,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848976,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786128,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786128,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837856,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837856,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
```

```json
{
  "name": "descriptor_loc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582924464,
      "name": "descriptor_loc",
      "external": false,
      "loc": "fs/ext4/super.c:2874",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582924464,
      "name": "descriptor_loc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
ext4_fsblk_t descriptor_loc(struct super_block * sb, ext4_fsblk_t logical_sb_block, int nr)
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
