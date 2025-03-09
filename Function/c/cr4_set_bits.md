# Function: <code>cr4_set_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867858,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578963382,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579079261,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC",
        "arch/x86/kernel/process.c:__switch_to_xtra"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080933,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088725,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110940,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128946,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358363,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071587363986,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
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
      "addr": 18446744071580613821,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022189,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358363,
      "name": "cr4_set_bits",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868514,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578959830,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579075677,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076822,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087096,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579110715,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129133,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579365240,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579313313,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
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
      "addr": 18446744071579365240,
      "name": "cr4_set_bits",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868322,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578961894,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579074274,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:__switch_to_xtra",
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579075318,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085272,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579109224,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136317,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579383336,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579328565,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:88",
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
      "addr": 18446744071579383336,
      "name": "cr4_set_bits",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578867632,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065910,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067606,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076856,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579100915,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134413,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579285815,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579322203,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:93",
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
      "addr": 18446744071579285815,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578868689,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074909,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076746,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579085315,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579112179,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149342,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579304390,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579346255,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:258",
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
      "addr": 18446744071579304390,
      "name": "cr4_set_bits",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870625,
      "name": "cr4_set_bits",
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
      "addr": 18446744071579079374,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579082165,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090691,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579118631,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159245,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579316423,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:303",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579357882,
      "name": "cr4_set_bits",
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
      "addr": 18446744071579316423,
      "name": "cr4_set_bits",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870449,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084078,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087573,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579096003,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579124370,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148717,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579341153,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579385192,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:291",
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
      "addr": 18446744071579341153,
      "name": "cr4_set_bits",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870977,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/events/core.c:refresh_pce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579093735,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097349,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579106419,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579133978,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161389,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356513,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    },
    {
      "addr": 18446744071579400645,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:293",
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
      "addr": 18446744071579356513,
      "name": "cr4_set_bits",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095719,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099333,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108243,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579135866,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163853,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579360769,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360769,
      "name": "cr4_set_bits",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108071,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111861,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121385,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151794,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579186093,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579387137,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:cr4_set_bits_and_update_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387137,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579107895,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579111557,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579121397,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579148976,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182285,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591266170,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:cr4_set_bits_and_update_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266170,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579114503,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118197,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579127621,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:fpu__init_cpu_xstate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151776,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579188610,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591208478,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:cr4_set_bits_and_update_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579151776,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071591208478,
      "name": "cr4_set_bits",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579139799,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579143653,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579153678,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579180592,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579223521,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592082077,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:cr4_set_bits_and_update_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180592,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071592082077,
      "name": "cr4_set_bits",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579175856,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:disable_TSC"
      ]
    },
    {
      "addr": 18446744071579181472,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579194976,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226560,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579269696,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593849599,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:36",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:cr4_set_bits_and_update_boot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175856,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579181472,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579194976,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071579226560,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579269696,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071593849599,
      "name": "cr4_set_bits",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579230400,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:disable_TSC"
      ]
    },
    {
      "addr": 18446744071579236752,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579251152,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579284976,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579332512,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579634768,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:37",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579230400,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579236752,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579251152,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579284976,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579332512,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579634768,
      "name": "cr4_set_bits",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236208,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:disable_TSC"
      ]
    },
    {
      "addr": 18446744071579242720,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579257632,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579291552,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579341232,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579648816,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:40",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236208,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579242720,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579257632,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579291552,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071579341232,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579648816,
      "name": "cr4_set_bits",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265056,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:disable_TSC"
      ]
    },
    {
      "addr": 18446744071579271664,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    },
    {
      "addr": 18446744071579287472,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579321872,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ]
    },
    {
      "addr": 18446744071579371360,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579682688,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:41",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:probe_page_size_mask",
        "arch/x86/mm/init.c:probe_page_size_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265056,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579271664,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579287472,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579321872,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071579371360,
      "name": "cr4_set_bits.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579682688,
      "name": "cr4_set_bits",
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
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096103,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099717,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108627,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579136250,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579164205,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356673,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356673,
      "name": "cr4_set_bits",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579028183,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579032165,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579041043,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579066816,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095773,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579288945,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288945,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579095655,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579099269,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579108179,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579135802,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163773,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356593,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356593,
      "name": "cr4_set_bits",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void cr4_set_bits(long unsigned int mask)
```

```json
{
  "name": "cr4_set_bits",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579099966,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/process.c:disable_TSC"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579103749,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113251,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579140922,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu",
        "arch/x86/kernel/cpu/common.c:identify_cpu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579168957,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579365041,
      "name": "cr4_set_bits",
      "external": false,
      "loc": "arch/x86/include/asm/tlbflush.h:313",
      "file": "arch/x86/mm/init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping",
        "arch/x86/mm/init.c:init_mem_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365041,
      "name": "cr4_set_bits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void cr4_set_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cr4_set_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cr4_set_bits(long unsigned int mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cr4_set_bits(long unsigned int mask)
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
