# Function: <code>pmdp_invalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747376,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:191",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_page_to_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747376,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866528,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:162",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866528,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908464,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:162",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908464,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580954016,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:182",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954016,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055744,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:184",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055744,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194416,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:184",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194416,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581277792,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581277792,
      "name": "pmdp_invalidate",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581352256,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581352256,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411760,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411760,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581611888,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:194",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581611888,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581659216,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:194",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581659216,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681024,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:194",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681024,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581950304,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:194",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581950304,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582359920,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:195",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582359920,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582862320,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:195",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582862320,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583077824,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:197",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583077824,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260080,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:198",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260080,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492811328,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492811328,
      "name": "pmdp_invalidate",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282756704,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "arch/powerpc/mm/book3s64/pgtable.c:105",
      "file": "arch/powerpc/mm/book3s64/pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282756704,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581380608,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581380608,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323312,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323312,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581371808,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581371808,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
```

```json
{
  "name": "pmdp_invalidate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581435696,
      "name": "pmdp_invalidate",
      "external": true,
      "loc": "mm/pgtable-generic.c:185",
      "file": "mm/pgtable-generic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:page_mkclean_one",
        "mm/madvise.c:madvise_cold_or_pageout_pte_range",
        "mm/huge_memory.c:set_pmd_migration_entry",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:change_huge_pmd",
        "mm/huge_memory.c:madvise_free_huge_pmd",
        "fs/dax.c:dax_entry_mkclean",
        "fs/proc/task_mmu.c:clear_refs_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581435696,
      "name": "pmdp_invalidate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 253
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>pmd_t</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
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
pmd_t pmdp_invalidate(struct vm_area_struct * vma, long unsigned int address, pmd_t * pmdp)
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
