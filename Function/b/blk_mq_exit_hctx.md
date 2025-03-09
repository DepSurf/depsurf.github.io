# Function: <code>blk_mq_exit_hctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582791966,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:1628",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069760,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:1682",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069760,
      "name": "blk_mq_exit_hctx.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177968,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:1710",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177968,
      "name": "blk_mq_exit_hctx.isra.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235568,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:1877",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235568,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583414064,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2011",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583414064,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621568,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2080",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621568,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728640,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2248",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728640,
      "name": "blk_mq_exit_hctx.isra.69",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921072,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2247",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921072,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584024368,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584024368,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418176,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2462",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418176,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534720,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2563",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534720,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584566784,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2624",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566784,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584978656,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2676",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978656,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585679216,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3431",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679216,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586456576,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3595",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586456576,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700048,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3607",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700048,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972032,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:3623",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972032,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495849952,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495849952,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229197108,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229197108,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290044112,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290044112,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274983780,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274983780,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993104,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993104,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928960,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928960,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976864,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976864,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_exit_hctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072880,
      "name": "blk_mq_exit_hctx",
      "external": false,
      "loc": "block/blk-mq.c:2273",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072880,
      "name": "blk_mq_exit_hctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
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
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void blk_mq_exit_hctx(struct request_queue * q, struct blk_mq_tag_set * set, struct blk_mq_hw_ctx * hctx, unsigned int hctx_idx)
```
</details>
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
