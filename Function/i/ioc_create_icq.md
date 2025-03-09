# Function: <code>ioc_create_icq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582773776,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:357",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582773776,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583052128,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:357",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052128,
      "name": "ioc_create_icq",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583157904,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:357",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583157904,
      "name": "ioc_create_icq",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215344,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:388",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215344,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583391968,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:389",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583391968,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:389",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:get_request",
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602358,
      "name": "ioc_create_icq.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583601952,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708401,
      "name": "ioc_create_icq.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583708016,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583897034,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583896640,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000372,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583999984,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:372",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584389396,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584389008,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:372",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591372663,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584503232,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:372",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315262,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584537648,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:372",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592313337,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071584948768,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": false,
      "loc": "block/blk-ioc.c:367",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650992,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 407
    },
    {
      "addr": 18446744071594096063,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
struct io_cq * ioc_create_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586424128,
      "name": "ioc_create_icq",
      "external": false,
      "loc": "block/blk-ioc.c:367",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586424128,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
struct io_cq * ioc_create_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671680,
      "name": "ioc_create_icq",
      "external": false,
      "loc": "block/blk-ioc.c:363",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671680,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
struct io_cq * ioc_create_icq(struct request_queue * q)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942576,
      "name": "ioc_create_icq",
      "external": false,
      "loc": "block/blk-ioc.c:363",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-ioc.c:ioc_find_get_icq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942576,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495828792,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495828792,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229177384,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229177384,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290018720,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290018720,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274962502,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274962502,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583969108,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583968720,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583906014,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583905632,
      "name": "ioc_create_icq",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952868,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071583952480,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct io_cq * ioc_create_icq(struct io_context * ioc, struct request_queue * q, gfp_t gfp_mask)
```

```json
{
  "name": "ioc_create_icq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ioc_create_icq",
      "external": true,
      "loc": "block/blk-ioc.c:365",
      "file": "block/blk-ioc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_assign_ioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054859,
      "name": "ioc_create_icq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071584054448,
      "name": "ioc_create_icq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct io_context * ioc</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
<li>
<b>Param reordered. </b>
<code>ioc, q, gfp_mask</code> ➡️ <code>q</code>
</li>
</ul>
</details>
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
