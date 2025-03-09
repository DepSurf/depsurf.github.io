# Function: <code>set_capacity_and_notify</code>

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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:60",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372935,
      "name": "set_capacity_and_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584573648,
      "name": "set_capacity_and_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:57",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315533,
      "name": "set_capacity_and_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071584606160,
      "name": "set_capacity_and_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592315121,
      "name": "set_capacity_and_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071585022208,
      "name": "set_capacity_and_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:73",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:array_size_store",
        "drivers/md/dm.c:__bind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594099605,
      "name": "set_capacity_and_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071585737888,
      "name": "set_capacity_and_notify",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586519552,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:73",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:blk_mark_disk_dead",
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:array_size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586519552,
      "name": "set_capacity_and_notify",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586759456,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_config_changed_work",
        "drivers/block/virtio_blk.c:virtblk_update_capacity",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:array_size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586759456,
      "name": "set_capacity_and_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
```

```json
{
  "name": "set_capacity_and_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587031744,
      "name": "set_capacity_and_notify",
      "external": true,
      "loc": "block/genhd.c:69",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:loop_set_status",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_update_capacity",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/md.c:md_do_sync",
        "drivers/md/md.c:update_size",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:do_md_run",
        "drivers/md/md.c:array_size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031744,
      "name": "set_capacity_and_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
bool set_capacity_and_notify(struct gendisk * disk, sector_t size)
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
