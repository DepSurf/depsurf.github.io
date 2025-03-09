# Function: <code>__setup_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579747936,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1110",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:setup_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579747936,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1558
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770224,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1124",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770224,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1556
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579797120,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1124",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797120,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1583
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579794336,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1111",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579794336,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1698
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579828000,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1139",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579828000,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1785
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1183",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861856,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1664
    },
    {
      "addr": 18446744071579864830,
      "name": "__setup_irq.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1194",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908864,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1664
    },
    {
      "addr": 18446744071579911850,
      "name": "__setup_irq.cold.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1294",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944272,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071579948954,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994416,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071579999004,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1369",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041760,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1879
    },
    {
      "addr": 18446744071580047942,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1439",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580024960,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1877
    },
    {
      "addr": 18446744071591303038,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1439",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025664,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1866
    },
    {
      "addr": 18446744071591245881,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1463",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158064,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1943
    },
    {
      "addr": 18446744071592138455,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1505",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580303968,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1895
    },
    {
      "addr": 18446744071593909237,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1497",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580516384,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1939
    },
    {
      "addr": 18446744071595989355,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1503",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589312,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1933
    },
    {
      "addr": 18446744071596507278,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1505",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653664,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
    },
    {
      "addr": 18446744071597404943,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491184848,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491184848,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2080
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225207796,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225207796,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2044
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284087152,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284087152,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2756
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271732332,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271732332,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1508
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
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579963152,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071579967740,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900992,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071579905580,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954688,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071579959276,
      "name": "__setup_irq.cold",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int __setup_irq(unsigned int irq, struct irq_desc * desc, struct irqaction * new)
```

```json
{
  "name": "__setup_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__setup_irq",
      "external": false,
      "loc": "kernel/irq/manage.c:1286",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:request_percpu_nmi",
        "kernel/irq/manage.c:__request_percpu_irq",
        "kernel/irq/manage.c:setup_percpu_irq",
        "kernel/irq/manage.c:request_nmi",
        "kernel/irq/manage.c:request_threaded_irq",
        "kernel/irq/manage.c:setup_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001072,
      "name": "__setup_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1814
    },
    {
      "addr": 18446744071580005724,
      "name": "__setup_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
