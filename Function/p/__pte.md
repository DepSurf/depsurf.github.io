# Function: <code>__pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578958186,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578967754,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992058,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994218,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060386,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595008933,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220975,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579358483,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:pfn_pte",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595065293,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288494,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308380,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:native_set_fixmap",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:pmd_set_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316302,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580448889,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661786,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715187,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580737732,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580763601,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790724,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361413,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832555,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880199,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898698,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973524,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954141,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583920173,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959334,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578968297,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578988634,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578992530,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056809,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595173607,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221246,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587847326,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595231019,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294504,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308500,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321875,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580524184,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580793138,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830600,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855408,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580872507,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580886113,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927278,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862879,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958367,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581007793,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033381,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050108,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128786,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241767,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584251378,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580859,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:375",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961398,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970073,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_set_fixmap",
        "arch/x86/xen/mmu.c:xen_release_pud",
        "arch/x86/xen/mmu.c:xen_alloc_pud",
        "arch/x86/xen/mmu.c:xen_release_pmd",
        "arch/x86/xen/mmu.c:xen_release_pte",
        "arch/x86/xen/mmu.c:xen_alloc_pmd",
        "arch/x86/xen/mmu.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990506,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994370,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055821,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595415987,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233400,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588062142,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595474076,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310004,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323732,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337107,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580587522,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580855987,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896177,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580925661,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580940445,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580954200,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995614,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077585,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032053,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081817,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108569,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133054,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203856,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583357079,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584432991,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765552,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:366",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578956912,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578966100,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973526,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578978189,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579048051,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596335101,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230996,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588288828,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395628,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307932,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321090,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331076,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580617470,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798633,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901319,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940912,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580969943,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580984618,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580999394,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044511,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588304038,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581078917,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130575,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147089,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581173165,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252719,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584517833,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888862,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205901,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578960123,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578969295,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976419,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983364,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579049449,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579056903,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652504,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246601,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588854124,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602714696,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330276,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579344274,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579348872,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579356597,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602724784,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580698206,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872134,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997875,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041058,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072427,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581087617,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110612,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154997,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869352,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190293,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244549,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281618,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581309592,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384684,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584927865,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377758,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588755074,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962699,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578972200,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979190,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986236,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579054210,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579061791,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822310,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579259078,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589233278,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602887370,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579340923,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355661,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360684,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368809,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602896249,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830648,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006085,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581132453,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176541,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207752,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581230476,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246566,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298244,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248386,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335978,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581390028,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430191,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451289,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534778,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159102,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681553,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133087,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:360",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578960795,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578970314,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977398,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995068,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060292,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066367,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604617455,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282742,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589476416,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604684380,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367826,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382845,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388204,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396265,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604692481,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693558,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897869,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083334,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214139,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259897,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291895,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581313455,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330122,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381644,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490672,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419741,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473724,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501945,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534908,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620766,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585269918,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820774,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589368084,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967799,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977321,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578984374,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578999170,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579068140,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074911,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579080786,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604713632,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579297010,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589936033,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604783909,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382669,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398307,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579403710,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411641,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604792596,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793568,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995397,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146319,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275017,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333630,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366473,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581424377,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581439990,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581492966,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951629,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530616,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588680,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611580,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638129,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581733135,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585480806,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123878,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824917,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970231,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979721,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986742,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000674,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070236,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076911,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579082787,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604725934,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302562,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590163585,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809664,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579386973,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579401619,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406894,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414825,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604818142,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604819298,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049398,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203855,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333817,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393038,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426217,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581485769,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504214,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581557451,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590179170,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595528,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652344,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682492,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581709153,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581806687,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585621510,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328678,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590051141,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
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
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578979831,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578990069,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996086,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005360,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077402,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:unmap_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579087127,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579094161,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579138907,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332543,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393564,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ]
    },
    {
      "addr": 18446744071579405984,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ]
    },
    {
      "addr": 18446744071579410994,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417484,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427321,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444621,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence",
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609156010,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157490,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232047,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394350,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531632,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591196,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628897,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691064,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711573,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767764,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197474,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581810168,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870296,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901029,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926853,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023267,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044622,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586345162,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150811,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
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
      "addr": 18446744071579393564,
      "name": "__pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579405984,
      "name": "__pte",
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
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982001,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578991557,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997990,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009728,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579079338,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579089191,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095377,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591251416,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579334127,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591266254,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ]
    },
    {
      "addr": 18446744071612218680,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411636,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417516,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427017,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442295,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612226505,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227973,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274642,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437869,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575280,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:insert_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637212,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672075,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696308,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759365,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581816254,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692377,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857768,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916426,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946555,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072408,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586461208,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236795,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:372",
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
      "addr": 18446744071591266254,
      "name": "__pte",
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
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991089,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000296,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579007402,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579020469,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086299,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579095746,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579101582,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591195175,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336813,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591208565,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ]
    },
    {
      "addr": 18446744071614359673,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414804,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579420590,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430028,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444524,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614367750,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368736,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291276,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458269,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596811,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658855,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694300,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786365,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844025,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591635127,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892872,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941433,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972484,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097429,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586344964,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179461,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
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
      "addr": 18446744071591208565,
      "name": "__pte",
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
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579008145,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017990,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579025450,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579038437,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109381,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579119103,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579125502,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592060960,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392135,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592082203,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ]
    },
    {
      "addr": 18446744071615290351,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579477684,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579484142,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494208,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509532,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615299300,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615300280,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535566,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872769,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927127,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966476,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070141,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135247,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172567,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187576,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236200,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_unprotect",
        "mm/kfence/core.c:kfence_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247146,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275134,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412106,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865284,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035541,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:389",
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
      "addr": 18446744071592082203,
      "name": "__pte",
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
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579025681,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579037180,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579044958,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579058925,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579140533,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151675,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159804,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827469,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458609,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593849742,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/init_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ]
    },
    {
      "addr": 18446744071617069821,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556133,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563429,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579574566,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579592916,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617079291,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617080347,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884497,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270965,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334182,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582385128,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509665,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582583993,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631461,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582648856,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706288,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page",
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718415,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744147,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582758429,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925209,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588151361,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800965,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
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
      "addr": 18446744071593849742,
      "name": "__pte",
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579054163,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066722,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627533299,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579090366,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579184898,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200530,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579209997,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579271048,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547754,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596438447,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627718824,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579663061,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579671080,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579683248,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704096,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627732300,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627734535,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317744,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582762792,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:remap_pfn_range_notrack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835146,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582892996,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028237,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114672,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122286,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596455165,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171214,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231908,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page",
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245353,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275818,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583292360,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480873,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589545189,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746732,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:395",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579054067,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066594,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619279635,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579084110,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188965,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204587,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215547,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277328,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579563051,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596979278,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619476296,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579677211,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579685050,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579697104,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717584,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619491545,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619493806,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518857,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978326,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:remap_p4d_range",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583050366,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098723,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583108260,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250693,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583326063,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332551,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596996495,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387294,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451100,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583464355,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496059,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583510601,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583697058,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589846788,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271014,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
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
      "addr": 18446744071582946128,
      "name": "__pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pte_t __pte(pteval_t val)
```

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579079457,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579091682,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list",
        "arch/x86/xen/p2m.c:xen_rebuild_p2m_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621570531,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt_boot",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579109902,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:set_page_prot_flags",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_ptpage",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579218181,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:map_ldt_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233931,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579244856,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307344,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579590587,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597907710,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:phys_pte_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621772904,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579711339,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579719562,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731632,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752304,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621788537,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_clone_user_shared"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621790766,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687745,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583150846,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583232137,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583281002,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583297229,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmap_pfn_apply",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583485173,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583562096,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568532,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597925976,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629662,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643908,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583660155,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684128,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583700913,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583899739,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730456,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:make_uffd_wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590183392,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155750,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:392",
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
      "addr": 18446744071583121408,
      "name": "__pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970247,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980073,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987094,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001026,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070588,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077263,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579083139,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604652237,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298370,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589765873,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604723606,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382877,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397523,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402734,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410665,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604732022,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604733178,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581018246,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172703,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302665,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361886,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395065,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454617,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472950,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581526187,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781458,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581564264,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621080,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651228,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581677889,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581775423,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585383158,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935462,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653397,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970167,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578979657,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986678,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000610,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579070172,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076847,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579082723,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730000,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299570,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590209281,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604801173,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579382797,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397443,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402654,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410585,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604809589,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810745,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009446,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581163903,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293865,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353086,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386265,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581445817,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581464262,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581517499,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224866,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555576,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612392,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642540,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669201,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581766735,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585571910,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267238,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096773,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
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
  "name": "__pte",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578970759,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/grant-table.c:arch_gnttab_unmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578980249,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578987558,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996898,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_set_fixmap",
        "arch/x86/xen/mmu_pv.c:xen_release_pud",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pud",
        "arch/x86/xen/mmu_pv.c:xen_release_pmd",
        "arch/x86/xen/mmu_pv.c:xen_release_pte",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pmd",
        "arch/x86/xen/mmu_pv.c:xen_alloc_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074268,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ldt.c:write_ldt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080943,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579086819,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/kernel/alternative.c:__text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604730046,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308402,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590259649,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:pfn_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813792,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/ioremap.c:__early_set_fixmap",
        "arch/x86/mm/ioremap.c:__early_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391583,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:__split_large_page",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579405939,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_set_huge",
        "arch/x86/mm/pgtable.c:pud_set_huge",
        "arch/x86/mm/pgtable.c:native_set_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411518,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/cpu_entry_area.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/cpu_entry_area.c:cea_set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419449,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604822270,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604823455,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581070697,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230175,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358009,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417022,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450585,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581510277,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528985,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581582499,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275224,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620616,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679992,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708924,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581735611,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581835567,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679878,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xlate_mmu.c:remap_pfn_fn",
        "drivers/xen/xlate_mmu.c:remap_pte_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402406,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590147029,
      "name": "__pte",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:362",
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
pte_t __pte(pteval_t val)
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
pte_t __pte(pteval_t val)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
pte_t __pte(pteval_t val)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
