# Function: <code>blk_mq_sched_insert_requests</code>

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
void blk_mq_sched_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259824,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:389",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583259824,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void blk_mq_sched_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439408,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:465",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583439408,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void blk_mq_sched_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650704,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:481",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583650704,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757072,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:411",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583757072,
      "name": "blk_mq_sched_insert_requests",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583946128,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:413",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583946128,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049696,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071584049696,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445632,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:508",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445632,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561888,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:470",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561888,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594800,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:472",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594800,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585009488,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:482",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009488,
      "name": "blk_mq_sched_insert_requests",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725200,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:461",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725200,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506368,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:460",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_flush_plug_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506368,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495886528,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446603336495886528,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229231120,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 3229231120,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290091056,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 13835058055290091056,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275007428,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446743936275007428,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018432,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071584018432,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583954240,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071583954240,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002192,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071584002192,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
```

```json
{
  "name": "blk_mq_sched_insert_requests",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104544,
      "name": "blk_mq_sched_insert_requests",
      "external": true,
      "loc": "block/blk-mq-sched.c:443",
      "file": "block/blk-mq-sched.c",
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
      "addr": 18446744071584104544,
      "name": "blk_mq_sched_insert_requests",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void blk_mq_sched_insert_requests(struct request_queue * q, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
</ul>
</details>
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
void blk_mq_sched_insert_requests(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, struct list_head * list, bool run_queue_async)
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
