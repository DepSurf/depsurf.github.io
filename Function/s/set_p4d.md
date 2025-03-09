# Function: <code>set_p4d</code>

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
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596306201,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596322008,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230515,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596394159,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293052,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303416,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588293582,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596408528,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898425,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953281,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304695,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586888163,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:581",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602594819,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602624128,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049736,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602639962,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579246085,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602712806,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579313543,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325101,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579346759,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588858646,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602721987,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602733168,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000524,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055025,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588870059,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587377007,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602763163,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602792836,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054517,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602809629,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258545,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602885461,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324742,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336564,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579358405,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589237804,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382677,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602906724,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134159,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581193745,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589249047,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587680857,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:545",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604557256,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604586701,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059573,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604604671,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282209,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589480715,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348806,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363108,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579385763,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589481842,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410247,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604703088,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210591,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277025,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491333,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587811593,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:529",
      "file": "arch/x86/power/hibernate.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604651590,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604682087,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579067129,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604700266,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296474,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940371,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369025,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377677,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579401255,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589941531,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426037,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802970,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286745,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351474,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589952307,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588117305,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:530",
      "file": "arch/x86/power/hibernate.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604663862,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694529,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069460,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604712650,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302026,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590167923,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373265,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579381965,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579404519,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590169083,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579429205,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604828697,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345465,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581410978,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179841,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588322937,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578870992,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071579018377,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579075965,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609059284,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332651,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579389200,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pud_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping"
      ]
    },
    {
      "addr": 18446744071579402303,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579413278,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:sync_current_stack_to_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422295,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579453969,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579454629,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609172432,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/bios_uv.c:efi_uv1_memmap_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581541817,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611058,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800288,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    },
    {
      "addr": 18446744071591143416,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:532",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578870992,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579018377,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579393738,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579453969,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581800288,
      "name": "set_p4d",
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591238361,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071591242725,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579078445,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612122644,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334235,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394592,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pud_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579421717,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591272903,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579451493,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581585001,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658422,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591332700,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    },
    {
      "addr": 18446744071591227176,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:454",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591238361,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591242725,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591266397,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591272903,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591332700,
      "name": "set_p4d",
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591181178,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071591185841,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579085348,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591190700,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336934,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397426,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579424775,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591215783,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579453958,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607242,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680230,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275400,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    },
    {
      "addr": 18446744071591176422,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181178,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591185841,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591208708,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591215783,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071591275400,
      "name": "set_p4d",
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592037323,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071592048013,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579108390,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592054909,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579392251,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579459650,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579488400,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092392,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579519350,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874362,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949510,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216066,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    },
    {
      "addr": 18446744071592030002,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592037323,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592048013,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592082346,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592092392,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071592216066,
      "name": "set_p4d",
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593803363,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ]
    },
    {
      "addr": 18446744071593814499,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ]
    },
    {
      "addr": 18446744071579139426,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593821768,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579458780,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579535559,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5"
      ]
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579568414,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859464,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ]
    },
    {
      "addr": 18446744071579603476,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593968924,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/percpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_populate_pte"
      ]
    },
    {
      "addr": 18446744071582272602,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358948,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593994743,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/sparse-vmemmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ]
    },
    {
      "addr": 18446744071593797830,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593803363,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593814499,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071579532704,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593859464,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593968924,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593994743,
      "name": "set_p4d",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627491798,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627540134,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579183649,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199212,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579547947,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596433172,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579676651,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596439906,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr",
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579716483,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627851885,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764663,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861220,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596456069,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595742096,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:488",
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
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619235926,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619286304,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579187615,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203260,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579563247,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596973940,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579690523,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596980516,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730067,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619628781,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_populate_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981037,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583076724,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596997397,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596268064,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:483",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621526006,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits",
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621578800,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216831,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct_to_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621602978,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590783,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable",
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597902372,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_p4d_table",
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:phys_p4d_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:sync_global_pgds_l5",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init",
        "arch/x86/mm/init_64.c:ident_p4d_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579725051,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:populate_pgd",
        "arch/x86/mm/pat/set_memory.c:populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597908948,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline_kaslr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765011,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd",
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583011115,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583135364,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:free_pud_range",
        "mm/memory.c:pgd_populate",
        "mm/memory.c:p4d_populate"
      ],
      "caller_func": [
        "mm/memory.c:free_p4d_range"
      ]
    },
    {
      "addr": 18446744071583258980,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad",
        "mm/pgtable-generic.c:pgd_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600283,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597150752,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping",
        "arch/x86/power/hibernate_64.c:set_up_temporary_text_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:482",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121664,
      "name": "set_p4d",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604590134,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604620810,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069812,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604638940,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297834,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589770211,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369169,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377869,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579400423,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771371,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425045,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604742577,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314313,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379826,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782129,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587926585,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate.c",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667958,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698625,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579069396,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604716732,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299034,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590213619,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369089,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377789,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579400343,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214779,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579424965,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820144,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305513,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371026,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590225537,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588259993,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate.c",
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
  "name": "set_p4d",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667963,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/entry/vsyscall/vsyscall_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:set_vsyscall_pgtable_user_bits"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604698631,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579073234,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604716762,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_bsp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307866,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590263987,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:__kernel_physical_mapping_init",
        "arch/x86/mm/init_64.c:__init_extra_mapping",
        "arch/x86/mm/init_64.c:fill_pud",
        "arch/x86/mm/init_64.c:sync_global_pgds_l4",
        "arch/x86/mm/init_64.c:kernel_ident_mapping_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579377521,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386269,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579408899,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:switch_mm_irqs_off"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590265147,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/kaslr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kaslr.c:init_trampoline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434149,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604832854,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/platform/efi/efi_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369513,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pud_alloc",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434914,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:p4d_clear_bad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275895,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588395513,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "set_p4d",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:518",
      "file": "arch/x86/power/hibernate.c",
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
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
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void set_p4d(p4d_t * p4dp, p4d_t p4d)
```
</details>
</li>
</ul>
