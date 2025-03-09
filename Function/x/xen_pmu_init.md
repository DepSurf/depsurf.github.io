# Function: <code>xen_pmu_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579002192,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:512",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    },
    {
      "addr": 18446744071595250598,
      "name": "xen_pmu_init",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:483",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579002192,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578999280,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:512",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp.c:xen_cpu_up"
      ]
    },
    {
      "addr": 18446744071595432246,
      "name": "xen_pmu_init",
      "external": false,
      "loc": "drivers/xen/sys-hypervisor.c:458",
      "file": "drivers/xen/sys-hypervisor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999280,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579001104,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:512",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp.c:xen_cpu_up",
        "arch/x86/xen/smp.c:xen_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001104,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578962544,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:512",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578962544,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578965792,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:513",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578965792,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:513",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578969196,
      "name": "xen_pmu_init.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578968240,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_up",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967292,
      "name": "xen_pmu_init.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578966320,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 610
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578974368,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578973392,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976768,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578975792,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986577,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578985808,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242497,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578987568,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185567,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071578996352,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 618
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592047652,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071579013872,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 733
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:511",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814103,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071579032544,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 852
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:524",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595956710,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579062176,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 889
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:524",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596474066,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579062048,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 889
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:524",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597369407,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071579087136,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 889
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977120,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578976144,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578976704,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578975728,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
void xen_pmu_init(int cpu)
```

```json
{
  "name": "xen_pmu_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xen_pmu_init",
      "external": true,
      "loc": "arch/x86/xen/pmu.c:520",
      "file": "arch/x86/xen/pmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/suspend.c:xen_arch_resume",
        "arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578977296,
      "name": "xen_pmu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071578976320,
      "name": "xen_pmu_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 612
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void xen_pmu_init(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void xen_pmu_init(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void xen_pmu_init(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void xen_pmu_init(int cpu)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void xen_pmu_init(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
