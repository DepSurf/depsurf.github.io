# Function: <code>is_swap_pmd</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580969597,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001565,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012986,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040212,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045049,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581053894,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581168159,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581250952,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276454,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330261,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788071,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581907067,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581104621,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581138821,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147550,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179079,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection",
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183685,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581192508,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581312866,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393560,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425254,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478597,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961698,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582092602,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:184",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581184452,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581211771,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227374,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259011,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581266079,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581275656,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394402,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479206,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510854,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568789,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582048013,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582186986,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:190",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581254629,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581287902,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581301434,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335031,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340664,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350095,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581506594,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620454,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680374,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582212405,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582350362,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:205",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581313155,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581346622,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360074,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394589,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399976,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408717,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581486635,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570962,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581658335,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691302,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581752342,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582293301,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582449226,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int is_swap_pmd(pmd_t pmd)
```

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581497488,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581551181,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557530,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592508,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581599227,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607675,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581691919,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789314,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876972,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581908742,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581972742,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582577845,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744186,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:246",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581497488,
      "name": "is_swap_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int is_swap_pmd(pmd_t pmd)
```

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581538000,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581594317,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602439,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638527,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581645668,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581655099,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581736783,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836738,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925221,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581953910,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582020950,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582649155,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817594,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:225",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581538000,
      "name": "is_swap_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int is_swap_pmd(pmd_t pmd)
```

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581559792,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581614708,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624968,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660158,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581667314,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676586,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581765128,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867570,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948410,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581979430,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047446,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678314,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582847898,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559792,
      "name": "is_swap_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int is_swap_pmd(pmd_t pmd)
```

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581824048,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581881765,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_pmd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892456,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928493,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581936392,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581945783,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582047789,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158613,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252990,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582281702,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582354230,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380810,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583004284,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583180954,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:230",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581824048,
      "name": "is_swap_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int is_swap_pmd(pmd_t pmd)
```

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582216192,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/gup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582284003,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582290523,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303554,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336250,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582344943,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582352474,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582355234,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582478776,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613877,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731559,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741756,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770547,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854461,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582882202,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943932,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474783,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583668650,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:244",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216192,
      "name": "is_swap_pmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582713489,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582776433,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582783022,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582798050,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837280,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582846181,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582853773,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582857319,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582992329,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137525,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252183,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583273063,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583305189,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583401262,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583431994,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500869,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584067340,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584275418,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:229",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582927880,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582992696,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583000022,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012176,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583052346,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583061794,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583070157,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072736,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583078291,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202707,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583348044,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471655,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494934,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583524481,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583621750,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651108,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583715257,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584293727,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584505894,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:191",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583102044,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583174508,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_p4d_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179398,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191282,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:mlock_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583233994,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583243356,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583252059,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254784,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583260630,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583439225,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583584046,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range",
        "mm/mempolicy.c:queue_folios_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663959,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686165,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719233,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583816422,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583845636,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:hwpoison_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583905090,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages",
        "mm/userfaultfd.c:move_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583916152,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510543,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584735254,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:312",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492720752,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751912,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492764996,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492798020,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492801972,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492808708,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493008196,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493136688,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493206024,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494062420,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/mremap.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282816644,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "arch/powerpc/mm/book3s64/subpage_prot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/book3s64/subpage_prot.c:subpage_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286064060,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286111284,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286129540,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286169712,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286178068,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286188096,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286308012,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286435984,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286573724,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286619512,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286712928,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287499256,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287723016,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:356",
      "file": "mm/mremap.c",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581282003,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581315470,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328922,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363437,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368824,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581377565,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581455483,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539698,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627071,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660038,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721078,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582262037,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582417962,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581228237,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask",
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258667,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272746,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305513,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312350,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321437,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pagewalk.c:walk_pgd_range"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581481442,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568274,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581599862,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659929,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198924,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582357354,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581273203,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581306670,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320122,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581354637,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360024,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368765,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581446683,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531010,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618383,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651350,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581712390,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252517,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582408442,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
  "name": "is_swap_pmd",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581337076,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581370670,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384106,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418614,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423917,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432637,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/pagewalk.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581511147,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593618,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686823,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581717782,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__pmd_trans_huge_lock",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581779926,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327717,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582489322,
      "name": "is_swap_pmd",
      "external": false,
      "loc": "include/linux/huge_mm.h:210",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int is_swap_pmd(pmd_t pmd)
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
int is_swap_pmd(pmd_t pmd)
```
</details>
</li>
</ul>
