# Function: <code>stop_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580026576,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:569",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init",
        "kernel/cpu.c:_cpu_down",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "mm/page_alloc.c:build_all_zonelists",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580026576,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059168,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:573",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "mm/page_alloc.c:build_all_zonelists",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059168,
      "name": "stop_machine",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580099280,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:588",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "mm/page_alloc.c:build_all_zonelists",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099280,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580105280,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:591",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105280,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157936,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:591",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157936,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217648,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:619",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217648,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580270096,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:619",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580270096,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320976,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:627",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320976,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580369792,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369792,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580443216,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:602",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443216,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580431328,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:623",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431328,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435728,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:624",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435728,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600384,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:624",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600384,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803904,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:622",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803904,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089408,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:622",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089408,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181088,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:622",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181088,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581286768,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:622",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581286768,
      "name": "stop_machine",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491633704,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpufeature.c:enable_cpu_capabilities",
        "arch/arm64/kernel/alternative.c:apply_alternatives_all",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491633704,
      "name": "stop_machine",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225586860,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ftrace.c:arch_ftrace_update_code",
        "arch/arm/mm/init.c:free_initmem",
        "arch/arm/mm/init.c:mark_rodata_ro",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225586860,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284627472,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:split_kernel_mapping",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284627472,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272030606,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272030606,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580338592,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338592,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580285760,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285760,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329840,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329840,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int stop_machine(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580384992,
      "name": "stop_machine",
      "external": true,
      "loc": "kernel/stop_machine.c:631",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_aps_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_restore",
        "kernel/time/timekeeping.c:timekeeping_notify",
        "kernel/trace/ftrace.c:arch_ftrace_update_code",
        "drivers/xen/manage.c:do_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384992,
      "name": "stop_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
