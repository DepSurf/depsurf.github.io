# Function: <code>blk_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582738288,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1498",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_make_request",
        "block/scsi_ioctl.c:sg_io",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582738288,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583020496,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1458",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583020496,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583125696,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1463",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125696,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184416,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1566",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184416,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583363088,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1686",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583363088,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583570896,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:1783",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "block/bsg.c:blk_complete_sgv4_hdr_rq",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570896,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682496,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:591",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682496,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871312,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:589",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871312,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974208,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974208,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361072,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:635",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361072,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478160,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:644",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478160,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584513088,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:645",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584513088,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924272,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:643",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924272,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495793528,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
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
      "addr": 18446603336495793528,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229149204,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
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
      "addr": 3229149204,
      "name": "blk_put_request",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289980976,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289980976,
      "name": "blk_put_request",
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274938470,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
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
      "addr": 18446743936274938470,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942944,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942944,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879888,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879888,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926704,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926704,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_put_request(struct request * req)
```

```json
{
  "name": "blk_put_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028096,
      "name": "blk_put_request",
      "external": true,
      "loc": "block/blk-core.c:593",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg.c:bsg_sg_io",
        "block/bsg-lib.c:bsg_transport_free_rq",
        "drivers/scsi/scsi_error.c:eh_lock_door_done",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_finish_rem_req",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028096,
      "name": "blk_put_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void blk_put_request(struct request * req)
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
