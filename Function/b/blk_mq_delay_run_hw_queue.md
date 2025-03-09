# Function: <code>blk_mq_delay_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236800,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1171",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236800,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412944,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1302",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget",
        "drivers/md/dm-rq.c:dm_mq_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412944,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583633078,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1345",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622832,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735226,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1469",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727680,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583923560,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1467",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915776,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584026851,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018992,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584416240,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1520",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416160,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584532160,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1611",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532080,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584563425,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1576",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563328,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584974321,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1587",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974224,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585680742,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2110",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680544,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586457670,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457456,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700752,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2218",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700752,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972736,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2236",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972736,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495859668,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495853064,
      "name": "blk_mq_delay_run_hw_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229206836,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229198180,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290057440,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290045472,
      "name": "blk_mq_delay_run_hw_queue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274986806,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274978782,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583995587,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987728,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583931443,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923584,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583979347,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971488,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```

```json
{
  "name": "blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584081593,
      "name": "blk_mq_delay_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1483",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_get_budget"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074192,
      "name": "blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, long unsigned int msecs)
```
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
