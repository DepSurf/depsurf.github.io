# Function: <code>__ptep_modify_prot_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578967808,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:405",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579256528,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:405",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578967808,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579256528,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578964720,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:410",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579255584,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:410",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578964720,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579255584,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578966544,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:434",
      "file": "arch/x86/xen/mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579269104,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:434",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578966544,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579269104,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578975472,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:539",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579265728,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:539",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578975472,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579265728,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978640,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:540",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282496,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:540",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978640,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579282496,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578981376,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:583",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579293952,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:583",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578981376,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579293952,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct mm_struct * mm, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578979440,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579318944,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578979440,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579318944,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578986416,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334144,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578986416,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579334144,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988784,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579338352,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988784,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579338352,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999136,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:795",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579368048,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:795",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999136,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579368048,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579000960,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:844",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579367056,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:844",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579000960,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579367056,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579008960,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:844",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579371408,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:844",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579008960,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579371408,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579432624,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:863",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432624,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501616,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:896",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501616,
      "name": "__ptep_modify_prot_commit",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598800,
      "name": "__ptep_modify_prot_commit",
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
      "addr": 18446744071579598800,
      "name": "__ptep_modify_prot_commit",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611520,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:944",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611520,
      "name": "__ptep_modify_prot_commit",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643200,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/linux/pgtable.h:1075",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643200,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492753096,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798680,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
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
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226612664,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
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
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272765484,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989136,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334256,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989136,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579334256,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581260442,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306342,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582360043,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578988720,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579334176,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578988720,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579334176,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```

```json
{
  "name": "__ptep_modify_prot_commit",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578989856,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579342528,
      "name": "__ptep_modify_prot_commit",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:621",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578989856,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579342528,
      "name": "__ptep_modify_prot_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
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
void __ptep_modify_prot_commit(struct vm_area_struct * vma, long unsigned int addr, pte_t * ptep, pte_t pte)
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
