# Function: <code>__put_anon_vma</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580726832,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1534",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:anon_vma_prepare",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726832,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846144,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1710",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846144,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916640,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1709",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916640,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961024,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1619",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961024,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063344,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1704",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063344,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581202272,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1722",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202272,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581285984,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1757",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581285984,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360400,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360400,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420080,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420080,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621824,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1805",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621824,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668032,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1799",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668032,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581690256,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1821",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581690256,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581961648,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:2222",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581961648,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582381584,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:2349",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582381584,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582884976,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:2363",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582884976,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583099824,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:2361",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583099824,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583282544,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:2518",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_lock_anon_vma_read",
        "mm/rmap.c:folio_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:move_pages_huge_pmd",
        "mm/userfaultfd.c:move_pages_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583282544,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492820096,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492820096,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226626948,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226626948,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286203008,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286203008,
      "name": "__put_anon_vma",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272777962,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:anon_vma_fork",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272777962,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581388928,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581388928,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581331632,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581331632,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380128,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_rmap_item_from_tree",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380128,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __put_anon_vma(struct anon_vma * anon_vma)
```

```json
{
  "name": "__put_anon_vma",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444000,
      "name": "__put_anon_vma",
      "external": true,
      "loc": "mm/rmap.c:1767",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_lock_anon_vma_read",
        "mm/rmap.c:page_get_anon_vma",
        "mm/rmap.c:unlink_anon_vmas",
        "mm/rmap.c:__anon_vma_prepare",
        "mm/ksm.c:remove_node_from_stable_tree",
        "mm/ksm.c:break_cow",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444000,
      "name": "__put_anon_vma",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
