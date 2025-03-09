# Function: <code>set_cpu_possible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377424,
      "name": "set_cpu_possible",
      "external": true,
      "loc": "kernel/cpu.c:782",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel",
        "arch/x86/xen/smp.c:xen_smp_init",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377424,
      "name": "set_cpu_possible",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595150683,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:726",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_smp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595197107,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:726",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:prefill_possible_map",
        "arch/x86/kernel/smpboot.c:smp_init_package_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579191049,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:726",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595247133,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:726",
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
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595393380,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:731",
      "file": "arch/x86/xen/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp.c:xen_smp_init",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595440060,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:731",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202545,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:731",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595491277,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:731",
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
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596312594,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:774",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596360773,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:774",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200310,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:774",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596412369,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:774",
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
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602630153,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:778",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602678648,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:778",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216031,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:778",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602737100,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:778",
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
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602798801,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602850156,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228052,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602909565,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:780",
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
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604592881,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604646977,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579251748,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:792",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604707180,
      "name": "set_cpu_possible",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604688521,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:791",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604744732,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:791",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265725,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:791",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604807522,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:791",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604700956,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604758131,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267373,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604841822,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039091,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:826",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps"
      ]
    },
    {
      "addr": 18446744071609104219,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:826",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294976,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:826",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609176443,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:826",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039091,
      "name": "set_cpu_possible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591243043,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:832",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps",
        "arch/x86/xen/smp_pv.c:xen_filter_cpu_maps"
      ]
    },
    {
      "addr": 18446744071612169137,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:832",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301024,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:832",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612241877,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:832",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591243043,
      "name": "set_cpu_possible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591186546,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ]
    },
    {
      "addr": 18446744071614309649,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303888,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614382377,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186546,
      "name": "set_cpu_possible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592049601,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ]
    },
    {
      "addr": 18446744071615237453,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351616,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615315206,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:803",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049601,
      "name": "set_cpu_possible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void set_cpu_possible(unsigned int cpu, bool possible)
```

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593815937,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:829",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ]
    },
    {
      "addr": 18446744071617013276,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:829",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413536,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:829",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617096992,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:829",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593815937,
      "name": "set_cpu_possible",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627544814,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:938",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627644935,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:938",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579495734,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:938",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627757665,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:938",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619291091,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:990",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619401389,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:990",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579507885,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:990",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619518241,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:990",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621583649,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config",
        "arch/x86/xen/smp_pv.c:_get_smp_config"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621696762,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579530717,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:cpu_update_apic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621815249,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:1010",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510823304,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/arm64/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/smp.c:smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510874256,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243271080,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/arm/kernel/devtree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/devtree.c:arm_dt_init_cpu_maps"
      ],
      "caller_func": []
    },
    {
      "addr": 3243308084,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/arm/mach-imx/platsmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-imx/platsmp.c:imx_smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3243332304,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/arm/mach-omap2/omap-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mach-omap2/omap-smp.c:omap4_smp_init_cpus"
      ],
      "caller_func": []
    },
    {
      "addr": 3243360896,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302390604,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/powerpc/kernel/setup-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ],
      "caller_func": [
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps",
        "arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps"
      ]
    },
    {
      "addr": 13835058055302504092,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "kernel/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:boot_cpu_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282361224,
      "name": "set_cpu_possible.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270611618,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/riscv/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/smpboot.c:setup_smp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270616560,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604627244,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684410,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266077,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604747089,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651964,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201517,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604714706,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604705052,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604761994,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579267277,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824656,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_cpu_possible",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604705068,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/xen/smp_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/smp_pv.c:xen_smp_init",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604762251,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:prefill_possible_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579272877,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604845979,
      "name": "set_cpu_possible",
      "external": false,
      "loc": "include/linux/cpumask.h:821",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void set_cpu_possible(unsigned int cpu, bool possible)
```
</details>
</li>
</ul>
