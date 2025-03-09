# Function: <code>smp_call_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579909632,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:488",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/xen/smp.c:xen_stop_other_cpus",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "kernel/trace/ftrace.c:ftrace_modify_all_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579909632,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939404,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:472",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_stop_other_cpus",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc",
        "kernel/trace/ftrace.c:ftrace_modify_all_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939344,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579970700,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:476",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_stop_other_cpus",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc",
        "kernel/trace/ftrace.c:ftrace_modify_all_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970544,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579976092,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:487",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_unregfunc",
        "arch/x86/kernel/tracepoint.c:trace_irq_vector_regfunc",
        "kernel/trace/ftrace.c:ftrace_modify_all_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975936,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580022543,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:489",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/memory.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022384,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580076607,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:489",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/memory.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076448,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580123919,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:489",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123760,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580169327,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580169264,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580217263,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217200,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285551,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:596",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285200,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580269071,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:734",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268720,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273103,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:1010",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580273008,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425087,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:1012",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580424992,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648031,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:1031",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647824,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915039,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:1030",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914800,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000671,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:878",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581000432,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581096815,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:898",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096576,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491456140,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table",
        "drivers/tty/sysrq.c:sysrq_showregs_othercpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491455920,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225442300,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger",
        "kernel/trace/ftrace.c:ftrace_modify_all_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225442140,
      "name": "smp_call_function",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284407008,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/powerpc/kernel/dawr.c:dawr_write_file_bool",
        "arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284406720,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271911936,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "drivers/tty/sysrq.c:sysrq_showregs_othercpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271911762,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580186063,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580186000,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580133631,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580133488,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580177535,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu"
      ],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580177472,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void smp_call_function(smp_call_func_t func, void * info, int wait)
```

```json
{
  "name": "smp_call_function",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580229664,
      "name": "smp_call_function",
      "external": true,
      "loc": "kernel/smp.c:506",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_stop_other_cpus",
        "kernel/smp.c:kick_all_cpus_sync",
        "kernel/smp.c:on_each_cpu",
        "kernel/trace/ftrace.c:ftrace_modify_all_code",
        "mm/mmu_gather.c:tlb_remove_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580229664,
      "name": "smp_call_function",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
