# Function: <code>bitmap_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579485754,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_unbound_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580460630,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407217,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:323",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503195,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536102,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586850017,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579124770,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579523866,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600106,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587040795,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:336",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579120590,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579511683,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580630353,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587168235,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:357",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579134498,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579538611,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580711393,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587673611,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:379",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579144157,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:410",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579565027,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:410",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843041,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:410",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588003195,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:410",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209663,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579602259,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912497,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588169034,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579223400,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625564,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009457,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588489148,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:411",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579225698,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651596,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064577,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588696828,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631648,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:737",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631648,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584750688,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:737",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584750688,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584778864,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:748",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584778864,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209616,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:878",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209616,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045872,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:895",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045872,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587028880,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:906",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587028880,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587284032,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:906",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_default_mask_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587284032,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587632608,
      "name": "bitmap_parse",
      "external": true,
      "loc": "lib/bitmap-str.c:473",
      "file": "lib/bitmap-str.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/trace/trace_boot.c:trace_boot_set_instance_options",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap-str.c:bitmap_parse_user",
        "net/core/sysctl_net_core.c:flow_limit_cpu_sysctl",
        "net/core/sysctl_net_core.c:rps_default_mask_sysctl",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587632608,
      "name": "bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490824420,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492422604,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502254664,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224857580,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 3226306688,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 3234999216,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283659244,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285693096,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295749736,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271497938,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272509678,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278495862,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579224546,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579627900,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033425,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303564,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579159474,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556252,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580979505,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588016380,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579225618,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579625180,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581024625,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588635388,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
  "name": "bitmap_parse",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231026,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579658828,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086641,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "kernel/padata.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/padata.c:store_cpumask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588775164,
      "name": "bitmap_parse",
      "external": false,
      "loc": "include/linux/bitmap.h:435",
      "file": "net/core/net-sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int bitmap_parse(const char * start, unsigned int buflen, long unsigned int * maskp, int nmaskbits)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
