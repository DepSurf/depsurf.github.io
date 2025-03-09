# Function: <code>blk_queue_write_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583050512,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:842",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/virtio_blk.c:virtblk_update_cache_mode",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050512,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583155904,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:879",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583155904,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213088,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:891",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213088,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390064,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:892",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390064,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583599616,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:890",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583599616,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583705888,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:832",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705888,
      "name": "blk_queue_write_cache",
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894480,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:820",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894480,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997776,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997776,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386560,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:782",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386560,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584501104,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:795",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501104,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584535488,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:792",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584535488,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584946272,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:792",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946272,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585648128,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:824",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585648128,
      "name": "blk_queue_write_cache",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586420864,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:825",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586420864,
      "name": "blk_queue_write_cache",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586668368,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:831",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586668368,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586939584,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:833",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/virtio_blk.c:cache_type_store",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:cache_type_store",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586939584,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495825544,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495825544,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229173640,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229173640,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290015344,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290015344,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274960192,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions",
        "drivers/mmc/core/block.c:mmc_blk_alloc_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274960192,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583966512,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/nvme/host/core.c:nvme_set_queue_limits",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966512,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583903424,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/nvme/host/core.c:nvme_set_queue_limits",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583903424,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583950272,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583950272,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```

```json
{
  "name": "blk_queue_write_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584052256,
      "name": "blk_queue_write_cache",
      "external": true,
      "loc": "block/blk-settings.c:821",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:xlvbd_flush",
        "drivers/scsi/sd.c:sd_set_flush_flag",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm-table.c:dm_table_set_restrictions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584052256,
      "name": "blk_queue_write_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void blk_queue_write_cache(struct request_queue * q, bool wc, bool fua)
```
</details>
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
