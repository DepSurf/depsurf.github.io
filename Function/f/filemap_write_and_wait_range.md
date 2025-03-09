# Function: <code>filemap_write_and_wait_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580478000,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:479",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:generic_file_read_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:__generic_file_write_iter",
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/dax.c:dax_do_io",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_fallocate",
        "fs/fuse/file.c:fuse_fsync_common",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580478000,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580558816,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:559",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_fsync_common",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558816,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580623904,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:524",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/libfs.c:__generic_file_fsync",
        "fs/block_dev.c:blkdev_fsync",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/fsync.c:ext4_sync_file",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_fsync_common",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623904,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651664,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:555",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter",
        "fs/fuse/file.c:fuse_fsync_common",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651664,
      "name": "filemap_write_and_wait_range",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735904,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:650",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735904,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873936,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:650",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/read_write.c:vfs_clone_file_prep_inodes",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873936,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945616,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:627",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945616,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581042928,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:666",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042928,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581098368,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098368,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581274656,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:648",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/ioctl.c:fiemap_prep",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274656,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581321392,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:649",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581321392,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341328,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:680",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_cache_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341328,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581571472,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:698",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_vma_close",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571472,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581947552,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:667",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:sync_blockdev_range",
        "block/bdev.c:set_blocksize",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581947552,
      "name": "filemap_write_and_wait_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582387215,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:665",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter"
      ],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/direct-io.c:__iomap_dio_rw",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_cache_write_iter",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:sync_blockdev_range",
        "block/bdev.c:set_blocksize",
        "block/fops.c:blkdev_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381360,
      "name": "filemap_write_and_wait_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071582382144,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582589655,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:672",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/filemap.c:kiocb_write_and_wait"
      ],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/filemap.c:kiocb_write_and_wait",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/libfs.c:direct_write_fallback",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:sync_blockdev_range",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582416,
      "name": "filemap_write_and_wait_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071582582816,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582753639,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:667",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/filemap.c:kiocb_write_and_wait"
      ],
      "caller_func": [
        "mm/filemap.c:kiocb_invalidate_pages",
        "mm/filemap.c:kiocb_write_and_wait",
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:fiemap_prep",
        "fs/libfs.c:direct_write_fallback",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/remap_range.c:__generic_remap_file_range_prep",
        "fs/direct-io.c:__blockdev_direct_IO",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_zero_range",
        "fs/ext4/file.c:ext4_dio_write_iter",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:__fuse_copy_file_range",
        "fs/fuse/file.c:fuse_file_fallocate",
        "fs/fuse/file.c:fuse_direct_io",
        "block/bdev.c:bdev_mark_dead",
        "block/bdev.c:bdev_release",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:bdev_freeze",
        "block/bdev.c:sync_blockdev_range",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582752976,
      "name": "filemap_write_and_wait_range.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071582753952,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492463144,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492463144,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226338840,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226338840,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285743488,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285743488,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272534336,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272534336,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581067216,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581067216,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014416,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014416,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581058416,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058416,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int filemap_write_and_wait_range(struct address_space * mapping, loff_t lstart, loff_t lend)
```

```json
{
  "name": "filemap_write_and_wait_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581120000,
      "name": "filemap_write_and_wait_range",
      "external": true,
      "loc": "mm/filemap.c:675",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__generic_file_write_iter",
        "mm/filemap.c:generic_file_direct_write",
        "mm/filemap.c:generic_file_read_iter",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/read_write.c:generic_remap_file_range_prep",
        "fs/direct-io.c:do_blockdev_direct_IO",
        "fs/iomap/direct-io.c:iomap_dio_rw",
        "fs/ext4/extents.c:ext4_insert_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/extents.c:ext4_collapse_range",
        "fs/ext4/inode.c:ext4_punch_hole",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/fuse/file.c:fuse_file_write_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120000,
      "name": "filemap_write_and_wait_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
