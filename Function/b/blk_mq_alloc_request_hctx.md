# Function: <code>blk_mq_alloc_request_hctx</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, int rw, unsigned int flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583068560,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:274",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068560,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, int rw, unsigned int flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583176464,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:271",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583176464,
      "name": "blk_mq_alloc_request_hctx",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, unsigned int flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583233328,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:377",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233328,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410816,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:413",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410816,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583625216,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:425",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625216,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730320,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:438",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730320,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917184,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:435",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917184,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584020464,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020464,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584410304,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:433",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584410304,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526272,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:429",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526272,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558528,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:430",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558528,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969824,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:437",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969824,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585675856,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:539",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675856,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586451504,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:636",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451504,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 556
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717616,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:610",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717616,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, blk_opf_t opf, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586988800,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:614",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586988800,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 713
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495856656,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495856656,
      "name": "blk_mq_alloc_request_hctx",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229199640,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229199640,
      "name": "blk_mq_alloc_request_hctx",
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290047344,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290047344,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274979962,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274979962,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583989200,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989200,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583925056,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvme/host/core.c:nvme_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925056,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972960,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972960,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, unsigned int op, blk_mq_req_flags_t flags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_alloc_request_hctx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584076736,
      "name": "blk_mq_alloc_request_hctx",
      "external": true,
      "loc": "block/blk-mq.c:446",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584076736,
      "name": "blk_mq_alloc_request_hctx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct request * blk_mq_alloc_request_hctx(struct request_queue * q, int rw, unsigned int flags, unsigned int hctx_idx)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int flags</code> ➡️ <code>blk_mq_req_flags_t flags</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
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
