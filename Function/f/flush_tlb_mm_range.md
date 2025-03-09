# Function: <code>flush_tlb_mm_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314400,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:186",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "arch/x86/mm/pgtable.c:pmdp_splitting_flush",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314400,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314352,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:306",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314352,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329632,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:321",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/huge_memory.c:move_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329632,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579323264,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:242",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323264,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579348208,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:605",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/memory.c:zap_page_range",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348208,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, long unsigned int vmflag)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359904,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:618",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:copy_mm",
        "kernel/fork.c:copy_mm",
        "mm/memory.c:zap_page_range",
        "mm/mprotect.c:change_protection",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359904,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387408,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:728",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387408,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402976,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402976,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579406224,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406224,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416208,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:949",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:unmap_ldt_struct",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_normal_pmd",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416208,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416288,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:885",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416288,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419328,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:925",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419328,
      "name": "flush_tlb_mm_range",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:984",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088053,
      "name": "flush_tlb_mm_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579482848,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:958",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593854977,
      "name": "flush_tlb_mm_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579561808,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:981",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969670,
      "name": "flush_tlb_mm_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071579669232,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1000",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487262,
      "name": "flush_tlb_mm_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579683200,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1001",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:unmap_page_range",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_finish_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/migrate_device.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma",
        "fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry",
        "fs/proc/task_mmu.c:pagemap_scan_pmd_entry",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383884,
      "name": "flush_tlb_mm_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071579717648,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402064,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402064,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331504,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/memory.c:zap_pte_range",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331504,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579401984,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579401984,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```

```json
{
  "name": "flush_tlb_mm_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410768,
      "name": "flush_tlb_mm_range",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:767",
      "file": "arch/x86/mm/tlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/ldt.c:write_ldt",
        "arch/x86/kernel/alternative.c:__text_poke",
        "arch/x86/mm/pgtable.c:pmdp_clear_flush_young",
        "kernel/fork.c:dup_mmap",
        "mm/mmu_gather.c:tlb_flush_mmu",
        "mm/mmu_gather.c:tlb_remove_table",
        "mm/mmu_gather.c:tlb_table_flush",
        "mm/mprotect.c:change_protection_range",
        "mm/mremap.c:move_page_tables",
        "mm/mremap.c:move_page_tables",
        "mm/pgtable-generic.c:pmdp_collapse_flush",
        "mm/pgtable-generic.c:pmdp_invalidate",
        "mm/pgtable-generic.c:pudp_huge_clear_flush",
        "mm/pgtable-generic.c:pmdp_huge_clear_flush",
        "mm/pgtable-generic.c:ptep_clear_flush",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:flush_tlb_batched_pending",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_numa_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410768,
      "name": "flush_tlb_mm_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int stride_shift</code>
</li>
<li>
<b>Param added. </b>
<code>bool freed_tables</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int vmflag</code>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void flush_tlb_mm_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, unsigned int stride_shift, bool freed_tables)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
