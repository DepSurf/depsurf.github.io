# Function: <code>pte_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279807,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580677579,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:follow_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580726074,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:120",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580801146,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580845759,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/khugepaged.c",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580865452,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580916084,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:131",
      "file": "fs/dax.c",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580900230,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580960065,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:153",
      "file": "fs/dax.c",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311151,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580997233,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581061967,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158301,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581251318,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308892,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581395227,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "fs/dax.c",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579322911,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581098983,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142908,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:handle_pte_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176250,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581200920,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581302952,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581336284,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392911,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454414,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545790,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:163",
      "file": "fs/dax.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579347807,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581181763,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222728,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259586,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581284638,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581386631,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581420057,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:try_to_merge_one_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581478527,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539263,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581629084,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:165",
      "file": "fs/dax.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363535,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581252188,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296393,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333327,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581358922,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498129,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581527748,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581589212,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581646454,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744426,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579367775,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581310796,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581355161,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392735,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418601,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562656,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581592640,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581658197,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718150,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581817476,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579396863,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581500506,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552743,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_one_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581591544,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581619988,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772943,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581808544,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876838,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937068,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582037738,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582041989,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467495,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:184",
      "file": "fs/dax.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399135,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581540666,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581597399,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637550,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581666013,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821103,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581856195,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581924618,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581979624,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582086578,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090949,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524663,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582809949,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587940833,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579402239,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581564320,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620091,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581659193,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688266,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850210,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581886877,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581947527,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582007623,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582110387,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582116021,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582553469,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582838669,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587822364,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:183",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579464575,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581829088,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887595,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927474,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581961465,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582141494,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582181565,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252174,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310007,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582426702,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582432405,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869623,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583171693,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588427383,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:154",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:follow_fault_pfn"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579540015,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582220888,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582243353,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582333863,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380764,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582594290,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582647920,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719057,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582741218,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582806202,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582941713,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948981,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583422994,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583672438,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589828284,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:157",
      "file": "drivers/vfio/vfio_iommu_type1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio_iommu_type1.c:vaddr_get_pfns"
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579643519,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582710306,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582739225,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582835179,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582884247,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583112311,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583170343,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583246076,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583272422,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583346502,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583498526,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583506181,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584011331,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584279958,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:158",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579657599,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925173,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582954713,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583050399,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099095,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583322524,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583386213,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583465149,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495725,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583558777,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713524,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583721544,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584235987,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584510118,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:159",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
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
int pte_write(pte_t pte)
```

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579691519,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:spurious_kernel_fault_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583099386,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126698,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:generic_access_phys",
        "mm/memory.c:follow_phys",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_present_pte"
      ],
      "caller_func": [
        "mm/memory.c:wp_page_copy"
      ]
    },
    {
      "addr": 18446744071583232822,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281333,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544807,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583628373,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:write_protect_page",
        "mm/ksm.c:write_protect_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660967,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686981,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_collect_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583758659,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:hpage_collapse_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914276,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_handle_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583921827,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584450596,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584730133,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:173",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121856,
      "name": "pte_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282726132,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "arch/powerpc/mm/ioremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/ioremap.c:ioremap_prot"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283256956,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "arch/powerpc/xmon/xmon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/xmon/xmon.c:format_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283329724,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "arch/powerpc/kvm/book3s_hv_rm_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_get_hpa",
        "arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286060912,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286123008,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286170800,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286200208,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286420872,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286464140,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286573224,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286636940,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286652872,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286815632,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287412348,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287481996,
      "name": "pte_write",
      "external": false,
      "loc": "arch/powerpc/include/asm/book3s/64/pgtable.h:416",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_entry_mkclean",
        "fs/dax.c:dax_entry_mkclean"
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272713562,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272734564,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272765702,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272777060,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272899370,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273031680,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273385480,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:handle_userfault"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/riscv/include/asm/pgtable.h:214",
      "file": "fs/dax.c",
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
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363679,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581279644,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324009,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361583,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581387449,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581531392,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561376,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581626933,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581686886,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581786212,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579294991,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581225784,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581267779,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581305987,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_protection_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581330201,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473221,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581503024,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581568059,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625898,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724378,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579363599,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581270844,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315209,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581352783,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378649,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581522704,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552688,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581618245,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581678198,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777524,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pte_write",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579372031,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581334727,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581379163,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:follow_phys",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416719,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442515,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_unmap_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581587655,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:follow_hugetlb_page",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617812,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581686687,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_collect_pmd",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581744829,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_pmd",
        "mm/khugepaged.c:__collapse_huge_page_isolate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846482,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_hugetlb_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "pte_write",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:182",
      "file": "fs/dax.c",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int pte_write(pte_t pte)
```
</details>
</li>
</ul>
