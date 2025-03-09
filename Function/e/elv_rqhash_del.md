# Function: <code>elv_rqhash_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582726368,
      "name": "elv_rqhash_del",
      "external": false,
      "loc": "block/elevator.c:251",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_dispatch_sort",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_merge_requests"
      ],
      "caller_func": [
        "block/elevator.c:elv_dispatch_sort",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_merge_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582726368,
      "name": "elv_rqhash_del.isra.6.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583005594,
      "name": "elv_rqhash_del",
      "external": false,
      "loc": "block/elevator.c:251",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583004128,
      "name": "elv_rqhash_del.isra.7.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583110602,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:251",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583109248,
      "name": "elv_rqhash_del.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583109824,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583166846,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:275",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583164272,
      "name": "elv_rqhash_del.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583164352,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583341668,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:292",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337872,
      "name": "elv_rqhash_del.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071583337952,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583549914,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:261",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ],
      "caller_func": [
        "block/elevator.c:elv_merge_requests",
        "block/elevator.c:elv_dispatch_add_tail",
        "block/elevator.c:elv_dispatch_sort"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583546816,
      "name": "elv_rqhash_del.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071583546880,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670448,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:196",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670448,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583859056,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:197",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859056,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583961696,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961696,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584350240,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350240,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584466880,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:206",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584466880,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584501840,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:206",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501840,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912336,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:206",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912336,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585613968,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:211",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585613968,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586383264,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:179",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586383264,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586629632,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:179",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586629632,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586900528,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:179",
      "file": "block/elevator.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:__dd_dispatch_request",
        "block/mq-deadline.c:dd_merged_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586900528,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495784376,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request",
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495784376,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229135544,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229135544,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289961168,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request",
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289961168,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274927150,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request",
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274927150,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583930432,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930432,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583867376,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867376,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583914192,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914192,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```

```json
{
  "name": "elv_rqhash_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584015600,
      "name": "elv_rqhash_del",
      "external": true,
      "loc": "block/elevator.c:207",
      "file": "block/elevator.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/mq-deadline.c:deadline_remove_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584015600,
      "name": "elv_rqhash_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void elv_rqhash_del(struct request_queue * q, struct request * rq)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
