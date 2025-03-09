# Function: <code>stop_machine_cpuslocked</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105040,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:555",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine",
        "mm/page_alloc.c:build_all_zonelists"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105040,
      "name": "stop_machine_cpuslocked",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580157696,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:555",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/main.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157696,
      "name": "stop_machine_cpuslocked",
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217408,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:583",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217408,
      "name": "stop_machine_cpuslocked",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580269856,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:583",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269856,
      "name": "stop_machine_cpuslocked",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580320736,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:591",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580320736,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580369568,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580369568,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442848,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:566",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442848,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580430960,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:587",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430960,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580435344,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:588",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580435344,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:588",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/microcode/core.c:reload_store",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162375,
      "name": "stop_machine_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580599984,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:586",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935480,
      "name": "stop_machine_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580803472,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:586",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596000658,
      "name": "stop_machine_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581088960,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:586",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596519151,
      "name": "stop_machine_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581180704,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:586",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597419501,
      "name": "stop_machine_cpuslocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581286384,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491633464,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/insn.c:aarch64_insn_patch_text",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491633464,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225586584,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/patch.c:patch_text",
        "arch/arm/probes/kprobes/core.c:arch_disarm_kprobe",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225586584,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284627072,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/mm/numa.c:numa_update_cpu_topology",
        "arch/powerpc/platforms/powernv/subcore.c:set_subcores_per_core",
        "arch/powerpc/platforms/pseries/lpar.c:pseries_lpar_resize_hpt",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284627072,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272030434,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272030434,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580338368,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580338368,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580285568,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285568,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329616,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329616,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
```

```json
{
  "name": "stop_machine_cpuslocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580384768,
      "name": "stop_machine_cpuslocked",
      "external": true,
      "loc": "kernel/stop_machine.c:595",
      "file": "kernel/stop_machine.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del_page",
        "kernel/cpu.c:takedown_cpu",
        "kernel/stop_machine.c:stop_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580384768,
      "name": "stop_machine_cpuslocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int stop_machine_cpuslocked(cpu_stop_fn_t fn, void * data, const struct cpumask * cpus)
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
