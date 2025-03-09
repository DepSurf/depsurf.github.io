# Function: <code>cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579376080,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:537",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376080,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579388208,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1018",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579388208,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579408576,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:976",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579408576,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393408,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:888",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393408,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421344,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1072",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421344,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436112,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1162",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436112,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579472352,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1179",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472352,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490144,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1191",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490144,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516064,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516064,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579544723,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1249",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544640,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071579547752,
      "name": "cpu_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579526435,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1253",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579526352,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071591277785,
      "name": "cpu_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579530643,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1357",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:write_cpuhp_target",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579530560,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071591220683,
      "name": "cpu_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579602837,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1383",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602736,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    },
    {
      "addr": 18446744071592099575,
      "name": "cpu_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695341,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1395",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579695232,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071593867110,
      "name": "cpu_up.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579819056,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1419",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:bringup_nonboot_cpus",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819056,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579868448,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1701",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_bringup_mask",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868448,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int cpu_up(unsigned int cpu, enum cpuhp_state target)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579906352,
      "name": "cpu_up",
      "external": false,
      "loc": "kernel/cpu.c:1739",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:target_store",
        "kernel/cpu.c:cpuhp_bringup_mask",
        "kernel/cpu.c:bringup_hibernate_cpu",
        "kernel/cpu.c:cpu_device_up"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579906352,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490653320,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490653320,
      "name": "cpu_up",
      "section": ".text",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224729892,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224729892,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283475744,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283475744,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271400460,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:smp_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271400460,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489728,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489728,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418592,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418592,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579489648,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579489648,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int cpu_up(unsigned int cpu)
```

```json
{
  "name": "cpu_up",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579522032,
      "name": "cpu_up",
      "external": true,
      "loc": "kernel/cpu.c:1206",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:disable_mmiotrace",
        "kernel/smp.c:smp_init",
        "drivers/base/cpu.c:cpu_subsys_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522032,
      "name": "cpu_up",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state target</code>
</li>
</ul>
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
