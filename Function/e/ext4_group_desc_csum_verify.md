# Function: <code>ext4_group_desc_csum_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581707440,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2100",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707440,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581899728,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2219",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899728,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581989184,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2244",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989184,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205728,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2302",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205728,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582354480,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2305",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582354480,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582545312,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2346",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582545312,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582646496,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2408",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582646496,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582819376,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2451",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582819376,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582922720,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582922720,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583239232,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2623",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239232,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583341072,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2828",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341072,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583363984,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2854",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363984,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583706896,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2840",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706896,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261040,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:3219",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261040,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584910688,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:3208",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584910688,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585139488,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:3262",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139488,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585372272,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:3268",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585372272,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494599584,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494599584,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228042252,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228042252,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288401264,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288401264,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273975982,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273975982,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582891456,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582891456,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582828608,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582828608,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880352,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880352,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int ext4_group_desc_csum_verify(struct super_block * sb, __u32 block_group, struct ext4_group_desc * gdp)
```

```json
{
  "name": "ext4_group_desc_csum_verify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967136,
      "name": "ext4_group_desc_csum_verify",
      "external": true,
      "loc": "fs/ext4/super.c:2469",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_check_descriptors"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967136,
      "name": "ext4_group_desc_csum_verify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
