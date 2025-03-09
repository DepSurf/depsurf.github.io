# Function: <code>blk_mq_alloc_and_init_hctx</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583740158,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2701",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583928901,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2733",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584032261,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422016,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2956",
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
      "addr": 18446744071584422016,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537040,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3061",
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
      "addr": 18446744071584537040,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584575949,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3121",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584988973,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3160",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585687856,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3930",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585687856,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586468352,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:4137",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586468352,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586713968,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:4149",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586713968,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```

```json
{
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586986448,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:4165",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986448,
      "name": "blk_mq_alloc_and_init_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495865520,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229212576,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290064692,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274991092,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584000997,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583936821,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583984757,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
  "name": "blk_mq_alloc_and_init_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584087072,
      "name": "blk_mq_alloc_and_init_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2756",
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
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct blk_mq_hw_ctx * blk_mq_alloc_and_init_hctx(struct blk_mq_tag_set * set, struct request_queue * q, int hctx_idx, int node)
```
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
