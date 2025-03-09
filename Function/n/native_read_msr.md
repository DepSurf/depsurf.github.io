# Function: <code>native_read_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579161887,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:60",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165502,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:60",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579163957,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165828,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256656,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256656,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114035,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173674,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177142,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:check_current_patch_level",
        "arch/x86/kernel/cpu/microcode/amd.c:__apply_microcode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270192,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:83",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270192,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266832,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:110",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266832,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579283520,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:111",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579283520,
      "name": "native_read_msr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294928,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294928,
      "name": "native_read_msr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579319616,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319616,
      "name": "native_read_msr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334848,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334848,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339056,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339056,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368768,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368768,
      "name": "native_read_msr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367776,
      "name": "native_read_msr",
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
      "addr": 18446744071579367776,
      "name": "native_read_msr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372000,
      "name": "native_read_msr",
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
      "addr": 18446744071579372000,
      "name": "native_read_msr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433264,
      "name": "native_read_msr",
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
      "addr": 18446744071579433264,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502256,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502256,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060895,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070591,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579599632,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599632,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579060767,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070415,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612320,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612320,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085855,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/pmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/pmu.c:pmu_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095631,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_do_read_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169763,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_snp_boot_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642032,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:114",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579642032,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334960,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334960,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868096,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:x86_pmu_disable_all"
      ],
      "caller_func": [
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug",
        "arch/x86/events/core.c:perf_event_print_debug"
      ]
    },
    {
      "addr": 18446744071578875739,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/amd/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/core.c:amd_pmu_wait_on_overflow"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604585087,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_handle_irq",
        "arch/x86/events/amd/ibs.c:perf_ibs_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578886810,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/msr.c:msr_event_start",
        "arch/x86/events/msr.c:msr_event_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578894971,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_cpu_dying",
        "arch/x86/events/intel/core.c:intel_pmu_cpu_starting",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_handle_irq_v4",
        "arch/x86/events/intel/core.c:intel_pmu_enable_event",
        "arch/x86/events/intel/core.c:intel_pmu_disable_event"
      ],
      "caller_func": [
        "arch/x86/events/intel/core.c:intel_pmu_init",
        "arch/x86/events/intel/core.c:intel_pmu_reset",
        "arch/x86/events/intel/core.c:intel_pmu_reset"
      ]
    },
    {
      "addr": 18446744071578912318,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/ds.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/ds.c:intel_pmu_disable_bts",
        "arch/x86/events/intel/ds.c:intel_pmu_enable_bts"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578915161,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/knc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_handle_irq",
        "arch/x86/events/intel/knc.c:knc_pmu_enable_all",
        "arch/x86/events/intel/knc.c:knc_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578919561,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/lbr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_read",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_disable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task",
        "arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578921836,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/p4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq",
        "arch/x86/events/intel/p4.c:p4_pmu_handle_irq"
      ],
      "caller_func": [
        "arch/x86/events/intel/p4.c:p4_pmu_init"
      ]
    },
    {
      "addr": 18446744071578925301,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/p6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/p6.c:p6_pmu_enable_all",
        "arch/x86/events/intel/p6.c:p6_pmu_disable_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578930661,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_read_offset",
        "arch/x86/events/intel/pt.c:pt_handle_status"
      ],
      "caller_func": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ]
    },
    {
      "addr": 18446744071578939170,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore.c:uncore_msr_read_counter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578948032,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/uncore_nhmex.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578951158,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/uncore_snb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snb.c:icl_uncore_cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578958880,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/events/intel/uncore_snbep.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box",
        "arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578964453,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hyperv_stop_tsc_emulation",
        "arch/x86/hyperv/hv_init.c:hv_reenlightenment_notify",
        "arch/x86/hyperv/hv_init.c:hv_cpu_init"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    },
    {
      "addr": 18446744071578972533,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/hyperv/hv_apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_apic.c:hv_apic_icr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973177,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/hyperv/hv_spinlock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604599079,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:init_real_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973248,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/process_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs",
        "arch/x86/kernel/process_64.c:__show_regs"
      ]
    },
    {
      "addr": 18446744071604615851,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579026413,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/tsc_msr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr",
        "arch/x86/kernel/tsc_msr.c:cpu_khz_from_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579029475,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": [
        "arch/x86/kernel/process.c:arch_post_acpi_subsys_init"
      ]
    },
    {
      "addr": 18446744071579053845,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/step.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/step.c:set_task_blockstep"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066079,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604623313,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:check_bugs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073877,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/aperfmperf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz",
        "arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_snapshot_khz"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604625355,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/umwait.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/umwait.c:umwait_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079835,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080837,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/tsx.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/tsx.c:tsx_enable",
        "arch/x86/kernel/cpu/tsx.c:tsx_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579081592,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/intel_epb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_offline",
        "arch/x86/kernel/cpu/intel_epb.c:intel_epb_restore"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579083122,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:cpu_has_amd_erratum",
        "arch/x86/kernel/cpu/amd.c:init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:early_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd",
        "arch/x86/kernel/cpu/amd.c:bsp_init_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087163,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088400,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ]
    },
    {
      "addr": 18446744071579089194,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin"
      ]
    },
    {
      "addr": 18446744071579100473,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_cpu_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup",
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579107206,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mce/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_clear",
        "arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init",
        "arch/x86/kernel/cpu/mce/intel.c:__cmci_disable_bank",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_discover",
        "arch/x86/kernel/cpu/mce/intel.c:cmci_toggle_interrupt_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111572,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mce/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:log_and_reset_block",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:amd_deferred_error_interrupt",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:__log_error",
        "arch/x86/kernel/cpu/mce/amd.c:disable_err_thresholding",
        "arch/x86/kernel/cpu/mce/amd.c:threshold_restart_bank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579117721,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mce/therm_throt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_init_thermal",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt",
        "arch/x86/kernel/cpu/mce/therm_throt.c:intel_thermal_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604628751,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129029,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_have_wrcomb",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_set_all",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr",
        "arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state",
        "arch/x86/kernel/cpu/mtrr/generic.c:get_mtrr_state"
      ]
    },
    {
      "addr": 18446744071579131818,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mtrr/cleanup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_trim_uncached_memory",
        "arch/x86/kernel/cpu/mtrr/cleanup.c:mtrr_cleanup"
      ]
    },
    {
      "addr": 18446744071579135900,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143384,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604638527,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163947,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/resctrl/monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_update",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count",
        "arch/x86/kernel/cpu/resctrl/monitor.c:free_rmid",
        "arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579179957,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:hv_get_tsc_khz"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform"
      ]
    },
    {
      "addr": 18446744071579194233,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/tsc_sync.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust",
        "arch/x86/kernel/tsc_sync.c:tsc_verify_tsc_adjust"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198005,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:__x2apic_enable"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic.c:setup_nox2apic"
      ]
    },
    {
      "addr": 18446744071579224547,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:fixup_cpu_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip2_get_apic_id",
        "arch/x86/kernel/apic/apic_numachip.c:numachip1_get_apic_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579226016,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_phys.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228176,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_cluster.c:native_x2apic_icr_read",
        "arch/x86/kernel/apic/x2apic_cluster.c:native_apic_msr_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239877,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579245839,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:resume_execution"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262759,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/amd_nb.c:amd_get_mmconfig_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287151,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/mmconf-fam10h_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/mmconf-fam10h_64.c:fam10h_check_enable_mmcfg",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321070,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/mm/pat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat.c:pat_init",
        "arch/x86/mm/pat.c:init_cache_modes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180570,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "kernel/kexec_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_core.c:crash_save_cpu",
        "kernel/kexec_core.c:crash_save_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584372112,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/lib/msr-smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr-smp.c:__rdmsr_on_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584816164,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_cpu_online",
        "drivers/idle/intel_idle.c:intel_idle_cpu_online"
      ],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ]
    },
    {
      "addr": 18446744071585080169,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/acpi/processor_perflib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587453253,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/cpufreq/acpi-cpufreq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_amd",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_write_intel",
        "drivers/cpufreq/acpi-cpufreq.c:cpu_freq_read_intel",
        "drivers/cpufreq/acpi-cpufreq.c:boost_set_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587461957,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init_on_cpu",
        "drivers/cpufreq/powernow-k8.c:powernowk8_target_fn",
        "drivers/cpufreq/powernow-k8.c:transition_frequency_fidvid"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/cpufreq/speedstep-centrino.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071605001345,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/cpufreq/intel_pstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_fast_switch",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_target",
        "drivers/cpufreq/intel_pstate.c:intel_cpufreq_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_verify_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_set_policy",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_util",
        "drivers/cpufreq/intel_pstate.c:knl_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:core_get_max_pstate_physical",
        "drivers/cpufreq/intel_pstate.c:core_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:atom_get_vid",
        "drivers/cpufreq/intel_pstate.c:airmont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:silvermont_get_scaling",
        "drivers/cpufreq/intel_pstate.c:atom_get_turbo_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_max_pstate",
        "drivers/cpufreq/intel_pstate.c:atom_get_min_pstate",
        "drivers/cpufreq/intel_pstate.c:store_no_turbo",
        "drivers/cpufreq/intel_pstate.c:show_no_turbo",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605020010,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "drivers/clocksource/hyperv_timer.c:read_hv_sched_clock_msr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605022316,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/hv/vmbus_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/vmbus_drv.c:hv_acpi_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587560277,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "drivers/hv/hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_disable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs",
        "drivers/hv/hv.c:hv_synic_enable_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587640309,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/pci/amd_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/pci/amd_bus.c:amd_bus_cpu_online"
      ],
      "caller_func": [
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    },
    {
      "addr": 18446744071587640734,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state",
        "arch/x86/power/cpu.c:save_processor_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589452084,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862000,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578889920,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578921600,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578933051,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071578964016,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071578973248,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579027584,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579063552,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579088080,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579088864,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579128448,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579131818,
      "name": "native_read_msr.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071579179824,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579195920,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071584815760,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587640240,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579334880,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334880,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
long long unsigned int native_read_msr(unsigned int msr)
```

```json
{
  "name": "native_read_msr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343232,
      "name": "native_read_msr",
      "external": false,
      "loc": "arch/x86/include/asm/msr.h:125",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343232,
      "name": "native_read_msr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```
</details>
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
long long unsigned int native_read_msr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long long unsigned int native_read_msr(unsigned int msr)
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
