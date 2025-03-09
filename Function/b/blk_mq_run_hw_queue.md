# Function: <code>blk_mq_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582795328,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:856",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_hctx_notify",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq-tag.c:bt_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795328,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583074256,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:934",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq.c:blk_mq_hctx_notify",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:__blk_mq_run_hw_queue",
        "block/blk-mq-tag.c:bt_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074256,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184064,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:974",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184064,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583237351,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1177",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236832,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412976,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1308",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412976,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583622864,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1351",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622864,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727712,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1475",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727712,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583918960,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1473",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583918960,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584022256,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584022256,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584416272,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1535",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584416272,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532192,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1626",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_freeze_queue_start",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532192,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584563568,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1591",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563568,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974464,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1602",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974464,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585680928,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2125",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680928,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586457872,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2288",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queue",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586457872,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701392,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2236",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queue",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701392,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
void blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973376,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:2254",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queue",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973376,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495853120,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495853120,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229202272,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229202272,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290050704,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290050704,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274981512,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_stopped_hw_queues",
        "block/blk-mq.c:blk_mq_start_hw_queues",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274981512,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583990992,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990992,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583926848,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583926848,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974752,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974752,
      "name": "blk_mq_run_hw_queue",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx, bool async)
```

```json
{
  "name": "blk_mq_run_hw_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584074224,
      "name": "blk_mq_run_hw_queue",
      "external": true,
      "loc": "block/blk-mq.c:1489",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_hctx_notify_dead",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_request_bypass_insert",
        "block/blk-mq.c:blk_mq_start_hw_queue",
        "block/blk-mq.c:blk_mq_run_hw_queues",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_wake",
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request",
        "block/blk-mq-sched.c:blk_mq_sched_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584074224,
      "name": "blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
