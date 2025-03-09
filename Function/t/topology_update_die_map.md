# Function: <code>topology_update_die_map</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257290,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579252032,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258954,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579253744,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:364",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:validate_apic_and_package_id",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285917,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579280896,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:359",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:validate_apic_and_package_id",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258378,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579288272,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:358",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201508,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579291040,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:357",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592072239,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579336144,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:353",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593838784,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579396672,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476048,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476048,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489392,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:406",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489392,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519456,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:406",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_prepare_cpus_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519456,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 583
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257658,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579252448,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192847,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579187696,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258858,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579253648,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int topology_update_die_map(unsigned int die, unsigned int cpu)
```

```json
{
  "name": "topology_update_die_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_die_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:351",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu",
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264458,
      "name": "topology_update_die_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579259216,
      "name": "topology_update_die_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int topology_update_die_map(unsigned int die, unsigned int cpu)
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
