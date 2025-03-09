# Function: <code>__blk_mq_delay_run_hw_queue</code>

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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583236672,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1146",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236672,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412800,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1277",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412800,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622480,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1324",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622480,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727328,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1448",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727328,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583915424,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915424,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018640,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018640,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415808,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1492",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415808,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531728,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1583",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531728,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584562960,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1548",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584562960,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584973856,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1559",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584973856,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680144,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:2082",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680144,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457056,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:2249",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457056,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
    }
  ]
}
```
</details>
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495852584,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495852584,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229197776,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229197776,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290044880,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290044880,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274978410,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274978410,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987376,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987376,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583923232,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923232,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971136,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971136,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
```

```json
{
  "name": "__blk_mq_delay_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073792,
      "name": "__blk_mq_delay_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073792,
      "name": "__blk_mq_delay_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __blk_mq_delay_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async, long unsigned int msecs)
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
