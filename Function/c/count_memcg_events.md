# Function: <code>count_memcg_events</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580722980,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:627",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580761344,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:627",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580808793,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:630",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580848720,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:630",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580875808,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945926,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580985205,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012594,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139646,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965015,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:696",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580950139,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022075,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581062245,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086139,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215854,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046860,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:736",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039779,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086138,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581121991,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151710,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289231,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581625663,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581642611,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211253,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:716",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581095287,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142122,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581179021,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209599,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347951,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581696490,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581714702,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292149,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581283668,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581361172,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391962,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552207,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581898381,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930556,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582575392,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:731",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581304894,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581404697,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426862,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581595347,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944621,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982257,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582637886,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1000",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581322910,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581422069,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581454558,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581615827,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970606,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009108,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582674046,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1041",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581570635,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672773,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581708843,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581882755,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273303,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311497,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001403,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1033",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581922864,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    },
    {
      "addr": 18446744071582038784,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ]
    },
    {
      "addr": 18446744071582080336,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio"
      ]
    },
    {
      "addr": 18446744071582240384,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071582533488,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ]
    },
    {
      "addr": 18446744071582749472,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071582791440,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    },
    {
      "addr": 18446744071583463424,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581922864,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582038784,
      "name": "count_memcg_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582080336,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582240384,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582533488,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071582749472,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071582791440,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071583463424,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582359584,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    },
    {
      "addr": 18446744071582475104,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    },
    {
      "addr": 18446744071582555744,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio"
      ]
    },
    {
      "addr": 18446744071582730896,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071583048576,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ]
    },
    {
      "addr": 18446744071583282640,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071583326448,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ]
    },
    {
      "addr": 18446744071584054944,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1057",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359584,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582475104,
      "name": "count_memcg_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582555744,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582730896,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583048576,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583282640,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583326448,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584054944,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582562928,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    },
    {
      "addr": 18446744071582669936,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    },
    {
      "addr": 18446744071582761024,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio"
      ]
    },
    {
      "addr": 18446744071582947056,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071583257152,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_frontswap_load",
        "mm/zswap.c:zswap_frontswap_store"
      ]
    },
    {
      "addr": 18446744071583502144,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071583545296,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ]
    },
    {
      "addr": 18446744071584280736,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1073",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562928,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582669936,
      "name": "count_memcg_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582761024,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582947056,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583257152,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583502144,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583545296,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584280736,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582733792,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault"
      ]
    },
    {
      "addr": 18446744071582840800,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_folio_list"
      ]
    },
    {
      "addr": 18446744071582936112,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio"
      ]
    },
    {
      "addr": 18446744071583123056,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ]
    },
    {
      "addr": 18446744071583445040,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/page_io.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/page_io.c:__swap_writepage",
        "mm/page_io.c:swap_writepage_bdev_sync",
        "mm/page_io.c:swap_writepage_fs"
      ]
    },
    {
      "addr": 18446744071583490784,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/zswap.c:zswap_load",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:shrink_memcg_cb"
      ]
    },
    {
      "addr": 18446744071583696384,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    },
    {
      "addr": 18446744071583738544,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ]
    },
    {
      "addr": 18446744071584497536,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:1090",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733792,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071582840800,
      "name": "count_memcg_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071582936112,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583123056,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583445040,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583490784,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583696384,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071583738544,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071584497536,
      "name": "count_memcg_events.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492459852,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492521024,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492559432,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492596044,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753740,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493140012,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493161304,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493867864,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226335692,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3226386124,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226421908,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450616,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226582180,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285738796,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285807656,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285864848,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285909784,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286113476,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286625724,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286657416,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287498004,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272531588,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272573332,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272604216,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272627844,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272734990,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273432370,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581064135,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581110970,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581147869,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178447,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316799,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581665226,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683438,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260885,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011345,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058042,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581094813,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125247,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260959,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604444,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622064,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197858,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581055335,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102170,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581139069,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169647,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307999,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581656538,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581674750,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251365,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
  "name": "count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581116867,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581164426,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581201606,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232437,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581372004,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722935,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581741371,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331702,
      "name": "count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:753",
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
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
