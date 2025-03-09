# Function: <code>ext4_block_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581694768,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:175",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_fill_super"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694768,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581908717,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:204",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886512,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581998766,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:206",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581975520,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582215634,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:208",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191664,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582364532,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:208",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340336,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582555082,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:208",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582529824,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582656325,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:231",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582630912,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582824161,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:232",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803536,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582927521,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906896,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583223043,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:207",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583220432,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583324931,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:296",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583322352,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583347672,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:296",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583345168,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583691615,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:293",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583688992,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584242692,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:312",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239648,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584887588,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:306",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584883984,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585114740,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:306",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585111184,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585347156,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:314",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_valid_block_bitmap",
        "fs/ext4/balloc.c:ext4_init_block_bitmap",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/balloc.c:ext4_num_overhead_clusters",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343632,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494604104,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494581816,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228047176,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228024872,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288406692,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288379936,
      "name": "ext4_block_bitmap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273979870,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273961564,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582896257,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875632,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582833409,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582812784,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582885153,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582864512,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
ext4_fsblk_t ext4_block_bitmap(struct super_block * sb, struct ext4_group_desc * bg)
```

```json
{
  "name": "ext4_block_bitmap",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582971905,
      "name": "ext4_block_bitmap",
      "external": true,
      "loc": "fs/ext4/super.c:227",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/balloc.c:ext4_free_clusters_after_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582951168,
      "name": "ext4_block_bitmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
