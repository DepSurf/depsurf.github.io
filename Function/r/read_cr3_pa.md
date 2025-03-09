# Function: <code>read_cr3_pa</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596266586,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:237",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596303712,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:237",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295619,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:237",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395046,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:237",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888415,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:237",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602582266,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:241",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071578998310,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:241",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579316115,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:241",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602713715,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:241",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377259,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:241",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998310,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602750194,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:239",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001703,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:239",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579326792,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:239",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602886373,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:239",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681126,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:239",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579001703,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604544253,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:228",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000599,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:228",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579350842,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:228",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604683383,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:228",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820351,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:228",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000599,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604638362,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008023,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579365986,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604782867,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123455,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008023,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604650650,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010380,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579370226,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604808634,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328255,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010380,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609000623,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018403,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579397570,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ]
    },
    {
      "addr": 18446744071609147214,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150440,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018403,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579395680,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612064495,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242751,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579383461,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579399234,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:show_fault_oops"
      ]
    },
    {
      "addr": 18446744071612217556,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236424,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242751,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071579397824,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614202607,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185867,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579384853,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579403225,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614358788,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179144,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:245",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185867,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615120103,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592048039,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579446711,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579465577,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615289253,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035208,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:247",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048039,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616881385,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593814575,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579521774,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579542168,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617068629,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800630,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:250",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814575,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627469760,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627536629,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622012,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579647216,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627717328,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746386,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619282613,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619298800,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579635948,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579661616,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619474800,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270674,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:201",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621575045,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621592288,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579665740,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579695616,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:show_fault_oops",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621771280,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155410,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:216",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604576922,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010732,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579366130,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604722576,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935039,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010732,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604568640,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296468,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604690478,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648321,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604654746,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010316,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579366050,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604800143,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588266815,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579010316,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
```

```json
{
  "name": "read_cr3_pa",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604654746,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/kernel/head64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/head64.c:__early_make_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013532,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579374482,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812762,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:early_ioremap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588401983,
      "name": "read_cr3_pa",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:231",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579013532,
      "name": "read_cr3_pa",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
long unsigned int read_cr3_pa()
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int read_cr3_pa()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int read_cr3_pa()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int read_cr3_pa()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int read_cr3_pa()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int read_cr3_pa()
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
long unsigned int read_cr3_pa()
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
