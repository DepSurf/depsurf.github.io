# Function: <code>ext4_map_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581567568,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:458",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/file.c:ext4_llseek",
        "fs/ext4/file.c:ext4_llseek",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581567568,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1183
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752400,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:474",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inode.c:ext4_get_next_extent",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752400,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1458
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840512,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:481",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/file.c:ext4_overwrite_io",
        "fs/ext4/inode.c:ext4_get_next_extent",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/readpage.c:ext4_mpage_readpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840512,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1498
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581990192,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:487",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_get_next_extent",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581990192,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1486
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139728,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:497",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_set_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139728,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1486
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582328704,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:498",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582328704,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1493
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582427296,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:498",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582427296,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1511
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582596528,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:502",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596528,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1552
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697280,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697280,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009312,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:490",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009312,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1412
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583084784,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:501",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:ext4_iomap_alloc",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_replay_del_range",
        "fs/ext4/fast_commit.c:ext4_fc_replay_add_range",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583084784,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1416
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583109792,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:502",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109792,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1424
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:501",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:skip_hole",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592258407,
      "name": "ext4_map_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071583449328,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1489
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:500",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:skip_hole",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594039658,
      "name": "ext4_map_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583970880,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1646
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:506",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:skip_hole",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596072660,
      "name": "ext4_map_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584598848,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1646
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:478",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:skip_hole",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/super.c:ext4_journal_bmap",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596596163,
      "name": "ext4_map_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584825152,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1555
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:478",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_ext_clear_bb",
        "fs/ext4/extents.c:ext4_ext_replay_set_iblocks",
        "fs/ext4/extents.c:skip_hole",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/file.c:ext4_dio_write_checks",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin_report",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_one_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/namei.c:ext4_append",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/super.c:ext4_journal_bmap",
        "fs/ext4/xattr.c:ext4_xattr_inode_write",
        "fs/ext4/fast_commit.c:ext4_fc_set_bitmaps_and_counters",
        "fs/ext4/fast_commit.c:ext4_fc_write_inode_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597501682,
      "name": "ext4_map_blocks.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071585058112,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1579
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494354184,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494354184,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1384
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227787248,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227787248,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1596
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288083280,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_writepages",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288083280,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2012
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273783902,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273783902,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1284
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582666016,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666016,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603184,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603184,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582655872,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582655872,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
int ext4_map_blocks(handle_t * handle, struct inode * inode, struct ext4_map_blocks * map, int flags)
```

```json
{
  "name": "ext4_map_blocks",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582739552,
      "name": "ext4_map_blocks",
      "external": true,
      "loc": "fs/ext4/inode.c:511",
      "file": "fs/ext4/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/block_validity.c:ext4_setup_system_zone",
        "fs/ext4/dir.c:ext4_readdir",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_convert_unwritten_extents",
        "fs/ext4/extents.c:ext4_alloc_file_blocks",
        "fs/ext4/file.c:ext4_file_write_iter",
        "fs/ext4/inline.c:ext4_convert_inline_data_nolock",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:ext4_iomap_begin",
        "fs/ext4/inode.c:mpage_map_and_submit_extent",
        "fs/ext4/inode.c:ext4_getblk",
        "fs/ext4/inode.c:_ext4_get_block",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "fs/ext4/xattr.c:ext4_xattr_inode_lookup_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582739552,
      "name": "ext4_map_blocks",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1532
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
