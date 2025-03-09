# Function: <code>blk_mq_alloc_rq_map</code>

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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583245840,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1716",
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
      "addr": 18446744071583245840,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583424992,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1850",
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
      "addr": 18446744071583424992,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636240,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1907",
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
      "addr": 18446744071583636240,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741312,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2073",
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
      "addr": 18446744071583741312,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930224,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2072",
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
      "addr": 18446744071583930224,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584033584,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446744071584033584,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584428272,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2201",
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
      "addr": 18446744071584428272,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584544640,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2302",
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
      "addr": 18446744071584544640,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577072,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2368",
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
      "addr": 18446744071584577072,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584990032,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2391",
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
      "addr": 18446744071584990032,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585702434,
      "name": "blk_mq_alloc_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:3147",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586482194,
      "name": "blk_mq_alloc_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:3310",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586729762,
      "name": "blk_mq_alloc_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:3322",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587001394,
      "name": "blk_mq_alloc_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:3338",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495866720,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446603336495866720,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229213792,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 3229213792,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290066272,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 13835058055290066272,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274992232,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446743936274992232,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584002320,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446744071584002320,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583938144,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446744071583938144,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583986080,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446744071583986080,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
```

```json
{
  "name": "blk_mq_alloc_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584088384,
      "name": "blk_mq_alloc_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2098",
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
      "addr": 18446744071584088384,
      "name": "blk_mq_alloc_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct blk_mq_tags * blk_mq_alloc_rq_map(struct blk_mq_tag_set * set, unsigned int hctx_idx, unsigned int nr_tags, unsigned int reserved_tags, unsigned int flags)
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
