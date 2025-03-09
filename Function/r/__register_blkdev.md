# Function: <code>__register_blkdev</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:429",
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
      "addr": 18446744071591372833,
      "name": "__register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584568384,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:217",
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
      "addr": 18446744071591315431,
      "name": "__register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071584600512,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:232",
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
      "addr": 18446744071592315193,
      "name": "__register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071585022400,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 628
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:241",
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
      "addr": 18446744071594099496,
      "name": "__register_blkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071585732016,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586513136,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:218",
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
      "addr": 18446744071586513136,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586759696,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:214",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/virtio_blk.c:virtio_blk_init",
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
      "addr": 18446744071586759696,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
```

```json
{
  "name": "__register_blkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031984,
      "name": "__register_blkdev",
      "external": true,
      "loc": "block/genhd.c:214",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:genhd_device_init",
        "drivers/block/loop.c:loop_init",
        "drivers/block/virtio_blk.c:virtio_blk_init",
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
      "addr": 18446744071587031984,
      "name": "__register_blkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 625
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __register_blkdev(unsigned int major, const char * name, void (*)(dev_t) probe)
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
