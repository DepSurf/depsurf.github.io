# Function: <code>alloc_bootmem_cpumask_var</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:693",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:693",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:693",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:695",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:695",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:695",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595638671,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:114",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595638671,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596732722,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:146",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596732722,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603066147,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:163",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603066147,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603240161,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:164",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603240161,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605051391,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:164",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605051391,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605169206,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605169206,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605209765,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605209765,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609297077,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609297077,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612366505,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612366505,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614507808,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614507808,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615456028,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615456028,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617256566,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup_type",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617256566,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628225520,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:82",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628225520,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619994544,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:83",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619994544,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 117
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622307280,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:84",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/sched/build_utility.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/rcu/tree.c:rcu_nocb_setup",
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622307280,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 117
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/powerpc/platforms/pseries/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/sched/isolation.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "alloc_bootmem_cpumask_var",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "kernel/irq/irqdesc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605098409,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605098409,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605066487,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup",
        "kernel/rcu/tree.c:rcu_nocb_setup",
        "kernel/time/tick-sched.c:tick_nohz_full_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605066487,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605186803,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605186803,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```

```json
{
  "name": "alloc_bootmem_cpumask_var",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605213975,
      "name": "alloc_bootmem_cpumask_var",
      "external": true,
      "loc": "lib/cpumask.c:165",
      "file": "lib/cpumask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/kernel/cpu/common.c:setup_cpu_local_masks",
        "arch/x86/mm/numa.c:setup_node_to_cpumask_map",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/sched/isolation.c:housekeeping_setup",
        "kernel/irq/irqdesc.c:irq_affinity_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605213975,
      "name": "alloc_bootmem_cpumask_var",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```
</details>
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
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void alloc_bootmem_cpumask_var(cpumask_var_t * mask)
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
