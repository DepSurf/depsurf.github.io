# Function: <code>ext4_discard_preallocations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809680,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3940",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809680,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1145
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582004064,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3954",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582004064,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1151
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582094112,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3961",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_clear_inode",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582094112,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1151
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058176,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4018",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058176,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1078
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209520,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4018",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209520,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 942
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582398464,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3988",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582398464,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582497440,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3987",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582497440,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 926
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582669712,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:3989",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582669712,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1009
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582771728,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582771728,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1001
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583082544,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4147",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583082544,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1069
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161520,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4324",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161520,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1070
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188032,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4857",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583188032,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583531232,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4913",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583531232,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 939
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584065184,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4968",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065184,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1090
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584698080,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4938",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584698080,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
void ext4_discard_preallocations(struct inode * inode, unsigned int needed)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923312,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5526",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923312,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1093
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155424,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:5501",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/extents.c:ext4_datasem_ensure_credits",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/indirect.c:ext4_ind_truncate_ensure_credits",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155424,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1059
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494438112,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494438112,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1040
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227873716,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227873716,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1216
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288188992,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/file.c:ext4_release_file",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288188992,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1832
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273850888,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273850888,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1230
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582740464,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582740464,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1001
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582677632,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582677632,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1001
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582730320,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730320,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1001
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
void ext4_discard_preallocations(struct inode * inode)
```

```json
{
  "name": "ext4_discard_preallocations",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815344,
      "name": "ext4_discard_preallocations",
      "external": true,
      "loc": "fs/ext4/mballoc.c:4008",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_ext_map_blocks",
        "fs/ext4/inode.c:ext4_truncate",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_da_update_reserve_space",
        "fs/ext4/inode.c:ext4_truncate_restart_trans",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/move_extent.c:ext4_move_extents",
        "fs/ext4/super.c:ext4_clear_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815344,
      "name": "ext4_discard_preallocations",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1012
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int needed</code>
</li>
</ul>
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
<b>Param removed. </b>
<code>unsigned int needed</code>
</li>
</ul>
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
