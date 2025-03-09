# Function: <code>unmask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753784,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:301",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_edge_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755376,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777414,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:301",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778240,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804124,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:300",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805680,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579801584,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:402",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800464,
      "name": "unmask_irq.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579803344,
      "name": "unmask_irq",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579835532,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:425",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834368,
      "name": "unmask_irq.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579837472,
      "name": "unmask_irq",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579868787,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:423",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867888,
      "name": "unmask_irq.part.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579871344,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579915827,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:423",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914928,
      "name": "unmask_irq.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579918384,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579953901,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952640,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579956432,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580003757,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002496,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580006288,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580053598,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056176,
      "name": "unmask_irq",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036190,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038768,
      "name": "unmask_irq",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580036510,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:432",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039632,
      "name": "unmask_irq",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169070,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:432",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172192,
      "name": "unmask_irq",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580316305,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318320,
      "name": "unmask_irq",
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580530145,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:431",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532384,
      "name": "unmask_irq",
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580603425,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:432",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605696,
      "name": "unmask_irq",
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
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580667937,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:432",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:unmask_threaded_irq",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable",
        "kernel/irq/chip.c:irq_enable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670208,
      "name": "unmask_irq",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491197952,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491196464,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336491202712,
      "name": "unmask_irq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225219332,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225217272,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3225221644,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284103084,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284100128,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 13835058055284106128,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271741510,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271739656,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936271744158,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579972493,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579971232,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579975024,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579910301,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909056,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579912832,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579964029,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962768,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579966560,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void unmask_irq(struct irq_desc * desc)
```

```json
{
  "name": "unmask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011082,
      "name": "unmask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:429",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:unmask_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009824,
      "name": "unmask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580013088,
      "name": "unmask_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
