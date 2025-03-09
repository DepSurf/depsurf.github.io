# Function: <code>pmd_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746736,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:31",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:free_pgd_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746736,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865952,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:31",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865952,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907920,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:31",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_mask",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907920,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580953376,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:37",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580953376,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055120,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:38",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055120,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193840,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:38",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193840,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277120,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277120,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351568,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351568,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411072,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411072,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611184,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:48",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:apply_to_p4d_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_p4d_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611184,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581658528,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:48",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:pte_alloc_one_map",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:__apply_to_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_p4d_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581658528,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581680336,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:48",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680336,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581949616,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:48",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_pmd_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vunmap_range_noflush",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949616,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359088,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:49",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359088,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582861392,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:49",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_map_pmd",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:finish_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vunmap_p4d_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_vma",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/mapping_dirty_helpers.c:wp_clean_pmd_entry",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582861392,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583076896,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:51",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/pgtable-generic.c:__pte_offset_map",
        "mm/vmalloc.c:vunmap_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583076896,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583259152,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:52",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:apply_to_pmd_range",
        "mm/memory.c:copy_p4d_range",
        "mm/memory.c:free_pud_range",
        "mm/pgtable-generic.c:__pte_offset_map",
        "mm/vmalloc.c:vunmap_p4d_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583259152,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492810096,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492810096,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226620980,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/pgd.c:pgd_free",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:unuse_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226620980,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286191384,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range",
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/vmalloc.c:vunmap_page_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286191384,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272772658,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272772658,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379920,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379920,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323784,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_pmd_mask",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:alloc_set_pte",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pgd_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pagewalk.c:walk_pgd_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323784,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371120,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371120,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pmd_clear_bad(pmd_t * pmd)
```

```json
{
  "name": "pmd_clear_bad",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435008,
      "name": "pmd_clear_bad",
      "external": true,
      "loc": "mm/pgtable-generic.c:39",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:free_pud_range",
        "mm/mincore.c:mincore_pte_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:swapin_walk_pmd_entry",
        "mm/swapfile.c:try_to_unuse",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435008,
      "name": "pmd_clear_bad",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
