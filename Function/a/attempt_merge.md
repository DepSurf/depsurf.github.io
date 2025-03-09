# Function: <code>attempt_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582782080,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:647",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:attempt_back_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582782080,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2061
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
int attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583061088,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:673",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061088,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583167456,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:664",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167456,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2337
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583224416,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:648",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583224416,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2552
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583401136,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:649",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583401136,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2517
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583611232,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:676",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611232,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2693
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583716896,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583716896,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2528
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583905504,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:671",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583905504,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584008720,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008720,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
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
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584402853,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:721",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584401936,
      "name": "attempt_merge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 577
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584518853,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:736",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_attempt_req_merge"
      ],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584516752,
      "name": "attempt_merge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071584517536,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584551461,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:739",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_attempt_req_merge"
      ],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584548368,
      "name": "attempt_merge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
    },
    {
      "addr": 18446744071584549584,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584962789,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:725",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_attempt_req_merge"
      ],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584959680,
      "name": "attempt_merge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
    },
    {
      "addr": 18446744071584960896,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585663760,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:746",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585663760,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439136,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:811",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439136,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1255
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586686256,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:805",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586686256,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1267
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957584,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:801",
      "file": "block/blk-merge.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_mq_sched_try_merge",
        "block/blk-merge.c:blk_attempt_req_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957584,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1267
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495838256,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495838256,
      "name": "attempt_merge.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1780
    },
    {
      "addr": 18446603336495840040,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229186484,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229186484,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1968
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290030112,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290030112,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2104
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274969554,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274969554,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583977456,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977456,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583913648,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583913648,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1738
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583961216,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583961216,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2002
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
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```

```json
{
  "name": "attempt_merge",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584063232,
      "name": "attempt_merge",
      "external": false,
      "loc": "block/blk-merge.c:724",
      "file": "block/blk-merge.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-merge.c:blk_attempt_req_merge",
        "block/blk-merge.c:attempt_front_merge",
        "block/blk-merge.c:attempt_back_merge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584063232,
      "name": "attempt_merge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2072
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct request *</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct request * attempt_merge(struct request_queue * q, struct request * req, struct request * next)
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
