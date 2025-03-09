# Function: <code>filemap_write_and_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580477824,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:444",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:set_blocksize",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:__blkdev_put",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477824,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580558608,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:523",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558608,
      "name": "filemap_write_and_wait",
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580623696,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:488",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580623696,
      "name": "filemap_write_and_wait",
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651472,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:516",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651472,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580735696,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:612",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580735696,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580873728,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:612",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/iomap.c:iomap_bmap",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873728,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945408,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:589",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/iomap.c:iomap_bmap",
        "fs/iomap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945408,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581042720,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:626",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042720,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581098144,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098144,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581726403,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582167631,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582386083,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607149,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582702933,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583039432,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044309,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285790,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429230,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583440574,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583521445,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2792",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_vma_close"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581774464,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214159,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440664,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582680141,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582774213,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115064,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583120277,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401238,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543054,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583554094,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583631141,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2654",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_vma_close"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581802006,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239564,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467710,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:bdev_disk_changed",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582708902,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582803205,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583140760,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583145497,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583424184,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583566158,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583577582,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583654229,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2890",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_vma_close"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582087148,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582558284,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035478,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583130295,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481271,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485961,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583773655,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583924718,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583935854,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584013333,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "fs/fuse/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/file.c:fuse_vma_close"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584892855,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/fs.h:2873",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582525905,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583087101,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583509490,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583619959,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584005714,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584008095,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584333759,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504030,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584515834,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585590759,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583024949,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583654861,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106825,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/verity/enable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/verity/enable.c:fsverity_ioctl_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584224087,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635819,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584638236,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982639,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585172318,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585185818,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586357434,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:58",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583234623,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583871693,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584453527,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858793,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584861276,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585211458,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585401281,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585414922,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586604120,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:blkdev_put",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:freeze_bdev",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583471053,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:__do_sys_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584078717,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ioctl.c:fiemap_prep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584676647,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/iomap/fiemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/fiemap.c:iomap_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091721,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585094202,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585444114,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ext4/verity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/verity.c:ext4_end_enable_verity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585636209,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ecryptfs/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/file.c:ecryptfs_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585649818,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "fs/ecryptfs/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586874348,
      "name": "filemap_write_and_wait",
      "external": false,
      "loc": "include/linux/pagemap.h:62",
      "file": "block/bdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bdev.c:bdev_mark_dead",
        "block/bdev.c:bdev_release",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:bdev_freeze",
        "block/bdev.c:set_blocksize"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492462824,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492462824,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226338560,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226338560,
      "name": "filemap_write_and_wait",
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285743168,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285743168,
      "name": "filemap_write_and_wait",
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272534014,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272534014,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066992,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066992,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581014192,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014192,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581058192,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058192,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int filemap_write_and_wait(struct address_space * mapping)
```

```json
{
  "name": "filemap_write_and_wait",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119776,
      "name": "filemap_write_and_wait",
      "external": true,
      "loc": "mm/filemap.c:635",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:freeze_bdev",
        "fs/block_dev.c:set_blocksize",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/iomap/fiemap.c:iomap_bmap",
        "fs/iomap/fiemap.c:iomap_fiemap",
        "fs/ext4/inode.c:ext4_change_inode_journal_flag",
        "fs/ext4/inode.c:ext4_bmap",
        "fs/ext4/inode.c:ext4_evict_inode",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl_setflags",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/ecryptfs/file.c:ecryptfs_flush",
        "fs/ecryptfs/main.c:ecryptfs_put_lower_file",
        "fs/fuse/file.c:fuse_vma_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119776,
      "name": "filemap_write_and_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int filemap_write_and_wait(struct address_space * mapping)
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
