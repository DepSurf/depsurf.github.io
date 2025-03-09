# Function: <code>mask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753601,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:293",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755328,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579777310,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:293",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778192,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804031,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:292",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805632,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579802719,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:391",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800304,
      "name": "mask_irq.part.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071579803312,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579836845,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:414",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834192,
      "name": "mask_irq.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579837440,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579870705,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:412",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579867712,
      "name": "mask_irq.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579871312,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579917745,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:412",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914752,
      "name": "mask_irq.part.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579918352,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579955796,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952352,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579956400,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580005668,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580002208,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580006256,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055236,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056096,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580037828,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038688,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580038692,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:421",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039552,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171252,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:421",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172112,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580319962,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580318224,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580534170,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:420",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580532272,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607527,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:421",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580605584,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580672039,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:421",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable",
        "kernel/irq/chip.c:irq_disable"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580670096,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491199840,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491196096,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336491202656,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225221004,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225216948,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 3225221600,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284104736,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284099600,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    },
    {
      "addr": 13835058055284106080,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271743542,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271739378,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936271744104,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579974404,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970944,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579974992,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579912212,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908768,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579912800,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579965940,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962480,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579966528,
      "name": "mask_irq",
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
void mask_irq(struct irq_desc * desc)
```

```json
{
  "name": "mask_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580012468,
      "name": "mask_irq",
      "external": true,
      "loc": "kernel/irq/chip.c:418",
      "file": "kernel/irq/chip.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_trigger",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/pm.c:suspend_device_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009536,
      "name": "mask_irq.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071580013056,
      "name": "mask_irq",
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
