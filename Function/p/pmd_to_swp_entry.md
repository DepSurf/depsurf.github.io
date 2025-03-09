# Function: <code>pmd_to_swp_entry</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580968576,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001632,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581051802,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    },
    {
      "addr": 18446744071581169022,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581257410,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293496,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910189,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049904,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190939,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403644,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440595,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582096108,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:272",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581274097,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581487132,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524019,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190533,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:268",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348568,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595275,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581632957,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353894,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407880,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665835,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581703997,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452790,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581551237,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606029,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581887339,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581920029,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582746354,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581603568,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581594373,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581653460,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ]
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581933243,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966717,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582818594,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:255",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650864,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581565291,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581614771,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674849,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867367,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581958579,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994798,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582111184,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582846158,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:262",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581830057,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581882128,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944097,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582158405,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582263315,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582296990,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582427504,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179921,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:285",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582284388,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353492,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613456,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582731606,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582784812,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071582943985,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676267,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:405",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582750688,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582776858,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582854993,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583137099,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583252230,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583317772,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583500921,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584283726,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:500",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583284224,
      "name": "pmd_to_swp_entry",
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
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582993109,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583071180,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583078559,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583347850,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583471702,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583536268,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    },
    {
      "addr": 18446744071583715309,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584512880,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:491",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583503424,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583174950,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583253136,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260928,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/pgtable-generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/pgtable-generic.c:__pte_offset_map"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583836,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_folios_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664006,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730207,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd"
      ],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:copy_huge_pmd"
      ]
    },
    {
      "addr": 18446744071583916204,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584738785,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:496",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:pagemap_thp_category",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583697792,
      "name": "pmd_to_swp_entry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/huge_memory.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/page_vma_mapped.c",
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
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286062576,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286111332,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286183928,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286436128,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286583136,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286637472,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286818032,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287720700,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:290",
      "file": "mm/page_vma_mapped.c",
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
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376728,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581634571,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581672733,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421526,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_pmd_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319704,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/page_vma_mapped.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_vma_mapped.c:page_vma_mapped_walk",
        "mm/page_vma_mapped.c:page_vma_mapped_walk"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581575559,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612205,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582356712,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581367928,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625883,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581664045,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412006,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmd_to_swp_entry",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581431799,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
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
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:queue_pages_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581692237,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:pmd_migration_entry_wait"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730413,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582491446,
      "name": "pmd_to_swp_entry",
      "external": false,
      "loc": "include/linux/swapops.h:253",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
swp_entry_t pmd_to_swp_entry(pmd_t pmd)
```
</details>
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
