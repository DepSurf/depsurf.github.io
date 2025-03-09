# Function: <code>__mmu_notifier_invalidate_range_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580826128,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:205",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580826128,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580951696,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:205",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580951696,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024976,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:205",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:khugepaged",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024976,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581071200,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:192",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581071200,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581182304,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:192",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/khugepaged.c:khugepaged",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581182304,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void __mmu_notifier_invalidate_range_end(struct mm_struct * mm, long unsigned int start, long unsigned int end, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327040,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:192",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327040,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410992,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:194",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_vma",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410992,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524576,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:192",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524576,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581590208,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581590208,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581804704,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:569",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_collect",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581804704,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852368,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_collect",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852368,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581883056,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883056,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592216759,
      "name": "__mmu_notifier_invalidate_range_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582177680,
      "name": "__mmu_notifier_invalidate_range_end",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:migrate_vma_pages",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593995607,
      "name": "__mmu_notifier_invalidate_range_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071582636960,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596044977,
      "name": "__mmu_notifier_invalidate_range_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583158544,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:592",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596567411,
      "name": "__mmu_notifier_invalidate_range_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583368912,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:574",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/userfaultfd.c:move_pages_pte",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597472853,
      "name": "__mmu_notifier_invalidate_range_end.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583605760,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493029344,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493029344,
      "name": "__mmu_notifier_invalidate_range_end",
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226746460,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226746460,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286460320,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286460320,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272903834,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:try_to_merge_one_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272903834,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558944,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558944,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581500592,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581500592,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581550256,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581550256,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range, bool only_end)
```

```json
{
  "name": "__mmu_notifier_invalidate_range_end",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581615392,
      "name": "__mmu_notifier_invalidate_range_end",
      "external": true,
      "loc": "mm/mmu_notifier.c:193",
      "file": "mm/mmu_notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/oom_kill.c:__oom_reap_task_mm",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_vma_pages",
        "mm/migrate.c:migrate_vma_setup",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback",
        "mm/khugepaged.c:collapse_huge_page",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581615392,
      "name": "__mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool only_end</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier_range * range</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, start, end, only_end</code> ➡️ <code>range, only_end</code>
</li>
</ul>
</details>
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
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool only_end</code>
</li>
</ul>
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
