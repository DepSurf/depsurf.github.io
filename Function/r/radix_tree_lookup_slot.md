# Function: <code>radix_tree_lookup_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582969776,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:551",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_huge_page_move_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582969776,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583258480,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:721",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583258480,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583375120,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:955",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583375120,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588224544,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1074",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224544,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588774608,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1073",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap",
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588774608,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(const struct radix_tree_root * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153248,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:1074",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_fix_revmap",
        "mm/filemap.c:find_get_entry",
        "mm/migrate.c:migrate_huge_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153248,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589385792,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:816",
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
      "addr": 18446744071589385792,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589842816,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071589842816,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068912,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071590068912,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585066064,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071585066064,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585215392,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071585215392,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585098240,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071585098240,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585546496,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071585546496,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702176,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071586702176,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595863872,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:795",
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
      "addr": 18446744071595863872,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596381216,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:794",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596381216,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597276464,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:794",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597276464,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503846832,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446603336503846832,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236466348,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 3236466348,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297700848,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297700848,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279736860,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446743936279736860,
      "name": "radix_tree_lookup_slot",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671168,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071589671168,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589396992,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071589396992,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590114544,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071590114544,
      "name": "radix_tree_lookup_slot",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * * radix_tree_lookup_slot(const struct xarray * root, long unsigned int index)
```

```json
{
  "name": "radix_tree_lookup_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164928,
      "name": "radix_tree_lookup_slot",
      "external": true,
      "loc": "lib/radix-tree.c:803",
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
      "addr": 18446744071590164928,
      "name": "radix_tree_lookup_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<b>Param type changed. </b>
<code>struct radix_tree_root * root</code> ➡️ <code>const struct radix_tree_root * root</code>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct radix_tree_root * root</code> ➡️ <code>const struct xarray * root</code>
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
