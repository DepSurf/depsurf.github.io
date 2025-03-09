# Function: <code>blk_queue_logical_block_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582769296,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:352",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582769296,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583047664,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:352",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583047664,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583153312,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:370",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583153312,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583210592,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:381",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583210592,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583387168,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:382",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/lightnvm/core.c:nvm_register",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583387168,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597200,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:382",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597200,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703728,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:326",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_revalidate_disk",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703728,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, short unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892368,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:330",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892368,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583995632,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583995632,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384384,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:324",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384384,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498400,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:328",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498400,
      "name": "blk_queue_logical_block_size",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533088,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:301",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533088,
      "name": "blk_queue_logical_block_size",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584944000,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:304",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584944000,
      "name": "blk_queue_logical_block_size",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646688,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:303",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646688,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418928,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:303",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418928,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666432,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:309",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666432,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937456,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:306",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_simple_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_configure",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:get_sectorsize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937456,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495822920,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495822920,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229172424,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229172424,
      "name": "blk_queue_logical_block_size",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290012000,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290012000,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274957774,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274957774,
      "name": "blk_queue_logical_block_size",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964368,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964368,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901280,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/nvdimm/pmem.c:pmem_attach_disk",
        "drivers/nvdimm/blk.c:nd_blk_probe",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk",
        "drivers/nvme/host/core.c:nvme_alloc_ns",
        "drivers/nvme/host/core.c:nvme_update_disk_info",
        "drivers/nvme/host/multipath.c:nvme_mpath_alloc_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901280,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948128,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948128,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void blk_queue_logical_block_size(struct request_queue * q, unsigned int size)
```

```json
{
  "name": "blk_queue_logical_block_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050112,
      "name": "blk_queue_logical_block_size",
      "external": true,
      "loc": "block/blk-settings.c:331",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_ioctl",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/sd.c:sd_read_capacity",
        "drivers/scsi/sr.c:sr_block_revalidate_disk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050112,
      "name": "blk_queue_logical_block_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>short unsigned int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
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
