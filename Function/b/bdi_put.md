# Function: <code>bdi_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580816384,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:956",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816384,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580907753,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:971",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907616,
      "name": "bdi_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581042569,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:969",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_exit_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042848,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581121161,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:972",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-core.c:blk_exit_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581121008,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581185789,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:959",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185632,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581244441,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581244288,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581433485,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1030",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:__blk_alloc_queue",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581433312,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581476013,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:899",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475856,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581496765,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:898",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue",
        "block/blk-sysfs.c:blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581496608,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755142,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:981",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/bdev.c:bdev_free_inode",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755728,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582136714,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:971",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/squashfs/super.c:squashfs_fill_super",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/bdev.c:bdev_free_inode",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137264,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582614007,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1094",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/bdev.c:bdev_free_inode",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614576,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582822775,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1107",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/bdev.c:bdev_free_inode",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823344,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582996866,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1103",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/bdev.c:bdev_free_inode",
        "block/genhd.c:__alloc_disk_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582996048,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492642024,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492642024,
      "name": "bdi_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226484116,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue",
        "drivers/mtd/mtdcore.c:cleanup_mtd",
        "drivers/mtd/mtdcore.c:init_mtd",
        "drivers/mtd/mtdcore.c:init_mtd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226484116,
      "name": "bdi_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285958688,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init",
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285958688,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272658838,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272657852,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581213289,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213136,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581159993,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159840,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581204489,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204336,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void bdi_put(struct backing_dev_info * bdi)
```

```json
{
  "name": "bdi_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581267817,
      "name": "bdi_put",
      "external": true,
      "loc": "mm/backing-dev.c:1040",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_exit",
        "mm/backing-dev.c:wb_init"
      ],
      "caller_func": [
        "fs/super.c:super_setup_bdi_name",
        "fs/super.c:generic_shutdown_super",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/block_dev.c:bdev_evict_inode",
        "fs/fuse/inode.c:fuse_fill_super_common",
        "block/blk-core.c:blk_alloc_queue_node",
        "block/blk-sysfs.c:__blk_release_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267664,
      "name": "bdi_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void bdi_put(struct backing_dev_info * bdi)
```
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
