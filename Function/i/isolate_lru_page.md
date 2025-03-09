# Function: <code>isolate_lru_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559504,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1424",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:putback_lru_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mlock.c:mlock_vma_page",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SyS_move_pages",
        "mm/huge_memory.c:khugepaged",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559504,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580651088,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1525",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:putback_lru_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SyS_move_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580651088,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718224,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1559",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:putback_lru_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SYSC_move_pages",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718224,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 637
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580753776,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1598",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:putback_lru_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SYSC_move_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753776,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840976,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1615",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:putback_lru_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:SYSC_move_pages",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840976,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 592
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580977520,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1593",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977520,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054480,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1760",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:kernel_move_pages",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054480,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119168,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1797",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119168,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176208,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176208,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376112,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1765",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376112,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 562
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581419904,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1763",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:isolate_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581419904,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581441168,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1958",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441168,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 453
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581695056,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:2091",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/mlock.c:munlock_vma_page",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695056,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995808,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/folio-compat.c:154",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:__soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995808,
      "name": "isolate_lru_page",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431664,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/folio-compat.c:115",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431664,
      "name": "isolate_lru_page",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582637056,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/folio-compat.c:114",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:numamigrate_isolate_page",
        "mm/migrate.c:add_page_for_migration",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_in_use_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637056,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808288,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/folio-compat.c:108",
      "file": "mm/folio-compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808288,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492556256,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492556256,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 684
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226418920,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226418920,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285860448,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285860448,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 920
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272601534,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272601534,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581145056,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581145056,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581092000,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581092000,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136256,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136256,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int isolate_lru_page(struct page * page)
```

```json
{
  "name": "isolate_lru_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198768,
      "name": "isolate_lru_page",
      "external": true,
      "loc": "mm/vmscan.c:1796",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mlock.c:mlock_vma_page",
        "mm/mlock.c:clear_page_mlock",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:migrate_page_add",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:do_pages_move",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_isolate",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memory-failure.c:delete_from_lru_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198768,
      "name": "isolate_lru_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 565
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
