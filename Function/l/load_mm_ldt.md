# Function: <code>load_mm_ldt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579112185,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587365277,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:__schedule",
        "kernel/sched/core.c:idle_task_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580614231,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "mm/mmu_context.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmu_context.c:use_mm",
        "mm/mmu_context.c:use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022850,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586165335,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579111964,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313628,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586579646,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:66",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579110505,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579328890,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763966,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579102228,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322392,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586887220,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:67",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579050632,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:103",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113627,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:103",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346732,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:103",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587375849,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:103",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579055992,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:104",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579119982,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:104",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358428,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:104",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587679505,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:104",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579060808,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:99",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579125718,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:99",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579385887,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:99",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587810593,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:99",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579068659,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579135402,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401383,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115932,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:fix_processor_context"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070755,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137322,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579404647,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588321375,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579078672,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:flush_ldt",
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579078672,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579081024,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:flush_ldt",
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081024,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579087888,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:flush_ldt",
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579087888,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:flush_ldt",
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592054316,
      "name": "load_mm_ldt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579111008,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593821143,
      "name": "load_mm_ldt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579142384,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595958975,
      "name": "load_mm_ldt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579186720,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596476377,
      "name": "load_mm_ldt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579190784,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void load_mm_ldt(struct mm_struct * mm)
```

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "load_mm_ldt",
      "external": true,
      "loc": "arch/x86/kernel/ldt.c:42",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:switch_ldt",
        "arch/x86/kernel/cpu/common.c:cpu_init",
        "arch/x86/power/cpu.c:fix_processor_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597372142,
      "name": "load_mm_ldt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071579220032,
      "name": "load_mm_ldt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579071107,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137706,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400551,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925023,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579003924,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068489,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330019,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641548,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/cpu.c:restore_processor_state"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579070691,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579137258,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400471,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588258431,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "load_mm_ldt",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579074787,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:flush_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579142378,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/kernel/cpu/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/common.c:cpu_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409096,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588393951,
      "name": "load_mm_ldt",
      "external": false,
      "loc": "arch/x86/include/asm/mmu_context.h:100",
      "file": "arch/x86/power/cpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void load_mm_ldt(struct mm_struct * mm)
```
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
