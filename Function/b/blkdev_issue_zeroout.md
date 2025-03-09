# Function: <code>blkdev_issue_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788144,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:285",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/extents.c:ext4_ext_zeroout",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788144,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065744,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:252",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065744,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, bool discard)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173552,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:354",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173552,
      "name": "blkdev_issue_zeroout",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583230832,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:359",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583230832,
      "name": "blkdev_issue_zeroout",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407616,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:365",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407616,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583618400,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:393",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618400,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583722992,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "fs/ext4/resize.c:ext4_flex_group_add",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722992,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583911184,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583911184,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014336,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014336,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405888,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405888,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520960,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:392",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520960,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584553552,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:392",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584553552,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964960,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:393",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964960,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585669472,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:254",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585669472,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586445280,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:252",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586445280,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 530
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586692384,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:252",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586692384,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586963728,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:252",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/inode.c:ext4_issue_zeroout",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "block/fops.c:blkdev_fallocate",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586963728,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495844328,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495844328,
      "name": "blkdev_issue_zeroout",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229192468,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229192468,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290037664,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290037664,
      "name": "blkdev_issue_zeroout",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274974370,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274974370,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583983072,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583983072,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918928,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918928,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966832,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966832,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
int blkdev_issue_zeroout(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, unsigned int flags)
```

```json
{
  "name": "blkdev_issue_zeroout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584068848,
      "name": "blkdev_issue_zeroout",
      "external": true,
      "loc": "block/blk-lib.c:358",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_fallocate",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/dax.c:__dax_zero_page_range",
        "fs/ext4/ialloc.c:ext4_init_inode_table",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "fs/ext4/resize.c:setup_new_flex_group_blocks",
        "block/ioctl.c:blkdev_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584068848,
      "name": "blkdev_issue_zeroout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool discard</code>
</li>
</ul>
</details>
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
