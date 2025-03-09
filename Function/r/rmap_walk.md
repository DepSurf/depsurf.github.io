# Function: <code>rmap_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729120,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1663",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_munlock",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729120,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 766
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
int rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580848384,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1851",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848384,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580918864,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1850",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918864,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580963136,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1758",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963136,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065456,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1843",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065456,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581204400,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1861",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581204400,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581288112,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1896",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288112,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581362528,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581362528,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422208,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422208,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581621692,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1944",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_munlock"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623984,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581667900,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1938",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_munlock"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670224,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581690124,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1962",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:try_to_munlock"
      ],
      "caller_func": [
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692448,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581963840,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:2363",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:page_mlock",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963840,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582367982,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:2500",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582383904,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rmap_walk(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582873182,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:2514",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": [
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582887520,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void rmap_walk(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583087467,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:2512",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102368,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void rmap_walk(struct folio * folio, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583269925,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:2671",
      "file": "mm/rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:make_device_exclusive_range",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_migrate",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_mkclean",
        "mm/rmap.c:folio_referenced",
        "mm/rmap.c:folio_referenced"
      ],
      "caller_func": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/page_idle.c:page_idle_clear_pte_refs",
        "mm/page_idle.c:page_idle_clear_pte_refs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583285168,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492822792,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492822792,
      "name": "rmap_walk",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226629476,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226629476,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286206816,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_mkclean",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286206816,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272780074,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272780074,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581391056,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581391056,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581333760,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581333760,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581382256,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581382256,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void rmap_walk(struct page * page, struct rmap_walk_control * rwc)
```

```json
{
  "name": "rmap_walk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581446144,
      "name": "rmap_walk",
      "external": true,
      "loc": "mm/rmap.c:1906",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_munlock",
        "mm/rmap.c:try_to_unmap",
        "mm/rmap.c:page_referenced",
        "mm/rmap.c:page_referenced",
        "mm/migrate.c:remove_migration_ptes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581446144,
      "name": "rmap_walk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
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
