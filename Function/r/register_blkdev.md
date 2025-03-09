# Function: <code>register_blkdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582816928,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:286",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/virtio_blk.c:init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582816928,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096080,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:287",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/brd.c:brd_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/virtio_blk.c:init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096080,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583207584,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:287",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583207584,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583265760,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:288",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583265760,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583445408,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:325",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445408,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:340",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583665691,
      "name": "register_blkdev.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583656672,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:353",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583772507,
      "name": "register_blkdev.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583762944,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583962179,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583952416,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584065683,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584055904,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:440",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584462944,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584452112,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495895768,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495895768,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229238908,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/mtd/mtd_blkdevs.c:register_mtd_blktrans",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229238908,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290100624,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290100624,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275012740,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init",
        "drivers/mmc/core/block.c:mmc_blk_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275012740,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034419,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584024640,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970183,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071583960448,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018179,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584008400,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int register_blkdev(unsigned int major, const char * name)
```

```json
{
  "name": "register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "register_blkdev",
      "external": true,
      "loc": "block/genhd.c:354",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/xen-blkfront.c:xlblk_init",
        "drivers/scsi/sd.c:init_sd",
        "drivers/scsi/sr.c:init_sr",
        "drivers/md/md.c:md_init",
        "drivers/md/md.c:md_init",
        "drivers/md/dm.c:local_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120725,
      "name": "register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584110896,
      "name": "register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
int register_blkdev(unsigned int major, const char * name)
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
