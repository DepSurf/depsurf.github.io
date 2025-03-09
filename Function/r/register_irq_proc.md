# Function: <code>register_irq_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579770224,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:325",
      "file": "kernel/irq/proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770224,
      "name": "register_irq_proc.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071579771024,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579794601,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:324",
      "file": "kernel/irq/proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793424,
      "name": "register_irq_proc.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071579794208,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579821801,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:324",
      "file": "kernel/irq/proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/proc.c:init_irq_proc"
      ],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819824,
      "name": "register_irq_proc.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071579821408,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579819680,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:392",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819680,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855072,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:394",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855072,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579888640,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:330",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888640,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935696,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:330",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935696,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974320,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:330",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974320,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023840,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023840,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580074336,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580074336,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056448,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056448,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580057152,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057152,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580189616,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580189616,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580339824,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580339824,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580557200,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557200,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630672,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630672,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580695824,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580695824,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491227616,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491227616,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225241804,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225241804,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284129840,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284129840,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271762576,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271762576,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992576,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992576,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579931248,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931248,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984112,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984112,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
void register_irq_proc(unsigned int irq, struct irq_desc * desc)
```

```json
{
  "name": "register_irq_proc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030752,
      "name": "register_irq_proc",
      "external": true,
      "loc": "kernel/irq/proc.c:338",
      "file": "kernel/irq/proc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/proc.c:init_irq_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030752,
      "name": "register_irq_proc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
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
