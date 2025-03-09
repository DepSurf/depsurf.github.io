# Function: <code>__getblk_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581220512,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1390",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581220512,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387952,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1380",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:jbd2_journal_init_inode",
        "fs/jbd2/journal.c:jbd2_journal_init_dev",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387952,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465696,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1380",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465696,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 821
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581520400,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1375",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581520400,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 719
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581662544,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1335",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581662544,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1306",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581839106,
      "name": "__getblk_gfp.cold.62",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581826976,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1314",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581926347,
      "name": "__getblk_gfp.cold.65",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071581913104,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063789,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582050240,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 656
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582141626,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582128096,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582370645,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1348",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582367456,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582428877,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1347",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426240,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1352",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591283514,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071582453728,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1327",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592232888,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
    },
    {
      "addr": 18446744071582779824,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1326",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594012593,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071583324544,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1326",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596052693,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071583910400,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584139485,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1438",
      "file": "fs/buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead"
      ],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_grow_indepth",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_breadahead_unmovable",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/jbd2/journal.c:jbd2_fc_get_buf",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139088,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493670744,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493670744,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227204104,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227204104,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287271712,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_insert_extent",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287271712,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1076
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
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273297250,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273297250,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 662
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110362,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582096832,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582047802,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582034272,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_alloc_branch",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582100842,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582087312,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__getblk_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__getblk_gfp",
      "external": true,
      "loc": "fs/buffer.c:1315",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/buffer.c:__bread_gfp",
        "fs/buffer.c:__breadahead",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/extents.c:ext4_ext_create_new_leaf",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:ext4_ext_split",
        "fs/ext4/extents.c:__read_extent_tree_block",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/indirect.c:ext4_ind_map_blocks",
        "fs/ext4/indirect.c:ext4_get_branch",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/mmp.c:read_mmp_block",
        "fs/ext4/resize.c:ext4_get_bitmap",
        "fs/ext4/resize.c:update_backups",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:set_flexbg_block_bitmap",
        "fs/ext4/resize.c:bclean",
        "fs/ext4/super.c:ext4_sb_bread",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/jbd2/recovery.c:do_one_pass",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/recovery.c:jread",
        "fs/jbd2/journal.c:journal_init_common",
        "fs/jbd2/journal.c:jbd2_journal_get_descriptor_buffer",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat_add_new_entries",
        "fs/fat/dir.c:fat_alloc_new_dir",
        "fs/fat/fatent.c:fat_mirror_bhs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173707,
      "name": "__getblk_gfp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582160016,
      "name": "__getblk_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 647
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct buffer_head * __getblk_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```
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
