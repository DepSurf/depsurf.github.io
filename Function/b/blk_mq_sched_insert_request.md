# Function: <code>blk_mq_sched_insert_request</code>

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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async, bool can_block)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259440,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:357",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259440,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async, bool can_block)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439056,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:430",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439056,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 350
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583650320,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:446",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583650320,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583756704,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:376",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583756704,
      "name": "blk_mq_sched_insert_request",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:378",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947115,
      "name": "blk_mq_sched_insert_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071583945760,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049296,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049296,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584445248,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:449",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584445248,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561600,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:417",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561600,
      "name": "blk_mq_sched_insert_request",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584594512,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:419",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594512,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585009216,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:429",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009216,
      "name": "blk_mq_sched_insert_request",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724928,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:408",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724928,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506080,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:407",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_execute_rq",
        "block/blk-mq.c:blk_execute_rq_nowait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506080,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495886064,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495886064,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229230672,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229230672,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290090464,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290090464,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275007080,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275007080,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018032,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018032,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583953840,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583953840,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001792,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001792,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
```

```json
{
  "name": "blk_mq_sched_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584104144,
      "name": "blk_mq_sched_insert_request",
      "external": true,
      "loc": "block/blk-mq-sched.c:384",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-exec.c:blk_execute_rq_nowait",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104144,
      "name": "blk_mq_sched_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async, bool can_block)
```
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
<b>Param removed. </b>
<code>bool can_block</code>
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void blk_mq_sched_insert_request(struct request * rq, bool at_head, bool run_queue, bool async)
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
