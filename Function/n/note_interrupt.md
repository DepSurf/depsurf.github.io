# Function: <code>note_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751664,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:273",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751664,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774128,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774128,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579801008,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801008,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 623
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579798128,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:273",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798128,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579831872,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:274",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831872,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 657
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866307,
      "name": "note_interrupt.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071579865536,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913331,
      "name": "note_interrupt.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071579912560,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950735,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579949952,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000591,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579999808,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049520,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071580048912,
      "name": "note_interrupt",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303510,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071580031776,
      "name": "note_interrupt",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591246353,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580032352,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592139139,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580164880,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593909862,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071580311136,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580524368,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524368,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597120,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597120,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580661632,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:272",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580661632,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 757
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491192200,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491192200,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225213616,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225213616,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 704
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284095584,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284095584,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271737046,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271737046,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579969327,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579968544,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907151,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579906368,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960863,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071579960080,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void note_interrupt(struct irq_desc * desc, irqreturn_t action_ret)
```

```json
{
  "name": "note_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "note_interrupt",
      "external": true,
      "loc": "kernel/irq/spurious.c:271",
      "file": "kernel/irq/spurious.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_nested_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007327,
      "name": "note_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580006544,
      "name": "note_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
