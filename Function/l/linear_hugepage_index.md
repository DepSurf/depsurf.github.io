# Function: <code>linear_hugepage_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580795840,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:623",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:do_wp_page",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580795840,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908672,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:625",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/khugepaged.c:khugepaged",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908672,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976688,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:625",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/dax.c:dax_iomap_pmd_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976688,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023264,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:627",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023264,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132720,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:628",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_iomap_fault",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132720,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275712,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:627",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_mapping_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275712,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358656,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:627",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358656,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581469360,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:629",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581469360,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533376,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533376,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741344,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:769",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/dax.c:dax_insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741344,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789808,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:799",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/dax.c:dax_insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789808,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817488,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:806",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/dax.c:dax_insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817488,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:808",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/dax.c:dax_insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592211350,
      "name": "linear_hugepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071582109568,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:825",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593989937,
      "name": "linear_hugepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071582554416,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:969",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596040536,
      "name": "linear_hugepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071583069088,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:963",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:shmem_swapin_range",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596562693,
      "name": "linear_hugepage_index.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    },
    {
      "addr": 18446744071583280080,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492963256,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492963256,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286378752,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/rmap.c:__page_set_anon_rmap",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286378752,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272874456,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272874456,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581502112,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581502112,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444336,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "drivers/dax/device.c:dev_dax_huge_fault",
        "drivers/dax/device.c:dev_dax_huge_fault",
        "drivers/dax/device.c:dev_dax_huge_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444336,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581493424,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581493424,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_hugepage_index",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558432,
      "name": "linear_hugepage_index",
      "external": true,
      "loc": "mm/hugetlb.c:630",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte",
        "mm/mincore.c:__mincore_unmapped_range",
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy",
        "mm/migrate.c:remove_migration_pte",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic",
        "fs/dax.c:dax_insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558432,
      "name": "linear_hugepage_index",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int linear_hugepage_index(struct vm_area_struct * vma, long unsigned int address)
```
</details>
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
