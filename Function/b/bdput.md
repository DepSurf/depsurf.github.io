# Function: <code>bdput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581236432,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:685",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_open"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:SyS_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236432,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581405618,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:763",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:SyS_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581402400,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581485855,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:1015",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:SyS_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482224,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581540011,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:931",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:SyS_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534832,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581682731,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:921",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:SyS_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_pr_clear",
        "drivers/md/dm.c:dm_pr_preempt",
        "drivers/md/dm.c:dm_pr_release",
        "drivers/md/dm.c:dm_pr_reserve",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm.c:dm_blk_ioctl",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581677392,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581846957,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:922",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840912,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581934093,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:961",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928288,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582071805,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_open",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582065872,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582149389,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143520,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582385972,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:939",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_acquire"
      ],
      "caller_func": [
        "kernel/power/user.c:snapshot_set_swap_area",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/genhd.c:invalidate_partition",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_closing",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582379872,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582441411,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:957",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get_no_open",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "block/genhd.c:set_disk_ro",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:disk_release",
        "block/genhd.c:printk_all_partitions",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:register_disk",
        "block/genhd.c:disk_part_iter_next",
        "block/genhd.c:disk_part_iter_next",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_closing"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434368,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582468483,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:963",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:blkdev_put",
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get_no_open",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get"
      ],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "block/genhd.c:__alloc_disk_node",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:disk_release",
        "block/partitions/core.c:blk_drop_partitions",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "block/partitions/core.c:part_release",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461296,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493701464,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493693536,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227225036,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/mtd/mtdsuper.c:get_tree_mtd",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227221284,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287297992,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287294560,
      "name": "bdput",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273317562,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273311722,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582118125,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112256,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055565,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582049696,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582108605,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102736,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void bdput(struct block_device * bdev)
```

```json
{
  "name": "bdput",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178753,
      "name": "bdput",
      "external": true,
      "loc": "fs/block_dev.c:958",
      "file": "fs/block_dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "fs/block_dev.c:bd_forget"
      ],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_show",
        "mm/swapfile.c:swap_type_of",
        "mm/swapfile.c:swap_type_of",
        "fs/quota/quota.c:kernel_quotactl",
        "fs/quota/quota.c:kernel_quotactl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:invalidate_partition",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/md/dm-table.c:dm_get_dev_t"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582175600,
      "name": "bdput",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void bdput(struct block_device * bdev)
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
