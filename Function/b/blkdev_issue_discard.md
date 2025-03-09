# Function: <code>blkdev_issue_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787136,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:40",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787136,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583065536,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:112",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583065536,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583172400,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:117",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/ext4/mballoc.c:ext4_free_data_callback",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/blk-lib.c:blkdev_issue_zeroout",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583172400,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229632,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:112",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:SyS_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229632,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583406560,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:113",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:SYSC_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583406560,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617104,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:132",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617104,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583721296,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_fs",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583721296,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583909472,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583909472,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584012656,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012656,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584405152,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:discard_swap",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584405152,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584522112,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:swap_do_scheduled_discard",
        "mm/swapfile.c:discard_swap",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_extent",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522112,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554736,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:131",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554736,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584966144,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:132",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/ext4/mballoc.c:ext4_try_to_trim_range",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966144,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668352,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:99",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668352,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586444080,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586444080,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586691216,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586691216,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962560,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/jbd2/journal.c:__jbd2_journal_erase",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_trim_fs",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/fops.c:blkdev_fallocate",
        "block/ioctl.c:blkdev_common_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962560,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495842664,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495842664,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229190664,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229190664,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290035312,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290035312,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274972992,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274972992,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583981392,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583981392,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917248,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917248,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583965152,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965152,
      "name": "blkdev_issue_discard",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int blkdev_issue_discard(struct block_device * bdev, sector_t sector, sector_t nr_sects, gfp_t gfp_mask, long unsigned int flags)
```

```json
{
  "name": "blkdev_issue_discard",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584067216,
      "name": "blkdev_issue_discard",
      "external": true,
      "loc": "block/blk-lib.c:97",
      "file": "block/blk-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:__do_sys_swapon",
        "mm/swapfile.c:swap_do_scheduled_discard",
        "fs/block_dev.c:blkdev_fallocate",
        "fs/ext4/mballoc.c:ext4_trim_all_free",
        "fs/ext4/mballoc.c:ext4_free_blocks",
        "fs/fat/fatent.c:fat_trim_clusters",
        "fs/fat/fatent.c:fat_free_clusters",
        "block/ioctl.c:blk_ioctl_discard"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584067216,
      "name": "blkdev_issue_discard",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
