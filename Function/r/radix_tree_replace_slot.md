# Function: <code>radix_tree_replace_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580474797,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:257",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__delete_from_page_cache",
        "mm/filemap.c:__delete_from_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580542781,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:257",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580581288,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:257",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580882808,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:257",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580547144,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:page_cache_tree_insert"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580631334,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "mm/truncate.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580672549,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581014769,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052392,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499765,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_fault",
        "fs/dax.c:dax_unlock_mapping_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583259644,
      "name": "radix_tree_replace_slot",
      "external": false,
      "loc": "include/linux/radix-tree.h:259",
      "file": "lib/radix-tree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/radix-tree.c:radix_tree_replace_clear_tags"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375744,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1100",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_pfn_mkwrite",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375744,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void radix_tree_replace_slot(struct radix_tree_root * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588225072,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1225",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588225072,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void radix_tree_replace_slot(struct radix_tree_root * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588775120,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1223",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588775120,
      "name": "radix_tree_replace_slot",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct radix_tree_root * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153776,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1224",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem",
        "fs/dax.c:dax_finish_sync_fault",
        "fs/dax.c:dax_writeback_mapping_range",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:grab_mapping_entry",
        "fs/dax.c:dax_lock_mapping_entry",
        "fs/dax.c:unlock_mapping_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153776,
      "name": "radix_tree_replace_slot",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589386336,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:936",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589386336,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589843408,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843408,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069504,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069504,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585065792,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585065792,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215120,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585215120,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585097968,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585097968,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545040,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545040,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586700592,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586700592,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595862176,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:915",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595862176,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596379408,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:914",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596379408,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597274656,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:914",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597274656,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503847456,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503847456,
      "name": "radix_tree_replace_slot",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236467100,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236467100,
      "name": "radix_tree_replace_slot",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297701680,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297701680,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279737384,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279737384,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671760,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671760,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589397584,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589397584,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590115136,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590115136,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct xarray * root, void * * slot, void * item)
```

```json
{
  "name": "radix_tree_replace_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590165520,
      "name": "radix_tree_replace_slot",
      "external": true,
      "loc": "lib/radix-tree.c:923",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590165520,
      "name": "radix_tree_replace_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void radix_tree_replace_slot(struct radix_tree_root * root, void * * slot, void * item)
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>struct xarray * root</code>
</li>
</ul>
</details>
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
