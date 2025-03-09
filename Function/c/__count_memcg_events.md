# Function: <code>__count_memcg_events</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580875825,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945943,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580985222,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
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
      "addr": 18446744071581012611,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139663,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581480505,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965032,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:679",
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
  "name": "__count_memcg_events",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580950156,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022092,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581062262,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
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
      "addr": 18446744071581086156,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215871,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581561257,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046877,
      "name": "__count_memcg_events",
      "external": false,
      "loc": "include/linux/memcontrol.h:719",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581673600,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:795",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581673600,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745856,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745856,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581964351,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:796",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:uncharge_batch"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581949056,
      "name": "__count_memcg_events.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
    },
    {
      "addr": 18446744071581968080,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582012879,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:899",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:uncharge_batch"
      ],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995456,
      "name": "__count_memcg_events.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071582017136,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582029301,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:791",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582042976,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582348432,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:831",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582348432,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582844325,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:809",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__folio_activate",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:count_memcg_events",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844144,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389840,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:879",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:count_memcg_events",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389840,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583610544,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:904",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:count_memcg_events",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583610544,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583805200,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:951",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:count_memcg_events",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583805200,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493198904,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493198904,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226830336,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226830336,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286702624,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286702624,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272978188,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272978188,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581714592,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581714592,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581653504,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653504,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705904,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705904,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```

```json
{
  "name": "__count_memcg_events",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773296,
      "name": "__count_memcg_events",
      "external": true,
      "loc": "mm/memcontrol.c:806",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773296,
      "name": "__count_memcg_events",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __count_memcg_events(struct mem_cgroup * memcg, enum vm_event_item idx, long unsigned int count)
```
</details>
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
