# Function: <code>__pmd_trans_huge_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma, spinlock_t * * ptl)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580903280,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1598",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:smaps_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903280,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581029824,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1467",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581029824,
      "name": "__pmd_trans_huge_lock",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105216,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1592",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105216,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581154864,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1836",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581154864,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276368,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1942",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276368,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581425168,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1930",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581425168,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510768,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1950",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510768,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620368,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2008",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620368,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581691216,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581691216,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581908656,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1886",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581908656,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953824,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1901",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953824,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979344,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1908",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979344,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281616,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1831",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281616,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582765776,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1857",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582765776,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583300096,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1956",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583300096,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583519296,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:1945",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_folios_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583519296,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714480,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2284",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/mlock.c:mlock_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_folios_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "mm/memory-failure.c:hwpoison_pte_range",
        "mm/userfaultfd.c:move_pages",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714480,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493136592,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493136592,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286619392,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286619392,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659952,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659952,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599776,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599776,
      "name": "__pmd_trans_huge_lock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651264,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651264,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```

```json
{
  "name": "__pmd_trans_huge_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717696,
      "name": "__pmd_trans_huge_lock",
      "external": true,
      "loc": "mm/huge_memory.c:2013",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:mincore_pte_range",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:move_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_count_precharge_pte_range",
        "fs/proc/task_mmu.c:gather_pte_stats",
        "fs/proc/task_mmu.c:pagemap_pmd_range",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717696,
      "name": "__pmd_trans_huge_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>spinlock_t * * ptl</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>spinlock_t *</code>
</li>
</ul>
</details>
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
spinlock_t * __pmd_trans_huge_lock(pmd_t * pmd, struct vm_area_struct * vma)
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
