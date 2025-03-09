# Function: <code>blk_mq_alloc_rqs</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583246016,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1758",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583246016,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 605
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583425168,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1892",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583425168,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636432,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1964",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636432,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741504,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2130",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741504,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930416,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2129",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930416,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033776,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584033776,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584428464,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2258",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_map_and_request",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428464,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544832,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2359",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_map_and_request",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544832,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577264,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2420",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_map_and_request",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577264,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990224,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2443",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_map_and_request",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584990224,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585701216,
      "name": "blk_mq_alloc_rqs",
      "external": false,
      "loc": "block/blk-mq.c:3198",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701216,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586480864,
      "name": "blk_mq_alloc_rqs",
      "external": false,
      "loc": "block/blk-mq.c:3362",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586480864,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586728432,
      "name": "blk_mq_alloc_rqs",
      "external": false,
      "loc": "block/blk-mq.c:3374",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586728432,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587000064,
      "name": "blk_mq_alloc_rqs",
      "external": false,
      "loc": "block/blk-mq.c:3390",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587000064,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495866944,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495866944,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229213996,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229213996,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290066560,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290066560,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274992406,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274992406,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002512,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584002512,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938336,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583938336,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986272,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583986272,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
```

```json
{
  "name": "blk_mq_alloc_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584088576,
      "name": "blk_mq_alloc_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2155",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584088576,
      "name": "blk_mq_alloc_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int blk_mq_alloc_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx, unsigned int depth)
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
