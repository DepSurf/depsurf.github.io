# Function: <code>set_disk_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582817520,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1351",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582817520,
      "name": "set_disk_ro",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583096672,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1380",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583096672,
      "name": "set_disk_ro",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583208176,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1380",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583208176,
      "name": "set_disk_ro",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583266336,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1403",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583266336,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446016,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1487",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446016,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583657248,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1522",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583657248,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583763520,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1547",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583763520,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953008,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1568",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953008,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056480,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056480,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584451872,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1790",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584451872,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584572160,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1640",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572160,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584604560,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1353",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584604560,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020048,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1400",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020048,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585737456,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1466",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585737456,
      "name": "set_disk_ro",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586516848,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1476",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516848,
      "name": "set_disk_ro",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764096,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1439",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764096,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void set_disk_ro(struct gendisk * disk, bool read_only)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587036576,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1452",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_check_and_set_ro",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/scsi/sd.c:sd_read_write_protect_flag",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:do_resume",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587036576,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495896552,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:force_ro_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495896552,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229243400,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:force_ro_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229243400,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290102016,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290102016,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275013390,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req",
        "drivers/mmc/core/block.c:force_ro_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275013390,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025216,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025216,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583961024,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961024,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008976,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008976,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void set_disk_ro(struct gendisk * disk, int flag)
```

```json
{
  "name": "set_disk_ro",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584111472,
      "name": "set_disk_ro",
      "external": true,
      "loc": "block/genhd.c:1577",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/nvdimm/bus.c:nvdimm_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:do_md_stop",
        "drivers/md/md.c:md_set_readonly",
        "drivers/md/md.c:restart_array",
        "drivers/md/md.c:md_run",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/md.c:array_state_store",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dev_suspend",
        "drivers/md/dm-ioctl.c:dm_early_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584111472,
      "name": "set_disk_ro",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool read_only</code>
</li>
<li>
<b>Param removed. </b>
<code>int flag</code>
</li>
</ul>
</details>
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
