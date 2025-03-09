# Function: <code>blk_mq_free_rqs</code>

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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244352,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1676",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244352,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423344,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1810",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423344,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634528,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:1867",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634528,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739664,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2033",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739664,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928400,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2032",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928400,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031760,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031760,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427168,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2161",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427168,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543440,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2262",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543440,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584575168,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2326",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584575168,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 398
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2349",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592314188,
      "name": "blk_mq_free_rqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071584988144,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3069",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594097851,
      "name": "blk_mq_free_rqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071585700736,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3232",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596106493,
      "name": "blk_mq_free_rqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586480352,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3244",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596630411,
      "name": "blk_mq_free_rqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586727920,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:3260",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs",
        "block/blk-mq-sched.c:blk_mq_sched_free_rqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597536944,
      "name": "blk_mq_free_rqs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071586999552,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495864968,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495864968,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229212020,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229212020,
      "name": "blk_mq_free_rqs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290063856,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290063856,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274990688,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274990688,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000496,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000496,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936320,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936320,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984256,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984256,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
```

```json
{
  "name": "blk_mq_free_rqs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086576,
      "name": "blk_mq_free_rqs",
      "external": true,
      "loc": "block/blk-mq.c:2058",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:blk_mq_alloc_rqs",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_sched_free_requests",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086576,
      "name": "blk_mq_free_rqs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void blk_mq_free_rqs(struct blk_mq_tag_set * set, struct blk_mq_tags * tags, unsigned int hctx_idx)
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
