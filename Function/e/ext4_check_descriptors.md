# Function: <code>ext4_check_descriptors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581716138,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2119",
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
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581908567,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2238",
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
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998618,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2263",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582215457,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2321",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582364324,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2324",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582554680,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2365",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582655926,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2427",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582819456,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2470",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582819456,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922800,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922800,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239328,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2642",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239328,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583341168,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2847",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341168,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1221
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364080,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2873",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364080,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1218
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706992,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2859",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706992,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1218
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261152,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:3238",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:__ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261152,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1247
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910816,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:3227",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910816,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1247
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585139616,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:3281",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139616,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372400,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:3287",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_group_desc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372400,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1244
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494599744,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494599744,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228042448,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228042448,
      "name": "ext4_check_descriptors",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288401408,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288401408,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1588
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273976090,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273976090,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582891536,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582891536,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828688,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828688,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880432,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880432,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1237
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
```

```json
{
  "name": "ext4_check_descriptors",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967216,
      "name": "ext4_check_descriptors",
      "external": false,
      "loc": "fs/ext4/super.c:2488",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967216,
      "name": "ext4_check_descriptors",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1205
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
int ext4_check_descriptors(struct super_block * sb, ext4_fsblk_t sb_block, ext4_group_t * first_not_zeroed)
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
