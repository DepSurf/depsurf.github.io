# Function: <code>irq_setup_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579793168,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:326",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793168,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826832,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:343",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826832,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860672,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:376",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860672,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:376",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911838,
      "name": "irq_setup_affinity.cold.50",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579907600,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:405",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_select_affinity_usr",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948913,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579942960,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998963,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579993184,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:488",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047901,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580040528,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:558",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302997,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580023728,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:558",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245840,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580024416,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:582",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592138414,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580156784,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:597",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593909198,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580302544,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580514800,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:589",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580514800,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587696,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:592",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587696,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580652048,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:594",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652048,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 454
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491183296,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491183296,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225206484,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225206484,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284085296,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284085296,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271731170,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271731170,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967699,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579961920,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905539,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579899760,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959235,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579953456,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int irq_setup_affinity(struct irq_desc * desc)
```

```json
{
  "name": "irq_setup_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_setup_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:412",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005683,
      "name": "irq_setup_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071579999840,
      "name": "irq_setup_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 387
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int irq_setup_affinity(struct irq_desc * desc)
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
