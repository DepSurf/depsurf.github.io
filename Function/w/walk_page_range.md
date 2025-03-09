# Function: <code>walk_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580746256,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:239",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:SyS_mincore",
        "mm/madvise.c:force_swapin_readahead",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:pagemap_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580746256,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865456,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:239",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:SyS_mincore",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:force_swapin_readahead",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865456,
      "name": "walk_page_range",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580907424,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:239",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:SyS_mincore",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:force_swapin_readahead",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580907424,
      "name": "walk_page_range",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952832,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:284",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:SyS_mincore",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952832,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054576,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:289",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:SyS_mincore",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_vma_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054576,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193296,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:293",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_vma_fault",
        "mm/hmm.c:hmm_vma_get_pfns",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193296,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276576,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:293",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_vma_fault",
        "mm/hmm.c:hmm_vma_get_pfns",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276576,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int walk_page_range(long unsigned int start, long unsigned int end, struct mm_walk * walk)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351024,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:293",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:queue_pages_range",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_snapshot",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351024,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581410432,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410432,
      "name": "walk_page_range",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609920,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:379",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:madvise_willneed",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_collect",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609920,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581657312,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:379",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:do_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_collect",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_count_precharge",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581657312,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581678944,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:379",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581678944,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581948224,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:427",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948224,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582357552,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:427",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582357552,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859552,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:427",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_mm",
        "mm/mincore.c:do_mincore",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859552,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583075072,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:470",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_mm",
        "mm/mincore.c:do_mincore",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583075072,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583257120,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:470",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:walk_mm",
        "mm/mincore.c:do_mincore",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:queue_pages_range",
        "mm/migrate_device.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_charge",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memory-failure.c:kill_accessing_process",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:do_pagemap_scan",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583257120,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492809352,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__do_sys_mincore",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492809352,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226620388,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226620388,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286189392,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286189392,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272772056,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__se_sys_mincore",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272772056,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379280,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379280,
      "name": "walk_page_range",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322288,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322288,
      "name": "walk_page_range",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370480,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370480,
      "name": "walk_page_range",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int walk_page_range(struct mm_struct * mm, long unsigned int start, long unsigned int end, const struct mm_walk_ops * ops, void * private)
```

```json
{
  "name": "walk_page_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434368,
      "name": "walk_page_range",
      "external": true,
      "loc": "mm/pagewalk.c:301",
      "file": "mm/pagewalk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mincore.c:__ia32_sys_mincore",
        "mm/mincore.c:__x64_sys_mincore",
        "mm/mprotect.c:mprotect_fixup",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_vma_setup",
        "mm/memcontrol.c:mem_cgroup_move_task",
        "mm/hmm.c:hmm_range_fault",
        "mm/hmm.c:hmm_range_fault",
        "fs/proc/task_mmu.c:pagemap_read",
        "fs/proc/task_mmu.c:clear_refs_write",
        "fs/proc/task_mmu.c:clear_refs_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434368,
      "name": "walk_page_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mm_struct * mm</code>
</li>
<li>
<b>Param added. </b>
<code>const struct mm_walk_ops * ops</code>
</li>
<li>
<b>Param added. </b>
<code>void * private</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_walk * walk</code>
</li>
<li>
<b>Param reordered. </b>
<code>start, end, walk</code> ➡️ <code>mm, start, end, ops, private</code>
</li>
</ul>
</details>
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
