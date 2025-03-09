# Function: <code>ext4_validate_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581527952,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:363",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581527952,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 929
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713600,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:366",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713600,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581801232,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:366",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581801232,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 912
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
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581872592,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:366",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581872592,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
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
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022592,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:367",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022592,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 846
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582210736,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:357",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582210736,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305584,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:357",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305584,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582472016,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:357",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472016,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582570912,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582570912,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582879632,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879632,
      "name": "ext4_validate_block_bitmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    },
    {
      "addr": 18446744071582880080,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582952352,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952352,
      "name": "ext4_validate_block_bitmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071582952800,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582978240,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582978240,
      "name": "ext4_validate_block_bitmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071582978688,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583314048,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314048,
      "name": "ext4_validate_block_bitmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
    },
    {
      "addr": 18446744071583314496,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    },
    {
      "addr": 18446744071592249989,
      "name": "ext4_validate_block_bitmap.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583821488,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071594031050,
      "name": "ext4_validate_block_bitmap.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443824,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596064603,
      "name": "ext4_validate_block_bitmap.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673296,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:397",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673296,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584906016,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:399",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584906016,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494217456,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494217456,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227648332,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227648332,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287913392,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287913392,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273674394,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273674394,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582539648,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539648,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582476816,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582476816,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582530128,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530128,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_validate_block_bitmap(struct super_block * sb, struct ext4_group_desc * desc, ext4_group_t block_group, struct buffer_head * bh)
```

```json
{
  "name": "ext4_validate_block_bitmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582610800,
      "name": "ext4_validate_block_bitmap",
      "external": false,
      "loc": "fs/ext4/balloc.c:365",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610800,
      "name": "ext4_validate_block_bitmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
