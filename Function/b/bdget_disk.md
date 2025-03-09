# Function: <code>bdget_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582818416,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:722",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:blkdev_get",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582818416,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583097568,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:748",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583097568,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583209072,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:748",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583209072,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583267248,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:760",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583267248,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446976,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:825",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446976,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583658448,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:873",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583658448,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583764720,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:895",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:dm_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583764720,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953680,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:917",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953680,
      "name": "bdget_disk",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584057152,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584057152,
      "name": "bdget_disk",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457088,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:1030",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:register_disk",
        "block/partitions/core.c:bdev_del_partition",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_closing",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457088,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584576433,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt"
      ],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575776,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584608676,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:708",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt"
      ],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608464,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495897408,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495897408,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229240840,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229240840,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290103696,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290103696,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275014402,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275014402,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025888,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025888,
      "name": "bdget_disk",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961696,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961696,
      "name": "bdget_disk",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009648,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009648,
      "name": "bdget_disk",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct block_device * bdget_disk(struct gendisk * disk, int partno)
```

```json
{
  "name": "bdget_disk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112160,
      "name": "bdget_disk",
      "external": true,
      "loc": "block/genhd.c:926",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:revalidate_disk",
        "fs/block_dev.c:bd_start_claiming",
        "block/genhd.c:invalidate_partition",
        "block/genhd.c:__device_add_disk",
        "drivers/block/xen-blkfront.c:blkif_release",
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm.c:alloc_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112160,
      "name": "bdget_disk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
struct block_device * bdget_disk(struct gendisk * disk, int partno)
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
