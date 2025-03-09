# Function: <code>ext4_get_group_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581529056,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:276",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581529056,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714672,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:279",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714672,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802304,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:279",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/block_validity.c:ext4_setup_system_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802304,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581873584,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:279",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581873584,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582023584,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:280",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023584,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582211728,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582211728,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582306576,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582306576,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582472944,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472944,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571872,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571872,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880352,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880352,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953136,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:recently_deleted",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953136,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979040,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979040,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592250130,
      "name": "ext4_get_group_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071583314912,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 238
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594031190,
      "name": "ext4_get_group_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071583822288,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596064743,
      "name": "ext4_get_group_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071584444672,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:266",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596588596,
      "name": "ext4_get_group_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584672848,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:265",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_mark_inode_used",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_other",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_mark_context",
        "fs/ext4/mballoc.c:ext4_mb_init_backend",
        "fs/ext4/mballoc.c:ext4_mb_prefetch_fini",
        "fs/ext4/mballoc.c:ext4_mb_prefetch",
        "fs/ext4/mballoc.c:ext4_mb_good_group_nolock",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_fill_flex_info",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597494424,
      "name": "ext4_get_group_desc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584905568,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494218744,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494218744,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227649584,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_inode_bit",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227649584,
      "name": "ext4_get_group_desc",
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287914768,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287914768,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273675528,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273675528,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582540608,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582540608,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582477776,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582477776,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531088,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531088,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
struct ext4_group_desc * ext4_get_group_desc(struct super_block * sb, ext4_group_t block_group, struct buffer_head * * bh)
```

```json
{
  "name": "ext4_get_group_desc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582611760,
      "name": "ext4_get_group_desc",
      "external": true,
      "loc": "fs/ext4/balloc.c:264",
      "file": "fs/ext4/balloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_count_free_clusters",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/fsmap.c:ext4_getfsmap_datadev",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_count_dirs",
        "fs/ext4/ialloc.c:ext4_count_free_inodes",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:find_group_orlov",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_mb_init",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/super.c:ext4_check_descriptors",
        "fs/ext4/super.c:ext4_mark_group_bitmap_corrupted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582611760,
      "name": "ext4_get_group_desc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
