# Function: <code>blk_get_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, int rw, gfp_t gfp_mask)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582750000,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1292",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_make_request",
        "block/scsi_ioctl.c:sg_io",
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750000,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct request * blk_get_request(struct request_queue * q, int rw, gfp_t gfp_mask)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583028128,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1311",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "drivers/block/virtio_blk.c:virtblk_serial_show",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583028128,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
struct request * blk_get_request(struct request_queue * q, int rw, gfp_t gfp_mask)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583132928,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1312",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132928,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, gfp_t gfp_mask)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583187968,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1415",
      "file": "block/blk-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187968,
      "name": "blk_get_request",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, gfp_t gfp_mask)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367280,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1533",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367280,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576240,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:1615",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576240,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682400,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:575",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_ioctl",
        "block/bsg.c:bsg_ioctl",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682400,
      "name": "blk_get_request",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871216,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:573",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871216,
      "name": "blk_get_request",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974112,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974112,
      "name": "blk_get_request",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360976,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:619",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_eh_lock_door",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360976,
      "name": "blk_get_request",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584478064,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:628",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_eh_lock_door",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584478064,
      "name": "blk_get_request",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584512992,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:629",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/sg.c:sg_start_req",
        "drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512992,
      "name": "blk_get_request",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584924176,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:627",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn",
        "drivers/scsi/sr.c:sr_read_cdda_bpc",
        "drivers/scsi/sg.c:sg_start_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584924176,
      "name": "blk_get_request",
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495793384,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
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
      "addr": 18446603336495793384,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229148996,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
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
      "addr": 3229148996,
      "name": "blk_get_request",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289980768,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289980768,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274938366,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
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
      "addr": 18446743936274938366,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583942848,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583942848,
      "name": "blk_get_request",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583879792,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583879792,
      "name": "blk_get_request",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926608,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926608,
      "name": "blk_get_request",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
```

```json
{
  "name": "blk_get_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028000,
      "name": "blk_get_request",
      "external": true,
      "loc": "block/blk-core.c:577",
      "file": "block/blk-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/scsi_ioctl.c:sg_scsi_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_sg_io",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_lib.c:__scsi_execute",
        "drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028000,
      "name": "blk_get_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_mq_req_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
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
struct request * blk_get_request(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags)
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
