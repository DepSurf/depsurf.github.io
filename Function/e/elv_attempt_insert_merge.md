# Function: <code>elv_attempt_insert_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582728391,
      "name": "elv_attempt_insert_merge",
      "external": false,
      "loc": "block/elevator.c:462",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elv_add_request"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583006060,
      "name": "elv_attempt_insert_merge",
      "external": false,
      "loc": "block/elevator.c:461",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elv_add_request"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583111059,
      "name": "elv_attempt_insert_merge",
      "external": false,
      "loc": "block/elevator.c:459",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:__elv_add_request"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583166464,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:488",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166464,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583341280,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:505",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341280,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583549488,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:474",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/elevator.c:__elv_add_request",
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549488,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672320,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:345",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672320,
      "name": "elv_attempt_insert_merge",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583860928,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:346",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860928,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963616,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963616,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584351568,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584351568,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468208,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:355",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468208,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503168,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:355",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503168,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq, struct list_head * free)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584913712,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:359",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584913712,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq, struct list_head * free)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585614864,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:364",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614864,
      "name": "elv_attempt_insert_merge",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq, struct list_head * free)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586384240,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:332",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586384240,
      "name": "elv_attempt_insert_merge",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq, struct list_head * free)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586630608,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:332",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630608,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq, struct list_head * free)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901504,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:332",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901504,
      "name": "elv_attempt_insert_merge",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495786768,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495786768,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229137552,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229137552,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289964848,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289964848,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274929322,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274929322,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932352,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932352,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583869296,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583869296,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583916112,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583916112,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_attempt_insert_merge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017488,
      "name": "elv_attempt_insert_merge",
      "external": true,
      "loc": "block/elevator.c:356",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_try_insert_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017488,
      "name": "elv_attempt_insert_merge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool elv_attempt_insert_merge(struct request_queue * q, struct request * rq)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head * free</code>
</li>
</ul>
</details>
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
