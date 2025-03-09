# Function: <code>irq_set_affinity_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746448,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:210",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746448,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768736,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:223",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768736,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795712,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:223",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795712,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792736,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:197",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792736,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826384,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:214",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826384,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579860160,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:247",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579860160,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579907088,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:247",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907088,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942400,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942400,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992576,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992576,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580039712,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:347",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580039712,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580022896,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:347",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022896,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580023600,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:347",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580023600,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580155856,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:340",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_set_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580155856,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 493
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580301520,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:355",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580301520,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580513696,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:347",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580513696,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 529
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:350",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596507182,
      "name": "irq_set_affinity_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580586304,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:352",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_apply_affinity_hint",
        "kernel/irq/manage.c:irq_force_affinity",
        "kernel/irq/manage.c:irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597404847,
      "name": "irq_set_affinity_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071580650656,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491182688,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu",
        "drivers/irqchip/irq-bcm7038-l1.c:bcm7038_l1_cpu_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491182688,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225205996,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225205996,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284084560,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284084560,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271730770,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271730770,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961312,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961312,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899152,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899152,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952848,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952848,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
int irq_set_affinity_locked(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_set_affinity_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999232,
      "name": "irq_set_affinity_locked",
      "external": true,
      "loc": "kernel/irq/manage.c:274",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:__irq_set_affinity",
        "kernel/irq/cpuhotplug.c:irq_affinity_online_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999232,
      "name": "irq_set_affinity_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
