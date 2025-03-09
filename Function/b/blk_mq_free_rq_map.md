# Function: <code>blk_mq_free_rq_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582792144,
      "name": "blk_mq_free_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1416",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_init_rq_map",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_map_swqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792144,
      "name": "blk_mq_free_rq_map.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069440,
      "name": "blk_mq_free_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1482",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_init_rq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069440,
      "name": "blk_mq_free_rq_map.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177600,
      "name": "blk_mq_free_rq_map",
      "external": false,
      "loc": "block/blk-mq.c:1544",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_init_rq_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177600,
      "name": "blk_mq_free_rq_map.isra.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583244560,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1706",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583244560,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583423552,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1840",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583423552,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583634736,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:1897",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583634736,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739872,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2063",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739872,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928608,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2062",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928608,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031968,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031968,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584428037,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2191",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:__blk_mq_alloc_map_and_request"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_exit_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428192,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544357,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2292",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:__blk_mq_alloc_map_and_request"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_exit_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544544,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584576789,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2358",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:__blk_mq_alloc_map_and_request"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_exit_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584576976,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags, unsigned int flags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584988661,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2381",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_map_and_request"
      ],
      "caller_func": [
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_exit_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989936,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585702113,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:3110",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585702320,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586481793,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:3273",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586482064,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586729361,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:3285",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586729632,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587000993,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:3301",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_free_tag_set",
        "block/blk-mq.c:blk_mq_alloc_set_map_and_rqs",
        "block/blk-mq.c:__blk_mq_free_map_and_rqs",
        "block/blk-mq.c:blk_mq_alloc_map_and_rqs"
      ],
      "caller_func": [
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001264,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495865192,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495865192,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229212240,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229212240,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290064192,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290064192,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274990850,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched",
        "block/blk-mq-sched.c:blk_mq_sched_tags_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274990850,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000704,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000704,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583936528,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936528,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583984464,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583984464,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
```

```json
{
  "name": "blk_mq_free_rq_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086784,
      "name": "blk_mq_free_rq_map",
      "external": true,
      "loc": "block/blk-mq.c:2088",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_alloc_tag_set",
        "block/blk-mq.c:blk_mq_free_map_and_requests",
        "block/blk-mq.c:__blk_mq_alloc_rq_map",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-tag.c:blk_mq_tag_update_depth",
        "block/blk-mq-sched.c:blk_mq_init_sched"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086784,
      "name": "blk_mq_free_rq_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void blk_mq_free_rq_map(struct blk_mq_tags * tags)
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
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
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
