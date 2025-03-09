# Function: <code>cpu_smt_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579176432,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579519104,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176432,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579519104,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579176864,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579533216,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176864,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071579533216,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579187280,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595502172,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579655373,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187280,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579557760,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185584,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596421924,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579629725,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676416,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185584,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579676416,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579201312,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602746320,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_init_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660454,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579706976,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201312,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579706976,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579213200,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579640265,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579692966,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579739968,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213200,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579739968,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236880,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579678176,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731222,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779728,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:198",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236880,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071579779728,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250272,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:204",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579710959,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:204",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579760568,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:204",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579807408,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:204",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250272,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579807408,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579251984,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579753311,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803224,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579854928,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251984,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579854928,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579277008,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579788063,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803185,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_smt",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579894256,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277008,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579894256,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579284144,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579779386,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579795415,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_smt",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579888976,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:202",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284144,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579888976,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579286832,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579787538,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812790,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579898160,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579286832,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579898160,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579330576,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579882334,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_starting",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:sched_core_unlock",
        "kernel/sched/core.c:sched_core_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579905210,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013264,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:203",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330576,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071580013264,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579391552,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579999569,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_starting",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:sched_core_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580017142,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580203765,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801566,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_core_cpuslocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391552,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071580136832,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579470208,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580161687,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:sched_core_unlock",
        "kernel/sched/core.c:sched_core_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185860,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580394917,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086878,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_core_cpuslocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470208,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071580311280,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579482928,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580209963,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:sched_core_unlock",
        "kernel/sched/core.c:sched_core_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580251030,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:sched_use_asym_prio",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580463365,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__sched_core_account_forceidle"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178350,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_core_cpuslocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482928,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071580377952,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579513008,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621818632,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:cpus_share_smt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258283,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:sched_core_cpu_deactivate",
        "kernel/sched/core.c:sched_core_cpu_starting",
        "kernel/sched/core.c:pick_next_task",
        "kernel/sched/core.c:__sched_core_flip",
        "kernel/sched/core.c:sched_core_unlock",
        "kernel/sched/core.c:sched_core_lock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580299537,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:should_we_balance",
        "kernel/sched/fair.c:find_idlest_group",
        "kernel/sched/fair.c:sched_use_asym_prio",
        "kernel/sched/fair.c:task_hot",
        "kernel/sched/fair.c:select_idle_sibling",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:select_idle_core",
        "kernel/sched/fair.c:__update_idle_core",
        "kernel/sched/fair.c:find_idlest_group_cpu",
        "kernel/sched/fair.c:update_numa_stats"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580523061,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:__sched_core_account_forceidle",
        "kernel/sched/build_utility.c:init_sched_groups_capacity"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284030,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:237",
      "file": "kernel/stop_machine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stop_machine.c:stop_core_cpuslocked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513008,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071580435904,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336490983448,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491051480,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491051480,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282507184,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/powerpc/kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055283786136,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283851356,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283928128,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282507184,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 13835058055283928128,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250688,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579729231,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579779000,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827280,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250688,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579827280,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579185936,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579657839,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579709800,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579761856,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185936,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579761856,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579251888,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579714879,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579763592,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579815296,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579251888,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579815296,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```

```json
{
  "name": "cpu_smt_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579257456,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579760975,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sched_cpu_deactivate",
        "kernel/sched/core.c:sched_cpu_activate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579811597,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:__update_idle_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579860416,
      "name": "cpu_smt_mask",
      "external": false,
      "loc": "include/linux/topology.h:219",
      "file": "kernel/sched/topology.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257456,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579860416,
      "name": "cpu_smt_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct cpumask * cpu_smt_mask(int cpu)
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
