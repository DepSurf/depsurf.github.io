# Function: <code>linear_page_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580663579,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:419",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:do_wp_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580689946,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:419",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722449,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:419",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580839454,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:419",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920016,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:419",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580695765,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580790943,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803482,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580838417,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580966578,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056306,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067242,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618990,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:405",
      "file": "fs/proc/task_mmu.c",
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580761349,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853978,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580868522,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908977,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581040324,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127905,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142554,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583985,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pmd_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581707393,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:424",
      "file": "fs/proc/task_mmu.c",
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580797847,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mcopy_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580898951,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580913594,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580955457,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581088408,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581130472,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179421,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581189754,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581251406,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642494,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761281,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:440",
      "file": "fs/proc/task_mmu.c",
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580871306,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581001098,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012730,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581056641,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581200600,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244434,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304914,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319937,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383280,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581787961,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581909160,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581005259,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581138225,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146689,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195438,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581345941,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581389916,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454160,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581465768,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581533558,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581957413,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582095325,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581082872,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581211169,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581226513,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278878,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581430037,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581473612,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581539022,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550100,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620966,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044417,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582188542,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:453",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581145848,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581287310,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581300416,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581353022,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581543406,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588572,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581649042,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665354,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581733332,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205078,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582351918,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:437",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581203384,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346030,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581359120,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581412526,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581608302,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581652236,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721136,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581737642,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806884,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582285921,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582450782,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581393954,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550253,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte",
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581556544,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625192,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581823214,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870188,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581940677,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581962752,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026061,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_zeropage_pte",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582570101,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582745385,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:488",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581514176,
      "name": "linear_page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581437474,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581593389,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581602052,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581671432,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732759,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581870553,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581916316,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987666,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582011499,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074667,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582641669,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582816905,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:551",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559152,
      "name": "linear_page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581457874,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613946,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581624580,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581693656,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581760938,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901161,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581941292,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582015439,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033158,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582102133,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670613,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582845814,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:567",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581582608,
      "name": "linear_page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581728335,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581880986,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071581892068,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965800,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042992,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195851,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582247036,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582318141,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342246,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582417333,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582996869,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175694,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:566",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847648,
      "name": "linear_page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582107433,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582283121,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault"
      ],
      "caller_func": [
        "mm/memory.c:print_bad_pte"
      ]
    },
    {
      "addr": 18446744071582289991,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384313,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582474400,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658799,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718979,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810198,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582837008,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582931401,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583468292,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662719,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:848",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240080,
      "name": "linear_page_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582581654,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582775662,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781741,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887972,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582988784,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/madvise.c:force_shm_swapin_readahead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182187,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583245998,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583353633,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583380362,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583487136,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_continue",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060896,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584269263,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:844",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582788860,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582991921,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582998128,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583102830,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugepage_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583200438,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:shmem_swapin_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399385,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583464876,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583572943,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600536,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583702739,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_pte_zeropage",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584287322,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584499599,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:865",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_hole",
        "fs/proc/task_mmu.c:smaps_pte_hole"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582964129,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583173688,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583177541,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583285473,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:hugetlb_add_new_anon_rmap",
        "mm/rmap.c:folio_add_new_anon_rmap",
        "mm/rmap.c:folio_add_anon_rmap_pmd",
        "mm/rmap.c:folio_add_anon_rmap_ptes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583435694,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/madvise.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/madvise.c:shmem_swapin_range",
        "mm/madvise.c:shmem_swapin_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544669,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_follow_page_mask",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte",
        "mm/hugetlb.c:hugetlb_mfill_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639680,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583660053,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583713815,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:move_pages_huge_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583766389,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:madvise_collapse",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583797000,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583899791,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_poison",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_continue",
        "mm/userfaultfd.c:mfill_atomic_zeropage",
        "mm/userfaultfd.c:mfill_atomic_copy",
        "mm/userfaultfd.c:mfill_atomic_install_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584504076,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584743231,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:957",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_entry",
        "fs/proc/task_mmu.c:smaps_pte_entry"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492592924,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492751756,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492764656,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492812308,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493048756,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493100892,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493169492,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493186452,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493272212,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493861880,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494063904,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226447460,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 3226582348,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226584292,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 3226622504,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226763548,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 3226801840,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 3226820792,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3226878056,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 3227520080,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_entry"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285905612,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286110880,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286128148,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286192192,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:__page_set_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286488476,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286559788,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286663244,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286689732,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286798748,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287489052,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287726232,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272621940,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272734322,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272742948,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272773166,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272917972,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272949824,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272964694,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273024332,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273428558,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273560604,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581172232,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581314878,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327968,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581381374,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581577038,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620972,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689872,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581706378,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581775620,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254657,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582419518,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119046,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581258366,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271792,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581324254,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581518606,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581562300,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581628896,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645384,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581713781,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582192289,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358768,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586126797,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "drivers/dax/device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/device.c:dev_dax_huge_fault",
        "drivers/dax/device.c:dev_dax_huge_fault",
        "drivers/dax/device.c:dev_dax_huge_fault"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581163432,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581306078,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319168,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372574,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581568350,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581612284,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581681184,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581697690,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766932,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245137,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582409998,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/task_mmu.c:smaps_pte_range"
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
  "name": "linear_page_index",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581229704,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swap_usage",
        "mm/shmem.c:shmem_swap_usage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370078,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:print_bad_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383152,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/mincore.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mincore.c:__mincore_unmapped_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581436894,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581633342,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:reuse_ksm_page",
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581679884,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:remove_migration_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749103,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:__collapse_huge_page_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581764826,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mctgt_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581835764,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_zeropage",
        "mm/userfaultfd.c:mcopy_atomic",
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321985,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_insert_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582488654,
      "name": "linear_page_index",
      "external": false,
      "loc": "include/linux/pagemap.h:447",
      "file": "fs/proc/task_mmu.c",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
long unsigned int linear_page_index(struct vm_area_struct * vma, long unsigned int address)
```
</details>
</li>
</ul>
