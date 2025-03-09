# Function: <code>remove_migration_ptes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void remove_migration_ptes(struct page * old, struct page * new)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580878736,
      "name": "remove_migration_ptes",
      "external": false,
      "loc": "mm/migrate.c:189",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878736,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013216,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:279",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013216,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087392,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:279",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087392,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134928,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:265",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134928,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253008,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:288",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253008,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399152,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399152,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581482752,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:290",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482752,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593792,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:288",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593792,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661872,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661872,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581873001,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:294",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581883232,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581919209,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:290",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581929248,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581944185,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:263",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954592,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582249241,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:271",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_unmap",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:__unmap_and_move"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582259328,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct folio * src, struct folio * dst, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582727317,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:271",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": [
        "mm/migrate.c:writeout",
        "mm/migrate_device.c:migrate_vma_finalize",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:__split_huge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582725168,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void remove_migration_ptes(struct folio * src, struct folio * dst, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583254758,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:286",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:unmap_and_move_huge_page"
      ],
      "caller_func": [
        "mm/migrate.c:writeout",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250768,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void remove_migration_ptes(struct folio * src, struct folio * dst, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583476804,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:282",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src"
      ],
      "caller_func": [
        "mm/migrate.c:writeout",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470512,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void remove_migration_ptes(struct folio * src, struct folio * dst, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583669282,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:285",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate.c:unmap_and_move_huge_page",
        "mm/migrate.c:migrate_folio_undo_src"
      ],
      "caller_func": [
        "mm/migrate.c:writeout",
        "mm/migrate_device.c:migrate_device_finalize",
        "mm/migrate_device.c:migrate_device_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662784,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493111604,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493107640,
      "name": "remove_migration_ptes",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226804356,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226804356,
      "name": "remove_migration_ptes",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286577360,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286577360,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272957714,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_pages"
      ],
      "caller_func": [
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272954448,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630608,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630608,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571664,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571664,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621920,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621920,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void remove_migration_ptes(struct page * old, struct page * new, bool locked)
```

```json
{
  "name": "remove_migration_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688304,
      "name": "remove_migration_ptes",
      "external": true,
      "loc": "mm/migrate.c:289",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_vma_finalize",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:move_to_new_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688304,
      "name": "remove_migration_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<b>Param added. </b>
<code>bool locked</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * src</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio * dst</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * old</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * new</code>
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
