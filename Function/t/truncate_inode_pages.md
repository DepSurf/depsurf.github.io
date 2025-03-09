# Function: <code>truncate_inode_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580546272,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:388",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/indirect.c:ext4_ind_direct_IO",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546272,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580635846,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:399",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635664,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580702934,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:428",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702752,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580736486,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:427",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736304,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580823446,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:480",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823264,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580960246,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:476",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960064,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036470,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:473",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_try_to_write_inline_data",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/ioctl.c:ext4_ioctl",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036288,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581100311,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581100128,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581157255,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581157072,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343047,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:set_blocksize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342864,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581384775,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:set_blocksize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384592,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581404983,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:422",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:set_blocksize",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_orphan_cleanup",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404816,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581654791,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:423",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581654608,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582026486,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:450",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026288,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582460166,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:446",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459936,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582665318,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:447",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/file.c:ext4_handle_inode_extension",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665104,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582836166,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:437",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_convert_inline_data_to_extent",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_write_inline_data_end",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/orphan.c:ext4_process_orphan",
        "fs/ext4/verity.c:ext4_end_enable_verity",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "block/bdev.c:blkdev_flush_mapping",
        "block/bdev.c:set_blocksize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835952,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492535220,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492534840,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226400284,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226400004,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285830928,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285830592,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272585906,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272585644,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581126103,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125920,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581073063,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072896,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581117303,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581117120,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void truncate_inode_pages(struct address_space * mapping, loff_t lstart)
```

```json
{
  "name": "truncate_inode_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581179767,
      "name": "truncate_inode_pages",
      "external": true,
      "loc": "mm/truncate.c:474",
      "file": "mm/truncate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/truncate.c:truncate_pagecache",
        "mm/truncate.c:truncate_inode_pages_final"
      ],
      "caller_func": [
        "fs/block_dev.c:kill_bdev",
        "fs/quota/dquot.c:dquot_disable",
        "fs/ext4/inline.c:ext4_da_write_inline_data_begin",
        "fs/ext4/inline.c:ext4_convert_inline_data_to_extent",
        "fs/ext4/inode.c:ext4_direct_IO_write",
        "fs/ext4/inode.c:ext4_iomap_end",
        "fs/ext4/inode.c:ext4_da_write_begin",
        "fs/ext4/inode.c:ext4_journalled_write_end",
        "fs/ext4/inode.c:ext4_write_end",
        "fs/ext4/inode.c:ext4_write_begin",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/ioctl.c:swap_inode_boot_loader",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/fuse/readdir.c:fuse_readdir_uncached"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179600,
      "name": "truncate_inode_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
