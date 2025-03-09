# Function: <code>__ext4_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581696992,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:409",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/sysfs.c:ext4_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581696992,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888736,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:438",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/sysfs.c:ext4_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888736,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581977792,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:440",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/sysfs.c:ext4_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581977792,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582193952,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:445",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582193952,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342608,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:445",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/extents.c:ext4_ext_remove_space",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342608,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:448",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562486,
      "name": "__ext4_error.cold.135",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071582532016,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:490",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/extents.c:ext4_ext_rm_leaf",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582663702,
      "name": "__ext4_error.cold.139",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071582633104,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:501",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836279,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582805696,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940406,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582909056,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:534",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583254454,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071583222416,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:734",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:ext4_check_bdev_write_error",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591347785,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583324320,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:743",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591290619,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583347056,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:742",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592269674,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    },
    {
      "addr": 18446744071583690992,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:761",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594051146,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584241856,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584886640,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:754",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584886640,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585113792,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:754",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585113792,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, bool force_ro, int error, __u64 block, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585346208,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:823",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_wait_block_bitmap",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_validate_block_bitmap",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/ext4_jbd2.c:__ext4_forget",
        "fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access",
        "fs/ext4/ext4_jbd2.c:ext4_journal_check_start",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_validate_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:__ext4_get_inode_loc",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_clear_bb",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_bb",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_convert_meta_bg",
        "fs/ext4/resize.c:ext4_resize_begin",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:__ext4_remount",
        "fs/ext4/super.c:ext4_clear_journal_err",
        "fs/ext4/super.c:count_overhead",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/orphan.c:ext4_init_orphan_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585346208,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494584752,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494584752,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228027436,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228027436,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288383104,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288383104,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273964020,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273964020,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582909142,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582877792,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582846294,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582814944,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582897750,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582866672,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
void __ext4_error(struct super_block * sb, const char * function, unsigned int line, const char * fmt, void (anon))
```

```json
{
  "name": "__ext4_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ext4_error",
      "external": true,
      "loc": "fs/ext4/super.c:496",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_read_block_bitmap_nowait",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/balloc.c:ext4_get_group_desc",
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/extents.c:ext4_remove_blocks",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:ext4_orphan_get",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:__ext4_new_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_free_inode",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/ialloc.c:ext4_read_inode_bitmap",
        "fs/ext4/inode.c:__ext4_iget",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_group_add_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_mb_discard_lg_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_discard_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_discard_group_preallocations",
        "fs/ext4/mballoc.c:ext4_mb_mark_diskspace_used",
        "fs/ext4/mballoc.c:mb_find_extent",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/resize.c:ext4_resize_fs",
        "fs/ext4/super.c:ext4_enable_quotas",
        "fs/ext4/super.c:ext4_calculate_overhead",
        "fs/ext4/sysfs.c:ext4_attr_store",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget",
        "fs/ext4/xattr.c:ext4_xattr_inode_iget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582984838,
      "name": "__ext4_error.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071582953312,
      "name": "__ext4_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
<code>int error</code>
</li>
<li>
<b>Param added. </b>
<code>__u64 block</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, fmt, (anon)</code> ➡️ <code>sb, function, line, error, block, fmt, (anon)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_ro</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, function, line, error, block, fmt, (anon)</code> ➡️ <code>sb, function, line, force_ro, error, block, fmt, (anon)</code>
</li>
</ul>
</details>
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
