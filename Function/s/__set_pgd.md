# Function: <code>__set_pgd</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609014988,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018390,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579075943,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331815,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389585,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579401615,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413305,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422024,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453982,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579454302,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609172444,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581519240,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610940,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800473,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591143337,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:553",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579018390,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393777,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579453982,
      "name": "__set_pgd.constprop.0",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612076998,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242738,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579078423,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333399,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579395108,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421434,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591272916,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579451166,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566429,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658320,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591332874,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591227097,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:475",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591242738,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266436,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591272916,
      "name": "__set_pgd.constprop.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614215505,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185854,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579085326,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336150,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398586,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579424546,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215867,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579453673,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581586494,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680135,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275574,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591176339,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591185854,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208747,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591215867,
      "name": "__set_pgd.constprop.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615134332,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592048026,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579108361,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391460,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579460824,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579488171,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092476,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579519042,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581853840,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949415,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216273,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592030057,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:506",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592048026,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082385,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592092476,
      "name": "__set_pgd.constprop.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616897654,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593814537,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579139372,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579457973,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579536697,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579568163,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859596,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579603160,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593969460,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582247291,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358798,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593994974,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593797884,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593814537,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579532816,
      "name": "__set_pgd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593859596,
      "name": "__set_pgd.constprop.0",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491458,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627538767,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183628,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547127,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627715765,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579676400,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439765,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716135,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582634986,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582734827,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861054,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583153370,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595742003,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:512",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235586,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619284943,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187594,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562423,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619473237,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579690272,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729719,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844186,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582953627,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076558,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583363802,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596267971,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:507",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
  "name": "__set_pgd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621525666,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621577439,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216810,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579589959,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621769717,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579724800,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579764663,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583018714,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583135899,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258814,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600474,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597150659,
      "name": "__set_pgd",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:505",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
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
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
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
void __set_pgd(pgd_t * pgdp, pgd_t pgd)
```
</details>
</li>
</ul>
