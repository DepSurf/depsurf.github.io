# Function: <code>set_cpu_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377520,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:798",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp.c:stop_self",
        "arch/x86/xen/smp.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "arch/x86/kernel/smpboot.c:cpu_disable_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377520,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579017335,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:744",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:stop_self",
        "arch/x86/xen/smp.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076128,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:744",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182957,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:744",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595247080,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:744",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579019207,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:749",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:stop_self",
        "arch/x86/xen/smp.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074551,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:749",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193468,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:749",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595491224,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:749",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579013863,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066759,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191699,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412316,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579014358,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:796",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075861,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:796",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207512,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:796",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602737047,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:796",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579017030,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:798",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081269,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:798",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218921,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:798",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602909530,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:798",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579018534,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:810",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086693,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:810",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242601,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:810",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604707138,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:810",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_online",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579026302,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:809",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096439,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:809",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:stop_this_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256580,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:809",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807481,
      "name": "set_cpu_online",
      "external": false,
      "loc": "include/linux/cpumask.h:809",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579518304,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518304,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547696,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2463",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547696,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579529392,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2474",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579529392,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579533648,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2594",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533648,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579606016,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2621",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606016,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579698944,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2643",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698944,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579824096,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2669",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824096,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579873168,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:3065",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579873168,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579911216,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:3147",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup_and_idle",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911216,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490656208,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/smp.c:local_cpu_stop",
        "arch/arm64/kernel/smp.c:__cpu_disable",
        "arch/arm64/kernel/smp.c:secondary_start_kernel",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490656208,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224732556,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/smp.c:panic_smp_self_stop",
        "arch/arm/kernel/smp.c:handle_IPI",
        "arch/arm/kernel/smp.c:secondary_start_kernel",
        "arch/arm/kernel/smp.c:__cpu_disable",
        "arch/arm/kernel/machine_kexec.c:machine_crash_nonpanic_core",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224732556,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302504012,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": [
        "arch/powerpc/kernel/smp.c:start_secondary",
        "arch/powerpc/kernel/smp.c:generic_cpu_disable",
        "arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_disable",
        "arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_disable",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283466512,
      "name": "set_cpu_online.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 13835058055283479504,
      "name": "set_cpu_online",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270616478,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": [
        "arch/riscv/kernel/smpboot.c:smp_callin",
        "arch/riscv/kernel/smp.c:riscv_software_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271401810,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491968,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491968,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579420832,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420832,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491888,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491888,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```

```json
{
  "name": "set_cpu_online",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524384,
      "name": "set_cpu_online",
      "external": true,
      "loc": "kernel/cpu.c:2332",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:stop_self",
        "arch/x86/xen/smp_pv.c:cpu_bringup",
        "arch/x86/kernel/process.c:stop_this_cpu",
        "arch/x86/kernel/smpboot.c:cpu_disable_common",
        "arch/x86/kernel/smpboot.c:start_secondary",
        "kernel/cpu.c:boot_cpu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579524384,
      "name": "set_cpu_online",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void set_cpu_online(unsigned int cpu, bool online)
```
</details>
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
