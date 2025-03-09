# Function: <code>blk_mq_update_queue_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int blk_mq_update_queue_map(unsigned int * map, unsigned int nr_queues, const struct cpumask * online_mask)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582811584,
      "name": "blk_mq_update_queue_map",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:34",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq-cpumap.c:blk_mq_make_queue_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582811584,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int blk_mq_update_queue_map(unsigned int * map, unsigned int nr_queues, const struct cpumask * online_mask)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583090720,
      "name": "blk_mq_update_queue_map",
      "external": true,
      "loc": "block/blk-mq-cpumap.c:34",
      "file": "block/blk-mq-cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_queue_reinit",
        "block/blk-mq-cpumap.c:blk_mq_make_queue_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583090720,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583235792,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:2481",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583235792,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583415904,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:2627",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415904,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583623728,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:2689",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623728,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583728848,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:2955",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583728848,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583915808,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:2988",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583915808,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584019024,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019024,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409616,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3199",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409616,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584525552,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3306",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584525552,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557920,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3368",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557920,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584969504,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3400",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969504,
      "name": "blk_mq_update_queue_map",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585674432,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:4163",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585674432,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586455856,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:4365",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586455856,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586699296,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:4364",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699296,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586970544,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:4380",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:__blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970544,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495847200,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495847200,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229198216,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229198216,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290045504,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290045504,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274978834,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274978834,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583987760,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987760,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583923616,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583923616,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583971520,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971520,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
```

```json
{
  "name": "blk_mq_update_queue_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584075280,
      "name": "blk_mq_update_queue_map",
      "external": false,
      "loc": "block/blk-mq.c:3008",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_update_nr_hw_queues",
        "block/blk-mq.c:blk_mq_alloc_tag_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075280,
      "name": "blk_mq_update_queue_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int blk_mq_update_queue_map(unsigned int * map, unsigned int nr_queues, const struct cpumask * online_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set * set)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
