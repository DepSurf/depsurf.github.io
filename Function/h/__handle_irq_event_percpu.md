# Function: <code>__handle_irq_event_percpu</code>

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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762208,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:135",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762208,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579789184,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:135",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579789184,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579786704,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:135",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786704,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579820096,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:135",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579820096,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854487,
      "name": "__handle_irq_event_percpu.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579853472,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901447,
      "name": "__handle_irq_event_percpu.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579900432,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936279,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579935280,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579986407,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579985408,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580034670,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580033584,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302942,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580017168,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245785,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580017952,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592138311,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071580150208,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:139",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593909087,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580295136,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:139",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595989299,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580506704,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:139",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596507016,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580578848,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:139",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597404681,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071580643200,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491173576,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491173576,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225198136,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225198136,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284073808,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284073808,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271724780,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271724780,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955143,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579954144,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579892999,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579892016,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946679,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579945680,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
```

```json
{
  "name": "__handle_irq_event_percpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__handle_irq_event_percpu",
      "external": true,
      "loc": "kernel/irq/handle.c:137",
      "file": "kernel/irq/handle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/handle.c:handle_irq_event_percpu",
        "kernel/irq/chip.c:handle_untracked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579993109,
      "name": "__handle_irq_event_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579992064,
      "name": "__handle_irq_event_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc * desc, unsigned int * flags)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int * flags</code>
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
