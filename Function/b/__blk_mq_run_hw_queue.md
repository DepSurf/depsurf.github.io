# Function: <code>__blk_mq_run_hw_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582795504,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:722",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_request",
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_delay_work_fn",
        "block/blk-mq.c:blk_mq_run_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582795504,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 886
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074432,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:799",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_map_request",
        "block/blk-mq.c:blk_mq_delay_work_fn",
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:blk_mq_alloc_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074432,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583185088,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:931",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_work_fn",
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:blk_mq_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185088,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583236528,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1101",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583236528,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412400,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1204",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412400,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583621200,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1227",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621200,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583725808,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1351",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583725808,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583914288,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1349",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583914288,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017504,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017504,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415488,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1386",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415488,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528832,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1502",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528832,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560784,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1467",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560784,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972912,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1478",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972912,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585674208,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:2006",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674208,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448800,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:2173",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448800,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495850232,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495850232,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229196396,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229196396,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290042896,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290042896,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274977304,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274977304,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986240,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986240,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922096,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922096,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583970000,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970000,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "__blk_mq_run_hw_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584072176,
      "name": "__blk_mq_run_hw_queue",
      "external": false,
      "loc": "block/blk-mq.c:1365",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_run_work_fn",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584072176,
      "name": "__blk_mq_run_hw_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void __blk_mq_run_hw_queue(struct blk_mq_hw_ctx * hctx)
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
