# Function: <code>blk_queue_bounce_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582769895,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:190",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_make_request"
      ],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/md/dm.c:dm_setup_md_queue",
        "drivers/md/dm.c:dm_setup_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582770144,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583048295,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:190",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_make_request"
      ],
      "caller_func": [
        "drivers/block/brd.c:brd_alloc",
        "drivers/block/virtio_blk.c:virtblk_probe",
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/md/dm.c:dm_init_normal_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048544,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583153863,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:194",
      "file": "block/blk-settings.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-settings.c:blk_queue_make_request"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_set_queue_limits",
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/md/dm.c:dm_init_normal_md_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583154128,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583211376,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:189",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583211376,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388080,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:190",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388080,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597984,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:190",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597984,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704256,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:134",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704256,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892880,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:135",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583892880,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996176,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996176,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584384864,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:102",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584384864,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498992,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:102",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498992,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532896,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:97",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532896,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584943808,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:98",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584943808,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585646480,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:97",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585646480,
      "name": "blk_queue_bounce_limit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586418624,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:97",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586418624,
      "name": "blk_queue_bounce_limit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666144,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:98",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666144,
      "name": "blk_queue_bounce_limit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void blk_queue_bounce_limit(struct request_queue * q, enum blk_bounce bounce)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586937168,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:98",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586937168,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495822616,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495822616,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229172952,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229172952,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290011824,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290011824,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274957496,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue",
        "drivers/mmc/core/queue.c:mmc_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274957496,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583964912,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964912,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583901824,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583901824,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583948672,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583948672,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void blk_queue_bounce_limit(struct request_queue * q, u64 max_addr)
```

```json
{
  "name": "blk_queue_bounce_limit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584050656,
      "name": "blk_queue_bounce_limit",
      "external": true,
      "loc": "block/blk-settings.c:136",
      "file": "block/blk-settings.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_init_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584050656,
      "name": "blk_queue_bounce_limit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<code>enum blk_bounce bounce</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 max_addr</code>
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
