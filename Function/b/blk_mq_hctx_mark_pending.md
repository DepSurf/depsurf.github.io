# Function: <code>blk_mq_hctx_mark_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582788992,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:64",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_hctx_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788992,
      "name": "blk_mq_hctx_mark_pending",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583066496,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:64",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583066496,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583176800,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:50",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_sq_make_request",
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176800,
      "name": "blk_mq_hctx_mark_pending.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235920,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:73",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235920,
      "name": "blk_mq_hctx_mark_pending.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583414480,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:74",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_make_request",
        "block/blk-mq.c:blk_mq_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414480,
      "name": "blk_mq_hctx_mark_pending.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583622000,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:74",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583622000,
      "name": "blk_mq_hctx_mark_pending.isra.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583724592,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:74",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583724592,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583914976,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:76",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914976,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584018192,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584018192,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584413648,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:78",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584413648,
      "name": "blk_mq_hctx_mark_pending",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584529328,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:80",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584529328,
      "name": "blk_mq_hctx_mark_pending",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560048,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:80",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560048,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:80",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971824,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    },
    {
      "addr": 18446744071592313503,
      "name": "blk_mq_hctx_mark_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:109",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677984,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071594096850,
      "name": "blk_mq_hctx_mark_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:110",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586454864,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071596105614,
      "name": "blk_mq_hctx_mark_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:69",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698736,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071596629527,
      "name": "blk_mq_hctx_mark_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:69",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_request",
        "block/blk-mq.c:blk_mq_insert_requests"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969984,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071597536033,
      "name": "blk_mq_hctx_mark_pending.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495848840,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495848840,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229197012,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229197012,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290038320,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290038320,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274974730,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274974730,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986928,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986928,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922784,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922784,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970688,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970688,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```

```json
{
  "name": "blk_mq_hctx_mark_pending",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073120,
      "name": "blk_mq_hctx_mark_pending",
      "external": false,
      "loc": "block/blk-mq.c:77",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_insert_requests",
        "block/blk-mq.c:__blk_mq_insert_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073120,
      "name": "blk_mq_hctx_mark_pending",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void blk_mq_hctx_mark_pending(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx)
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
