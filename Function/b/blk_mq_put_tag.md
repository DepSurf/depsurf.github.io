# Function: <code>blk_mq_put_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, unsigned int tag, unsigned int * last_tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582807760,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:404",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582807760,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, unsigned int tag, unsigned int * last_tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583086864,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:404",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583086864,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194896,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:195",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194896,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251584,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:184",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_put_driver_tag",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251584,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430976,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:184",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:__blk_mq_try_issue_directly",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_free_request",
        "block/blk-mq.c:blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430976,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583642160,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:200",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642160,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748576,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:200",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748576,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583937616,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:193",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583937616,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041088,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041088,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584435648,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:221",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584435648,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584552048,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:181",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552048,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584584864,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:181",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584864,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584999779,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:182",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999904,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585713092,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:222",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713184,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586493369,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:218",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586493488,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586740953,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:225",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586741072,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587013033,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:225",
      "file": "block/blk-mq-tag.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-tag.c:blk_mq_get_tag",
        "block/blk-mq-tag.c:blk_mq_get_tag"
      ],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587013152,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495875712,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495875712,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229221584,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229221584,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290077008,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290077008,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274998830,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274998830,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584009824,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584009824,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583945648,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583945648,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993584,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993584,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void blk_mq_put_tag(struct blk_mq_hw_ctx * hctx, struct blk_mq_tags * tags, struct blk_mq_ctx * ctx, unsigned int tag)
```

```json
{
  "name": "blk_mq_put_tag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095888,
      "name": "blk_mq_put_tag",
      "external": true,
      "loc": "block/blk-mq-tag.c:194",
      "file": "block/blk-mq-tag.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-flush.c:mq_flush_data_end_io",
        "block/blk-flush.c:flush_end_io",
        "block/blk-mq.c:blk_mq_dispatch_rq_list",
        "block/blk-mq.c:__blk_mq_free_request",
        "block/blk-mq.c:__blk_mq_free_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095888,
      "name": "blk_mq_put_tag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_ctx * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int * last_tag</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, tag, last_tag</code> ➡️ <code>hctx, ctx, tag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_tags * tags</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, ctx, tag</code> ➡️ <code>hctx, tags, ctx, tag</code>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx * hctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, tags, ctx, tag</code> ➡️ <code>tags, ctx, tag</code>
</li>
</ul>
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
