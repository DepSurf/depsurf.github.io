# Function: <code>pmd_trans_huge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580657934,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580668782,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690231,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714866,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718313,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580723446,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745649,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751069,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762941,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811319,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900794,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:page_check_address_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921745,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973369,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314999,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434566,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580554932,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580766817,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789777,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803732,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830232,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834787,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841971,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864311,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580871302,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885299,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938843,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032101,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077407,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128628,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481853,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619447,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580620075,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832380,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask",
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854228,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868772,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895747,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900963,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580905263,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
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
      "addr": 18446744071580906279,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580912515,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:page_check_address_transhuge",
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939206,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953387,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009255,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107396,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153011,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581203698,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562736,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583771,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707847,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:179",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580645323,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879339,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899277,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913835,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940464,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945499,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950055,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
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
      "addr": 18446744071580952442,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580957488,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983421,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998560,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056851,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157577,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200307,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252410,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618345,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642605,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761479,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:212",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580728651,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964268,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ]
    },
    {
      "addr": 18446744071581001861,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013135,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040269,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045095,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050756,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581054286,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581059164,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086341,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109775,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168472,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251016,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280249,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330402,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384318,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394277,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762803,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788135,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault",
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907345,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:227",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962672,
      "name": "pmd_trans_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864350,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581100584,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139007,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147693,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178917,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection",
        "mm/mprotect.c:change_protection",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182728,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189792,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192525,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197859,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229334,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245690,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313177,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393743,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581428783,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478732,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534571,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581544823,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581931641,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961751,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582092879,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:237",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581097584,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580930129,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178629,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211945,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227517,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259247,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265172,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272765,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275677,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281203,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312310,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329210,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394783,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479389,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581514602,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568924,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620556,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627751,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016057,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045267,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582187263,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:239",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581177312,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029579,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581248847,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581288083,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301586,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581334862,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339754,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347229,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350116,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355827,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423123,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448595,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506996,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624217,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680510,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732931,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746839,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152596,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209629,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582350641,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247040,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581083892,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307455,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346803,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360226,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394424,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399043,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581406541,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408730,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581415363,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484515,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581512819,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571364,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658518,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695090,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752478,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806483,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581819119,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229876,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290525,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582449505,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581305584,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581269988,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581502778,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581551352,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_fault_around",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557682,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590693,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598572,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604866,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608016,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581616531,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689747,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581720221,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789425,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877147,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581912677,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972878,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582027138,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036750,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042320,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582458813,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582577988,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744460,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:261",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311544,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542938,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581594488,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_fault_around",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602594,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636709,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644941,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652528,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655440,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581663523,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739491,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581768129,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836849,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925402,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581958367,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021086,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075789,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085582,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091280,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582515725,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582649288,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817868,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581333933,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575347,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615112,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625115,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658357,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666437,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673506,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676927,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581685532,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767779,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581795885,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867681,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948591,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581984352,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047580,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582100794,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110919,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116352,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582545300,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582678367,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848172,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:260",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581582109,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581839977,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581881778,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892603,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926629,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935292,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942855,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946138,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581954992,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050435,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071582079863,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158721,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253171,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286337,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354364,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380980,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417194,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427239,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432736,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582861419,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583004503,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181228,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:231",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581938875,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582232102,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284016,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290700,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303728,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333466,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582344956,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352440,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355445,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582370253,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582476038,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071582519665,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613998,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741988,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770236,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854640,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882381,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931293,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943854,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949369,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431961,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583475135,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668937,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:234",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582373899,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582513645,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582712945,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582776446,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783190,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798195,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834362,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846194,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853739,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857067,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582990420,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071583037704,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137652,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166237,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273427,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583304860,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331481,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401456,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432186,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487028,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500782,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506600,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019973,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584067695,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275711,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:235",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582578848,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582715674,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938817,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582992709,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000201,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012348,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052359,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583061807,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070123,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072788,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583078347,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201275,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348195,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382361,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495012,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
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
      "addr": 18446744071583524160,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583550313,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622215,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651321,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702595,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715130,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721753,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584239062,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584294082,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584506214,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:236",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582749390,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885009,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:walk_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583114047,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174521,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179577,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191460,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234007,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583243369,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252025,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254836,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583260682,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583436764,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583584207,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622044,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683063,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718864,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583744521,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:find_pmd_or_thp_or_none"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816884,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845849,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905143,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916026,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583922585,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584451175,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584510898,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pmd_fault",
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735583,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:272",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282719392,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "arch/powerpc/mm/pgtable.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/pgtable.c:__find_linux_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055282816752,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285722920,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286057360,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ]
    },
    {
      "addr": 13835058055286111920,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286129776,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286169808,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286177948,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183920,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286189040,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286196192,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286304404,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 13835058055286345700,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286436400,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286574816,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286623764,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286713360,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286799900,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286818336,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287413672,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287496148,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287723232,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:1211",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286052176,
      "name": "pmd_trans_huge",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:885",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052740,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276303,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315651,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329074,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363272,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367891,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375389,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377578,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581384211,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453363,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581481555,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540100,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627254,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663826,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721214,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775219,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787855,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198612,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582259261,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582418241,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581274432,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581000004,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222765,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258721,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272899,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305689,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311306,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581318745,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321456,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range",
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326975,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395694,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423871,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481808,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568492,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603503,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660069,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713532,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581725772,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135504,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582196183,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582357633,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
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
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581043940,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267503,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306851,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320274,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354472,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359091,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581366589,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368778,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581375411,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444563,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581472867,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531412,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618566,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655138,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712526,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766531,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779167,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189092,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582249741,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582408721,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581265632,
      "name": "pmd_trans_huge",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```

```json
{
  "name": "pmd_trans_huge",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581105625,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331359,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370851,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384251,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418454,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581422997,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430483,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432650,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581439267,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:mm_find_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509043,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071581537681,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594031,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687006,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721527,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780060,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835363,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581848127,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582265202,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327770,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582489594,
      "name": "pmd_trans_huge",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:256",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:gather_pte_stats",
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
      "addr": 18446744071581329488,
      "name": "pmd_trans_huge",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int pmd_trans_huge(pmd_t pmd)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pmd_trans_huge(pmd_t pmd)
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
int pmd_trans_huge(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pmd_trans_huge(pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pmd_trans_huge(pmd_t pmd)
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
int pmd_trans_huge(pmd_t pmd)
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
