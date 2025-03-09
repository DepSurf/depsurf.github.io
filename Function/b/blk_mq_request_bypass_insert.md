# Function: <code>blk_mq_request_bypass_insert</code>

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
void blk_mq_request_bypass_insert(struct request * rq)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583243408,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1364",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243408,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void blk_mq_request_bypass_insert(struct request * rq, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422384,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1499",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422384,
      "name": "blk_mq_request_bypass_insert",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void blk_mq_request_bypass_insert(struct request * rq, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633360,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1532",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633360,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void blk_mq_request_bypass_insert(struct request * rq, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736128,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1657",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736128,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void blk_mq_request_bypass_insert(struct request * rq, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924496,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1655",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924496,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027808,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027808,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584419396,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1741",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425296,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584535760,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1833",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540384,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584568272,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1852",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572096,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584982806,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1863",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984752,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585699484,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:2377",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697152,
      "name": "blk_mq_request_bypass_insert",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586478945,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:2520",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586476688,
      "name": "blk_mq_request_bypass_insert",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586721012,
      "name": "blk_mq_request_bypass_insert",
      "external": false,
      "loc": "block/blk-mq.c:2447",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586992196,
      "name": "blk_mq_request_bypass_insert",
      "external": false,
      "loc": "block/blk-mq.c:2467",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_plug_issue_direct",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_requeue_work"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495860432,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495860432,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229207364,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229207364,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290058128,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290058128,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274987102,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274987102,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996544,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996544,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932384,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932384,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980304,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980304,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
```

```json
{
  "name": "blk_mq_request_bypass_insert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082576,
      "name": "blk_mq_request_bypass_insert",
      "external": true,
      "loc": "block/blk-mq.c:1671",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:blk_insert_flush",
        "block/blk-mq.c:blk_mq_try_issue_list_directly",
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_requeue_work",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082576,
      "name": "blk_mq_request_bypass_insert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void blk_mq_request_bypass_insert(struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool run_queue</code>
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool at_head</code>
</li>
<li>
<b>Param reordered. </b>
<code>rq, run_queue</code> ➡️ <code>rq, at_head, run_queue</code>
</li>
</ul>
</details>
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
void blk_mq_request_bypass_insert(struct request * rq, bool at_head, bool run_queue)
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
