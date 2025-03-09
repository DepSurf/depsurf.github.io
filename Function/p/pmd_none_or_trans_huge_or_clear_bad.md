# Function: <code>pmd_none_or_trans_huge_or_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580669875,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690253,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580745636,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580751053,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762920,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580811346,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921778,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434584,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:680",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
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
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580766853,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789845,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803870,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830043,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834853,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864819,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580871365,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580885262,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937556,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077656,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619679,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:689",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580832416,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580854296,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868910,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895565,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580901029,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580906787,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580939269,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953357,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009296,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581153247,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581708079,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:703",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580875079,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580900745,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913979,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580940440,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945565,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580951398,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580983483,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580998560,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056904,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200517,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761711,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:817",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580969646,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580997609,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013182,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040353,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045144,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053989,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581086423,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581109749,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581168523,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251066,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330445,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907397,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:870",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581104700,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581131776,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147742,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581175872,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182779,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192586,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581229385,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245677,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581313230,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393637,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478777,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092933,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:913",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581184531,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581213271,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227566,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259234,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265223,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275746,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312361,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329197,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394836,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479283,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568969,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187317,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254729,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581268859,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301635,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332917,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339805,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350185,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423174,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448586,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507049,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680563,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582350695,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313526,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581327643,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360275,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392325,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399094,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408782,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581484566,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446744071581512810,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581571417,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658412,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752531,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449559,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581502991,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581540920,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557731,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590629,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581598660,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607771,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581689779,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
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
      "addr": 18446744071581720212,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789470,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581877049,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972931,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042179,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744514,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1165",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581543151,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581584104,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602646,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581636676,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645023,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655195,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581739523,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
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
      "addr": 18446744071581768120,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836894,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925299,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582021139,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091139,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817922,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1255",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581334221,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581566183,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581606395,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625167,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658324,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666511,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676682,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581767811,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
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
      "addr": 18446744071581795876,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867726,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948488,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047633,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116211,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848226,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1267",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842448,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581582397,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581830949,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581873515,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": [
        "mm/memory.c:finish_fault"
      ]
    },
    {
      "addr": 18446744071581892655,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581926596,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935374,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945879,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582050467,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
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
      "addr": 18446744071582079854,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158766,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582253068,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354417,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381034,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432595,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583181282,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1286",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581849120,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071583175792,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581939070,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582224068,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582271754,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290758,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333389,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582345021,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355310,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582476069,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
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
      "addr": 18446744071582519656,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614041,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741838,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854691,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882433,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582949219,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668989,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1348",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666416,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582374097,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_map_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713879,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582763786,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783244,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582834292,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846264,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857409,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582990451,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
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
      "addr": 18446744071583037691,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137696,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273145,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401511,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432237,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506437,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275763,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/linux/pgtable.h:1371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584273552,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492720800,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492752168,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492765112,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798052,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492801976,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492808772,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492902932,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446603336492935060,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493008356,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493206028,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494062476,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226570080,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226694164,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226719608,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286064116,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286111732,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286129568,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286169800,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286177268,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286188104,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286304412,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 13835058055286345688,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286435988,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286573776,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286712936,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287723024,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272725354,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272828752,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272853286,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581282374,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581296491,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329123,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361173,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367942,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377630,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581453414,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446744071581481546,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581540153,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627148,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721267,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418295,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581228333,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259492,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272928,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305677,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311357,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321501,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395710,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446744071581423862,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481845,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568374,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660097,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582357670,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273574,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287691,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320323,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352373,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359142,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368830,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581444614,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446744071581472858,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531465,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618460,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712579,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582408775,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_none_or_trans_huge_or_clear_bad",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581337447,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581351835,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384300,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416309,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423048,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432702,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581509094,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
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
      "addr": 18446744071581537672,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:try_to_unuse"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594085,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686900,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780113,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582489648,
      "name": "pmd_none_or_trans_huge_or_clear_bad",
      "external": false,
      "loc": "include/asm-generic/pgtable.h:951",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```
</details>
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
int pmd_none_or_trans_huge_or_clear_bad(pmd_t * pmd)
```
</details>
</li>
</ul>
