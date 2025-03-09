# Function: <code>native_write_msr_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int native_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958818,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001407,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255826,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255984,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:91",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255984,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int native_write_msr_safe(unsigned int msr, unsigned int low, unsigned int high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578955908,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:130",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998394,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:130",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write",
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254932,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:130",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256528,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:130",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256528,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957748,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:144",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000218,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:144",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write",
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268500,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:144",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270064,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:144",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270064,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961711,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:155",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970308,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:155",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265124,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:155",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266704,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:155",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266704,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578964943,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:156",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973556,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:156",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281972,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:156",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283392,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:156",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283392,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967388,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976378,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293463,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_register_clock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294816,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294816,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965462,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974458,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319504,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319504,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972501,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981465,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334720,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334720,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578974901,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983849,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338928,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338928,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578984901,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994329,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368640,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368640,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578986661,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996249,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367648,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367648,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578995493,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004889,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371872,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371872,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579012965,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022457,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433136,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:168",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433136,
      "name": "native_write_msr_safe",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579031613,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579040956,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502080,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502080,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061074,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075882,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599424,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599424,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060946,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075525,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612112,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612112,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579086034,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579100981,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_write_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641824,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:153",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641824,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975253,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984201,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334832,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334832,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604582548,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:init_hw_perf_events"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578897789,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578914790,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_enable_event",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578923456,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_enable_event",
        "arch/x86/events/intel/p4.c:p4_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578925139,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_event",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067419,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init",
        "arch/x86/kernel/cpu/common.c:syscall_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085183,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107074,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579116819,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129845,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604638471,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182103,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372985,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__wrmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584375437,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585073444,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_set_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541221,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578900338,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071578921664,
      "name": "native_write_msr_safe.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578974837,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983785,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334752,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334752,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```

```json
{
  "name": "native_write_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975429,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984377,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_write_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343104,
      "name": "native_write_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:170",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343104,
      "name": "native_write_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<b>Param type changed. </b>
<code>unsigned int low</code> ➡️ <code>u32 low</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int high</code> ➡️ <code>u32 high</code>
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
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int native_write_msr_safe(unsigned int msr, u32 low, u32 high)
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
