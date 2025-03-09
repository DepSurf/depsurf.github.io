# Function: <code>native_cpuid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594968610,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_check_mwait",
        "arch/x86/xen/enlighten.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595019753,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595019953,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165288,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183058,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256320,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256320,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595131528,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_check_mwait",
        "arch/x86/xen/enlighten.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579160550,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163558,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166023,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183394,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579255376,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:195",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255376,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595374198,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_check_mwait",
        "arch/x86/xen/enlighten.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579114026,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170054,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173665,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579177699,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd",
        "arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579193906,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579268896,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:210",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268896,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596300353,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106063,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579169878,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579171720,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192102,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579265504,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:203",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265504,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602618120,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119067,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184806,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189090,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579207922,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282336,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579370793,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:207",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mem_encrypt.c:sme_enable",
        "arch/x86/mm/mem_encrypt.c:sme_enable",
        "arch/x86/mm/mem_encrypt.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579282336,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071579370793,
      "name": "native_cpuid.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602786363,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127345,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579196277,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200424,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219321,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293792,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602898649,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:205",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293792,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604580444,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134017,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185685,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579189816,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579243011,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579318784,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604696033,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:194",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318784,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604675752,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579144447,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198421,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579202652,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257027,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333984,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604796113,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579333984,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604688220,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146703,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200645,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204908,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258691,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338192,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604821839,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338192,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609039108,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164854,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221557,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225858,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579285105,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367888,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071609160104,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367888,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612102514,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579162086,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216005,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579219810,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292433,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366912,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071612230702,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579366912,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614243490,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168886,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218469,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579222290,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295105,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371280,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071614371451,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:211",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371280,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615163655,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel",
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579201906,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256773,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579261100,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342225,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432496,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071615303534,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:213",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432496,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616928261,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579252239,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308213,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312940,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403285,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579501472,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071617083965,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501472,
      "name": "native_cpuid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627532034,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314040,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373957,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377967,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483861,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579598432,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071627739801,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598432,
      "name": "native_cpuid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619277282,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321181,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info",
        "arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383301,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387340,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579483552,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579611152,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071619498857,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611152,
      "name": "native_cpuid",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621569842,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579351116,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579413980,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume",
        "arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417899,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap",
        "arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob",
        "arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579513760,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:mwait_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579640928,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071621795689,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/cpuid.h:30",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640928,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604614501,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579147071,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199493,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203756,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579257395,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334096,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604735719,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334096,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578877534,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/events/amd/uncore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/uncore.c:amd_uncore_cpu_starting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604585033,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/events/amd/ibs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:amd_ibs_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586969,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/events/intel/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/core.c:intel_pmu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604595110,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/events/intel/pt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/intel/pt.c:pt_init",
        "arch/x86/events/intel/pt.c:pt_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604597065,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/platform/pvh/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/pvh/enlighten.c:xen_prepare_pvh"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604615826,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/tsc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tsc.c:tsc_init",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc",
        "arch/x86/kernel/tsc.c:native_calibrate_tsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604618302,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate",
        "arch/x86/kernel/fpu/xstate.c:check_xstate_against_struct",
        "arch/x86/kernel/fpu/xstate.c:xfeature_is_aligned"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061574,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/cacheinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_intel_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_hygon_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:init_amd_cacheinfo",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_hygon_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cacheinfo_amd_init_llc_id",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs",
        "arch/x86/kernel/cpu/cacheinfo.c:cpuid4_cache_lookup_regs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062481,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/scattered.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features",
        "arch/x86/kernel/cpu/scattered.c:init_scattered_cpuid_features"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579062828,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/topology.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology",
        "arch/x86/kernel/cpu/topology.c:detect_extended_topology_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069265,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:microcode_check",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:early_cpu_init",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:get_cpu_cap",
        "arch/x86/kernel/cpu/common.c:detect_num_cpu_cores"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076687,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:intel_detect_tlb",
        "arch/x86/kernel/cpu/intel.c:init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel",
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604625566,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel_pconfig.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_pconfig.c:intel_pconfig_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084250,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/amd.c:init_amd",
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
      "addr": 18446744071579086779,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/hygon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/hygon.c:init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:early_init_hygon",
        "arch/x86/kernel/cpu/hygon.c:bsp_init_hygon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088238,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/centaur.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur",
        "arch/x86/kernel/cpu/centaur.c:init_centaur"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089026,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/zhaoxin.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:init_zhaoxin",
        "arch/x86/kernel/cpu/zhaoxin.c:early_init_zhaoxin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579094817,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604628567,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/mtrr/mtrr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init",
        "arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_bp_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134485,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:save_microcode_in_initrd",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138706,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141145,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/amd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604637311,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604640040,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_platform",
        "arch/x86/kernel/cpu/vmware.c:vmware_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604640538,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/mshyperv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform",
        "arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_platform"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604641328,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/acrn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/acrn.c:acrn_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183381,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/acpi/cstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184996,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185815,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579192589,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239715,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579262522,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/amd_nb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604674002,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_setup_pv_tlb_flush",
        "arch/x86/kernel/kvm.c:kvm_apic_init",
        "arch/x86/kernel/kvm.c:__kvm_cpuid_base",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_guest_init",
        "arch/x86/kernel/kvm.c:kvm_cpu_down_prepare",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_pv_guest_cpu_reboot",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_guest_cpu_init",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init",
        "arch/x86/kernel/kvm.c:kvm_spinlock_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270378,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/jailhouse.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604703340,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604900950,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "drivers/idle/intel_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init",
        "drivers/idle/intel_idle.c:intel_idle_cpuidle_driver_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587459437,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "drivers/cpufreq/powernow-k8.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/powernow-k8.c:find_psb_table"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604692316,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579146623,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200565,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204828,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258595,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334016,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604813286,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334016,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```

```json
{
  "name": "native_cpuid",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604692272,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait",
        "arch/x86/xen/enlighten_pv.c:xen_check_mwait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151759,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579205845,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp",
        "arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210108,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264195,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342368,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604825996,
      "name": "native_cpuid",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:197",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342368,
      "name": "native_cpuid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
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
void native_cpuid(unsigned int * eax, unsigned int * ebx, unsigned int * ecx, unsigned int * edx)
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
