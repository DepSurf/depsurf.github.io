# Function: <code>__mmu_notifier_invalidate_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826288,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:230",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826288,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951856,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:230",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951856,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025136,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:230",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025136,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071360,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:217",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/dax.c:dax_writeback_mapping_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071360,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182480,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:224",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182480,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327216,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:224",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327216,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411152,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:226",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411152,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524272,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:224",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524272,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590384,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590384,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804912,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:584",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804912,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852576,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852576,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883264,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883264,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582177904,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582177904,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637184,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637184,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583158784,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583158784,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583369152,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:607",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583369152,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493029560,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/madvise.c:tlb_flush_mmu_tlbonly",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493029560,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226746684,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:tlb_flush_mmu_tlbonly"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226746684,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286460672,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286460672,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272903982,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:unmap_page_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272903982,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559120,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559120,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500768,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500768,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550432,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550432,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615568,
      "name": "__mmu_notifier_invalidate_range",
      "external": true,
      "loc": "mm/mmu_notifier.c:231",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/memory.c:wp_page_copy",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615568,
      "name": "__mmu_notifier_invalidate_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __mmu_notifier_invalidate_range(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```
</details>
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
