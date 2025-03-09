# Function: <code>__blk_mq_insert_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790832,
      "name": "__blk_mq_insert_request",
      "external": false,
      "loc": "block/blk-mq.c:986",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_make_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790832,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583080211,
      "name": "__blk_mq_insert_request",
      "external": false,
      "loc": "block/blk-mq.c:1065",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_request"
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
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583189149,
      "name": "__blk_mq_insert_request",
      "external": false,
      "loc": "block/blk-mq.c:1129",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_request"
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583241787,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_make_request"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243184,
      "name": "__blk_mq_insert_request",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583420419,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1484",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_make_request"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422160,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583633136,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1517",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583633136,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583735888,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1642",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735888,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924256,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1640",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924256,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027568,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027568,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425056,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1722",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425056,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584540176,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1813",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584540176,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571888,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1832",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571888,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584984464,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1843",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584984464,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585696816,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:2357",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585696816,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586476336,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:2500",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586476336,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495860144,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495860144,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229207116,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229207116,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290057744,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290057744,
      "name": "__blk_mq_insert_request",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274986872,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274986872,
      "name": "__blk_mq_insert_request",
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583996304,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996304,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583932144,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932144,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583980064,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980064,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```

```json
{
  "name": "__blk_mq_insert_request",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082304,
      "name": "__blk_mq_insert_request",
      "external": true,
      "loc": "block/blk-mq.c:1656",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082304,
      "name": "__blk_mq_insert_request",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx * hctx, struct request * rq, bool at_head)
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
