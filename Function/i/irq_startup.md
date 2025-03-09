# Function: <code>irq_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579754992,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:189",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754992,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int irq_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777856,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:189",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777856,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int irq_startup(struct irq_desc * desc, bool resend)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804560,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:188",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804560,
      "name": "irq_startup",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802176,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:251",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/autoprobe.c:probe_irq_on",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802176,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836192,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:257",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836192,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870048,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870048,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917088,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917088,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579957937,
      "name": "irq_startup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579955168,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005024,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005024,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054640,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054640,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037232,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037232,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038000,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038000,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170560,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170560,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580317456,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:252",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580317456,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580531424,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:254",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531424,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604720,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:254",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604720,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669232,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:254",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:__irq_do_set_handler",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669232,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491201096,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491201096,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225220164,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225220164,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284104112,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284104112,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271742932,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271742932,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973760,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973760,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911568,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911568,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965296,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965296,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int irq_startup(struct irq_desc * desc, bool resend, bool force)
```

```json
{
  "name": "irq_startup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011824,
      "name": "irq_startup",
      "external": true,
      "loc": "kernel/irq/chip.c:255",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/chip.c:irq_activate_and_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011824,
      "name": "irq_startup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
</ul>
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
