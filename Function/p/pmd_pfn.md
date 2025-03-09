# Function: <code>pmd_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594977911,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:150",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277953,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:150",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579281322,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:150",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292665,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:150",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:slow_virt_to_phys",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435509,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:150",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595140696,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579277321,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579280678,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293534,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309402,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580781241,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026410,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617491,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595383378,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/xen/mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu.c:xen_relocate_p2m"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579292649,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295942,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579309034,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579324628,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580843913,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101562,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579662,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581705917,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:161",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579290057,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293190,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579307508,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880720,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580889385,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_normal_page_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150378,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640775,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763343,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range"
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578980144,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579310558,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table"
      ]
    },
    {
      "addr": 18446744071579313727,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:vmalloc_fault",
        "arch/x86/mm/fault.c:vmalloc_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579329803,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602724418,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872171,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580965294,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977635,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:handle_pte_fault",
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
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013357,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040644,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045637,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050810,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086554,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
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
      "addr": 18446744071581110336,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160676,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168647,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191037,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249996,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280125,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303799,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330717,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384702,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394474,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786344,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907523,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305424,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578983326,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579322013,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579341234,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368998,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071602895868,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006128,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101610,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112907,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
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
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071581147874,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176005,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182977,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190042,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581194483,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229514,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
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
      "addr": 18446744071581246301,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303811,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313346,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336676,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392346,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428630,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453801,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478901,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534799,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545271,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959741,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582093051,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:199",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579316560,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581109504,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578981184,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579346317,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable"
      ]
    },
    {
      "addr": 18446744071579368041,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__change_page_attr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579396454,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604693177,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581083376,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179567,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192037,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:apply_to_page_range",
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071581227698,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259356,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265426,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272998,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277859,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312490,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
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
      "addr": 18446744071581329821,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387475,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394952,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420484,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477962,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514453,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538637,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581569093,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620786,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628468,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041033,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187435,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:201",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341296,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581189536,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578988199,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362004,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579382820,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579411836,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604793195,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146361,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249798,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264861,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301763,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333085,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340011,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347462,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352324,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423311,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
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
      "addr": 18446744071581439694,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581499133,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507279,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581529782,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601413,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624078,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642955,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680695,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733156,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747555,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202127,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350813,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356672,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990567,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579366244,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579387124,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579415020,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604818916,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203897,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308406,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323677,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360403,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392493,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399300,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406774,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581411828,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484703,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503918,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581563645,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571647,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594679,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656810,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581694951,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581715044,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752663,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806708,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819816,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282964,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449677,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360912,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579000053,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pmd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579393049,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579425517,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444368,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609157109,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394392,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510813,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531372,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range"
      ]
    },
    {
      "addr": 18446744071581557851,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590788,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597555,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581604914,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607128,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611958,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689908,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581711216,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581774231,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789591,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809286,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581875530,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912504,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581929980,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973055,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023287,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036378,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570671,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744624,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:220",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394819,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071581498560,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581515600,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579001872,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pmd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579397317,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579425213,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579441968,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612227603,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581437910,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550941,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575020,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_numa_page",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pte_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_fault",
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
      "addr": 18446744071581602766,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636804,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581643739,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581652788,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654545,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659286,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739652,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759008,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822375,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837015,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581856902,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924009,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958155,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581976835,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021263,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072443,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085210,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582642991,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818032,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591267399,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071581539296,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071581560752,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579012413,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579400569,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579428212,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579444848,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614368382,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334740,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581458310,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574045,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581600103,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
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
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581625291,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658452,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665243,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672936,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676040,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679942,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581699485,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767940,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581785956,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581851607,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867847,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892006,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946921,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984187,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582004846,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047759,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097464,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111459,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671007,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848336,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:219",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591209719,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581582016,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579030653,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579462891,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579492405,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579509648,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615299933,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582916,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838656,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581879915,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:free_pud_range"
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
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071581892779,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926724,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933593,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581942231,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945238,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949222,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581971282,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050596,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582069732,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582142951,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158887,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582171572,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:vmemmap_remap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582186710,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251561,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286171,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582307288,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354543,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381152,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412140,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427779,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997263,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181392,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:190",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592083423,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071581846976,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579050691,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579539440,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579555217,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579572607,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579593236,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579605109,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581939685,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230760,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279579,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
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
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:insert_pages",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071582290884,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303782,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333560,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342535,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582351792,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354566,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358614,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378495,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582394453,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476213,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508928,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582595899,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614156,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629063,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646434,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582730898,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740125,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770280,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582809038,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854802,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882681,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925259,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944349,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583669098,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:193",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533424,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071582239264,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081668,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579642880,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579662036,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680989,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579704414,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579718923,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374719,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514167,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range",
        "mm/vmscan.c:walk_pmd_range",
        "mm/vmscan.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582721024,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772106,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remap_pfn_range_notrack",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
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
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:apply_to_pte_range",
        "mm/memory.c:insert_pages",
        "mm/memory.c:vm_normal_page_pmd"
      ]
    },
    {
      "addr": 18446744071582783384,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798245,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834471,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582843814,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582853146,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856538,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860841,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmd_mkinvalid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881980,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582900721,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582990617,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583027602,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583121741,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137827,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166332,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251436,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271394,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304908,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot",
        "mm/huge_memory.c:vmf_insert_pfn_pmd_prot"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583350173,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    },
    {
      "addr": 18446744071583401644,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432500,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583480933,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583501279,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275890,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:194",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730144,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071583283936,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071583330848,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579080404,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579656928,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579676212,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579694869,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579717902,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579732546,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716283,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range",
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937424,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582966709,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012565,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060246,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583070682,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583079025,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map_lock",
        "mm/pgtable-generic.c:pte_offset_map_nolock",
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096165,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115851,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583204030,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583332013,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_should_optimize",
        "mm/hugetlb_vmemmap.c:__split_vmemmap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583347493,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583494471,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524208,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549982,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_huge_page"
      ]
    },
    {
      "addr": 18446744071583602998,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583651482,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715719,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584513274,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:195",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549696,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579106180,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:xen_pud_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579690800,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579710340,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pgtable.c:pmdp_invalidate_ad"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579729397,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/pat/set_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pat/set_memory.c:__split_large_page",
        "arch/x86/mm/pat/set_memory.c:__should_split_large_page",
        "arch/x86/mm/pat/set_memory.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579752470,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_pmd_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579767490,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:pg_level_to_pfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885627,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range",
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583112656,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_huge_pmd",
        "mm/gup.c:gup_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583145637,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191939,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range",
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583241718,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583252433,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583261329,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map_lock",
        "mm/pgtable-generic.c:pte_offset_map_nolock",
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278465,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583298747,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:vmalloc_to_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439488,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583567411,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/hugetlb_vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_vmemmap.c:vmemmap_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583502,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685704,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718912,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ]
    },
    {
      "addr": 18446744071583747150,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    },
    {
      "addr": 18446744071583794854,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583846020,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583904515,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583913701,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738536,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697552,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071583742624,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990919,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362148,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579383028,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410860,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604732796,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172745,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581277254,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292525,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329251,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361341,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368148,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375622,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380676,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453551,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472654,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581532381,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540383,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563415,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625546,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663687,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683780,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721399,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775444,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788552,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251700,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418413,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356816,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579292880,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579312765,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:__change_page_attr_set_clr",
        "arch/x86/mm/pageattr.c:slow_virt_to_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579339850,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:clear_page_presence"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604700508,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119564,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223369,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236960,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273043,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305792,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311536,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318890,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323368,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395843,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421374,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581474210,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481960,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505036,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566846,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603460,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622386,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660213,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713682,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581726358,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189531,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357771,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578990503,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579362068,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579382948,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579410780,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604810363,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581163945,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268454,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283725,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320451,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352541,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359348,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366822,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371876,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444751,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581463966,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581523693,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531695,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581554727,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581616858,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581654999,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581675092,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712711,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766756,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779864,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242180,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408893,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356736,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
```

```json
{
  "name": "pmd_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578991703,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:__xen_pgd_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579370500,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:register_page_bootmem_memmap",
        "arch/x86/mm/init_64.c:kern_addr_valid"
      ],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table"
      ]
    },
    {
      "addr": 18446744071579390379,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/pageattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/pageattr.c:__change_page_attr",
        "arch/x86/mm/pageattr.c:__split_large_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579419644,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071604823073,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "arch/x86/mm/mem_encrypt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581230217,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332339,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347712,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
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
        "mm/memory.c:remap_pfn_range",
        "mm/memory.c:__get_locked_pte",
        "mm/memory.c:vm_normal_page_pmd",
        "mm/memory.c:free_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384428,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416477,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423254,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430716,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581435764,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:pmdp_invalidate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509231,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528686,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581588633,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594314,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619781,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685304,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_trans_migrating",
        "mm/migrate.c:migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721390,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741711,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780245,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835588,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848824,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319770,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489766,
      "name": "pmd_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:218",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365168,
      "name": "pmd_pfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
long unsigned int pmd_pfn(pmd_t pmd)
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
long unsigned int pmd_pfn(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int pmd_pfn(pmd_t pmd)
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
long unsigned int pmd_pfn(pmd_t pmd)
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
