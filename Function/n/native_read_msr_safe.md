# Function: <code>native_read_msr_safe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578958981,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:68",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001132,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:68",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255952,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:68",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255952,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578956039,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998748,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256592,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256592,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578957879,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000572,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270128,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:96",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270128,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578961963,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:122",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970530,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:122",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579266768,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:122",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266768,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965195,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:123",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976754,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:123",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283456,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:123",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283456,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578967740,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978930,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294864,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294864,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578965680,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578974578,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579319552,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319552,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578972862,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578981587,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334768,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334768,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975262,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983971,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338976,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338976,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578985230,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994451,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368688,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368688,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578986990,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996371,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367696,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367696,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578995851,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005011,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371920,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371920,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579013320,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579022579,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433184,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:135",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433184,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579031880,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041110,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579502160,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502160,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061432,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070506,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599520,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599520,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579061304,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070330,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612208,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612208,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579086392,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095546,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579641920,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:126",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641920,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975614,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984323,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334880,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334880,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578873701,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events",
        "arch/x86/events/core.c:init_hw_perf_events"
      ]
    },
    {
      "addr": 18446744071578874224,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/events/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578900385,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/events/intel/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578972969,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079014,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085131,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086360,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579092670,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579103433,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/mce/severity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/severity.c:mce_severity_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106866,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111492,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604634254,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:amd_special_default_mtrr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579181867,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/acpi/sleep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/sleep.c:x86_acpi_suspend_lowlevel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202237,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604662841,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/vector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/vector.c:print_local_APIC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604666263,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/io_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/io_apic.c:check_timer"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222412,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/msi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579225909,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579228022,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_acpi_madt_oem_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270558,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584373267,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_safe_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584375397,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/lib/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584921455,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/acpi/acpi_lpit.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585074335,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/acpi/processor_throttling.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_ptc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585694642,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/iommu/amd_iommu_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu_init.c:iommu_update_intcapxt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585755029,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/iommu/intel_irq_remapping.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel_irq_remapping.c:dmar_ir_hotplug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587404675,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/edac/mce_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/edac/mce_amd.c:amd_decode_mce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587474913,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587536462,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/platform/x86/intel_pmc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_resume",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_suspend",
        "drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587541292,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "drivers/platform/x86/intel_turbo_max_3.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605030385,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/pci/mmconfig-shared.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/mmconfig-shared.c:pci_mmcfg_amd_fam10h"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640897,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873701,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071578900385,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975198,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983907,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334800,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334800,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```

```json
{
  "name": "native_read_msr_safe",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578975790,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:xen_read_pmc",
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984499,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_read_msr_safe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579343152,
      "name": "native_read_msr_safe",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:137",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343152,
      "name": "native_read_msr_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long long unsigned int native_read_msr_safe(unsigned int msr, int * err)
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
