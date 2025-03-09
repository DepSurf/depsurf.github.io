# Function: <code>topology_update_package_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int apicid, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579176800,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:262",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:smp_store_boot_cpu_info",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579176800,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int apicid, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579177248,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:266",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:smp_init_package_map",
        "arch/x86/kernel/apic/apic.c:generic_processor_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177248,
      "name": "topology_update_package_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187808,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:280",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_secondary_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187808,
      "name": "topology_update_package_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186112,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:283",
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
      "addr": 18446744071579186112,
      "name": "topology_update_package_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201904,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:295",
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
      "addr": 18446744071579201904,
      "name": "topology_update_package_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:315",
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
      "addr": 18446744071579219534,
      "name": "topology_update_package_map.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579213872,
      "name": "topology_update_package_map",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:315",
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
      "addr": 18446744071579243224,
      "name": "topology_update_package_map.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579237552,
      "name": "topology_update_package_map",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579257265,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579251936,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579258929,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579253648,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:341",
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
      "addr": 18446744071579285892,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579280800,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:336",
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
      "addr": 18446744071591258353,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579288176,
      "name": "topology_update_package_map",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:335",
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
      "addr": 18446744071591201483,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579290944,
      "name": "topology_update_package_map",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:334",
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
      "addr": 18446744071592072214,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579336016,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:330",
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
      "addr": 18446744071593838759,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579396528,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475872,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579475872,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489216,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:383",
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
      "addr": 18446744071579489216,
      "name": "topology_update_package_map",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519184,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:381",
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
      "addr": 18446744071579519184,
      "name": "topology_update_package_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579257633,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579252352,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579192822,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579187600,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579258833,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579253552,
      "name": "topology_update_package_map",
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```

```json
{
  "name": "topology_update_package_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "topology_update_package_map",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:328",
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
      "addr": 18446744071579264433,
      "name": "topology_update_package_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071579259120,
      "name": "topology_update_package_map",
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int pkg</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int apicid</code>
</li>
</ul>
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
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int topology_update_package_map(unsigned int pkg, unsigned int cpu)
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
