# Function: <code>blk_mq_stop_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790112,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:901",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/xen-blkfront.c:xlvbd_release_gendisk",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:dm_swap_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790112,
      "name": "blk_mq_stop_hw_queues",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067648,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:979",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/virtio_blk.c:virtblk_freeze",
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block",
        "drivers/md/dm-rq.c:dm_stop_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067648,
      "name": "blk_mq_stop_hw_queues",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583175381,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1038",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_quiesce_queue"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free",
        "drivers/scsi/scsi_lib.c:scsi_internal_device_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175296,
      "name": "blk_mq_stop_hw_queues",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235008,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1244",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235008,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583413504,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1379",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583413504,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621488,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1438",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621488,
      "name": "blk_mq_stop_hw_queues",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726096,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1562",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726096,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583914624,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1560",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914624,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017840,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017840,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584412576,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1642",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412576,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527184,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1733",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527184,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558976,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1752",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558976,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970448,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1763",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970448,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585678224,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2277",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585678224,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586455120,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2420",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455120,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698992,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2382",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698992,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970240,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:2401",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_remove",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:talk_to_blkback",
        "drivers/block/xen-blkfront.c:setup_blkring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970240,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495848624,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495848624,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229196924,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229196924,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290043520,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290043520,
      "name": "blk_mq_stop_hw_queues",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274977718,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274977718,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986576,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_freeze",
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986576,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922432,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922432,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970336,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970336,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_stop_hw_queues(struct request_queue * q)
```

```json
{
  "name": "blk_mq_stop_hw_queues",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072464,
      "name": "blk_mq_stop_hw_queues",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072464,
      "name": "blk_mq_stop_hw_queues",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
