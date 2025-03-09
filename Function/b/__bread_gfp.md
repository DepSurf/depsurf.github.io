# Function: <code>__bread_gfp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223808,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1428",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:reserve_backup_gdb",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223808,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581390656,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1418",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581390656,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469072,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1418",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469072,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524560,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1413",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524560,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666912,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1373",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666912,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830352,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1344",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:ext4_ext_migrate",
        "fs/ext4/migrate.c:free_ext_idx",
        "fs/ext4/migrate.c:free_dind_blocks",
        "fs/ext4/migrate.c:update_dind_extent_range",
        "fs/ext4/migrate.c:update_ind_extent_range",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/resize.c:ext4_group_add",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/resize.c:ext4_add_new_descs",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/xattr.c:ext4_xattr_delete_inode",
        "fs/ext4/xattr.c:ext4_expand_extra_isize_ea",
        "fs/ext4/xattr.c:ext4_xattr_get_block",
        "fs/ext4/xattr.c:ext4_xattr_block_set",
        "fs/ext4/xattr.c:ext4_get_inode_usage",
        "fs/ext4/xattr.c:ext4_listxattr",
        "fs/ext4/xattr.c:ext4_xattr_get",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830352,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917600,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1352",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_load_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917600,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054752,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054752,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582132448,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582132448,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370640,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1397",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370640,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582428848,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1396",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582428848,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582454848,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1401",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582454848,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780320,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1376",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780320,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583325088,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1375",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583325088,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583912752,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1364",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583912752,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584139456,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1476",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584139456,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584355600,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1461",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/super.c:ext4_get_journal_blkdev",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_rebuild_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584355600,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493676584,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493676584,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227208628,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227208628,
      "name": "__bread_gfp",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287278464,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287278464,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273301308,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273301308,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582101184,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582101184,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038624,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038624,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582091664,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582091664,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
struct buffer_head * __bread_gfp(struct block_device * bdev, sector_t block, unsigned int size, gfp_t gfp)
```

```json
{
  "name": "__bread_gfp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582164432,
      "name": "__bread_gfp",
      "external": true,
      "loc": "fs/buffer.c:1353",
      "file": "fs/buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/indirect.c:ext4_free_branches",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_group_extend",
        "fs/ext4/super.c:ext4_get_dev_journal",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/squashfs/block.c:squashfs_read_data",
        "fs/fat/dir.c:fat__get_entry",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/fatent.c:fat12_ent_bread",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:fat_fill_super",
        "fs/fat/inode.c:__fat_write_inode",
        "fs/fat/inode.c:fat_set_state",
        "fs/fat/misc.c:fat_clusters_flush",
        "fs/fat/nfs.c:fat_get_parent",
        "fs/fat/nfs.c:__fat_nfs_get_inode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164432,
      "name": "__bread_gfp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
