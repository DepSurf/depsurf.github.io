# Function: <code>blk_execute_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582775840,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:99",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_io",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/bsg.c:bsg_ioctl",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582775840,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
int blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583054176,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:99",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583054176,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
int blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160000,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:99",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160000,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583217328,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:94",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583217328,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583393984,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:94",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583393984,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583603968,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:94",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583603968,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583709792,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:76",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583709792,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583898768,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898768,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002080,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002080,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584394592,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:79",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584394592,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584508704,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:79",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508704,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584542816,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:76",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584542816,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
blk_status_t blk_execute_rq(struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584954080,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:90",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954080,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
blk_status_t blk_execute_rq(struct request * rq, bool at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679680,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-mq.c:1258",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679680,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
blk_status_t blk_execute_rq(struct request * rq, bool at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586458832,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-mq.c:1386",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586458832,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
blk_status_t blk_execute_rq(struct request * rq, bool at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586710720,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-mq.c:1392",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586710720,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
blk_status_t blk_execute_rq(struct request * rq, bool at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586982544,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-mq.c:1395",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/block/virtio_blk.c:virtblk_report_zones",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:scsi_execute_cmd",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586982544,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495831688,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/mmc/core/block.c:mmc_ext_csd_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_get",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495831688,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229179620,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/mmc/core/block.c:mmc_ext_csd_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_get",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229179620,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290021936,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290021936,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274964362,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/mmc/core/block.c:mmc_ext_csd_open",
        "drivers/mmc/core/block.c:mmc_dbg_card_status_get",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274964362,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970816,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970816,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583907712,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/nvme/host/core.c:nvme_submit_user_cmd",
        "drivers/nvme/host/core.c:__nvme_submit_sync_cmd",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583907712,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954576,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583954576,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_execute_rq(struct request_queue * q, struct gendisk * bd_disk, struct request * rq, int at_head)
```

```json
{
  "name": "blk_execute_rq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584056576,
      "name": "blk_execute_rq",
      "external": true,
      "loc": "block/blk-exec.c:77",
      "file": "block/blk-exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056576,
      "name": "blk_execute_rq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, bd_disk, rq, at_head</code> ➡️ <code>bd_disk, rq, at_head</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk * bd_disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>bd_disk, rq, at_head</code> ➡️ <code>rq, at_head</code>
</li>
<li>
<b>Param type changed. </b>
<code>int at_head</code> ➡️ <code>bool at_head</code>
</li>
</ul>
</details>
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
