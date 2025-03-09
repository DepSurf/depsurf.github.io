# Function: <code>mksaveddirty_shift</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
pgprotval_t mksaveddirty_shift(pgprotval_t v)
```

```json
{
  "name": "mksaveddirty_shift",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579118739,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "arch/x86/xen/mmu_pv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/xen/mmu_pv.c:make_lowmem_page_readonly"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100996,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173402,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:do_numa_page",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:finish_mkwrite_fault",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:insert_pfn",
        "mm/memory.c:restore_exclusive_pte"
      ],
      "caller_func": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:copy_present_pte",
        "mm/memory.c:restore_exclusive_pte"
      ]
    },
    {
      "addr": 18446744071583232156,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/mprotect.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mprotect.c:change_pte_range",
        "mm/mprotect.c:change_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583267738,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583469808,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:unuse_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583561067,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_change_protection",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/hugetlb.c:hugetlb_no_page",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:hugetlb_wp",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range",
        "mm/hugetlb.c:copy_hugetlb_page_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583622796,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660351,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683950,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730523,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__split_huge_zero_page_pmd",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:huge_pmd_set_accessed",
        "mm/huge_memory.c:huge_pud_set_accessed",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:copy_huge_pud",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:insert_pfn_pud",
        "mm/huge_memory.c:insert_pfn_pud",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:vmf_insert_pfn_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:pmd_modify"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583757770,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583891906,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583921867,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "mm/mapping_dirty_helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mapping_dirty_helpers.c:wp_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584730597,
      "name": "mksaveddirty_shift",
      "external": false,
      "loc": "arch/x86/include/asm/pgtable.h:340",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:make_uffd_wp_pte",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:clear_soft_dirty"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121952,
      "name": "mksaveddirty_shift",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
pgprotval_t mksaveddirty_shift(pgprotval_t v)
```
</details>
</li>
</ul>
