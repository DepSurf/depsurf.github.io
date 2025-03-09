# Function: <code>blk_mq_sched_mark_restart_hctx</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583258448,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": false,
      "loc": "block/blk-mq-sched.c:57",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583438090,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": false,
      "loc": "block/blk-mq-sched.c:57",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583649578,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": false,
      "loc": "block/blk-mq-sched.c:57",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583756215,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:64",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583755760,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583945329,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_dispatch_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583944864,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584048865,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584048400,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584444492,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584443152,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584560803,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:51",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560512,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584593715,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:51",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593024,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585008338,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:51",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585007616,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585724122,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:25",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585723456,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586503184,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:24",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586503184,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586750352,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:22",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750352,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587022608,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:22",
      "file": "block/blk-mq-sched.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_mark_tag_wait",
        "block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587022608,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495885444,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495884752,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229230196,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229227988,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290089648,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290088960,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275006674,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275004806,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584017601,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017136,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583953409,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952960,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584001361,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000896,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_sched_mark_restart_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584103727,
      "name": "blk_mq_sched_mark_restart_hctx",
      "external": true,
      "loc": "block/blk-mq-sched.c:65",
      "file": "block/blk-mq-sched.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests",
        "block/blk-mq-sched.c:blk_mq_sched_dispatch_requests"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/mq-deadline.c:dd_finish_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103280,
      "name": "blk_mq_sched_mark_restart_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx * hctx)
```
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
