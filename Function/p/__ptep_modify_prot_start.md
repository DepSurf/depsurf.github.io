# Function: <code>__ptep_modify_prot_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967776,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:393",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256496,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:393",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967776,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579256496,
      "name": "__ptep_modify_prot_start",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964688,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:398",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255552,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:398",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964688,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579255552,
      "name": "__ptep_modify_prot_start",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966512,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:422",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579269072,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:422",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966512,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579269072,
      "name": "__ptep_modify_prot_start",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578975440,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:527",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265696,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:527",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975440,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071579265696,
      "name": "__ptep_modify_prot_start",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978624,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:528",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282480,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:528",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978624,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579282480,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981360,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:571",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293936,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:571",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981360,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579293936,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct mm_struct * mm, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979424,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318928,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979424,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579318928,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578986400,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334128,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986400,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579334128,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988768,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338336,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988768,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579338336,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999120,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:783",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579368032,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:783",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999120,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579368032,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000944,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:832",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367040,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:832",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000944,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579367040,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579008944,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:832",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579371392,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:832",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008944,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579371392,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432608,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:851",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432608,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501600,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:884",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501600,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598768,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:920",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598768,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611488,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:932",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611488,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641264,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/linux/pgtable.h:1063",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641264,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492752964,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798540,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226612596,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272765444,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989120,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334240,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989120,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579334240,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581260303,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306176,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360032,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_pte_range"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988704,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334160,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988704,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579334160,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate ❓</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```

```json
{
  "name": "__ptep_modify_prot_start",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989840,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342512,
      "name": "__ptep_modify_prot_start",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:609",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989840,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
    },
    {
      "addr": 18446744071579342512,
      "name": "__ptep_modify_prot_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 6
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct * vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
</ul>
</details>
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
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
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
pte_t __ptep_modify_prot_start(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep)
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
