# Function: <code>vm_normal_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580669072,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:750",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:copy_page_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:can_gather_numa_stats",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669072,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779024,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:752",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779024,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843744,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:754",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843744,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889216,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:820",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:copy_page_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889216,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581270640,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270640,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581329440,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581329440,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526800,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:592",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_one_pte",
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mc_handle_present_pte",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526800,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570752,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:594",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570752,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591776,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:606",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591776,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581858592,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:605",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:__munlock_pagevec_fill",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581858592,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253216,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:612",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/mlock.c:mlock_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253216,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582744592,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:565",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/mlock.c:mlock_pte_range",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:can_change_pte_writable",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582744592,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582961120,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:584",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:vm_normal_folio",
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:can_change_pte_writable",
        "mm/ksm.c:break_ksm_pmd_entry",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/hmm.c:hmm_vma_handle_pte",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961120,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583138624,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:582",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:get_gate_page",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_present_pte",
        "mm/mprotect.c:can_change_pte_writable",
        "mm/ksm.c:break_ksm_pmd_entry",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/hmm.c:hmm_vma_handle_pte",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583138624,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492737072,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492737072,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226567668,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226567668,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286086576,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286086576,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272724950,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272724950,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581298288,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581298288,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581243328,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_protection_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581243328,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581289488,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289488,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```

```json
{
  "name": "vm_normal_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581353616,
      "name": "vm_normal_page",
      "external": true,
      "loc": "mm/memory.c:574",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_wp_page",
        "mm/mlock.c:munlock_vma_pages_range",
        "mm/mprotect.c:change_pte_range",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353616,
      "name": "vm_normal_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct page * vm_normal_page(struct vm_area_struct * vma, long unsigned int addr, pte_t pte)
```
</details>
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
