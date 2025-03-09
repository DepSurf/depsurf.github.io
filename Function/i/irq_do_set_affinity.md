# Function: <code>irq_do_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579746080,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:190",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/migration.c:irq_move_masked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746080,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579768368,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:203",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/migration.c:irq_move_masked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579768368,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579795344,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:203",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/migration.c:irq_move_masked_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579795344,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579792608,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:177",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792608,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826160,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:190",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826160,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:190",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864799,
      "name": "irq_do_set_affinity.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579859936,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:190",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911807,
      "name": "irq_do_set_affinity.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579906864,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579948882,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579942176,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998932,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579992352,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:227",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047870,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580039296,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:227",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302966,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580022480,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:227",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245809,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580023184,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:220",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592138362,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071580155424,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:220",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593909146,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071580300960,
      "name": "irq_do_set_affinity",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:212",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595989334,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580513088,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:215",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596507134,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580585680,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:217",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:migrate_one_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597404799,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071580650032,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491182464,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491182464,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225205816,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225205816,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284084304,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284084304,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271730576,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271730576,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967668,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579961088,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905508,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579898928,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959204,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579952624,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int irq_do_set_affinity(struct irq_data * data, const struct cpumask * mask, bool force)
```

```json
{
  "name": "irq_do_set_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_do_set_affinity",
      "external": true,
      "loc": "kernel/irq/manage.c:216",
      "file": "kernel/irq/manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/manage.c:irq_setup_affinity",
        "kernel/irq/manage.c:irq_set_affinity_locked",
        "kernel/irq/chip.c:irq_startup",
        "kernel/irq/migration.c:irq_move_masked_irq",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu",
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005652,
      "name": "irq_do_set_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579999008,
      "name": "irq_do_set_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
