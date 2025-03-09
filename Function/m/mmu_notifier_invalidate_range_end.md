# Function: <code>mmu_notifier_invalidate_range_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580449014,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580665636,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580715683,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718979,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580801397,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580832847,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580890332,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580897593,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581430240,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580524333,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580775361,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830949,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580834732,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580870560,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580927443,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958830,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/ksm.c:try_to_merge_with_ksm_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020858,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032050,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581049006,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581611901,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580587667,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580840060,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580896532,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580900751,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580938480,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580995775,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581032418,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095458,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107345,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131854,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700447,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:285",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580617606,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883998,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580941154,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945289,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960579,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580982383,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044386,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079514,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142366,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581157548,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172316,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640862,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758379,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:265",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580698342,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580977807,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581041615,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045303,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581062817,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581085087,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581154885,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190634,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265314,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581293221,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:do_huge_pmd_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306110,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786427,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905355,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:268",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580830807,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_write_opcode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888615,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112722,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179280,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581183568,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581201611,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223901,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298353,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336499,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581412427,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440325,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581450511,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581959897,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_writeback_mapping_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582085993,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:287",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580898008,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580962275,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581191864,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260131,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265965,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284199,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306791,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381811,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420286,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page",
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581472759,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581500428,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534100,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041180,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181340,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:288",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580995522,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059392,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264674,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581335239,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581340559,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358524,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581419455,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493126,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530197,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581610005,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645164,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582202270,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348383,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:330",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581049530,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581115206,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581323470,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395067,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399858,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418193,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480799,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581557611,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595098,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662950,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680913,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716849,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283107,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582445490,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581232191,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581298966,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581521650,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592927,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581599150,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619563,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685186,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581767916,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809704,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868608,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935750,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041015,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570822,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741239,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:467",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581274799,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342966,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581596579,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638952,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581645455,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665785,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730946,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581815930,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581857314,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581914438,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581978287,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089975,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582643142,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582813098,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581291433,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362104,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619251,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581660583,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581666955,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581687851,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581759499,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581854169,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581892446,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946556,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582006308,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115047,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582671155,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582841833,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:473",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```

```json
{
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581535720,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581609352,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581855361,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": [
        "mm/memory.c:follow_invalidate_pte",
        "mm/memory.c:follow_invalidate_pte"
      ]
    },
    {
      "addr": 18446744071581928918,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581935968,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961485,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041547,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145982,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582187116,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251196,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308703,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582431431,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997411,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583174598,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847840,
      "name": "mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581884615,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581969350,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582248516,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582336815,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582344604,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380782,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473156,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582599977,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_unshare_all_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582646845,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739740,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582804934,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947915,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665756,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317851,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582395645,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582736682,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837841,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582845894,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884265,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582986578,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583096457,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166763,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270686,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331102,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583505035,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272841,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:479",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518964,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582601521,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582951854,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583053118,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583061506,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099113,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583198119,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583306345,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382658,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583491087,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583549941,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_and_free_pmd",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583720411,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584501495,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:478",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```

```json
{
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582687872,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772976,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133912,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:remove_device_exclusive_entry",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583234766,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583243047,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281421,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583434730,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544168,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_unshare_pmds",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:unmap_hugepage_range",
        "mm/hugetlb.c:move_hugetlb_page_tables",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622457,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583685012,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:__migrate_device_pages",
        "mm/migrate_device.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719013,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:__split_huge_pud",
        "mm/huge_memory.c:move_pages_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747329,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": [
        "mm/khugepaged.c:collapse_pte_mapped_thp"
      ]
    },
    {
      "addr": 18446744071583902990,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:move_pages_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583920939,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_clean_post_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584726842,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:484",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:clear_refs_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583737216,
      "name": "mmu_notifier_invalidate_range_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492406476,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492483328,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492729724,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492799276,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492802004,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492818168,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492900084,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492997232,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493034580,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493128412,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493163660,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493856508,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494060444,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226291024,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226356400,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 3226572572,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226613112,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226615964,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 3226625856,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 3226695040,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 3226751124,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3227517712,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285670988,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285769176,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286075628,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286172304,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286177376,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286200520,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286299336,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286423032,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286468104,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286578828,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286608652,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286651224,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287482104,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287718404,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272547966,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272721648,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272766128,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272768250,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272776792,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272830196,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272895396,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272910900,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273427760,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273559770,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581018378,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084054,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581292318,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581363915,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581368706,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387041,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449647,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581526347,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581563834,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631686,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649649,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685585,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251843,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582414226,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580964466,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031238,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581236754,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307482,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581311913,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581329779,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392015,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581468408,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505347,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581572742,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592378,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581624215,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582189397,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351922,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581009578,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581075254,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581283518,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355115,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359906,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378241,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440847,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581517659,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555146,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622998,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581640961,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676897,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582242323,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404706,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
  "name": "mmu_notifier_invalidate_range_end",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581070826,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581136944,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_reap_task_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347523,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:__follow_pte_pmd",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/memory.c:unmap_vmas",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418805,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423812,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/mremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mremap.c:move_page_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442207,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505338,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:madvise_free_single_vma"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581582659,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_cow",
        "mm/hugetlb.c:__unmap_hugepage_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620194,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689342,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707353,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page_fallback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581743551,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582319911,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582482579,
      "name": "mmu_notifier_invalidate_range_end",
      "external": false,
      "loc": "include/linux/mmu_notifier.h:371",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_refs_write"
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
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void mmu_notifier_invalidate_range_end(struct mmu_notifier_range * range)
```
</details>
</li>
</ul>
