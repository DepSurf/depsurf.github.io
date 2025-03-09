# Function: <code>prep_transhuge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581035791,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:461",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024768,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110973,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:491",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099584,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581159664,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:493",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581148384,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581283535,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:493",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:new_page_node",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:collapse_shmem",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268880,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581432540,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:490",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581417712,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581516025,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:500",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581503776,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581625588,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:505",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613520,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581696415,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684432,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581903115,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902704,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581949338,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:504",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948880,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581974956,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:521",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:alloc_migration_target",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974448,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582277640,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:521",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/mempolicy.c:new_page",
        "mm/migrate.c:alloc_misplaced_dst_page_thp",
        "mm/migrate.c:alloc_migration_target",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277120,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582760976,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:520",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__folio_alloc",
        "mm/mempolicy.c:folio_alloc",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582760976,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583294880,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:581",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__folio_alloc",
        "mm/mempolicy.c:folio_alloc",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/khugepaged.c:alloc_charge_hpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583294880,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583513984,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:580",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:__folio_alloc",
        "mm/mempolicy.c:folio_alloc",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/khugepaged.c:alloc_charge_hpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583513984,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493139928,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:alloc_new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493131792,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "prep_transhuge_page",
      "external": false,
      "loc": "include/linux/huge_mm.h:311",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "prep_transhuge_page",
      "external": false,
      "loc": "include/linux/huge_mm.h:311",
      "file": "mm/page_isolation.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286625624,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/mempolicy.c:alloc_new_node_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:khugepaged_alloc_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286610768,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "prep_transhuge_page",
      "external": false,
      "loc": "include/linux/huge_mm.h:311",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "prep_transhuge_page",
      "external": false,
      "loc": "include/linux/huge_mm.h:311",
      "file": "mm/page_isolation.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581665151,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653168,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581604369,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593392,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581656463,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644480,
      "name": "prep_transhuge_page",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void prep_transhuge_page(struct page * page)
```

```json
{
  "name": "prep_transhuge_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581722860,
      "name": "prep_transhuge_page",
      "external": true,
      "loc": "mm/huge_memory.c:511",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:do_huge_pmd_wp_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page"
      ],
      "caller_func": [
        "mm/shmem.c:shmem_alloc_hugepage",
        "mm/gup.c:new_non_cma_page",
        "mm/mempolicy.c:new_page",
        "mm/memory_hotplug.c:new_node_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:new_page",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581710896,
      "name": "prep_transhuge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void prep_transhuge_page(struct page * page)
```
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void prep_transhuge_page(struct page * page)
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
void prep_transhuge_page(struct page * page)
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
void prep_transhuge_page(struct page * page)
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
