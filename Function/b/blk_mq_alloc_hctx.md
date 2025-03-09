# Function: <code>blk_mq_alloc_hctx</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583929505,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2323",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584032865,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584421424,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2541",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584421424,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 590
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536432,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2642",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536432,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 602
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584565088,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2703",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565088,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584976000,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2759",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584976000,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687312,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3509",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687312,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586467792,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3673",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586467792,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713408,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3685",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713408,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
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
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586985840,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3701",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_and_init_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985840,
      "name": "blk_mq_alloc_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495866020,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229213168,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290065360,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274991092,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584001601,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583937425,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583985361,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584087670,
      "name": "blk_mq_alloc_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct blk_mq_hw_ctx * blk_mq_alloc_hctx(struct request_queue * q, struct blk_mq_tag_set * set, int node)
```
</details>
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
