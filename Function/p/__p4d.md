# Function: <code>__p4d</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4d_t __p4d(p4dval_t val)
```

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609015070,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609045140,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609059260,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331955,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389176,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pud_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579422160,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591187043,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579454605,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541793,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611046,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591198184,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591143238,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:541",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393751,
      "name": "__p4d",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4d_t __p4d(p4dval_t val)
```

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612077074,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612108496,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612122620,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333539,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394568,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579421570,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591682358,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579451469,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584977,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591693075,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591226998,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:463",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266410,
      "name": "__p4d",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4d_t __p4d(p4dval_t val)
```

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215581,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614248204,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591190675,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336241,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397400,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579424626,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591625805,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453933,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607217,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635573,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591176239,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208721,
      "name": "__p4d",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4d_t __p4d(p4dval_t val)
```

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134408,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615168326,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592054884,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391551,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459624,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579488251,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592799243,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579519325,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874337,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809541,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592029935,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082359,
      "name": "__p4d",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
p4d_t __p4d(p4dval_t val)
```

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897729,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071616934371,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821744,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579458063,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535534,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579568242,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594699361,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579603453,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617165649,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272578,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594710744,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593797766,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532752,
      "name": "__p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491541,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627540126,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199191,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579547220,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596437853,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676482,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439679,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716463,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851863,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764642,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596456048,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595741881,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:497",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235669,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286296,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203239,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579562516,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596978637,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690354,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980495,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730047,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628759,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981016,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596997376,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596267849,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:492",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525749,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578792,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621602957,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590052,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597907069,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579724882,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908927,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764991,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011094,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583125759,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600262,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597150537,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:491",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
p4d_t __p4d(p4dval_t val)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
p4d_t __p4d(p4dval_t val)
```
</details>
</li>
</ul>
