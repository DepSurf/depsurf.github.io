# Function: <code>blk_mq_insert_requests</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, int depth, bool from_schedule)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582800720,
      "name": "blk_mq_insert_requests",
      "external": false,
      "loc": "block/blk-mq.c:1018",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582800720,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void blk_mq_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, int depth, bool from_schedule)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583078880,
      "name": "blk_mq_insert_requests",
      "external": false,
      "loc": "block/blk-mq.c:1091",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583078880,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void blk_mq_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, int depth, bool from_schedule)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583187952,
      "name": "blk_mq_insert_requests",
      "external": false,
      "loc": "block/blk-mq.c:1153",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list",
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583187952,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243520,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1376",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243520,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422512,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1512",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422512,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633488,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1545",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633488,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736592,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1669",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736592,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583927056,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1667",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927056,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030416,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030416,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425440,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1757",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425440,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540528,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1849",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540528,
      "name": "blk_mq_insert_requests",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584572240,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1868",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572240,
      "name": "blk_mq_insert_requests",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984896,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1879",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984896,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697328,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:2393",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697328,
      "name": "blk_mq_insert_requests",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586476880,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:2536",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586476880,
      "name": "blk_mq_insert_requests",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586721136,
      "name": "blk_mq_insert_requests",
      "external": false,
      "loc": "block/blk-mq.c:2459",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721136,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586992320,
      "name": "blk_mq_insert_requests",
      "external": false,
      "loc": "block/blk-mq.c:2479",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586992320,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495863392,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495863392,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229210376,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229210376,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290061904,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290061904,
      "name": "blk_mq_insert_requests",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274989518,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274989518,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583999152,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999152,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583934976,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583934976,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583982912,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982912,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void blk_mq_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584085264,
      "name": "blk_mq_insert_requests",
      "external": true,
      "loc": "block/blk-mq.c:1687",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085264,
      "name": "blk_mq_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>int depth</code>
</li>
<li>
<b>Param removed. </b>
<code>bool from_schedule</code>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool run_queue_async</code>
</li>
</ul>
</details>
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
