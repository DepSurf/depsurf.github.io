# Function: <code>page_vma_mapped_walk</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904704,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:102",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:try_to_merge_one_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904704,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1419
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949488,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:102",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949488,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1421
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050400,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:116",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050400,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1887
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581189264,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:116",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_write_opcode",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581189264,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1853
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581272240,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581272240,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2024
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581346704,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581346704,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2029
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581406016,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581406016,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2029
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581604496,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:142",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581604496,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651776,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:143",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651776,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1862
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672640,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:150",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672640,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2676
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:153",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:page_mlock_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592200979,
      "name": "page_vma_mapped_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    },
    {
      "addr": 18446744071581941936,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2586
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:151",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593977705,
      "name": "page_vma_mapped_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071582351568,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2369
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:151",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596033641,
      "name": "page_vma_mapped_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071582852928,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2549
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:171",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596555687,
      "name": "page_vma_mapped_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446744071583069488,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1930
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:173",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:page_make_device_exclusive_one",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:folio_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597459792,
      "name": "page_vma_mapped_walk.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071583251360,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2031
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492806400,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492806400,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1344
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226619028,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/ksm.c:write_protect_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226619028,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286182992,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286182992,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3320
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272770642,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272770642,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581374864,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581374864,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2029
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318240,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318240,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1795
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581366064,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581366064,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2029
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
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```

```json
{
  "name": "page_vma_mapped_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429952,
      "name": "page_vma_mapped_walk",
      "external": true,
      "loc": "mm/page_vma_mapped.c:138",
      "file": "mm/page_vma_mapped.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "mm/page_vma_mapped.c:page_mapped_in_vma",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_mkclean_one",
        "mm/rmap.c:page_referenced_one",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:remove_migration_pte",
        "mm/page_idle.c:page_idle_clear_pte_refs_one",
        "mm/page_idle.c:page_idle_clear_pte_refs_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429952,
      "name": "page_vma_mapped_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2012
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool page_vma_mapped_walk(struct page_vma_mapped_walk * pvmw)
```
</details>
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
