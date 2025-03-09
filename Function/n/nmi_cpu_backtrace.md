# Function: <code>nmi_cpu_backtrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964464,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:148",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_all_cpu_backtrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964464,
      "name": "nmi_cpu_backtrace",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583251760,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:75",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:arch_trigger_all_cpu_backtrace_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583251760,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367040,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:86",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367040,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216048,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:87",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216048,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766000,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766000,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145187,
      "name": "nmi_cpu_backtrace.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071589144848,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380323,
      "name": "nmi_cpu_backtrace.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071589379984,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837370,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071589837040,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063514,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071590063184,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060411,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071585060080,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:92",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382033,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585209504,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:92",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324468,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585092480,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:92",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592342561,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071585540016,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:92",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594204121,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071586694640,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:92",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373499,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071595855936,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:94",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596903170,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071596372816,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:94",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597828226,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    },
    {
      "addr": 18446744071597266176,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236459456,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:handle_IPI",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236459456,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297691552,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297691552,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665770,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071589665440,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391594,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071589391264,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109146,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071590108816,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
```

```json
{
  "name": "nmi_cpu_backtrace",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nmi_cpu_backtrace",
      "external": true,
      "loc": "lib/nmi_backtrace.c:88",
      "file": "lib/nmi_backtrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/hw_nmi.c:nmi_cpu_backtrace_handler",
        "lib/nmi_backtrace.c:nmi_trigger_cpumask_backtrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159480,
      "name": "nmi_cpu_backtrace.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071590159120,
      "name": "nmi_cpu_backtrace",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
bool nmi_cpu_backtrace(struct pt_regs * regs)
```
</details>
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
bool nmi_cpu_backtrace(struct pt_regs * regs)
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
