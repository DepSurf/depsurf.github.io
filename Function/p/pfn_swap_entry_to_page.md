# Function: <code>pfn_swap_entry_to_page</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
```

```json
{
  "name": "pfn_swap_entry_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581861627,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071581944406,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252884,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582275500,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582327334,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582426383,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583180121,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847696,
      "name": "pfn_swap_entry_to_page",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
```

```json
{
  "name": "pfn_swap_entry_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581948355,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256603,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582335205,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582584826,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741058,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582759192,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582836554,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582942886,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583674866,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:370",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240144,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
```

```json
{
  "name": "pfn_swap_entry_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582382439,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582748168,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_pte_range"
      ],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071582836111,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583115278,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177448,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583272828,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583302688,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    },
    {
      "addr": 18446744071583367594,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583499735,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584283896,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:462",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582730592,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071583285312,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071584274240,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
```

```json
{
  "name": "pfn_swap_entry_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582583095,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582946688,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583051464,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325724,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583393932,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496228,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583522614,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    },
    {
      "addr": 18446744071583587338,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583714738,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584513033,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582946688,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071583505248,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    },
    {
      "addr": 18446744071584504688,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
```

```json
{
  "name": "pfn_swap_entry_to_page",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582754231,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:migration_entry_wait_on_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583122624,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte",
        "mm/memory.c:copy_nonpresent_pte"
      ]
    },
    {
      "addr": 18446744071583233170,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561812,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634306,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:break_ksm_pmd_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583687247,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717322,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    },
    {
      "addr": 18446744071583778234,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583915400,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743504,
      "name": "pfn_swap_entry_to_page",
      "external": false,
      "loc": "include/linux/swapops.h:458",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ],
      "caller_func": [
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_page_category",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:pte_to_pagemap_entry",
        "fs/proc/task_mmu.c:smaps_hugetlb_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122624,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071583699808,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071584732784,
      "name": "pfn_swap_entry_to_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct page * pfn_swap_entry_to_page(swp_entry_t entry)
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
