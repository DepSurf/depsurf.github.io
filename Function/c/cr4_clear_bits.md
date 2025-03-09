# Function: <code>cr4_clear_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867881,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079419,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595007182,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111726,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579173632,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    },
    {
      "addr": 18446744071579227818,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587364009,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:idle_task_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580613844,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022212,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:53",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579173632,
      "name": "cr4_clear_bits.constprop.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868537,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075578,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595171148,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111495,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579174176,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    },
    {
      "addr": 18446744071579228092,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313336,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174016,
      "name": "cr4_clear_bits.constprop.6",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868345,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074188,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595413500,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579110036,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184528,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    },
    {
      "addr": 18446744071579240505,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328588,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:101",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off",
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184368,
      "name": "cr4_clear_bits.constprop.6",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867655,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066044,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596334367,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579101719,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183255,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    },
    {
      "addr": 18446744071579185532,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579236619,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322226,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:106",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183104,
      "name": "cr4_clear_bits.constprop.6",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868729,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075070,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602651804,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113185,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579198914,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579201209,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579253065,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346295,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:270",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198528,
      "name": "cr4_clear_bits",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870678,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079546,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602821744,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119537,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210690,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579213089,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579264492,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358282,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:315",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210224,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870502,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084250,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604616888,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125273,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234418,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579236769,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579289099,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385278,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579234032,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578871030,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093898,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713026,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134920,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579248769,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579250177,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305482,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400727,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:305",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247360,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095882,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725371,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136840,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250929,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579251905,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309578,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249520,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108237,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609071650,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579152687,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274641,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579275996,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338520,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274288,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579108061,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612134985,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150336,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282453,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:emergency_vmx_disable_all",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579283196,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338525,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114669,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614274623,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579156682,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579284400,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579286755,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ]
    },
    {
      "addr": 18446744071579341488,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284400,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071579286048,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579341488,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081380,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139965,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615197263,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186212,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328272,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ]
    },
    {
      "addr": 18446744071579330499,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ],
      "caller_func": [
        "arch/x86/kernel/smp.c:__sysvec_reboot"
      ]
    },
    {
      "addr": 18446744071579398928,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328272,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579329776,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071579398928,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579109776,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable"
      ]
    },
    {
      "addr": 18446744071579175792,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ]
    },
    {
      "addr": 18446744071593826543,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579226496,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579388960,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ]
    },
    {
      "addr": 18446744071579390656,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579464272,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:46",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579109776,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579175792,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071593826543,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579226496,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071579388960,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579390656,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579464272,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579147440,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:47",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable"
      ]
    },
    {
      "addr": 18446744071579230320,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:47",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ]
    },
    {
      "addr": 18446744071579251072,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:47",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579284880,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:47",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579466832,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:47",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147440,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579230320,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579251072,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579284880,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579466832,
      "name": "cr4_clear_bits.constprop.0",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579148000,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:50",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable"
      ]
    },
    {
      "addr": 18446744071579236128,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:50",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ]
    },
    {
      "addr": 18446744071579257552,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:50",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579291456,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:50",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579479280,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:50",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:crash_nmi_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579148000,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579236128,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579257552,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579291456,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579479280,
      "name": "cr4_clear_bits.constprop.0",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579177280,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:51",
      "file": "arch/x86/realmode/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/realmode/init.c:load_trampoline_pgtable"
      ]
    },
    {
      "addr": 18446744071579264976,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:51",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ]
    },
    {
      "addr": 18446744071579287392,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:51",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ]
    },
    {
      "addr": 18446744071579322128,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:51",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177280,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579264976,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579287392,
      "name": "cr4_clear_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579322128,
      "name": "cr4_clear_bits",
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
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096266,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604651674,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137224,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579249633,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579250609,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305482,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248224,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028330,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604619427,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067973,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579185038,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579185876,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579239932,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183568,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095818,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729437,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136776,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579250833,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579251809,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579305482,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249424,
      "name": "cr4_clear_bits",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_clear_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579100157,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:set_tsc_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604729483,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579141896,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579256401,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/reboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart",
        "arch/x86/kernel/reboot.c:vmxoff_nmi"
      ],
      "caller_func": [
        "arch/x86/kernel/reboot.c:machine_real_restart"
      ]
    },
    {
      "addr": 18446744071579257377,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/smp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smp.c:smp_reboot_interrupt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313700,
      "name": "cr4_clear_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:323",
      "file": "arch/x86/kernel/crash.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown",
        "arch/x86/kernel/crash.c:kdump_nmi_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254992,
      "name": "cr4_clear_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
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
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cr4_clear_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cr4_clear_bits(long unsigned int mask)
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
