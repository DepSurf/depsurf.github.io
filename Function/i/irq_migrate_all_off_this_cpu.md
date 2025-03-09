# Function: <code>irq_migrate_all_off_this_cpu</code>

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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579821792,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:127",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821792,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857184,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:153",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857184,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 729
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891670,
      "name": "irq_migrate_all_off_this_cpu.cold.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071579890784,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938774,
      "name": "irq_migrate_all_off_this_cpu.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071579937856,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977376,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579976448,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026880,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071580025952,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580077558,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580077104,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304355,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580059232,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591247197,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580059840,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192400,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192400,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580342784,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342784,
      "name": "irq_migrate_all_off_this_cpu",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560416,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560416,
      "name": "irq_migrate_all_off_this_cpu",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633888,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633888,
      "name": "irq_migrate_all_off_this_cpu",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699040,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:155",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699040,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491229688,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:__cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491229688,
      "name": "irq_migrate_all_off_this_cpu",
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225243716,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:__cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225243716,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284132304,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/smp.c:generic_cpu_disable",
        "arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284132304,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 808
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995616,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579994688,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934282,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579933360,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987152,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071579986224,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
void irq_migrate_all_off_this_cpu()
```

```json
{
  "name": "irq_migrate_all_off_this_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "irq_migrate_all_off_this_cpu",
      "external": true,
      "loc": "kernel/irq/cpuhotplug.c:154",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/irq.c:fixup_irqs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580033863,
      "name": "irq_migrate_all_off_this_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071580032880,
      "name": "irq_migrate_all_off_this_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
void irq_migrate_all_off_this_cpu()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void irq_migrate_all_off_this_cpu()
```
</details>
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
