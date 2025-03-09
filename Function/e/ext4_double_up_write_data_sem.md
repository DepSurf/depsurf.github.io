# Function: <code>ext4_double_up_write_data_sem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820997,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:79",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581823712,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020605,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:79",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019632,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582110675,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:79",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109664,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582080819,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:79",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079600,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230431,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:79",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229200,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582420259,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419056,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582519866,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:ext4_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582518528,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582688613,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687248,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582790805,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582789440,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583103024,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102272,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583182064,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583181312,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583208691,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207936,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583552272,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551488,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584086949,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:72",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086128,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584719541,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718912,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584942914,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584942288,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585174391,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585173776,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494460140,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494458896,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227895932,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227894140,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288215284,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288213520,
      "name": "ext4_double_up_write_data_sem",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273867756,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273866600,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582759541,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758176,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582696709,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582695344,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582749397,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582748032,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void ext4_double_up_write_data_sem(struct inode * orig_inode, struct inode * donor_inode)
```

```json
{
  "name": "ext4_double_up_write_data_sem",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582834677,
      "name": "ext4_double_up_write_data_sem",
      "external": true,
      "loc": "fs/ext4/move_extent.c:71",
      "file": "fs/ext4/move_extent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ],
      "caller_func": [
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582833312,
      "name": "ext4_double_up_write_data_sem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
