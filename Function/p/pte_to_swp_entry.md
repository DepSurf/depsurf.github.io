# Function: <code>pte_to_swp_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580656832,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580670266,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580690661,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715366,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751397,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580771484,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790999,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880026,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:__migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920147,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434096,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580765079,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785238,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580804250,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580829277,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580871645,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927482,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013981,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067391,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618118,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830662,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849599,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869297,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896333,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904358,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939534,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995814,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088157,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142688,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706539,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580873392,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895023,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580914295,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939810,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580949263,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580983749,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SyS_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044551,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135630,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189895,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762849,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580967943,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580992798,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581013617,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041215,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050232,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086737,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098131,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:SYSC_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581155037,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251608,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320082,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581910750,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581099753,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127119,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581148168,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176681,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581188927,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581229711,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581238369,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298406,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393331,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465588,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581546111,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582097783,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:66",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581182505,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206367,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581227995,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260498,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273946,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581312687,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581321777,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381980,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478948,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581549924,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629477,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192186,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581252828,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581280783,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302078,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333769,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348345,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423506,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581432870,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493275,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581594576,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665559,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746027,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582355506,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581311436,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581339503,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360718,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393177,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407657,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581484898,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497110,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557770,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581657331,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737847,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581818017,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582454402,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581501135,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537239,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_one_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581558169,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591372,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604103,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581690105,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581702255,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768076,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876213,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581949205,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582035903,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582744060,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581541301,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580615,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581603084,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637388,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581651396,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581739849,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749976,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772405,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581815689,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581925035,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581997029,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582084751,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582816396,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581564179,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581601767,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625600,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659031,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674607,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581768133,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777798,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799765,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844315,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581948220,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582023637,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582109890,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582845305,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte)
```

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581828947,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581861537,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071581893088,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927303,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943856,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582050789,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060886,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582084181,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135546,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252801,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327141,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582378902,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426040,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583177355,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:75",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851936,
      "name": "pte_to_swp_entry",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte)
```

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582222021,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268044,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582291265,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334511,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353023,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582377931,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582477202,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582499207,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524021,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584731,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582731117,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582740968,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836796,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582879788,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925941,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582942304,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583423053,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583667675,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:77",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245472,
      "name": "pte_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
swp_entry_t pte_to_swp_entry(pte_t pte)
```

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582757247,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582783786,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835417,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854647,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881323,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991196,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013159,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042213,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:arch_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115180,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_mcopy_atomic_pte"
      ]
    },
    {
      "addr": 18446744071583177351,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583251709,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait_huge",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583271940,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380518,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583428640,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583481676,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583499153,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584011388,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584278659,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732624,
      "name": "pte_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071583068160,
      "name": "pte_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
swp_entry_t pte_to_swp_entry(pte_t pte)
```

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582975320,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583000515,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
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
      "addr": 18446744071583050678,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583069087,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096515,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583201865,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221694,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250708,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325627,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
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
      "addr": 18446744071583393839,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583471311,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495322,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559672,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600988,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583649744,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583698087,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583714247,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584235907,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584508729,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949104,
      "name": "pte_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
swp_entry_t pte_to_swp_entry(pte_t pte)
```

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583170552,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:handle_pte_marker",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583179891,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
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
      "addr": 18446744071583232457,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583250959,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:map_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278744,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437405,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457030,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swap_vma_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485188,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:generic_max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561714,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583584588,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634214,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663615,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migration_entry_wait_huge",
        "mm/migrate.c:migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686563,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583759568,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797269,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844560,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:check_hwpoisoned_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583903409,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages_pte",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914996,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450254,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584731922,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:133",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_hugetlb_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_hugetlb_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583128736,
      "name": "pte_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492719376,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492745536,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492765260,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492799000,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492806248,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492903112,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492917316,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492932576,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492998108,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493108560,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186636,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493283192,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494061288,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226550824,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226577692,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226584628,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226612752,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226619352,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 3226695440,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3226708224,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 3226719840,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226805256,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226821000,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3226887376,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3227521920,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286056080,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286101652,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286130428,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286171248,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286185988,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286305048,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286324356,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286342232,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286423136,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286572252,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286689416,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286816460,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287722460,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272713262,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272730306,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272743292,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765526,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272770556,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272827746,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272839258,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272851396,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272899770,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_huge_pmd",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272955168,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272964860,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273031022,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273560892,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581280284,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308351,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329566,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362025,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376505,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581453746,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465823,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526506,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626067,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706583,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786753,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582423138,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581226625,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581252159,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273172,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306405,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319611,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395992,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581408055,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420702,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468580,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581567256,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645582,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724930,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582357199,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581271484,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581299551,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581320766,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353225,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367705,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444946,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581457158,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517818,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617379,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697895,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778065,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582413618,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
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
  "name": "pte_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581335356,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363535,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384741,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:mincore_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417159,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431644,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:check_pte",
        "mm/page_vma_mapped.c:check_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509427,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521590,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
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
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:max_swapfile_size",
        "mm/swapfile.c:unuse_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582808,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:is_hugetlb_entry_hwpoisoned",
        "mm/hugetlb.c:is_hugetlb_entry_migration"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685823,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581765031,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846993,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582493050,
      "name": "pte_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:65",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
swp_entry_t pte_to_swp_entry(pte_t pte)
```
</details>
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
