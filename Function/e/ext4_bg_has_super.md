# Function: <code>ext4_bg_has_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581529984,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:746",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529984,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715632,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:752",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715632,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581803264,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:752",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581803264,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874576,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:752",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874576,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024576,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:752",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024576,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582212736,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:761",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212736,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582307584,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:761",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307584,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582473984,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:761",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473984,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582572912,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572912,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881424,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:771",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582881424,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582954304,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:797",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582954304,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582980208,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:797",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980208,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583316160,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:803",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583316160,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583823712,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:804",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583823712,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584446192,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:804",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446192,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584675088,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:846",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584675088,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584907808,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:854",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_blocks",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ioctl.c:ext4_update_backup_sb",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_setup_next_flex_gd",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:add_new_gdb_meta_bg",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:ext4_alloc_group_tables",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584907808,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494219992,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494219992,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227650820,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227650820,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287916384,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287916384,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273676564,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273676564,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582541648,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541648,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582478816,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478816,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582532128,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582532128,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int ext4_bg_has_super(struct super_block * sb, ext4_group_t group)
```

```json
{
  "name": "ext4_bg_has_super",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582612896,
      "name": "ext4_bg_has_super",
      "external": true,
      "loc": "fs/ext4/balloc.c:769",
      "file": "fs/ext4/balloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_num_base_meta_clusters",
        "fs/ext4/balloc.c:ext4_bg_num_gdb",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:verify_group_input",
        "fs/ext4/resize.c:ext4_group_overhead_blocks",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:descriptor_loc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582612896,
      "name": "ext4_bg_has_super",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
