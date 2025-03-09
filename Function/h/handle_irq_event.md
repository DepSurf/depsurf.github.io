# Function: <code>handle_irq_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579740720,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:186",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_simple_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_edge_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740720,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762752,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:194",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762752,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789712,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:194",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789712,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579787232,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:196",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787232,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820640,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:196",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820640,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854000,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854000,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900960,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900960,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935792,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935792,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579985920,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579985920,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580034096,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:205",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034096,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017664,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:205",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017664,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580018448,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:205",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018448,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150704,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:205",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150704,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580295648,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:202",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295648,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580507264,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:202",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580507264,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580579392,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:202",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580579392,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643744,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:202",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643744,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491174320,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_fasteoi_mask_irq",
        "kernel/irq/chip.c:handle_fasteoi_ack_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491174320,
      "name": "handle_irq_event",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225198900,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225198900,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284074720,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284074720,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271725364,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271725364,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954656,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954656,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579892512,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892512,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579946192,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946192,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
irqreturn_t handle_irq_event(struct irq_desc * desc)
```

```json
{
  "name": "handle_irq_event",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992624,
      "name": "handle_irq_event",
      "external": true,
      "loc": "kernel/irq/handle.c:198",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/spurious.c:try_one_irq",
        "kernel/irq/chip.c:handle_edge_irq",
        "kernel/irq/chip.c:handle_fasteoi_irq",
        "kernel/irq/chip.c:handle_level_irq",
        "kernel/irq/chip.c:handle_simple_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992624,
      "name": "handle_irq_event",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
