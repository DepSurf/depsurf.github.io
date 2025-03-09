# Function: <code>blk_mq_get_driver_tag</code>

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
bool blk_mq_get_driver_tag(struct request * rq, struct blk_mq_hw_ctx * * hctx, bool wait)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240160,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:857",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240160,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq, struct blk_mq_hw_ctx * * hctx, bool wait)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418704,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:969",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418704,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq, struct blk_mq_hw_ctx * * hctx, bool wait)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629760,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:967",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629760,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583734336,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1041",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583734336,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922656,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1040",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922656,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025952,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025952,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584415143,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq-tag.h:55",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528032,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.c:1129",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528032,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584559584,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.c:1087",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559584,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584981312,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1093",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584981312,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585693256,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:273",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585722797,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:273",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586472472,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:274",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586503853,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:274",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586720262,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:324",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_budget_and_tag",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586751021,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:324",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
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
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586991478,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:352",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_budget_and_tag",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq.c:blk_mq_mark_tag_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587023271,
      "name": "blk_mq_get_driver_tag",
      "external": false,
      "loc": "block/blk-mq.h:352",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_do_dispatch_sched"
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495858152,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495858152,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229205284,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229205284,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290055184,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290055184,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274985284,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274985284,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994688,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994688,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930544,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930544,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583978448,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978448,
      "name": "blk_mq_get_driver_tag",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```

```json
{
  "name": "blk_mq_get_driver_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584080688,
      "name": "blk_mq_get_driver_tag",
      "external": true,
      "loc": "block/blk-mq.c:1056",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080688,
      "name": "blk_mq_get_driver_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
bool blk_mq_get_driver_tag(struct request * rq, struct blk_mq_hw_ctx * * hctx, bool wait)
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
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx * * hctx</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wait</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool blk_mq_get_driver_tag(struct request * rq)
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
