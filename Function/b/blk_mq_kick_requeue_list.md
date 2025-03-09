# Function: <code>blk_mq_kick_requeue_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790032,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:519",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_flush_queue_rq",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/md/dm.c:dm_requeue_original_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790032,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583067568,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:575",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_flush_queue_rq",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/scsi/scsi_lib.c:scsi_io_completion",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert",
        "drivers/md/dm-rq.c:dm_requeue_original_request",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583067568,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583175120,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:590",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583175120,
      "name": "blk_mq_kick_requeue_list",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583234704,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:677",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234704,
      "name": "blk_mq_kick_requeue_list",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583412272,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:732",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412272,
      "name": "blk_mq_kick_requeue_list",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583621120,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:747",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621120,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583725728,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:791",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725728,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914208,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:790",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914208,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017424,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017424,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584423292,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:802",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409296,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584538284,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:852",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525104,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584569740,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:826",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557712,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584980652,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:832",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968896,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585691898,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:1382",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672784,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586471018,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:1510",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448656,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586706032,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:1503",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_requeue_request"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695168,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586976144,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:1506",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_requeue_request"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/scsi/scsi_error.c:scsi_eh_flush_done_q",
        "drivers/scsi/scsi_lib.c:scsi_run_queue",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966368,
      "name": "blk_mq_kick_requeue_list",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495846440,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495846440,
      "name": "blk_mq_kick_requeue_list",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229195820,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229195820,
      "name": "blk_mq_kick_requeue_list",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290054440,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_add_to_requeue_list"
      ],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290042640,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274977190,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274977190,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583986160,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986160,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922016,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922016,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583969920,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969920,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_kick_requeue_list(struct request_queue * q)
```

```json
{
  "name": "blk_mq_kick_requeue_list",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584071968,
      "name": "blk_mq_kick_requeue_list",
      "external": true,
      "loc": "block/blk-mq.c:803",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-debugfs.c:queue_state_write",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/md/dm-rq.c:dm_start_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071968,
      "name": "blk_mq_kick_requeue_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
