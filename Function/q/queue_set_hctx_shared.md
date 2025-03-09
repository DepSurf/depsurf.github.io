# Function: <code>queue_set_hctx_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582797641,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:1876",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_tag_set_depth",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583077598,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:1900",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583186668,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:1947",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231280,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2131",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231280,
      "name": "queue_set_hctx_shared",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583408576,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2269",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583408576,
      "name": "queue_set_hctx_shared",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619136,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2332",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619136,
      "name": "queue_set_hctx_shared",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583743785,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2518",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583932825,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2562",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584036170,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584430635,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2773",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584547054,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2878",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584579738,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2938",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970320,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2994",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970320,
      "name": "queue_set_hctx_shared",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585676336,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:3764",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585676336,
      "name": "queue_set_hctx_shared",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452448,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:3928",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452448,
      "name": "queue_set_hctx_shared",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586698128,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:3940",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586698128,
      "name": "queue_set_hctx_shared",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```

```json
{
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586969376,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:3956",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586969376,
      "name": "queue_set_hctx_shared",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495869252,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229216396,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290069640,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274994522,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584004906,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583940730,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583988666,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
  "name": "queue_set_hctx_shared",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584090970,
      "name": "queue_set_hctx_shared",
      "external": false,
      "loc": "block/blk-mq.c:2581",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
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
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void queue_set_hctx_shared(struct request_queue * q, bool shared)
```
</details>
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
