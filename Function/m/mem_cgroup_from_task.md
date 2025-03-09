# Function: <code>mem_cgroup_from_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580916064,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:817",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/shmem.c:shmem_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/rmap.c:invalid_page_referenced_vma",
        "fs/dax.c:__dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916064,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581085029,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:710",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "fs/dax.c:dax_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581062304,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581165460,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:712",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581137424,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581213253,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:682",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:oom_kill_process",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184608,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581343801,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:696",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:oom_kill_process",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "fs/dax.c:dax_iomap_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313776,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581491257,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:667",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:oom_kill_process",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459968,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581577114,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:805",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581543680,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581688426,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:922",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653824,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581761863,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581726352,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581981095,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:894",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581944112,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582031309,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:997",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:get_obj_cgroup_from_current",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991408,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582058045,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:875",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019440,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582366027,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:915",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/oom_kill.c:__oom_kill_process",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321680,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582863885,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:897",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_folio_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814448,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583411341,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:977",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_folio_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583357296,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583631582,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:1002",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_folio_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576720,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583826510,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:1045",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_can_attach",
        "mm/memcontrol.c:current_objcg_update",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_current",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_folio_referenced_vma",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "fs/dax.c:dax_iomap_pte_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583770176,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493215832,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493175832,
      "name": "mem_cgroup_from_task",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226846924,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226810660,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286728592,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286673136,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272992138,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272960236,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581730599,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581695088,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581669351,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581634112,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581721911,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581686400,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct mem_cgroup * mem_cgroup_from_task(struct task_struct * p)
```

```json
{
  "name": "mem_cgroup_from_task",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581790040,
      "name": "mem_cgroup_from_task",
      "external": true,
      "loc": "mm/memcontrol.c:933",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/filemap.c:filemap_fault",
        "mm/oom_kill.c:__oom_kill_process",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/rmap.c:invalid_page_referenced_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581753248,
      "name": "mem_cgroup_from_task",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
