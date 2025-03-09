# Function: <code>pte_val</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578962542,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594976015,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_set_pte_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m",
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994312,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:get_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004032,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587347127,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:phys_pte_init",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281515,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292566,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309405,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579316279,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579320937,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656850,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580663652,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:follow_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690677,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715149,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723710,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730971,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751409,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771484,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791014,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_huge_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810829,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361222,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580880038,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:__migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895901,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920165,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428385,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:418",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578959065,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595142130,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578994295,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579009616,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278293,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281563,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296277,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310158,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579321853,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579326535,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768620,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801169,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804266,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830773,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842232,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849861,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871661,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580894574,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580934075,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937242,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862634,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581013993,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056757,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067409,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616097,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586580833,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:391",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578961129,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/xen/enlighten.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten.c:xen_load_gdt",
        "arch/x86/xen/enlighten.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595384800,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init",
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578996135,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579011488,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293592,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296827,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579311767,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325406,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579337085,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579341767,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834156,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580865475,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869313,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896119,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904370,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912775,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920341,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939550,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962967,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581002395,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008987,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077340,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581088169,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133170,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142706,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579956,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581704545,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765526,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:382",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578967943,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578973096,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596306047,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init",
        "arch/x86/xen/mmu_pv.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579004371,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_domain_pte",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291116,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294647,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309407,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331054,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579335832,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880012,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910550,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914311,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941226,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949275,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959335,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964886,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983765,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581010184,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049963,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051275,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303793,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581135642,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179685,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189913,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581641002,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759665,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888836,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:390",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578971278,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578975820,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578998353,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005731,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310698,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579315085,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579331788,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356575,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579361272,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602724356,
      "name": "pte_val",
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
      "addr": 18446744071580964570,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009296,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:_vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013631,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040998,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050245,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061132,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581071418,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086750,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098144,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swap_readahead_detect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581105670,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SYSC_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160907,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162468,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869064,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581250569,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308637,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320099,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395204,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786592,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581906128,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377732,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578973998,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578977997,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579001742,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008499,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322183,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325967,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342787,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368790,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579373783,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895791,
      "name": "pte_val",
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
      "addr": 18446744071581100741,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142916,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:_vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581148182,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177818,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188940,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200090,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208492,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229724,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238385,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257989,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304058,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312579,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248026,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393095,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454298,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465605,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546126,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581960114,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091235,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681540,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:376",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578972134,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578976573,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579000638,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010003,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346487,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579350031,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579367542,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396246,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579401447,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604693100,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178822,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222736,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:_vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581228009,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258010,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273959,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283509,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289660,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312700,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321793,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340933,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387722,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394115,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490312,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478711,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539151,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549941,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629492,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041269,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186051,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820761,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979142,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578983551,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579008062,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579017300,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362182,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365180,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579388674,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411622,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579416773,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604793118,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995289,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249014,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296401,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302091,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336138,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348358,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581357870,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364332,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423516,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432886,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581451381,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499386,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506300,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951278,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530065,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594589,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646345,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665576,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744537,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202356,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582349475,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123865,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:386",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981542,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985919,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010419,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019604,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366422,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579369420,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579392002,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579414806,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579419957,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604818839,
      "name": "pte_val",
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
      "addr": 18446744071581049285,
      "name": "pte_val",
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
      "addr": 18446744071581307622,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355169,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360731,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391946,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407670,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417539,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423980,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484908,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497126,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581515605,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563898,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570668,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178805,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594969,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657348,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718041,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737864,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817581,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283194,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582448339,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328665,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991734,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578995407,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579018442,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579027300,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393451,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pte_table"
      ]
    },
    {
      "addr": 18446744071579398237,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579432394,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444600,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449424,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:print_pte",
        "arch/x86/mm/mmio-mod.c:print_pte"
      ]
    },
    {
      "addr": 18446744071609157032,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231934,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499376,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552751,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_one_pte",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581558196,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590170,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604126,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618883,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627253,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690133,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702282,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_ra_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724245,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774497,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788527,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197110,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809575,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876243,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936948,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949266,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582037809,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582043106,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570942,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740339,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150801,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:388",
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
      "addr": 18446744071579393577,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579449424,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581513920,
      "name": "pte_val",
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
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578993222,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578997327,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591242790,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579031316,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383550,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579397696,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pte_table"
      ]
    },
    {
      "addr": 18446744071579399901,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579431818,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579442200,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446688,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:print_pte",
        "arch/x86/mm/mmio-mod.c:print_pte"
      ]
    },
    {
      "addr": 18446744071612227526,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274529,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539536,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597407,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_shared",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581603111,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636570,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651419,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665159,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672949,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739877,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581750003,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772405,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822641,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835951,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692012,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857191,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924538,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581979499,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997090,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582086685,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092066,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643262,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811667,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940845,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236785,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:377",
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
      "addr": 18446744071591266267,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579446688,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581558928,
      "name": "pte_val",
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
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579001958,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579005903,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591185906,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579034284,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579384938,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579400950,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579403039,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579434778,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444485,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579449456,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071614368308,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581291169,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562864,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620044,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:wp_page_reuse",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581625626,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658138,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674637,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687217,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699382,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768161,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777825,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799765,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581851857,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866767,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634779,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892323,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947450,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582007511,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023698,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582110494,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117138,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671275,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840403,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587822376,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179451,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
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
      "addr": 18446744071591208578,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579449456,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581581872,
      "name": "pte_val",
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
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579019638,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023855,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592048078,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579053132,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579446805,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579463288,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579465384,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579499012,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509493,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579514432,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071615299859,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535459,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827504,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887548,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581893114,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926490,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943886,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961227,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971178,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050817,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060913,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084181,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143206,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582157802,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172380,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
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
      "addr": 18446744071582186996,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582236190,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_unprotect",
        "mm/kfence/core.c:kfence_protect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252091,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582309895,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327202,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582378930,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry",
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426809,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582433522,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997531,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173171,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427395,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035531,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:396",
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
      "addr": 18446744071592082216,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071579514432,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071581846832,
      "name": "pte_val",
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
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579038663,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579042444,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593814637,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080062,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579521867,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579539605,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:vmemmap_populate_hugepages",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579541959,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579580468,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579592853,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579597984,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071579604955,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581884391,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582220458,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243307,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071582291306,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333274,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353069,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380527,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
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
      "addr": 18446744071582394354,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477245,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499247,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524021,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582596166,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613047,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582631022,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_restore_pte",
        "mm/sparse-vmemmap.c:vmemmap_remap_pte",
        "mm/sparse-vmemmap.c:vmemmap_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646722,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706282,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page",
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731173,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582743069,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806120,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836845,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879828,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry",
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925987,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941824,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582950257,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583423098,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583668514,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828374,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800956,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
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
      "addr": 18446744071579532336,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579597984,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071582239120,
      "name": "pte_val",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068218,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579072060,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627537180,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113518,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579622106,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579643054,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646581,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690036,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704021,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710160,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071579718760,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582317600,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545157,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709837,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739179,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ]
    },
    {
      "addr": 18446744071582783828,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582833866,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854693,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884007,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
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
      "addr": 18446744071582900622,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991239,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013199,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042213,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:arch_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115247,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121909,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583136450,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596456713,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166633,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231902,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_protect_page",
        "mm/kfence/core.c:kfence_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251765,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272576,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346401,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380558,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428681,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry",
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481716,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498635,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583507553,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011431,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584275254,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585097265,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746723,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:402",
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
      "addr": 18446744071579710160,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071582729936,
      "name": "pte_val",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579068074,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579071868,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619283158,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579113838,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579636042,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579657102,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660991,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579703796,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717509,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579723440,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071579732370,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582518758,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582693957,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582924747,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954667,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000557,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583049245,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069127,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583098859,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115752,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201908,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221734,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250772,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325693,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332181,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346757,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596998076,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382833,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451091,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/kfence/core.c:kfence_init_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471367,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495871,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558680,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583601031,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649785,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry",
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698127,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713639,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583722433,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584235950,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584505702,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326839,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596271005,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:397",
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
      "addr": 18446744071579723440,
      "name": "pte_val",
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
pteval_t pte_val(pte_t pte)
```

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579093162,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097292,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621575590,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_early_virt_to_phys",
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579139646,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/ldt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/paravirt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579665834,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/kernel/sev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579690974,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_set_pmd",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694991,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579738404,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:kernel_page_present",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:__change_page_attr",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys",
        "arch/x86/mm/pat/set_memory.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752229,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pte_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579758304,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ]
    },
    {
      "addr": 18446744071579767314,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582687662,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867813,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583098923,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126645,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:vm_normal_page"
      ],
      "caller_func": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071583179933,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191690,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583231165,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583250999,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281143,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298648,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437447,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457070,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485252,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561781,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583568337,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_restore_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_pte",
        "mm/hugetlb_vmemmap.c:vmemmap_pte_entry",
        "mm/hugetlb_vmemmap.c:vmemmap_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583582749,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_hugetlb",
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597927404,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_populate_compound_pages",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622316,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:break_ksm_pmd_entry",
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643902,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/kfence/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583663671,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683725,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583758592,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:release_pte_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797312,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844601,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry",
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583903465,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ]
    },
    {
      "addr": 18446744071583914383,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923137,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "mm/ptdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ptdump.c:ptdump_pte_entry",
        "mm/ptdump.c:ptdump_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450299,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584735030,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585561543,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "fs/hugetlbfs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/hugetlbfs/inode.c:hugetlb_vma_maps_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
      "file": "drivers/xen/xlate_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071597155741,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:398",
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
      "addr": 18446744071579758304,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583121456,
      "name": "pte_val",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071583890128,
      "name": "pte_val",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282402512,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/kernel/mce_power.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kernel/mce_power.c:addr_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282443320,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/kernel/eeh.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282718752,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:maybe_pte_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/pgtable_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282726164,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/ioremap.c:ioremap_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282744808,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/hash_utils.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache",
        "arch/powerpc/mm/book3s64/hash_utils.c:update_mmu_cache",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_mm",
        "arch/powerpc/mm/book3s64/hash_utils.c:hash_page_do_lazy_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282761460,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/hash_tlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_tlb.c:flush_tlb_pmd_range",
        "arch/powerpc/mm/book3s64/hash_tlb.c:__flush_hash_table_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282775920,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/radix_pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_set_access_flags",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:radix__ptep_set_access_flags",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable",
        "arch/powerpc/mm/book3s64/radix_pgtable.c:remove_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282810508,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/hash_64k.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K",
        "arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282811964,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/hash_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/hash_hugetlbpage.c:__hash_page_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282815060,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/radix_hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit",
        "arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__huge_ptep_modify_prot_commit"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/book3s64/hash_hugepage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055282844416,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/mm/hugetlbpage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/hugetlbpage.c:follow_huge_pd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283266844,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283314308,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/kvm/book3s_64_vio_hv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283329652,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:real_vmalloc_addr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283363856,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "arch/powerpc/perf/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/perf/callchain.c:read_user_stack_slow"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285906392,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286058536,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286122844,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:vm_insert_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286130428,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_hugetlb",
        "mm/mincore.c:mincore_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286171248,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286175872,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286184016,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286199944,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286209532,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_page_range_noflush",
        "mm/vmalloc.c:vmap_page_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286305048,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286324356,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286342848,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286425272,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration",
        "mm/hugetlb.c:is_hugetlb_entry_migration",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286427820,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297817528,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286573104,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286637472,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286661952,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286689356,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286798808,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286815532,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287412332,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault",
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287481940,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean",
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287719900,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297671800,
      "name": "pte_val",
      "external": false,
      "loc": "arch/powerpc/include/asm/pgtable-be-types.h:11",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pud_range",
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
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981894,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986271,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010771,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019956,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362326,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365324,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387906,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410646,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415797,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604732719,
      "name": "pte_val",
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
      "addr": 18446744071581018133,
      "name": "pte_val",
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
      "addr": 18446744071581276470,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324017,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329579,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360794,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376518,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386387,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392828,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453756,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465840,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484341,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581532634,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539404,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781093,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563705,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626084,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686777,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706600,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786317,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251930,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417075,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935449,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578981478,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578985855,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579010355,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579019540,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362246,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579365244,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579387826,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410566,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579415717,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604810286,
      "name": "pte_val",
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
      "addr": 18446744071581009333,
      "name": "pte_val",
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
      "addr": 18446744071581267670,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315217,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320779,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581351994,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367718,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377587,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384028,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444956,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457174,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475653,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523946,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530716,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224501,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555017,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617396,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678089,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697912,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777629,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242410,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582407555,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267225,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_val",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578982070,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/p2m.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:__set_phys_to_machine",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:xen_alloc_p2m_entry",
        "arch/x86/xen/p2m.c:get_phys_to_machine"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071578986639,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_load_gdt",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579013571,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:pte_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579023108,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/xen/trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_ptep_modify_prot",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu_set_pte_at",
        "arch/x86/xen/trace.c:trace_raw_output_xen_mmu__set_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370678,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:vmemmap_populate",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579373676,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396354,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:kernel_page_present",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:cpa_flush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419430,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579424724,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "arch/x86/mm/mmio-mod.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mmio-mod.c:pre",
        "arch/x86/mm/mmio-mod.c:pre"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604822996,
      "name": "pte_val",
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
      "addr": 18446744071581070584,
      "name": "pte_val",
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
      "addr": 18446744071581331526,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379171,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:follow_pfn",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:vm_normal_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384754,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581415930,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:prot_none_hugetlb_entry",
        "mm/mprotect.c:prot_none_pte_entry",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431657,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581441438,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448044,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509437,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521606,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540405,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588874,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pgd",
        "mm/hugetlb.c:follow_huge_pud",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590186,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_hugetlb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590274859,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_verify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620065,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685840,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744716,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765048,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846626,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319997,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582487059,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_hugetlb_stats",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402393,
      "name": "pte_val",
      "external": false,
      "loc": "arch/x86/include/asm/paravirt.h:374",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
pteval_t pte_val(pte_t pte)
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
