# Function: <code>blk_mq_end_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_end_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582793664,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:318",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_abort_requeue_list",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_make_request",
        "drivers/block/virtio_blk.c:virtblk_request_done",
        "drivers/md/dm.c:dm_softirq_done",
        "drivers/md/dm.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582793664,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void blk_mq_end_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069920,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:374",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_abort_requeue_list",
        "drivers/block/virtio_blk.c:virtblk_request_done",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069920,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void blk_mq_end_request(struct request * rq, int error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583179424,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:371",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_abort_requeue_list",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/md/dm-rq.c:dm_softirq_done",
        "drivers/md/dm-rq.c:dm_softirq_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583179424,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583238528,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:472",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238528,
      "name": "blk_mq_end_request",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583416224,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:514",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583416224,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583627792,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:542",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583627792,
      "name": "blk_mq_end_request",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583732304,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:560",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732304,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583919936,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:555",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583919936,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584023232,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584023232,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584426585,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:569",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584414144,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584541452,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:562",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584530128,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584573164,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:563",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq",
        "drivers/md/dm-rq.c:dm_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584564608,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584985916,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:570",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975408,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585699018,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:942",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585690144,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586478745,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:1052",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467712,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713104,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:1048",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713104,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586984912,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:1058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_complete",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/virtio_blk.c:virtblk_poll",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984912,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495851248,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_job_put",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495851248,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229203932,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_job_put",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229203932,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290053248,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_job_put",
        "drivers/block/loop.c:lo_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290053248,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274982546,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_mq_issue_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq",
        "drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274982546,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583991968,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq",
        "drivers/nvme/host/core.c:nvme_complete_rq",
        "drivers/nvme/host/multipath.c:nvme_failover_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583991968,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927824,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/scsi/scsi_transport_fc.c:fc_bsg_job_timeout",
        "drivers/nvme/host/core.c:nvme_complete_rq",
        "drivers/nvme/host/multipath.c:nvme_failover_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927824,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583975728,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975728,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void blk_mq_end_request(struct request * rq, blk_status_t error)
```

```json
{
  "name": "blk_mq_end_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584079408,
      "name": "blk_mq_end_request",
      "external": true,
      "loc": "block/blk-mq.c:566",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-flush.c:blk_flush_complete_seq",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/bsg-lib.c:bsg_teardown_job",
        "drivers/block/loop.c:lo_complete_rq",
        "drivers/block/xen-blkfront.c:blkfront_resume",
        "drivers/block/xen-blkfront.c:blkif_complete_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079408,
      "name": "blk_mq_end_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
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
