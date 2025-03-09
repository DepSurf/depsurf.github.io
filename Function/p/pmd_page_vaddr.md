# Function: <code>pmd_page_vaddr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594979321,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579060262,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595008926,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579220942,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274256,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579280220,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579288352,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309256,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580656751,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:__get_user_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661808,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580690414,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714967,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718564,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723557,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580730926,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745726,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751285,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580763021,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811505,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587361313,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833435,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879854,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895758,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
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
      "addr": 18446744071580921939,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973650,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315192,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434746,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954065,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:522",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274256,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071580661808,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595142055,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056617,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595173540,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579221172,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278235,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579279284,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579287976,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309943,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579320814,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580768321,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790345,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580804009,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830342,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834226,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580842007,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849810,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864915,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580871534,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885378,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937734,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587862727,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959044,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581014379,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581033022,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
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
      "addr": 18446744071581056587,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077803,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128846,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481895,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619813,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241673,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586580813,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
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
      "addr": 18446744071579273472,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580770912,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595384725,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579055635,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595415920,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233326,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293529,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579294548,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579303368,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579325191,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336038,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580833857,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854863,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580869063,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895858,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900334,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905377,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906883,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580912551,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:__page_check_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920290,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939437,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953466,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009473,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588077433,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032626,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088554,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108193,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
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
      "addr": 18446744071581131605,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153396,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203930,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562775,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708227,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356985,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765506,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:559",
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
      "addr": 18446744071579288912,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580836336,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596305996,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579047884,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596335034,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579230922,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579291047,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579293841,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579301112,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330255,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580798725,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879465,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883917,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071580914128,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940597,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580944837,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950169,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580952243,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580964845,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983640,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998715,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057067,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588303886,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079714,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135978,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146745,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
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
      "addr": 18446744071581179077,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200666,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252791,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618388,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761855,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586888816,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588205799,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:698",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579285856,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071580913169,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602623666,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579056713,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602652387,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579246519,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310634,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579312812,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579323003,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579342160,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579355445,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602723001,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872248,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964336,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977709,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013429,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040713,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045717,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051437,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052945,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581071346,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086635,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109708,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm",
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168719,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588869170,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191113,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250457,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281274,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
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
      "addr": 18446744071581305826,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330792,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384779,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394992,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763075,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907596,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587377684,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588754970,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:708",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304704,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602792593,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579061659,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602822194,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579258963,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322118,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579325172,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333579,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579356378,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366966,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602895269,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602897550,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006228,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100666,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113003,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071581147965,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176093,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183079,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189950,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192731,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581208420,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229617,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238308,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581246391,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313437,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589248166,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336768,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392723,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430000,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
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
      "addr": 18446744071581453892,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478992,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502287,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534892,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545665,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931686,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582093143,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587681501,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate_64.c:swsusp_arch_resume"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589132982,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:750",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316720,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071581109664,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604586458,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579066235,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604617339,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579282627,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346422,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579349236,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579360443,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383541,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579394582,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411411,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604694934,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083476,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178742,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192130,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ]
    },
    {
      "addr": 18446744071581227792,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259445,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265522,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272898,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275891,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289588,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312593,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321716,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329911,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma",
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395043,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589490452,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420579,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478339,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581501759,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
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
      "addr": 18446744071581538728,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569184,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587538,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620878,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628946,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016102,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187524,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587820722,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589367984,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:775",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_page_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341456,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071581189696,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604681850,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579074779,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604713513,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579296891,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362113,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579363916,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375035,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579399014,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579409486,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579427112,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604794956,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146458,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248944,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264957,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301857,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333173,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340108,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347362,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350330,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581364260,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423417,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432812,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581446738,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507373,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589951423,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529875,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594865,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611392,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581646173,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680787,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698859,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733249,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581748194,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152641,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350905,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588123826,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589824818,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071579356832,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604694292,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076779,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604725815,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579302443,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366353,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579368156,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579379323,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579402326,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412670,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579430341,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604820691,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203994,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307552,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323773,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360497,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392581,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399400,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406674,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408923,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581423908,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484809,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497052,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510962,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571741,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590178950,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594772,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657181,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581682304,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581720140,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752755,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772299,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806801,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820285,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229921,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449769,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588328626,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590051042,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071579361072,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609044712,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579086995,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579138752,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579332403,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393371,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579397354,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411702,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579418683,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range",
        "arch/x86/mm/pat/set_memory.c:unmap_pte_range",
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579455848,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609159008,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394488,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499275,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521930,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071581557942,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590880,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597652,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581603691,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607203,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627187,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690011,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581698228,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_ra_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581719142,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789680,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591197242,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809378,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875897,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581900830,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939468,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973147,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581993033,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023379,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037347,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458848,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582744713,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585044485,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
      "file": "lib/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591150762,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:828",
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
      "addr": 18446744071579394767,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581515536,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612108068,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579089059,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591251271,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579333987,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397627,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579403722,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579412422,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579422941,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591273100,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612229606,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191070,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581438006,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539435,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596861,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071581602857,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636896,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643836,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581650987,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654623,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672883,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696170,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ioremap.c:ioremap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739755,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745204,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581767046,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837104,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591692155,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581856994,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924377,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946363,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581986537,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021355,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042601,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072532,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086179,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515760,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582818121,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591236746,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
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
      "addr": 18446744071591267347,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581560464,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614247906,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579095618,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591195033,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579336682,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400881,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579406908,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415542,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579425939,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216048,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614370384,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220531,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334841,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458403,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562764,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600205,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071581625383,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658540,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665341,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581673637,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676115,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699304,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768040,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773349,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581794068,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867936,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591634916,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892095,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947283,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972290,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582014187,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047853,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069080,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097554,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111832,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545335,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582848427,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591179412,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:827",
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
      "addr": 18446744071591209667,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581582096,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615168028,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579118975,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592060818,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579391996,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579463218,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579469458,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579478422,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579489603,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592092738,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615302362,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581460515,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583017,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581827404,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866628,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071581892871,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926812,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581934029,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581942984,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945314,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971100,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050696,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055986,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582077989,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158976,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592809020,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate",
        "mm/sparse-vmemmap.c:vmemmap_remap_range",
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186799,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251925,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582274979,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582316891,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354636,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381245,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412231,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582428152,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861454,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583181483,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592035492,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:798",
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
      "addr": 18446744071592083371,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071581847056,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616934052,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_pud"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579151548,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593827327,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579458500,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539534,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579546348,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579556997,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579569695,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593859873,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617082633,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581807761,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939783,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582220341,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582248401,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pages",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071582290973,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303877,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333649,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582343020,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582352536,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354644,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394277,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476310,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582492716,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582517697,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614244,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582630034,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_p4d_range",
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": [
        "mm/sparse-vmemmap.c:__populate_section_memmap",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ]
    },
    {
      "addr": 18446744071582646522,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582730990,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740510,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758355,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809113,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854891,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882774,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925352,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944862,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431995,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583669188,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593800914,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:796",
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
      "addr": 18446744071579533344,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582239360,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071582630656,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627539862,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579200403,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579270982,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:map_tboot_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579547660,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642975,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579645607,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579664036,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678004,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717035,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627737952,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582234383,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_get_pgtable_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374822,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508112,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582709727,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736566,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:insert_pages",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071582783481,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798348,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834570,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844323,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582853849,
      "name": "pmd_page_vaddr",
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
      "addr": 18446744071582856619,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range",
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900545,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582990721,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583007561,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583036452,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121873,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137927,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596454073,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166429,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251545,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271792,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583291836,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350261,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401744,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432599,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481033,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501773,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584020006,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584275990,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595746681,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:813",
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
      "addr": 18446744071582738064,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619286032,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579204459,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579562956,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579657023,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579660016,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579678180,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579691842,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579730603,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619497067,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582960884,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072040,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078479,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115675,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332145,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:vmemmap_remap_range",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596995401,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596270963,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:814",
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
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621578528,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_cleanmfnmap_p4d"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579233803,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/espfix_64.c:init_espfix_ap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579590492,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690895,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579693962,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579712324,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579726370,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579765547,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621793899,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:sme_populate_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138377,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254024,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260809,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298571,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page",
        "mm/vmalloc.c:vmap_pages_pud_range",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/vmalloc.c:vmap_range_noflush"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583567650,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_pmd_entry",
        "mm/hugetlb_vmemmap.c:vmemmap_split_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597924889,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:compound_section_tail_page",
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597155699,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:1029",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224497612,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "arch/arm/mm/flush.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/flush.c:__flush_anon_page",
        "arch/arm/mm/flush.c:flush_icache_alias"
      ],
      "caller_func": []
    },
    {
      "addr": 3243280368,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "arch/arm/mm/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/mmu.c:arm_pte_alloc",
        "arch/arm/mm/mmu.c:pte_offset_late_fixmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3224503328,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "arch/arm/mm/dump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/dump.c:walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3224509788,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "arch/arm/mm/highmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/mm/highmem.c:kmap_atomic_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "arch/arm/mm/copypage-v6.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226567560,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:apply_to_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226632904,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236447012,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/arm/include/asm/pgtable.h:189",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271359514,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "arch/riscv/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/fault.c:do_page_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272622350,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272713280,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272721778,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272743232,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765368,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272767932,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272770834,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272771726,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272781860,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272827702,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272839222,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272851934,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
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
      "addr": 18446743936270897054,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272910636,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272955406,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272984120,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024290,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273030984,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273385370,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273560862,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279720322,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:173",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604620573,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579077131,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604652118,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298251,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362257,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579364060,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375227,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398230,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408510,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426181,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604734571,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172842,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276400,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292621,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329345,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361429,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368248,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375522,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377771,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581392756,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453657,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465767,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479698,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540477,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589781238,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563508,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625917,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651040,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581688876,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721491,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741035,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775537,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789021,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198657,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418505,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935410,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589653298,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071579356976,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579009840,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604619804,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579234071,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292940,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295307,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304683,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:lookup_address_in_pgd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579327558,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338225,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:ptdump_walk_pgd_level_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579355278,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604702192,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119629,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222873,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237020,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273088,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305856,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311619,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318792,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321630,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335393,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395902,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407995,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421417,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581482009,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589504055,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505088,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568150,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581589698,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581627891,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660281,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679763,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:add_to_kill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713724,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581726647,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135533,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357835,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587648515,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589379143,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604698388,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579076715,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729881,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579299451,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362177,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579363980,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579375147,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579398150,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579408430,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579426101,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604812138,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164042,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267600,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283821,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320545,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352629,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359448,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366722,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368971,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581383956,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444857,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457100,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581471010,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531789,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590224646,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554820,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617229,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642352,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581680188,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712803,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732347,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766849,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780333,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189137,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408985,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588267186,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590096674,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071579356896,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```

```json
{
  "name": "pmd_page_vaddr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604698394,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pagetable_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579080811,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/espfix_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604729927,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/tboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/tboot.c:tboot_late_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579308283,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/kernel/machine_kexec_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/machine_kexec_64.c:init_transition_pgtable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370609,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:fill_pte",
        "arch/x86/mm/init_64.c:fill_pte"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:phys_pmd_init"
      ]
    },
    {
      "addr": 18446744071579372412,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579383627,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:unmap_pte_range",
        "arch/x86/mm/pageattr.c:unmap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579406646,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmd_free_pte_page",
        "arch/x86/mm/pgtable.c:pud_free_pmd_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579417294,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/dump_pagetables.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/dump_pagetables.c:walk_pud_level"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579435285,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/pti.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pti.c:pti_user_pagetable_walk_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604824848,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/mm/mem_encrypt_identity.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_identity.c:__sme_map_range_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230311,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331456,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347805,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384522,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416565,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423354,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430616,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432843,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581447972,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509337,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521532,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581535788,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594406,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590275004,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_pte_populate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619873,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685673,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708736,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071581746956,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780340,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581800635,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:dev_pagemap_mapping_shift"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835681,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849314,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265247,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489858,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402354,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
      "file": "arch/x86/power/hibernate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/power/hibernate.c:relocate_restore_code"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590146930,
      "name": "pmd_page_vaddr",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:792",
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
      "addr": 18446744071579365328,
      "name": "pmd_page_vaddr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int pmd_page_vaddr(pmd_t pmd)
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
long unsigned int pmd_page_vaddr(pmd_t pmd)
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
