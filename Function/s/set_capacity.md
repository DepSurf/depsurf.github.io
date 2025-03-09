# Function: <code>set_capacity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582824692,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833481,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584363431,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584535044,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/brd.c:brd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584538667,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:figure_loop_size",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:lo_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584555305,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/block/virtio_blk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/virtio_blk.c:virtblk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584560965,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866849,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584873953,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_done",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585724730,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:array_size_store",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585809349,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:462",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583103924,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113081,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/block/brd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584897352,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584907377,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/block/virtio_blk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584930480,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585229702,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585236352,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586160112,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586202997,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:451",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583215428,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583224787,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585087423,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585112975,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585424926,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585436160,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586362981,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_size_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407507,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:442",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583273307,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278787,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584976225,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585170618,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585195903,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585509711,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585520424,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586421406,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586510893,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583453495,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583459043,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585397499,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585599605,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585624063,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585941536,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585952008,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586890310,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586978358,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:428",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583664770,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583670013,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585641117,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585842681,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585870716,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586188618,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586204192,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587204419,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587275080,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:436",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583771602,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583777293,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585770517,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585980937,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586006494,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586331503,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344599,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587384737,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587455304,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:459",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583961236,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583966962,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586001894,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586213981,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586250265,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586574403,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588062,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587656213,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587728756,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584064708,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584070322,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586149063,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586362029,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586398467,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721580,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586735502,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587860389,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587933108,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582384618,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_disk_changed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584461912,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586906367,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131958,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587166765,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587537220,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588709085,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588770424,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:335",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__bind"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584577258,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:45",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567504,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584609370,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:43",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "fs/block_dev.c:bdev_disk_changed",
        "drivers/lightnvm/core.c:nvm_create_tgt",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584606080,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585023205,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:55",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021888,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585737822,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:58",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:invalidate_disk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585731488,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519470,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:58",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:invalidate_disk",
        "block/genhd.c:del_gendisk",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512864,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586761760,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:invalidate_disk",
        "block/genhd.c:blk_mark_disk_dead",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "block/partitions/core.c:bdev_disk_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759408,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void set_capacity(struct gendisk * disk, sector_t sectors)
```

```json
{
  "name": "set_capacity",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587034192,
      "name": "set_capacity",
      "external": true,
      "loc": "block/genhd.c:59",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:invalidate_disk",
        "block/genhd.c:__blk_mark_disk_dead",
        "block/genhd.c:set_capacity_and_notify"
      ],
      "caller_func": [
        "block/partitions/core.c:bdev_disk_changed",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sr.c:get_sectorsize",
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_done",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031696,
      "name": "set_capacity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495906956,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495913884,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498942376,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499214084,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499240584,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499632912,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499645668,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501087912,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501169372,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501426696,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229249760,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 3229256440,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 3231513744,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 3231737408,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 3232087296,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 3232101060,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 3232333948,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/mtd/mtd_blkdevs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev"
      ],
      "caller_func": []
    },
    {
      "addr": 3233588360,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 3233678792,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
      ],
      "caller_func": []
    },
    {
      "addr": 3233915292,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290115344,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290123732,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292079984,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292412440,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292952352,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292969844,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294561468,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294680788,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275021926,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275027466,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276326734,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276495558,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276815434,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276830086,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277811374,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277876310,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278034566,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/mmc/core/block.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584033444,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584039058,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585909431,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586123917,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586161047,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586412060,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425982,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586468769,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587491365,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587564084,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583969236,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583974818,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585968535,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099584,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/nvdimm/pmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/pmem.c:pmem_attach_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586113456,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/nvdimm/btt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586115590,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/nvdimm/blk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/blk.c:nd_blk_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288316,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586302238,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345009,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_update_disk_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587259525,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332164,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584017204,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584022818,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586099079,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586309997,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586346435,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586676140,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586690062,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587816533,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587889252,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_capacity",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584119774,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:del_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125362,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "block/partition-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/partition-generic.c:invalidate_partitions"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207687,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/lightnvm/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/lightnvm/core.c:nvm_create_tgt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586421668,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/loop.c:figure_loop_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586458128,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586782156,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sd.c:sd_revalidate_disk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586795388,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/scsi/sr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sr.c:sr_probe",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/scsi/sr.c:sr_done"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587919466,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588004566,
      "name": "set_capacity",
      "external": false,
      "loc": "include/linux/genhd.h:466",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_swap_table"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void set_capacity(struct gendisk * disk, sector_t sectors)
```
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
