# Function: <code>disk_get_part</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582816592,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:61",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:bdget_disk",
        "block/genhd.c:blk_lookup_devt"
      ],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816592,
      "name": "disk_get_part",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583098060,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:62",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583095744,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583209564,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:62",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "init/do_mounts.c:name_to_dev_t",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207248,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583267756,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:62",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265424,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583447484,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:108",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445072,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583658944,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:120",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583656336,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583765216,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:133",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583762608,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952080,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952080,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055568,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055568,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584461179,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:171",
      "file": "block/genhd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ],
      "caller_func": [
        "init/do_mounts.c:devt_from_partuuid",
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584458752,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495895376,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495895376,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229238764,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229238764,
      "name": "disk_get_part",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290100064,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290100064,
      "name": "disk_get_part",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275012400,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275012400,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024304,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024304,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583960112,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583960112,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008064,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008064,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
```

```json
{
  "name": "disk_get_part",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110528,
      "name": "disk_get_part",
      "external": true,
      "loc": "block/genhd.c:134",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/block_dev.c:__blkdev_get",
        "fs/block_dev.c:__blkdev_get",
        "block/ioctl.c:blkpg_ioctl",
        "block/ioctl.c:blkpg_ioctl",
        "block/genhd.c:blk_lookup_devt",
        "block/genhd.c:bdget_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110528,
      "name": "disk_get_part",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct hd_struct * disk_get_part(struct gendisk * disk, int partno)
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
