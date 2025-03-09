# Function: <code>dm_table_get_immutable_target</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210576,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:996",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210576,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586414976,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:997",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586414976,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586518752,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1037",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518752,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586986192,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1039",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586986192,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587284409,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1074",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587283824,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587464531,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1059",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587463984,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587737898,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1072",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587737360,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587942170,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587941632,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588794908,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1046",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type",
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795408,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588812867,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:991",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588813200,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588698755,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:977",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588699088,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589386771,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:972",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589387104,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590858172,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:974",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590863488,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592549988,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:969",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592556112,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592981044,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:963",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592986544,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593730484,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:985",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_determine_type"
      ],
      "caller_func": [
        "drivers/md/dm.c:__bind",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593737360,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501180876,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501180248,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233688152,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233687568,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294693456,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294692720,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277884578,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277884038,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587573146,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587572608,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587341226,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587340688,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587898314,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587897776,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```

```json
{
  "name": "dm_table_get_immutable_target",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588013578,
      "name": "dm_table_get_immutable_target",
      "external": true,
      "loc": "drivers/md/dm-table.c:1070",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete",
        "drivers/md/dm-table.c:dm_table_complete"
      ],
      "caller_func": [
        "drivers/md/dm.c:dm_swap_table",
        "drivers/md/dm-rq.c:dm_mq_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588013040,
      "name": "dm_table_get_immutable_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct dm_target * dm_table_get_immutable_target(struct dm_table * t)
```
</details>
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
