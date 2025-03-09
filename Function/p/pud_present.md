# Function: <code>pud_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977749,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579059588,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220581,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579275227,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280000,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292164,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd",
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580674836,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723301,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580800723,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905284,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:page_check_address_pmd",
        "mm/huge_memory.c:split_huge_page_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314880,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:586",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595140540,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055950,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579220819,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587849020,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579279032,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298923,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320522,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789085,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841791,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924360,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581034303,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481735,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595383222,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054974,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579232973,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588063833,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294296,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579314395,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335746,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853450,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905177,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912335,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992712,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109503,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562617,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:623",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596304531,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047258,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230575,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588290394,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293576,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311768,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329839,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898634,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949882,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580957375,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040200,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157872,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618226,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:762",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602622324,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056055,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246157,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588855735,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312567,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334368,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579354930,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581000731,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051040,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059024,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150262,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287416,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762645,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:771",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602791100,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061044,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579258618,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589235013,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324954,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579345192,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355241,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366452,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134362,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189700,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581197747,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293698,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434488,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501989,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930910,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604584967,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579065620,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579282282,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589478862,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579349018,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579371784,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382425,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394081,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210794,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272673,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281091,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376722,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581518008,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587237,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015326,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367425,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:838",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604680358,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074164,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579296548,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589939334,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363734,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386888,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397897,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409012,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581286953,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347137,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355715,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487622,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627802,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698671,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748853,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151921,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824351,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604692812,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076164,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579302100,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590166886,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367974,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579390280,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401209,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412196,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581345673,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406449,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415251,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552038,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698618,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772111,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820965,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229201,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590050575,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_present(pud_t pud)
```

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609041718,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086828,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579332059,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393997,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579397143,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410585,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430654,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512037,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581542025,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581605285,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608789,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581616423,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762504,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914600,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581992840,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582038323,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458656,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585044942,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:864",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393997,
      "name": "pud_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int pud_present(pud_t pud)
```

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612105076,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579088892,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579333643,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392925,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579403511,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411225,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430126,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190871,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552165,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581585264,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652433,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656243,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581663415,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697208,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810584,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961480,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042408,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582087203,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515568,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591266625,
      "name": "pud_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
int pud_present(pud_t pud)
```

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614244830,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095451,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579336340,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396445,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579406710,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414383,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433078,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220332,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575015,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607507,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673377,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677677,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581685419,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696823,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838973,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987418,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582068888,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582112291,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545145,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:863",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591208941,
      "name": "pud_present",
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
int pud_present(pud_t pud)
```

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615164906,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118809,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579391653,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579461729,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579469265,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477263,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579497291,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460319,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839656,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581874627,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942728,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946879,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581954880,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969033,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582129843,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582289506,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582382958,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428611,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861266,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:834",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592082579,
      "name": "pud_present",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pud_present(pud_t pud)
```

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616930905,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151379,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458162,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579537801,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init"
      ]
    },
    {
      "addr": 18446744071579546156,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579555699,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579578181,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807567,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582231784,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272847,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352313,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582356155,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582370138,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392021,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576862,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582773971,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885802,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943292,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431805,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:832",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532992,
      "name": "pud_present",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627536842,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579199747,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547319,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596432300,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645390,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662611,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579687247,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234181,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514864,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582722769,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764927,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853612,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582858119,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582871610,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898313,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583095764,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583296721,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435211,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583500223,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019814,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:850",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619282826,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579203795,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562615,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596973084,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579659806,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676763,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579701013,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437411,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716828,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938471,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981314,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069996,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583073617,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583088445,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113453,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305607,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583515795,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583650206,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583716591,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584238893,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:851",
      "file": "fs/userfaultfd.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621575258,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233139,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590151,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597901516,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693790,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710891,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735541,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_pmd_address",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582605923,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582886172,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583113701,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156666,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251898,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255665,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583270877,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583295830,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543479,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583709762,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845126,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583917231,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451006,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1073",
      "file": "fs/userfaultfd.c",
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297809728,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286110516,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183816,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286196076,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286629256,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286745676,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287413028,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297671224,
      "name": "pud_present",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:921",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271359480,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271361502,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "arch/riscv/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/hugetlbpage.c:pud_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714258,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272721422,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__pmd_alloc",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765220,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272767768,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272770794,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272775002,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272781814,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853244,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272890858,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273385328,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pud_present",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable-64.h:31",
      "file": "lib/ioremap.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604619093,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076516,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579297908,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589769174,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363878,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386184,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397113,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408036,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314521,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375297,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384099,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581520774,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581667354,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740847,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789701,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197937,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589652831,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579009412,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579233975,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589491936,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295174,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315606,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579326586,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337776,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258087,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318671,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326908,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462892,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606938,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679642,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727379,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135405,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589378609,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604696908,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076100,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579299108,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590212582,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579363798,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386104,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397033,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579407956,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305721,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366497,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375299,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581512086,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658666,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732159,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781013,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188417,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096207,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pud_present",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604696914,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080196,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579307940,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590262950,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:phys_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init",
        "arch/x86/mm/init_64.c:ident_pud_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579372230,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394616,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:lookup_pmd_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405529,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pud_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579416820,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581369721,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pmd_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430391,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439155,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577142,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:huge_pte_offset"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725050,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:split_huge_pmd_address",
        "mm/huge_memory.c:follow_devmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800447,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850021,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582264536,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146463,
      "name": "pud_present",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:855",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int pud_present(pud_t pud)
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
int pud_present(pud_t pud)
```
</details>
</li>
</ul>
