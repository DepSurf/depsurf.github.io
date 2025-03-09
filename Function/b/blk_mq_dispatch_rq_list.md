# Function: <code>blk_mq_dispatch_rq_list</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583184192,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:815",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_process_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583184192,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583242368,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:983",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242368,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583420944,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1077",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583420944,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1213
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631872,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1083",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631872,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1261
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734608,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1197",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734608,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1268
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1195",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935651,
      "name": "blk_mq_dispatch_rq_list.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071583922912,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1332
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584026208,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026208,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584423792,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1210",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584423792,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538784,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1348",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538784,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1390
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584570352,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1312",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584570352,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1525
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584982928,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1318",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584982928,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1530
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585695120,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1847",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585695120,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1688
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586474608,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:2013",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586474608,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1704
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725072,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:2013",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725072,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list, unsigned int nr_budgets)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586996240,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:2031",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586996240,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1310
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495858488,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495858488,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1656
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229205604,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229205604,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1512
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290055600,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290055600,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2144
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274985498,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274985498,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1374
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994944,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994944,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930800,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930800,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1338
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978704,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978704,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
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
bool blk_mq_dispatch_rq_list(struct request_queue * q, struct list_head * list, bool got_budget)
```

```json
{
  "name": "blk_mq_dispatch_rq_list",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584080944,
      "name": "blk_mq_dispatch_rq_list",
      "external": true,
      "loc": "block/blk-mq.c:1211",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_ctx",
        "block/blk-mq-sched.c:blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080944,
      "name": "blk_mq_dispatch_rq_list",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool blk_mq_dispatch_rq_list(struct blk_mq_hw_ctx * hctx, struct list_head * list)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool got_budget</code>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int nr_budgets</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param removed. </b>
<code>bool got_budget</code>
</li>
</ul>
</details>
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
