# Function: <code>blk_freeze_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582797549,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:102",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582797568,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583077982,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:102",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076560,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583187038,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:84",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583185552,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583248461,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:117",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239808,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583417904,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:154",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583417904,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583629152,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:169",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583629152,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583744274,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:175",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733872,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583933256,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:178",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921872,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584036616,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025168,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584431242,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:164",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422976,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584547658,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:168",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537968,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584580266,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:168",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_shared"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569424,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584994186,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:168",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584980208,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705783,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:197",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585691248,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586483927,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:197",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586470304,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586731511,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:156",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718512,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587003453,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:156",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_exit_queue",
        "block/blk-mq.c:blk_mq_init_allocated_queue"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586989776,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495869792,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495857208,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229216852,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229204520,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290070528,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290053968,
      "name": "blk_freeze_queue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274994980,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274984586,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584005352,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993904,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583941176,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583929760,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583989112,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583977664,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void blk_freeze_queue(struct request_queue * q)
```

```json
{
  "name": "blk_freeze_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584091416,
      "name": "blk_freeze_queue",
      "external": true,
      "loc": "block/blk-mq.c:179",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_update_nr_requests",
        "block/blk-mq.c:blk_mq_update_tag_set_depth"
      ],
      "caller_func": [
        "block/blk-core.c:blk_cleanup_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079904,
      "name": "blk_freeze_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
