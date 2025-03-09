# Function: <code>page_add_anon_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580724976,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1140",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/migrate.c:migrate_misplaced_transhuge_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580724976,
      "name": "page_add_anon_rmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843328,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1180",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843328,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913856,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1179",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913856,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580957808,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1082",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580957808,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581059552,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1086",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581059552,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581198192,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1087",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581198192,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281536,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1089",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_vma",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281536,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581356192,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1090",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581356192,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415728,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415728,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617152,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1100",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617152,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581663920,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1106",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581663920,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581685936,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1109",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581685936,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581955392,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1110",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:restore_exclusive_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581955392,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, rmap_t flags)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371104,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1200",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:restore_exclusive_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371104,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, rmap_t flags)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582873440,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1217",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:restore_exclusive_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582873440,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, rmap_t flags)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583089552,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1215",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:restore_exclusive_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:__split_huge_pmd_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583089552,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492815512,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492815512,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226624264,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_mm",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226624264,
      "name": "page_add_anon_rmap",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286196864,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286196864,
      "name": "page_add_anon_rmap",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272775364,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272775364,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384576,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384576,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581327344,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:unuse_pte_range",
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581327344,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581375776,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581375776,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, bool compound)
```

```json
{
  "name": "page_add_anon_rmap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439632,
      "name": "page_add_anon_rmap",
      "external": true,
      "loc": "mm/rmap.c:1088",
      "file": "mm/rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/ksm.c:replace_page",
        "mm/migrate.c:migrate_misplaced_transhuge_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439632,
      "name": "page_add_anon_rmap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<code>bool compound</code>
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
<code>rmap_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool compound</code>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void page_add_anon_rmap(struct page * page, struct vm_area_struct * vma, long unsigned int address, rmap_t flags)
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
